# Предсказание стоимости жилья

## Описание
Необхимо обучить модель линейной регрессии на данных о жилье в Калифорнии в 1990 году. На основе данных нужно предсказать медианную стоимость дома в жилом массиве. 

## Данные
В колонках датасета содержатся следующие данные:
- `longitude` — широта;
- `latitude` — долгота;
- `housing_median_age` — медианный возраст жителей жилого массива;
- `total_rooms` — общее количество комнат в домах жилого массива;
- `total_bedrooms` — общее количество спален в домах жилого массива;
- `population` — количество человек, которые проживают в жилом массиве;
- `households` — количество домовладений в жилом массиве;
- `median_income` — медианный доход жителей жилого массива;
- `median_house_value` — медианная стоимость дома в жилом массиве;
- `ocean_proximity` — близость к океану.

## Задачи
- обучить модель и сделать предсказания на тестовой выборке;
- использовать метрики RMSE, MAE и R2 при оценке качества модели.

## Используемые библиотеки
- pandas
- numpy
- seaborn
- matplotlib
- pyspark
- missingno