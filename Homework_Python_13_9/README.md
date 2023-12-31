# Анализ лояльных и ушедших клиентов банка

## Оглавление

[1. Цель работы](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Цель-работы)

[2. Краткая информация о данных](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Краткая-информация-о-данных)

[3. Этапы выполнения работы](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Этапы-выполнения-работы)

[4. Выводы](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Выводы)

## Цель работы

Цель работы - для разработки кампании лояльности по удержанию клиентов необходимо установить, чем ушедшие клиенты отличаются от лояльных и как связаны между собой различные признаки клиентов.

:arrow_up:[К оглавлению](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Оглавление)

## Краткая информация о данных

Данные содержат следующие признаки:
- *RowNumber* — номер строки таблицы (это лишняя информация, поэтому можете сразу от неё избавиться)
- *CustomerId* — идентификатор клиента
- *Surname* — фамилия клиента
- *CreditScore* — кредитный рейтинг клиента (чем он выше, тем больше клиент брал кредитов и возвращал их)
- *Geography* — страна клиента (банк международный)
- *Gender* — пол клиента
- *Age* — возраст клиента
- *Tenure* — сколько лет клиент пользуется услугами банка
- *Balance* — баланс на счетах клиента в банке
- *NumOfProducts* — количество услуг банка, которые приобрёл клиент
- *HasCrCard* — есть ли у клиента кредитная карта (1 — да, 0 — нет)
- *IsActiveMember* — есть ли у клиента статус активного клиента банка (1 — да, 0 — нет)
- *EstimatedSalary* — предполагаемая заработная плата клиента
- *Exited* — статус лояльности (1 — ушедший клиент, 0 — лояльный клиент)

:arrow_up:[К оглавлению](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Оглавление)

## Этапы выполнения работы

В процессе выполнения работы необходимо получить ответы на следующие вопросы:

- Узнать соотношение ушедших и лояльных клиентов, показать графически и дать комментарий по соотношению.
- Построить график, показывающий распределение баланса пользователей, у которых на счету больше 2 500 долларов, описать распределение и сделайте выводы.
- Рассмотреть распределение баланса клиента в разрезе признака оттока. Дать комментарий о различии суммы на накопительном счёте ушедших и лояльных клиентов, с чем это может быть связано, что может не устраивать ушедших клиентов в банке.
- Рассмотреть распределение возраста в разрезе признака оттока. Определить, в какой группе больше потенциальных выбросов, на какую возрастную категорию клиентов стоит обратить внимание банку.
- Построить график, показывающий взаимосвязь кредитного рейтинга клиента и его предполагаемой зарплаты, добавить расцветку по признаку оттока клиентов. Рассмотреть график на наличие взаимосвязи между признаками. Указать, если таковые имеются.
- Определить, кто чаще уходит: мужчины или женщины. Показать информацию графически.
- Как отток клиентов зависит от числа приобретённых у банка услуг? Для ответа построить многоуровневую столбчатую диаграмму.
- Как влияет наличие статуса активного клиента на отток клиентов? Построить диаграмму, иллюстрирующую это. Предложения банку, чтобы уменьшить отток клиентов среди неактивных.
- В какой стране доля ушедших клиентов больше? Построить тепловую картограмму, которая покажет это соотношение на карте мира. Предположить, с чем это может быть связано.
- Перевести числовой признак `CreditScore` в категориальный, создать новый признак `CreditScoreCat` — категории кредитного рейтинга. Построть сводную таблицу, строками которой являются категории кредитного рейтинга (`CreditScoreCat`), а столбцами — количество лет, в течение которых клиент пользуется услугами банка (`Tenure`). В ячейках сводной таблицы должно находиться среднее по признаку оттока (`Exited`) — доля ушедших пользователей. На основе полученной сводной таблицы построить тепловую карту с аннотацией. Найдите на тепловой карте категории клиентов, которые уходят чаще всего.

:arrow_up:[К оглавлению](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Оглавление)

## Выводы

В ходе выполнения работы получили ответы на все поставленные вопросы, а тайже применили навыки визуализации данных, полученных в ходе изучения терии урока.

:arrow_up:[К оглавлению](https://github.com/an-petruhin/Homeworks/tree/main/Homework_Python_13_9#Оглавление)

:arrow_up:[Назад к работам](https://github.com/an-petruhin/Homeworks#Homeworks)