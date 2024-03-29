# Исследование объявлений о продаже квартир

Цель исследования: научится определять рыночную стоимость объектов недвижимости в зависимости от факторов.

# Данные

Данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет.

airports_nearest — расстояние до ближайшего аэропорта в метрах (м)  
balcony — число балконов  
ceiling_height — высота потолков (м)  
cityCenters_nearest — расстояние до центра города (м)  
days_exposition — сколько дней было размещено объявление (от публикации до снятия)  
first_day_exposition — дата публикации  
floor — этаж  
floors_total — всего этажей в доме  
is_apartment — апартаменты (булев тип)  
kitchen_area — площадь кухни в квадратных метрах (м²)  
last_price — цена на момент снятия с публикации  
living_area — жилая площадь в квадратных метрах(м²)  
locality_name — название населённого пункта  
open_plan — свободная планировка (булев тип)  
parks_around3000 — число парков в радиусе 3 км  
parks_nearest — расстояние до ближайшего парка (м)  
ponds_around3000 — число водоёмов в радиусе 3 км  
ponds_nearest — расстояние до ближайшего водоёма (м)  
rooms — число комнат  
studio — квартира-студия (булев тип)  
total_area — площадь квартиры в квадратных метрах (м²)  
total_images — число фотографий квартиры в объявлении

# Задачи

Предобработка данных.  
Расчет и добавление новых параметров по существующим.  
Исследовательский анализ влияния различныз факторов на стоимость квартиры.

# Используемые библиотеки
*pandas*  
*matplotlib*    
*seaborn*

## Статус проекта
Завершен

## Ключевой вывод/результат
Среднестатистические квартиры имеют:  
площадь 50-60 квадратов,  
стоимость 4-6 млн,  
высоту потолков 2.7 м,  
число комнат 2, 3.  
Среднее время продажи 30 дней.

С ростом площади растет и цена. Что очевидно.  
В центре города цена в 3 раза выше. Внутри центра стоимость примерно одинаковая.  
Первый и последний этажи дешевле на 20% и 10% соответсвенно.  
После 14 года цены сильно упали. В центре такого эффекта не наблюдается.
