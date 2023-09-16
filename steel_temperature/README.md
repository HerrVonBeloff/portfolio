# Прогнозирование температуры стали при выплавке
## Описание проекта
Чтобы оптимизировать производственные расходы, металлургический комбинат ООО «Так закаляем сталь» решил уменьшить потребление электроэнергии на этапе обработки стали. Необходимо построить модель, которая предскажет температуру стали.
## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- sklearn.model_selection.**GridSearchCV**
- sklearn.preprocessing.**StandardScaler**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_absolute_error**
- sklearn.metrics.**make_scorer**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**
- catboost.**CatBoostRegressor**
- **matplotlib**

## Общий вывод
Была проведена предобработка данных и обучены модели на необходимых заказчику признаках. После выбора модели был проведён анализ значимости признаков для прогноза температуры.
