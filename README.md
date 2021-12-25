# Ответы на онлайн курс

## В зачете 11 заданий:
  
#### [1] Выборочные характеристики:
+ Вычисление среднего выборочного
+ Вычисление выборочной дисперсии
#### [2] Гистограмма:
+ Определение подходящей гистограммы
+ Подсчет кол-ва в элементов, попавших интервалы гистограммы (3)
+ Тип предполагаемого распределения
#### [3] Точечные оценки параметров распределения.
+ Первый параметр
+ Второй параметр
#### [4] Интервальные оценки параметров распределения.
+  Левая граница одного из параметров
+ Правая граница одного из параметров
    
---------
 
 #### Вам может попасться одно из трех типов распределений: нормальное, показательное и равномерное. Первые 7 заданий выполняются аналогично. Способ решения пунктов 3 и 4 сильно зависит от вашено распределения.
 
---------
 
*Для решения зачета рекомендую пользоваться MS excel'ем.

1) Находим  среднее функцией СРЗНАЧ()
2) Находим выборочную дисперсию функцией ДИСП.В()
3) Включаем надстройку с анализом данных ( Файл -> Параметры -> Надстройки -> Надстройки Excel -> Пакет анализа). Затем во вкладке данные тыкаем на "Анализ данных" -> "Гистограмма". Заполняем форму и смотрим на график. 
4) Вместе с графиком, у нас на том же/на новом листе должна была появится таблица с Карманами и Частотой. Значения в стобце Частота - искомое кол-во элементов. Копируем и вставляем.
5) См. 4
6) См. 4
7) То, что убывает - показательное, имеет ярковыраженный максимум - нормальное и равномерное - ... очевидно должно быть.

А теперь сложная часть:

 ##### [Нормальное распределение]

   Оценкой выборочного среднего (первого параметра) является среднее выборочное, а оценкой второго - выборочная дисперсия. В задание 8 и 9 копируем ответы из первых двух. В 10 и 11 следует обратить внимание, на то какие границы (левую/правую) и для какого параметра (первого-X; второго S0^2) вам нужно сосчитать. Формулу для выборочного среднего можно найти текстовых материалах курса (Лекция 9. Точные и асимптотические доверительные интервалы -> Страница 5). Формулу для дисперсии я не нашел. Буду рад, если скинете мне на почту: kimdaniiell@gmail.com. 
    
+ Левая граница доверительного интервала для X:
    = Xсреднее - 1,96 * КОРЕНЬ( S0^2 из 2 задания ) / КОРЕНЬ (500);
+ Правая граница доверительного интервала для X:
    = Xсреднее + 1,96 * КОРЕНЬ( S0^2 из 2 задания ) / КОРЕНЬ (500);

#### [Показательное распределение]

##### [Равномерное распределение]
