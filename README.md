# Репозиторий проектов курса "Специалист по Data Science" by Яндекс.Практикум
Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Специалист по Data Science":

| Название проекта          |Предметная область  |Описание проекта             | Используемые библиотеки     |
| :------------------------ | :----------------- |:----------------------------|:----------------------------|
| [Кластеризация спам-текстов](https://github.com/AlexeiGrib/yandex_empl/tree/main/NLP_spam%20clustering) |NLP/Сlassification|Кластеризация текстов спамных СМС-сообщений с помощью алгоритма KMeans и выявление в спамных СМС-сообщениях наиболее часто встречающихся слов. |pandas, re, nltk, sklearn (KMeans), matplotlib, wordcloud|
| [Определение токсичных комментариев](https://github.com/AlexeiGrib/yandex_empl/tree/main/NLP_toxic_comments_classification) |NLP/Clustering| Разделение текстовых комментариев на токсичные и нормальные с помощью алгоритмов классификации. | pandas, numpy, re, nltk, sklearn (GridSearchCV, CatBoostClassifier, LogisticRegression, TruncatedSVD, TfidfVectorizer), matplotlib|
| [Предсказание количества заказов для такси](https://github.com/AlexeiGrib/yandex_empl/tree/main/Time_Series_the_number_of_orders_prediction) |Time Series/Regression| Предсказание количества заказов для такси на горизонте следующего часа. | pandas, numpy, statsmodels (seasonal_decompose), sklearn (StandardScaler, TimeSeriesSplit, GridSearchCV, CatBoostRegressor, LGBMRegressor, LinearRegression, RandomForestRegressor), matplotlib|
