# Отчёт о тестировании KeyValidator приложения

## Краткое описание

15.09.2020 было проведено конфигурационное тестирование и тестирование установки приложения KeyValidator.

На тестирование затрачено: 0,3 часа.

В результате тестирования выявлены следующие дефекты:
* [Невалидность валидных ключей приложения в виде класса KeyValidator.](https://github.com/elena-liashkova/task1-KeyValidator/issues/1)
* [Валидность невалидных ключей приложения в виде класса KeyValidator.](https://github.com/elena-liashkova/task1-KeyValidator/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* баг-репорт.

В качестве тестовых данных использовались данные:
* инструкция по установке OpenJDK 11,
* руководство использования KeyValidator.

Тестирование производилось в следующем окружении:
1. Java
* Оpenjdk version "11.0.8" 2020-07-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
2. Windows
* Host Name:       LENA-LAPTOP
* Version              1909
* OS Name:          Microsoft Windows 10 Pro
* OS Version:       10.0.18363 N/A Build 18363
3. Browser Opera
Version:70.0.3728.178