## Overview
Анализ данных компании по аренде велосипедов.

### Описание данных:

* timestamp – дата и время (точность до часа)

* cnt – количество аренд велосипедов за этот час

* t1 – температура, в С

* t2 – температура "ощущается как", в С 

* hum – влажность (%)

* wind_speed – скорость ветра, км/ч

* weather_code – погодные условия:

    1 – ясно (SKC)

    2 – преимущественно ясно / встречаются отдельные облака (SCT)

    3 – облачно / значительные облака (BKN)

    4 – пасмурно (OVC)

    7 – небольшой дождь Rain/ light Rain shower/ Light rain 

    10 – дождь с грозой

    26 – снегопад 

    94 – ледяной туман (да, такое бывает!)

* isholiday – является ли день праздником (1 – праздник, 0 – нет)

* isweekend –  является ли день выходным (1 – выходной, 0 – нет)

* season – метеорологический сезон (0 – весна, 1 – лето, 2 – осень, 3 – зима)

## Описание проблемы 
Имеются данные за период с 4 января 2015 по 3 января 2017 компании, которая занимается арендой велосипедов. 

**Задача:**

Необходимо изучить динамику числа аренд, наличие связи с погодными условиями и выходными, а также объяснить несколько аномалий на графике.

---

Bicycle rental company data analysis.

### Data description:

* timestamp – date and time (accurate to the hour)

* cnt – number of bicycle rentals for this hour

* t1 – temperature, in C

* t2 – temperature “feels like”, in C

* hum – humidity (%)

* wind_speed – wind speed, km/h

* weather_code – weather conditions:

     1 – clear (SKC)

     2 – mostly clear / scattered clouds (SCT)

     3 – cloudy / significant clouds (BKN)

     4 – cloudy (OVC)

     7 – light rain Rain/ light Rain shower/ Light rain

     10 – rain with thunderstorm

     26 – snowfall

     94 – freezing fog (yes, it happens!)

* isholiday – whether the day is a holiday (1 – holiday, 0 – not)

* isweekend – whether the day is a weekend (1 – weekend, 0 – not)

* season – meteorological season (0 – spring, 1 – summer, 2 – autumn, 3 – winter)

## Description of the problem
Data available for the period from January 4, 2015 to January 3, 2017 for a bicycle rental company.

**Task:**

It is necessary to study the dynamics of the number of rentals, the connection with weather conditions and weekends, and also explain several anomalies in the graph.