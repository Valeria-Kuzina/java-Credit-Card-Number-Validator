# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

25.03.2020 - 25.03.2020 было проведено граничное тестирование (валидные и невалидные значения) приложения Credit Card Number Validator.

На тестирование затрачено: 2 час

В результате тестирования выявлены следующие дефекты:
* дефектов не выявлено

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Руководство использования

В качестве тестовых данных использовались данные [Генератор случайных номеров банковских карт](https://cartoved.ru/common/generator-kreditnyh-kart.html):

**Используемые номера карт и ожидаемый результат**
* 5369906034708356 Result is OK
* 5177436533492668 Result is OK
* dtgunvduvnf78783 Result is FAIL
* 5314502841872307 Result is OK
* 5405107406360100 Result is OK
* 1231231231231231 Result is FAIL
* 5288773632939942 Result is OK
* 5127177605555153 Result is OK
* 5323525748610255 Result is OK
* 0000000000000000 Result is FAIL

**Реальный результат запуска программы**

Полностью совпадает с ожидаемым.

Тестирование производилось в следующем окружении:
* Windows 10 Home x64
* Java 13
* IntelliJ IDEA Community Edition 2019.3.4
