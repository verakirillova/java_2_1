# Отчёт о тестировании приложения "Money Transfer"

## Краткое описание

17.01.2021 было проведено функциональное, негативное  тестирование приложения "Money Transfer".

На тестирование затрачено: 3 часа.

В результате тестирования выявлен один дефект.

## Описание процесса тестирования

Проводилось функциональное, негативное тестирование приложения "Money Transfer", где тестировалась функция пополнения счета клиента. 

Тестирование производилось в следующем окружении:

* Windows 10 Home, 64 bit
* JDK-11.0.9.1+1

## Результаты

1. 100 % не успешных тестов

1.  [Отрицательный баланс счета после перевода](https://github.com/verakirillova/java_2_1/issues/1)

## Общие рекомендации

Для корректной работы приложения "Money Transfer", необходимо изменить в программе переменную типа **int** на переменную типа **long**.


