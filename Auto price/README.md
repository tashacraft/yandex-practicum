# Определение стоимости автомобилей

## Задача
Сервис по продаже автомобилей с пробегом разрабатывает приложение, в котором можно узнать рыночную стоимость своего автомобиля. Нужно построить модель для определения стоимости автомобилей.


## План действий
1. Сделать предобработку данных и подготовить данные к обучению моделей.
2. Обучить разные модели, одна из которых — LightGBM и минимум одна - не бустинг.
3. Проанализировать время обучения, время предсказания и качество моделей.
4. Для оценки качества моделей применить метрику RMSE (значение должно быть меньше 2500).
5. Выбрать лучшую модель по критериям заказчика и проверить её качество на тестовой выборке.

## Данные
Признаки:
- дата скачивания анкеты из базы
- тип автомобильного кузова
- год регистрации автомобиля
- тип коробки передач
- мощность (л. с.)
- модель автомобиля
- пробег (км)
- месяц регистрации автомобиля
- тип топлива
- марка автомобиля
- была машина в ремонте или нет
- дата создания анкеты
- количество фотографий автомобиля
- почтовый индекс владельца анкеты (пользователя)
- дата последней активности пользователя

Целевой признак: цена (евро)

## Используемые библиотеки
- pandas
- matplotlib
- numpy
- seaborn
- sklearn
- catboost
- lightgbm
- time