### мое первое соревнование по машинному обучению на kaggle

###задача:
Определение интересных мест по координатам и названиям

###соревнование
https://www.kaggle.com/competitions/foursquare-location-matching

score 0.830

Использовано:
- kNN первоначальная группировка по координатам
- tf-idf токенизация
- для фичей:
---- levenstein.distance
---- levenstein.jaro_winkler
---- difflib.sequenceMatcher
- lightgbm основной алгоритм
- sklearn.gradientbosting дал меньший скор, здесь не представлен

Лежат 2 файла:
- подготовка тренировочного датасета
- обучение модели и сабмит
