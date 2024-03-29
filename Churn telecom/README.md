# Прогнозирование оттока клиентов оператора сотовой связи

## Задача
Обучить модель, которая прогнозирует возможный уход клиента, с максимально большим значением AUC-ROC (> 0.85).

## Описание данных

Данные находятся в четырех файлах:
- информация о договоре
- персональные данные клиента
- информация об интернет-услугах
- информация об услугах телефонии

## Используемые библиотеки
- pandas
- matplotlib
- numpy
- sklearn
- catboost
- lightgbm
- phik

## Результаты
1. Сделана предобработка данных и проведен исследовательский анализ данных.
2. Обучены 4 разных моделей (с подбором гиперпараметров на кросс-валидации), выбрана лучшая: <b>Catboost с AUC-ROC = 0.92, F1 для класса 0 - 0.92, для класса 1 - 0.76.</b>
3. Выявлены самые значимые признаки для обучения модели и  изучена матрица ошибок.