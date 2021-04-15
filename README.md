Задания курса Java от FreeIT:

# Lesson05

## До занятия:

Данное домашнее здание разделено на 2 этапа.
Автотесты к данному ДЗ отсутствуют, будет проверятся вручную и отправляться на доработку, если потребуется.

***Важное условие***

Нужно склонировать репозиторий, а потом на базе его создать проект `maven`.
Единственный автотест - это чтобы проект компилировался.

Выполненное ДЗ можно отправлять на проверку после выполнения каждого из этапов. Т.е. сделали первый этап - отправляйте на проверку и пингуйте Михаила/Дмитрия в телеграме.
Особое внимание следует обратить на такие темы:

- Классы и объекты (экземпляры) классов
- Наследование
- Полиморфизм (перегрузка методов/конструкторов)
- Абстрактные классы

### Этап 1

Создать класс Card с двумя полями:

- Имя владельца карты
- Баланс карты
Создать 2 конструктора:

1. Для создания карты с именем владельца и балансом
2. Для создания карты только с именем владельца (баланс задается автоматически)

Создать следующие методы:

1. Получение баланса карты
2. Добавление некоторой суммы на баланс
3. Снятие некоторой суммы с баланса карты
4. Создать дополнительный метод для получения баланса в другой валюте, указав обменный курс
 (передается в параметре метода)
 
### Этап 2

Данный этап делается на основе первого этапа.

Определите два подкласса `CreditCard` и `DebitCard` которые реализуют соотв. поведение:

- дебетовая карта: не допускает снятие денег (уменьшение баланса) если это приводит к отрицательному остатку на карте.
- кредитная карта: допускает снятие со счета, даже если баланс не положительный. т.е. у владельца карты накапливается долг.

`Подсказка: здесь нужно будет использовать наследование.`

### Этап (3 для скучающих)

В данном ДЗ отсутствуют тесты, но самые смелые ученики могут попробовать сами написать тесты для этого ДЗ.
Тестировать свой код очень полезно и зачастую это делать просто необходимо на реальных проектах.
Попробуйте написать тесты на каждый метод из ДЗ.
Если возникнут трудности или вопросы - задавайте, мы поможем вам разобраться с этим.



