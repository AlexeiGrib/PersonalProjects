# Описание проекта "Исследование рынка видеоигр".

## Цель проекта: 
определение факторов, оказывающих наибольшее влияние на успешность игры.

## Задачи проекта:

1. Чтение данных, их изучение, поиск аномальных и пропущенных значений в данных.

2. Предварительная обработка данных, расчёт дополнительных парамтеров.

3. Анализ данных.

4. Построение портрета пользователя каждого региона.

5. Построение гипотез и их проверка.

## Инструменты:

1. pandas
2. numpy
3. scipy
4. matplotlib

## Основные результаты проекта:

1. Импортированы необходимые для работы библиотеки, а также был прочитан и проанализирован предложенный набор данных.
2. Проведена предварительная обработка данных: преобразование типов данных, обработка аномальных значений, обработка пропущенных значений, расчёт дополнительных параметров.
3. Проведён анализ данных, даны ответы на основные вопросы проекта:
- подъём в выпуске игр приходится на 1994 год, до этого года игры выпускались досаточно вяло в силу, возможно, неразвитости технологий; пик в развитии игровой индустрии пришёлся на 2000-2011 годы, а с 2012 года наблюдается некоторое снижение количества реализованных игр; количество реализованных игр в 2016 году находится на уровне 2001 года, однако за 2016 год данные могут быть неполными;
- жизненный цикл платформы, в среднем, составляет 8 лет, из которых примерно 5 лет - это стадия роста, 3 года - стадия спада;
- актуальный период для построения прогноза был определён из средней длительности жизненного цикла платформы - 8 лет, c помощью этой информации был спрогнозирован рост продаж в 2017 году, так как в отрасли ожидается подъём после трёхлетнего спада;
- список актуальных платформ, которые лучше всего подходят для прогноза: Wii, X360, PS3, PS4, 3DS, PC, XOne, WiiU и PSV, при этом платформа считается актуальной, если для неё есть продажи с 2008 года и если для неё выпускаются игры в 2016 году;
- оценки критиков/пользователей не оказывают существенного виляния на уровень продаж;
- как с точки зрения суммарных объёмов продаж, так и с точки зерния количества выпущенных в жанре игр, наиболее популярным жанромоказался жанр Action, наименее популярным - Puzzle.
4. Сформирован портрет пользователя каждого региона:
- для Северной Америки, Европы и других регионов список топ-5 платформ не отличается: он включает такие платформы, как PS3, X360, Wii, PS4 и PC; в Японии в топ-5 платформ входят такие платформы, как 3DS, PS3, Wii, PSV и PS4;
- игроки в Северной Америке, а также в других континентах предпочитают одни и те же жанры: Action, Shooter, Sports, Misc и Role-Playing, в Европе предпочитают почти те же жанры, в Японии чаще всего играют в Role-Playing;
- в Северной Америке, Европе и других регионах большим спрсом пользуются игры с рейтингами E и T, игры с рейтингами EC, К-А и RP популярностью не пользуются, а игры с рейтингом E10+ и T заняли золотую серидину; в Японии любят игры с рейтингом T, игры с рейтингом E и M менее популярны, чем в других регионах, E10+ на уровне других регионах; игры с рейтингами EC, К-А и RP не любят нигде.
5. Построены и проверены гипотезы:
- средние пользовательские оценки у игроков платформ XBox One и PC отличаются: средняя пользовательская оценка для платформы XBox One составила 6.76 баллов, для PC - 7.17 баллов;
- средние пользовательские оценки средних пользовательских рейтингов жанров Action и Sports отличаются: средняя пользовательская оценка для жанра Action составила 7.07 баллов, для жанра Sports - 6.67 баллов.
