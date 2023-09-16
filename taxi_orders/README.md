# Прогноз количества заказов для сервиса такси

## Описание проекта

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**make_scorer**
- sklearn.preprocessing.**StandardScaler**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- **matplotlib**

## Общий вывод

Проведено исследование временного ряда заказов такси трендовые и сезонные закономерности. Проведено исследование трёх типов моделей. Как самая точная, выбрана модель случайного леса
