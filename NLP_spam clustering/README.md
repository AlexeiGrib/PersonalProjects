# Описание проекта "Кластеризация спам-текстов".

## Цель проекта: 
с помощью алгоритма KMeans провести кластеризацию текстов СМС-сообщений и выявить в спамных СМС слова с наибольшей частотой встречаемости.

## Задачи проекта:

1. Провести подготовку текста.

2. Подобрать оптимальное количество кластеров, провести кластеризацию с помощью алгоритма KMeans.

3. Оценить качество кластеризации с помощью метрик silhouette_score и v_measure_score.

4. Оценить частоту встречаемости слов в спамных СМС и выявить наиболее частые слова.

## Инструменты:

1. pandas
2. re
3. nltk.stopwords
4. nltk.SnowballStemmer
5. nltk.CountVectorizer
6. sklearn.KMeans
7. matplotlib
8. wordcloud

## Основные результаты проекта:

1. Подобрано оптимальное количество кластеров (оптимальное значение - 8 кластеров), оценено качество кластеризации.

2. Выявлены кластеры, в которых сконцентрированы спамные слова - все спамные СМС сосредоточены в 1, 2, 4 и 7 кластерах.

3. Определены ключевые слова, которые могут говорить о спамности СМС-сообщения, подсчитана частота встречаемости каждого спамного слова в каждом кластере - наиболее часто встречаемыми словами в спамных СМС оказались такие слова, как free, mobile, get, text, reply, www, com, txt.
