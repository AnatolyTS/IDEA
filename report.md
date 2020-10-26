# Отчёт о тестировании Intellia IDEA и валидация банковских карт

## Краткое описание

24.10.2020 - 24.10.2020 было проведено функциональное тестирование приложения Intellia IDEA.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Ошибка валидности карты, когда в номере больше 16 символов](https://github.com/AnatolyTS/IDEA/issues/2)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Отчет о тестировании


В качестве тестовых данных использовались данные https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md, https://www.freeformatter.com/credit-card-number-generator-validator.html и (см. скриншот) ![валидация банковских карт](https://sun1-16.userapi.com/rxMnLAFIedvHIcidwZEXnX-VXeaS4vHKkGSvcg/K5ecLxVLMIQ.jpg):


* Функция валидации банковских карт работает 


### Програмное окружение:
* Windows 10 x64
* 11.0.9 2020-10-20
* IntelliJ IDEA 202.7660.26
