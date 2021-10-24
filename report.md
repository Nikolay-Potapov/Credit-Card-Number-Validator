# Отчёт о тестировании "Банковское приложение"

## Краткое описание

24.10.2021 было проведено компонентное(модульное) тестирование приложения "Банковское приложение".

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
https://github.com/Nikolay-Potapov/Credit-Card-Number-Validator/issues/1
https://github.com/Nikolay-Potapov/Credit-Card-Number-Validator/issues/2
https://github.com/Nikolay-Potapov/Credit-Card-Number-Validator/issues/3

## Описание процесса тестирования

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* String number = "4916879269812094078"(номера банковских карт платежной системы VISA состоящих из 19 цифр)
* String number = "375305622823227"(номера банковских карт платежной системы American Express состоящих из 15 цифр)
* String number = "30568024877417"(номера банковских карт платежной системы Diners Club состоящих из 14 цифр)

Тестирование производилось в следующем окружении:
* Windows 10(x64), версия - 21H1,
* Версия Java - "11.0.12" 2021-07-20