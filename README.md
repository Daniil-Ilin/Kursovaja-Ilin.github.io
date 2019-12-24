# Отчет а лабораторных работах 4-7
# студент группы [ИДБ-16-06](https://github.com/stankin/design-2018/wiki/list-idb-16-06) Ильин Даниил Вадимович

Тема ВКР: Разработка ПО для сплайн-интерполяции рельефа местности.

Объект исследования: сплайн-интерполяционный метод моделирования рельефа.

Предмет исследования: методы моделирования рельефа.

Процессы верхнего уровня:

А1 Управление А2 Подготавка А3 Визуализация

Точка зрения: начальник отдела геодезии.

Цель моделирования: демонстрация работы метода визуализации рельефа.

Тема курсового проекта: Построение модели визуализации рельефа методом сплайн-интерполяции, а также повышение ее эффективности, путем уменьшение времени, затрачиваемого на визуализацию модели.

## Лабораторная 4

Контекстная диаграмма А0 "Моделирование рельефа"
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/01_A0.png)

Декомпозиция блока А0
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/02_A0-2.png)

Декомпозиция блока А2 "Обработка"
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/03_A2-3.png)

Декомпозиция блока А3 "Визуализация"
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/04_A3-3.png)

## Лабораторная 5

Определение основных средств автоматизации
* Определение конфигурации технических средств - сервер, пк.
* Определение конфигурации программных средств - Встроенные.
* Определение допустимых видов хранилищ и их размещения - база данных на сервере, память устройства.

Декомпозиция блока А31 "Подготовка данных"
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/05_A31-3.png)

Декомпозиция блока А32 "Применение алгоритма визуализации"
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/06_A32-2.png)

## Лабораторная 6

ER-диграмма для всех потоков:
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-1.png)

[Ссылка на код](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-1.txt)

ER-диграмма для всех ролей:
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-2.png)

[Ссылка на код](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-2.txt)

ER-диграмма для всех модулей:
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-3(2).png)

[Ссылка на код](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-3.txt)

ER-диграмма для всех программных модулей:
![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-4.png)

[Ссылка на код](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L6-4.txt)

## Лабораторная 7

**Расчёт трудозатрат на выполнение проекта:

**Расчет эффекта от внедрения проектируемой системы:

Период рассмотрения = 30 дней.                                                                              
Т (моделирование рельефа стандартным методом) =  400мс.                  
t (моделирование рельефа методом сплайн-интерполяции) = 100мс.                   
Поиск проводится порядка 500 раз в день.                                               
С системой: 500 * 0,1 =50 сек/день; 50 * 30 = 150 сек = 25 мин (за рассмотренный период)                    
Без системы: 500 * 0,4 = 200 сек/день; 500 * 30 = 100 мин (за рассмотренный период)                           
100 – 25 = 75 мин/мес. выгода.                                                                          
100 / 25 * 100% -100% = 300% (общий эффект от автоматизации).

На основе временных расчетов, был сделан вывод о том, что эффект от использования проекта составляет 300%.

**Определение количества функциональных точек:

![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L7-1.png)

**Трудозатраты по FPA IFPUG:

![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L7-2.png)

**Трудозатраты по COCOMO II:

![none](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/L7-3.png)


## Отчет по курсовому проекту

[Курсовой проект](https://github.com/Daniil-Ilin/Kursovaja-Ilin.github.io/blob/master/%D0%9A%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F%20%D0%98%D0%BB%D1%8C%D0%B8%D0%BD%20%D0%98%D0%94%D0%91-16-06%202%D0%92.docx)

