# Car price prediction

## Task
Development of a model for predicting the price of used cars according to its technical characteristics and equipment.

Stages of the project:
- data preprocessing and analysis;
- training of several models with the selection of hyperparameters;
- analysis of the results according to the stated criteria of the Customer.

## Data
The historical data used in the project contains the following categories:
- car price;
- car model;
- car model;
- body type;
- gearbox type:
- type of fuel used;
- mileage;
- car power;
- availability of car repair;
- year and month of vehicle registration;
- dates of creation of the profile, its download from the database and the last user activity;
- postal code of the user.
 
## Used libraries
*pandas*\
*numpy*\
*matplotlib*\
*sklearn*\
*catboost*\
*lightgbm*
***
# Определение стоимости автомобилей

## Задача
Разработка модели для предсказания стоимости подержанных автомобилей по его техническим характеристикам и комплектации. 

Этапы выполнения проекта:
- предобработка и анализ данных;
- обучение нескольких моделей с подбором гиперпараметров;
- анализ результатов по заявленным критериям Заказчика.

## Данные
Исторические данные, которые использовались в проекте, содержат следующие категории:
- стоимость автомобиля;
- марка автомобиля;
- модель автомобиля;
- тип кузова;
- тип коробки передач:
- тип используемого топлива;
- пробег;
- мощность автомобиля;
- наличие ремонта автомобиля;
- год и месяц регистрации автомобиля;
- даты создания анкеты, скачивания ее из базы и последней активности пользователя;
- почтовый индекс пользователя.
 
## Используемые библиотеки
*pandas*\
*numpy*\
*matplotlib*\
*sklearn*\
*catboost*\
*lightgbm*

## Выводы

Для предсказания рыночной стоимости автомобиля, который клиент хочет продать, были обучены и исследованы три модели: LinearRegression, градиентный бустинг на основе CatBoost и LightGBM. В процессе исследования перебирались гиперпараметры для минимизации метрики RMSE. Также замерялось время подбора гиперпараметров, обучения и предсказания моделей. 

В итоге для работы приложения предсказания стоимости автомобиля с учетом его характеристик рекомендовано использовать градиентный бустинг с помощью библиотеки LightGBM.

