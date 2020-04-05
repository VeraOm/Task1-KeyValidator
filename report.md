#  Отчет о тестировании KeyValidator
05.04.2020 - 05.04.2020 было проведено функциональное тестирование приложения KeyValidator.

На тестирование 1 час

В результате тестирования выявлены следующие дефекты:
* [Неправильные результаты проверки ключей KeyValidator #1](https://github.com/VeraOm/Task1-KeyValidator/issues/1#issue-594302189)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* [Правила оформления баг-репортов](https://github.com/netology-code/javaqa-homeworks/blob/master/report-requirements.md)

В качестве тестовых данных использовались данные https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md:
* Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
* Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK
* Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL

Тестирование производилось в следующем окружении:
*  ОС: Windows x64 Home
* Java: openjdk version "11.0.6" 2020-01-14
   OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
   OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
 
   
