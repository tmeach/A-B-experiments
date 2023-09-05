## Overview

ML проект по анализу прогнозируемой стоимости автомобилей и факторов, влиящих на ценообразование, с использованием модели линейной регрессии.

### Описание данных: 
- **car_ID**
- **symboling:** числовая оценка, уровень риска для автомобиля, которая может указывать на степень безопасности или риска при использовании.

- **Carname** - Марка автомобиля: Название или марка автомобиля.

- **fueltype:** Тип топлива, используемый в автомобиле (например, бензин или дизель).

- **aspiration:** Тип наддува двигателя (о "std" для стандартного атмосферного двигателя или "turbo" для турбонаддува).

- **doornumber:** Количество дверей в автомобиле.

- **carbody:** Тип кузова автомобиля (например, седан, хэтчбек, купе и др.).

- **drivewheel:** Тип привода автомобиля (например, передний, задний, полный).

- **enginelocation:** Расположение двигателя в автомобиле (например, передний или задний).

- **wheelbase:** Длина колесной базы, расстояние между передней и задней осью автомобиля.

- **enginesize:** Объем двигателя в кубических сантиметрах (cc).

- **fuelsystem:** Тип системы питания двигателя.

- **boreratio:** Отношение диаметра цилиндра к длине хода поршня, характеристика двигателя.

- **stroke:** Длина хода поршня, также характеристика двигателя.

- **compressionratio:** Степень сжатия двигателя.

- **horsepower:** Мощность двигателя в лошадиных силах (л.с.).

- **peakrpm:** Максимальное число оборотов в минуту (оборотов в минуту).

- **citympg:** Расход топлива в городе в милях на галлон (миль/галлон).

- **highwaympg:** Расход топлива на трассе в милях на галлон (миль/галлон).

- **price** - Цена автомобиля, в долларах.


## Описание проблемы 
Имеется датасет **cars.csv** с информацией о марке автомобилей, их характеристиках, и ценной. 

Необходимо на основе этих данных, используя модель линейной регрессии, построить собственную модель для предсказания цен автомобилей (target - 'price'). 


## Решение 
Используя методы Feature Engineering я построил три модели и сравнил метрику R-squared(R-квадрат).

R-squared" (R-квадрат) - это коэффициент детерминации. Он представляет собой статистическую меру, которая измеряет, насколько хорошо модель линейной регрессии соответствует данным. R-квадрат находится в диапазоне от 0 до 1 и может быть интерпретирован следующим образом:

- R-квадрат = 0: Модель не объясняет изменчивость зависимой переменной.
- R-квадрат = 1: Модель идеально соответствует данным и объясняет всю изменчивость зависимой переменной.
- R-квадрат между 0 и 1: Модель объясняет часть изменчивости зависимой переменной, и чем ближе значение к 1, тем лучше модель подходит к данным.


**Первая модель model_1:**
  
    Модель использует в качестве признака(Feature) только количество лошадинных сил (колонка 'horsepower'). 

    Результат R-squared = 0.653

**Вторая модель model_2:**
    
    Модель использует в качестве признака(Feature) все признаки, указанные в датасете. 

Результат R-squared = 0.959

**Третья модель model_3:**
    
    Модель использует в качестве признака(Feature) все признаки, указанные в датасете, за исключением марки автомобиля (колонка - 'Carname')

Результат R-squared = 0.914

## Вывод
    Результат R-squared у model_2, model_3 значимо лучше, чем у model_1, при этом у у model_2 и model_3 он примерно сопоставим. 

    Оставил model_3 так как в ней меньше предиктов, а R-squared изменился незначимо.Выбранная модель объясняет примерно 90% дисперсии (окр. до целого). 

--- 

ML project to analyze the predicted cost of cars and factors influencing pricing using a linear regression model.

### Data description:
- **car_ID**
- **symboling:** numerical rating, the level of risk for the vehicle, which can indicate the degree of safety or risk during use.

- **Carname** - Car make: The name or make of the car.

- **fueltype:** The type of fuel used in the car (for example, gasoline or diesel).

- **aspiration:** Type of engine boost (about “std” for a standard naturally aspirated engine or “turbo” for turbocharging).

- **doornumber:** Number of doors in the car.

- **carbody:** Car body type (for example, sedan, hatchback, coupe, etc.).

- **drivewheel:** Vehicle drive type (for example, front, rear, all-wheel drive).

- **enginelocation:** Engine location in the vehicle (for example, front or rear).

- **wheelbase:** Wheelbase length, the distance between the front and rear axle of the car.

- **enginesize:** Engine volume in cubic centimeters (cc).

- **fuelsystem:** Type of engine power system.

- **boreratio:** The ratio of the cylinder diameter to the piston stroke length, engine characteristics.

- **stroke:** Piston stroke length, also a characteristic of the engine.

- **compressionratio:** Engine compression ratio.

- **horsepower:** Engine power in horsepower (hp).

- **peakrpm:** Maximum revolutions per minute (RPM).

- **citympg:** City fuel consumption in miles per gallon (mpg).

- **highwaympg:** Highway fuel consumption in miles per gallon (mpg).

- **price** - The price of the car, in dollars.


## Description of the problem
There is a dataset **cars.csv** with information about the brand of cars, their characteristics, and valuable information.

Based on this data, using a linear regression model, it is necessary to build your own model for predicting car prices (target - 'price').


## Solution
Using Feature Engineering methods, I built three models and compared the R-squared metric.

"R-squared" is the coefficient of determination. It is a statistical measure that measures how well a linear regression model fits the data. R-squared ranges from 0 to 1 and can be interpreted as follows:

- R-squared = 0: The model does not explain the variability in the dependent variable.
- R-squared = 1: The model fits the data perfectly and explains all the variability in the dependent variable.
- R-squared between 0 and 1: The model explains some of the variability in the dependent variable, and the closer the value is to 1, the better the model fits the data.


**First model model_1:**
  
     The model uses only horsepower as a Feature ('horsepower' column).

     Result R-squared = 0.653

**Second model model_2:**
    
     The model uses all the features specified in the dataset as a Feature.

Result R-squared = 0.959

**Third model model_3:**
    
     The model uses as a Feature all the features specified in the dataset, with the exception of the car brand (column - 'Carname')

Result R-squared = 0.914

## Conclusion
     The R-squared result for model_2, model_3 is significantly better than for model_1, while for model_2 and model_3 it is approximately comparable.

     I left model_3 because it has fewer predictors, and R-squared changed insignificantly. The selected model explains approximately 90% of the variance (surrounded to the whole).


