Есть данные о такси-компании, которая хочет изучить отток водителей и посмотреть, какие есть различия между водителями, которые покидают сервис, и которые остаются. Нужно сформулировать и протестировать гипотезы, выделить группы водителей, которые наиболее подвержены "оттоку". На основе результатов сделать выводы о том, что можно улучшить в сервисе, чтобы в дальнейшем внести изменения.

Описание данных

* city – город
* phone – основное устройство, которое использует водитель
* signup_date – дата регистрации аккаунта (YYYYMMDD)
* last_trip_date – дата последней поездки (YYYYMMDD)
* avg_dist – среднее расстояние (в милях) за поездку в первые 30 дней после регистрации
* avg_rating_by_driver – средняя оценка поездок водителем
* avg_rating_of_driver – средняя оценка поездок водителя
* surge_pct – процент поездок, совершенных с множителем > 1 (кажется когда большая загруженность и тд)
* avg_surge – средний множитель всплеска за все поездки этого водителя
* trips_in_first_30_days – количество поездок, которые совершил водитель в первые 30 дней после регистрации
* luxury_car_user – TRUE, если пользователь в первые 30 дней использовал премиум-автомобиль
* weekday_pct – процент поездок пользователя, совершенных в будние дни


---


There is data available from a taxi company that wishes to study driver churn and examine the differences between drivers who leave the service and those who stay. The goal is to formulate and test hypotheses, identify driver groups most susceptible to churn, and draw conclusions about potential service improvements based on the results, aiming to make future changes. The company seeks to analyze this data to understand driver churn, identify relevant driver segments, and make data-driven improvements to the service to minimize churn in the future.

Data Description:

* city – the city where the driver is based
* phone – primary device used by the driver
* signup_date – date of account registration (YYYYMMDD)
* last_trip_date – date of the last trip (YYYYMMDD)
* avg_dist – average distance (in miles) of trips within the first 30 days after registration
* avg_rating_by_driver – average rating given by the driver to trips
* avg_rating_of_driver – average rating given to the driver by riders
* surge_pct – percentage of trips taken with surge multiplier > 1 (likely during high demand)
* avg_surge – average surge multiplier over all of this user's trips
* trips_in_first_30_days – the number of trips taken by the driver in the first 30 days after registration
* luxury_car_user – TRUE if the user took a luxury car in the first 30 days
* weekday_pct – the percentage of the user's trips occurring on weekdays
