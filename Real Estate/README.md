 # Исследование и анализ продаж недвижимости в Санкт-Петербурге и ЛО

## Данные
В наличии данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет:
- количество изображений
- цена, за которую продали квартиру
- общая площадь квартиры
- дата размещения объявления
- количество комнат в квартире
- высота потолков
- количество этажей в доме
- жилая площадь в квартире
- этаж квартиры
- является ли квартира апартаментами (булев тип)
- является ли квартира студией (булев тип)
- открытая ли планировка в квартире (булев тип)
- площадь кухни
- количество балконов
- название города/населенного пункта, где находится квартира
- расстояние до ближайшего аэропорта в метрах
- расстояние до центра города в метрах
- количество парков в радиусе 3 км
- расстояние до ближайшего парка в метрах
- количество водоемов в радиусе 3 км
- расстояние до ближайшего водоема в метрах
- дата продажи/снятия объявления квартиры

## Задача
Проанализировать объявления о продаже квартир и выявить параметры, которые влияют на конечную цену квартиры. Эти данные в дальнейшем помогут автоматически определять рыночную стоимость объектов недвижимости и отслеживать аномалии и мошенническую деятельность.

## Используемые библиотеки
- pandas
- matplotlib
- seaborn