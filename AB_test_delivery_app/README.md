Приложение по доставке готовых продуктов. У вас на руках имеется результат двух тестов:

* В первом тестировали разрешение фотографий блюд в приложении: пользователям показывались либо прямоугольные, либо новые квадратные. 
* Во втором: была обновлена кнопка заказа, и часть юзеров видела старый вариант, а часть – новый.

Коллега пришел к вам с просьбой: он посмотрел на графики и предположил, что среди групп могут встретиться различия. Ваша задача – помочь ему проверить гипотезы, сделать соответствующие выводы на основе статистических тестов и принять решения.

Описание данных

1. Тест на разрешение фотографий:  
* id – id клиента в эксперименте
* group – в каком разрешении показывались картинки (A – прямоугольные 16:9, B – квадратные, C – прямоугольные 12:4)
* events – сколько блюд суммарно было заказано за период

2. Тест на кнопку заказа:
* id – id клиента в эксперименте
* segment – сегмент (high/low)
* group – вид кнопки (control – старая версия, test – новая версия)
* events – сколько блюд суммарно было заказано за период

---

A ready-to-eat food delivery application. You have the results of two tests:

In the first test, the resolution of dish photos in the app was tested: users were shown either rectangular or new square photos.
In the second test, the order button was updated, with some users seeing the old version and others seeing the new one.
A colleague approached you with a request: they looked at the graphs and speculated that there might be differences among the groups. Your task is to help them test hypotheses, draw relevant conclusions based on statistical tests, and make decisions.

Data Description:

1. Photo Resolution Test:
* id – client ID in the experiment
* group – image display resolution (A – rectangular 16:9, B – square, C – rectangular 12:4)
* events – total number of dishes ordered over the period

2. Order Button Test:
* id – client ID in the experiment
* segment – segment (high/low)
* group – button type (control – old version, test – new version)
* events – total number of dishes ordered over the period
