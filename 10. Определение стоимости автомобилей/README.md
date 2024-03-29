# Определение стоимости автомобилей

*Задача: Обучить модель для определения рыночной стоимости автомобиля.*

**Проанализированы данные**: технические характеристики, комплектации и цены автомобилей.
Произведена обработка пропусков в признаках и аномалий в таргете.

Построена модель для определения стоимости автомобиля с пробегом.
Использованы численные методы, приближённые вычисления, оценка сложности алгоритма, градиентный спуск.

Примененные модели: LinearRegression, RandomForestRegressor, DecisionTreeRegressor, LGBMRegressor.

Наилучшие результаты получены с помощью LightGBM: RMSE составила 1567.

## Библиотеки и методы
* `pandas`
* `sklearn`
* `numpy`
* `LightGBM`
* `gradient-boosting`
* `StandardScaler`
* `OneHotEncoder`