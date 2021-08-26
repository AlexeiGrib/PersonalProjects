# Описание проекта "Определение токсичных комментариев."

## Цель проекта: 
обучить модель классифицировать комментарии на позитивные и негативные. 

## Условие успешности проекта: 
значение метрики F1-score не менее 0,75.

## Задачи проекта:

1. Чтение и обработка данных.

2. Моделирование и валидация.

## Инструменты:

1. pandas
2. numpy
3. re
4. nltk.stopwords
5. nltk.SnowballStemmer
6. sklearn.TruncatedSVD
7. sklearn.TfidfVectorizer
8. sklearn.GridSearchCV
9. sklearn.CatBoostClassifier
10. sklearn.LogisticRegression
11. matplotlib

## Результаты проекта:

1. Данные прочитаны и подготовлены для обучения моделей.

2. Протестированы 2 алгоритма классификации: LogisticRegression (метрика F1-score 0.779277) и CatBoostClassifier (метрика F1-score 0.604998 при 24 главных компонентах с использованием TruncatedSVD).
