# Учебные проекты курса Yandex Practicum "Специалист по Data Science"

В репозитории представлены избранные проекты, выполненные в ходе обучения в Яндекс.Практикуме по профессии "Специалист по Data Science".

## Список проектов

| Название проекта | Задача | Описание | Навыки и инструменты | 
| :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| [Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](анализ_рынка_недвижимости) | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от
удаленности от центра. Проведена предобработка данных. Добавлены новые данные.
Построены гистограммы, боксплоты, диаграммы рассеивания. | *python*, *pandas*, *matplotlib*, *предобработка данных*, *исследовательский анализ данных*, *визуализация данных*|  
| [Изучение закономерностей, определяющих успешность игр](исследование_продаж_видеоигр) | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры |  Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона.  При анализе использовал критерий Стьюдента для независимых выборок. | *python*, *pandas*, *matplotlib*, *numpy*, *seaborn*, *предобработка данных*, *исследовательский анализ данных*, *проверка статистических гипотез*, *описательная статистика*, *визуализация данных*|
| [Прогнозирование оттока клиента Банка](прогнозирование_оттока_клинетов_банка) | На основе данных из банка определить клиент, который может уйти | Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. | *python*, *pandas*, *matplotlib*, *scikit-learn*| 
| [Классификаиция клиентов телеком компании](рекомендации_тарифов) | На основе данных предложить клиенту тариф | Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тариф. | *python*, *pandas*, *matplotlib*, *scikit-learn*|
| [Определение наиболее выгодного региона нефтедобычи](поиск_выгодного_региона_нефтедобычи) | На основе данных геологи разведки выбрать район добычи нефти | Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль.  | *python*, *pandas*, *scikit-learn*, *бутстреп* |