# Прогнозирование заказов такси

## Задача
Спрогнозировать количество заказов такси на следующий час и построить модель для такого предсказания. Значение метрики RMSE должно быть не больше 48.

## Данные
Находятся в файле taxi.csv. Количество заказов в столбце "num_orders".

## Используемые библиотеки
- pandas
- matplotlib
- statsmodels
- sklearn
- catboost
- lightgbm

## Результаты
1. Найдены тренды и зависимости количества заказов от дня недели и  времени суток.
2. Обучено пять разных моделей на тренировочной выборке. У всех моделей RMSE получилось ниже 48. Выбрана лучшая: Линейная регрессия с RMSE 37.47 на тестовой выборке.