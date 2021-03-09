# Отчёт о тестировании приложения "Credit Card Number Validator"

## Краткое описание 
06.03.2021- 08.03.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 8ч.

В результате тестирования выявлен следующий дефект:

*Карты типов AMEX и Diners Club не проходят проверку на валидность - https://github.com/meleuz/Card-Number/issues/1

## Описание процесса тестирования 

В процессе тестирования использовались следующие артефакты:

*Техническое задание https://github.com/meleuz/Card-Number/blob/master/README.md

В качестве тестовых данных использовались данные:

*Техническое задание https://github.com/meleuz/Card-Number/blob/master/README.md

*Генератор валидных номеров карт - https://www.freeformatter.com/credit-card-number-generator-validator.html

Для более точного тестирования были использованы карты из разных платежных систем, в т.ч.:

Amex;

DinerClub;

MasterCard;

Visa;

MasterCard;

Maestro.


Тестирование производилось в следующем окружении:

Windows 8, 64 bit Java 11
