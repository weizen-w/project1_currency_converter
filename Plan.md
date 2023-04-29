Алгоритм для проекта «Конвертер валюты»

1.	Задать список валют для упорядоченного хранения – ArrayList <String>
2.	Создаем HashMap<String, double> для хранения курса валют
3.	Метод, для заполнения базы данных валют. Защита от повторов.
4.	Метод, для выбора конвертируемой валюты (№1).
      (вернуть из метода String curr1)
      Метод защитить от дураков. Ограничить в выборе от 1 до кол-ва валют.
5.	Выбор конвертируемой валюты (№2) с помощью метода.
6.	Спрашиваем сколько денег хочет конвертировать в выбранной валюте №1. Защита от дураков. Тип double.
7.	Сделать расчет: тип double
      double х1 = п5 * HashMap (п4) прим. 110дол * 0,9 = 100 евро
      double х2 = х1 * (1/HashMap (п5)) прим. 100 евро * 1/0,01 = 9000руб
8.	Вывод результата из п7 на консоль.

План работ: </br>
      Владимир – метод для заполнения базы данных (п3)</br>
      Андрей - заполняем BotPizzaEnum</br>
      Галина - метод для выбора валюты и защита от дураков (п4,п5)</br>
      Лука  - заполняем BotPizzaEnum