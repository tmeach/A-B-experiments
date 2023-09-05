## Overview:
Приложение по доставке готовых продуктов. 

### Описание данных

**1. Тест на разрешение фотографий:**
* id – id клиента в эксперименте
* group – в каком разрешении показывались картинки (A – прямоугольные 16:9, B – квадратные, C – прямоугольные 12:4)
* events – сколько блюд суммарно было заказано за период

**2. Тест на кнопку заказа:**
* id – id клиента в эксперименте
* segment – сегмент (high/low)
* group – вид кнопки (control – старая версия, test – новая версия)
* events – сколько блюд суммарно было заказано за период


## Описание проблемы:
Имеются результаты двух A/B тестов:

* В первом тестировали разрешение фотографий блюд в приложении: пользователям показывались либо прямоугольные, либо новые квадратные. 
* Во втором: была обновлена кнопка заказа, и часть юзеров видела старый вариант, а часть – новый.

Предполагается среди групп могут встретиться различия. 

**Задача:** 

Проверить гипотезы, сделать соответствующие выводы на основе статистических тестов и принять решения о том, какой функционал приложения оставлять.

---
Application for the delivery of ready-made products.

### Description of data

**1. Photo resolution test:**
* id – client id in the experiment
* group – in what resolution the pictures were shown (A – rectangular 16:9, B – square, C – rectangular 12:4)
* events – how many dishes were ordered in total during the period

**2. Order button test:**
* id – client id in the experiment
* segment – segment (high/low)
* group – button type (control – old version, test – new version)
* events – how many dishes were ordered in total during the period


## Description of the problem:
There are results of two A/B tests:

* The first tested the resolution of food photos in the application: users were shown either rectangular ones or new square ones.
* In the second: the order button was updated, and some users saw the old option, and some saw the new one.

It is expected that differences may occur among groups.

**Task:**

Test hypotheses, draw appropriate conclusions based on statistical tests, and make decisions about what application functionality to retain.