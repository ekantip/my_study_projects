# Привет!
### Меня зовут Екатерина, я аналитик данных.
С октября 2022 по июнь 2023 я училась на платформе ЯндексПрактикум, получила базовые навыки анализа на python (pandas, numpy, scipy, seaborn, plotly), освоила SQL-запросы к БД (postgre), построение дашбордов с помощью Tableau. 
В этой папке собраны мои учебные проекты. Ниже представлены проекты, наиболее полно представляющие приобретенные навыки. 
## Проект: [cегментация клиентов банка](https://github.com/ekantip/my_study_projects/blob/main/segmentation%20png.ipynb).
___Дано:___ в банке повысился отток клиентов (средний уровень составил 18%), необходимо провести сегментацию отточных клиентов для отдела маркетинга, чтобы они разработали предложения по удержанию клиентов.

___Что сделано:___ 
- короткий исследователтский анализ данных, чтобы получить общее представление о структуре данных
- работа с пропусками: выявлены связи между данными, на их основании проведена замена пропущенных значений,
- сравнение уровня оттока по каждому параметру клиента со средним уровнем оттока, чтобы определить сегменты
- сегментация наиболее отточных клиентов (уровень оттока более 36%), объединение 2-3 сегментов в один
- проверка гипотез (применила критерий Манна-Уитни, z-критерий),
- общие выводы 

___Инструменты:___ python, pandas, scipy, numpy, plotly

___Примечание___ 1)Визуализация проекта выпонена с помощью библиотеки plotly, для ее отображения на github все графики выгружены в формат png, к сожалению качество картинки оставляет желать лучшего и она не интерактивна, но для составления общего впечатления о  работе этого вполне достаточно. 2) Это выпускной проект, сделан мной целиком и полностью самостоятельно и отражает мое мышление и мой подход к работе.  

## Проект: [когортный анализ](https://github.com/ekantip/my_study_projects/blob/main/analysis%20of%20marketing%20indicators.ipynb)
___Дано:___ приложение Procrastinate. Задача — разобраться в причинах убытков рекламных компаний и помочь компании выйти в плюс.
Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года: лог сервера.
___Что сделано:___ 
- анализ расходов на маркетинг: анализ расходов по каналам привлечения, стоимость привлечения одного пользователя в канале (САС);
- оценка окупаемости рекламы: построены графики LTV и ROI, и графики динамики LTV, CAC и ROI 
- оценка окупаемости рекламы с разбивкой: по устройствам, по рекламным каналам, отдельно по странам и рекламным каналам
- выводы, рекомендации.

___Инструменты:___ python, pandas, numpy, matplotlib, seaborn

___Примечание___ Визуализация проекта выпонена с помощью библиотеки plotly, для ее отображения на github все графики выгружены в формат png, к сожалению качество картинки оставляет желать лучшего и она не интерактивна, но для составления общего впечатления о  работе этого вполне достаточно.

## Проект: [воронка продаж + АВ-тестирование](https://github.com/ekantip/my_study_projects/blob/main/sales_funnel_AAB_test.ipynb)
___Дано:___ стартап, продающий продукты питания. Провели АВ-тестирование, чтобы понять как влияет на покупателей изменение шрифта в приложении. Нужно построить воронку продаж, проверить результаты теста статистическими методами. Тестов было три: между контрольными группами 246 и 247 (АА), им показали страницы без изменений. Группа №248 получила измененный шрифт в приложении. 
___Что сделано:___ 
- предобработка данных (поиск дубликатов, переименование столбцов)
- проверка корректности проведения теста (равномерность распределения пользователей по группам, пересечение пользователей между группами, сроки проведения теста)
- построена воронка продаж в разбивке по группам теста
- проверка различия долей в группе А/А отдельно на каждом этапе воронки, чтобы убедиться что тест работает корректно
- проверка различия долей между группами 246 / 248 и 247 / 248
- общий вывод

___Инструменты:___ python, os, pandas, datetime, numpy, scipy, math, plotly

___Примечание:___ Визуализация проекта выпонена с помощью библиотеки plotly, для ее отображения на github все графики выгружены в формат png, к сожалению качество картинки оставляет желать лучшего и она не интерактивна, но для составления общего впечатления о  работе этого вполне достаточно.

