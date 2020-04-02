# Отчет о тестировании Credit Card Number Validator
## Краткое описание
02.04.2020 проведено функциональное тестирование приложения Credit Card Number Validator.\
На тестирование затрачен 1 час.\
В результате тестирования выявлены следующие дефекты:
* [некоторые номера валидных карт не проходят проверку](https://github.com/Valeriia-b/java-1-2/issues/1)
## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* тест-план, описанный в [Легенде](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0-1)
* бег репорты
* отчет о тестировании

В качестве тестовых данных использовались данные [генератора номеров кредитных карт](https://fakepersongenerator.com/Random1/credit_card_generator) и придуманные невалидные значения. 
* Валидные данные. Ожидаемый результат ОК:\
  4129438320887920 (Visa)\
  5291723806618900 (MasterCard)\
  379944408405944 (AmericanExpress)
  
 * Невалидные данные. Ожидаемый результат FAIL:\
   412345678900000\
   529172380661890012\
   3799444084059449
 
  Тестирование проводилось в следующем окружении:

* ОС: Winows 7 x64
* Java version: openjdk 11.0.6 2020-01-14\
  OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)\
  OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
 * Intelliji IDEA Community Edition 2019.3.4
  
