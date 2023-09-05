## Overview
A/B тест эксперимент в приложении для курьеров компании по доставке готовой еды.

**Описание данных**

* order_id - id заказа
* delivery_time - время доставки в минутах
* district - район доставки
* experiment_group - экспериментальная группа

## Описание проблемы
У компании есть несколько ресторанов в разных частях города и целый штат курьеров. Проблема — к вечеру скорость доставки падает из-за того, что курьеры уходят домой после рабочего дня, а количество заказов лишь растет. Это приводит к тому, что в момент пересмены доставка очень сильно проседает в эффективности. 

ML команда придумала новый алгоритм, который позволяет курьерам запланировать свои последние заказы перед окончанием рабочего дня так, чтобы их маршрут доставки совпадал с маршрутом до дома. То есть, чтобы курьеры доставляли последние свои заказы за день как бы "по пути" домой. 

## Решение
Был организован A/B тест на две равные группы курьеров. Часть курьеров использует старый алгоритм без опции "по пути", другие видят в своем приложении эту опцию и могут ее выбрать. Задача – проанализировать данные эксперимента и помочь бизнесу принять решение о раскатке новой фичи на всех курьеров.



---

A/B test experiment in an application for couriers of a ready-to-eat food delivery company.

**Description of data**

* order_id - order id
* delivery_time - delivery time in minutes
* district - delivery area
* experiment_group - experimental group

## Description of the problem
The company has several restaurants in different parts of the city and a whole staff of couriers. The problem is that in the evening the delivery speed drops due to the fact that couriers go home after work, and the number of orders only increases. This leads to the fact that at the time of shift change, delivery significantly decreases in efficiency.

The ML team came up with a new algorithm that allows couriers to schedule their last orders before the end of the working day so that their delivery route coincides with the route home. That is, so that couriers deliver their last orders of the day as if “on the way” home.

## Solution
An A/B test was organized for two equal groups of couriers. Some couriers use the old algorithm without the “along the way” option, others see this option in their application and can select it. The task is to analyze the experiment data and help the business make a decision on rolling out a new feature to all couriers.
