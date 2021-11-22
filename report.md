# Отчёт о тестировании приложения "Credit Card Number Validator",

## Краткое описание

24.10.2021 было проведено компонентное(модульное) тестирование приложение "Credit Card Number Validator".

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
* [Приложение не принимает валидные номера банковских карт состоящих из 19 цифр](https://github.com/Nikolay-Potapov/Credit-Card-Number-Validator/issues/1)
* [Приложение не принимает валидные номера банковских карт состоящих из 15 цифр](https://github.com/Nikolay-Potapov/Credit-Card-Number-Validator/issues/2)
* [Приложение не принимает валидные номера банковских карт состоящих из 14 цифр](https://github.com/Nikolay-Potapov/Credit-Card-Number-Validator/issues/3)

## Описание процесса тестирования

В качестве тестовых данных использовались [данные](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* Номер карты состоящий из 19 цифр - 3543632214155023665(Visa), 6011824168505105338(Discover),3540228348867654262(JCB);
* Номер карты состоящий из 15 цифр - 371988419724486(American Express (AMEX), 346966868933875(American Express (AMEX), 378002237998661(American Express (AMEX);
* Номер карты состоящий из 14 цифр - 30083548837541(Diners Club - Carte Blanche), 30355140711740(Diners Club - Carte Blanche), 36320054255534(Diners Club - International); 

**Тестирование производилось в следующем окружении:**
* Aspire 3 a315-42
* Windows 10 Pro, Версия 21H1
* java version "17.0.1"
