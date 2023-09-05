## Overview
Имеются данные компании - сервис такси. Компания хочет изучить причины оттока водителей

### Описание данных

* **city** – город
* **phone** – основное устройство, которое использует водитель
* **signup_date** – дата регистрации аккаунта (YYYYMMDD)
* **last_trip_date** – дата последней поездки (YYYYMMDD)
* **avg_dist** – среднее расстояние (в милях) за поездку в первые 30 дней после регистрации
* **avg_rating_by_driver** – средняя оценка поездок водителем
* **avg_rating_of_driver** – средняя оценка поездок водителя
* **surge_pct** – процент поездок, совершенных с множителем > 1 (кажется когда большая загруженность и тд)
* **avg_surge** – средний множитель всплеска за все поездки этого водителя
* **trips_in_first_30_days** – количество поездок, которые совершил водитель в первые 30 дней после регистрации
* **luxury_car_user** – TRUE, если пользователь в первые 30 дней использовал премиум-автомобиль
* **weekday_pctv** – процент поездок пользователя, совершенных в будние дни


Есть данные о такси-компании, которая хочет изучить отток водителей и посмотреть, какие есть различия между водителями, которые покидают сервис, и которые остаются. 

## Описание проблемы: 
Необходимо изучить причины оттока водителей, и посмотреть какие различия между водителями, которые перестают пользоваться сервисом, и теми, кто продолжает.

**Задачи:**

Нужно сформулировать и протестировать гипотезы, выделить группы водителей, которые наиболее подвержены "оттоку". На основе результатов сделать выводы о том, что можно улучшить в сервисе, чтобы в дальнейшем внести изменения.

---


There are company data - taxi service. The company wants to study the reasons for the outflow of drivers

### Description of data

* **city** – city
* **phone** is the main device used by the driver
* **signup_date** – account registration date (YYYYMMDD)
* **last_trip_date** – last trip date (YYYYMMDD)
* **avg_dist** - average distance (in miles) per trip in the first 30 days after registration
* **avg_rating_by_driver** – average rating of trips by a driver
* **avg_rating_of_driver** – average rating of driver's trips
* **surge_pct** - the percentage of trips made with a multiplier > 1 (it seems when there is a lot of workload, etc.)
* **avg_surge** is the average surge multiplier for all trips by this driver
* **trips_in_first_30_days** - the number of trips that the driver made in the first 30 days after registration
* **luxury_car_user** - TRUE if the user used a premium car in the first 30 days
* **weekday_pctv** - percentage of user trips made on weekdays


There is data on a taxi company that wants to study driver churn and see what the differences are between drivers who leave the service and those who stay.

## Description of the problem:
It is necessary to study the reasons for the churn of drivers, and see what the differences are between drivers who stop using the service and those who continue.

**Tasks:**

It is necessary to formulate and test hypotheses, identify groups of drivers that are most prone to churn. Based on the results, draw conclusions about what can be improved in the service in order to make changes in the future.