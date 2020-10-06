# Отчёт о тестировании <IntelliJ IDEA>

## Краткое описание

<05.10.2020> - <05.10.2020> было проведено <Функциональное тестирование, тестирование установки, системное, интеграционное > приложения <IntelliJ IDEA>.

На тестирование затрачено: <12>

## Описание процесса тестирования

1. Установка IntelliJ IDEA согласно [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
Ожидаемый результат:
Выполнена установка согласно [Руководства по установки
](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
Фактически результат:
Выполнена установка согласно [Руководства по установки
](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
2. Проверка работы IntelliJ IDEA
**Ожидаемый результат:**
Программа работает. 
![Программа работатет](https://user-images.githubusercontent.com/69162015/95088988-4acf7f00-072c-11eb-9ec0-2feae3717676.png)

**Фактический результат**
Программа работает.
![Программа работатет](https://user-images.githubusercontent.com/69162015/95088988-4acf7f00-072c-11eb-9ec0-2feae3717676.png)

3. Проверка работы программы с кодом из [Домашнего задания 1.1.2](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
**Ожидаемый результат:**
Код работает.
![Result is OK](https://user-images.githubusercontent.com/69162015/95092480-5f157b00-0730-11eb-9135-bd37897587e7.png)

**Фактический результат**
Код работает.
![Result is OK](https://user-images.githubusercontent.com/69162015/95092480-5f157b00-0730-11eb-9135-bd37897587e7.png)

В процессе тестирования использовались следующие артефакты*:
* [<Руководство по установке IntelliJ IDEA>](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* <Отчет о тестировании>

В качестве тестовых данных использовались данные <[freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)>:
* <Валидные данные>
MasterCard :
5234712827271328
5435941238577588
2720992630255761
**Ожидаемый результат :**
MasterCard :
5234712827271328 - Result is OK
5435941238577588 - Result is OK
2720992630255761 - Result is OK

![Код работатет result is OK](https://user-images.githubusercontent.com/69162015/95089934-64bd9180-072d-11eb-8f70-0a0ed45db137.png)

**Фактический результат :**
MasterCard :
5234712827271328 - Result is OK
5435941238577588 - Result is OK
2720992630255761 - Result is OK
![Код работатет result is OK](https://user-images.githubusercontent.com/69162015/95089934-64bd9180-072d-11eb-8f70-0a0ed45db137.png)

* <Невалидные данные>
MasterCard :
523471282727132& 
54359412385775ы 
2720992630255760 
**Ожидаемый результат:**
523471282727132& - Result is FAIL
54359412385775ы - Result is FAIL
2720992630255760 - Result is FAIL

![Result is Fail ](https://user-images.githubusercontent.com/69162015/95090311-cc73dc80-072d-11eb-93a9-faf612036910.png)

**Фактический результат:**
523471282727132& - Result is FAIL
54359412385775ы - Result is FAIL
2720992630255760 - Result is FAIL

![Result is Fail ](https://user-images.githubusercontent.com/69162015/95090311-cc73dc80-072d-11eb-93a9-faf612036910.png)

Тестирование производилось в следующем окружении:
* <64-Bit>
* < Java version "11.0.8" 2020-07-14>
* <[Git(https://github.com/Stepan164i/JavaQA---DZ-1.2.git)>
