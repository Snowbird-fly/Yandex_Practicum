**Поскольку большинство графиков в данном проекте являются интерактивными и сделаны с помощью библиотеки Plotly, то проектследует смотреть через nbviewer**
[открыть через nbviewer](https://nbviewer.org/github/Snowbird-fly/Portfolio/blob/ff4a9bf905fd417686d97e43f485bd1a3d7d654f/Loyalty_program/loyalty_program_analysis.ipynb)

Или можно открыть [проект с сохраненными в .png графиками](https://github.com/Snowbird-fly/Portfolio/blob/2a9e071e35c361bd9e21ebb44931b6528b2ddd16/Loyalty_program/loyalty_program_analysis_without_interactive.ipynb)

# Анализ программы лояльности магазина

**Задача:** проанализировать программу лояльности розничного магазина для нахождения путей увеличения ее эффективности.

**Цель:**
Выявить слабые места и возможные точки роста для увеличения эффективности программы лояльности.

## Описание данных

Датасет содержит данные о покупках в розничном магазине строительных материалов. Все покупатели могут получить доступ в магазин с использованием персональных карт. За 200 рублей в месяц они могут стать участниками программы лояльности. В программу включены скидки, специальные предложения, подарки.

Данные содержатся в двух файлах: файл с продажами и файл с товарами.

1. Файл **retail_dataset**.csv:
    * purchaseId — id чека;
    * item_ID — id товара;
    * purchasedate — дата покупки;
    * Quantity — количество товара;
    * CustomerID — id покупателя;
    * ShopID — id магазина;
    * loyalty_program — участвует ли покупатель в программе лояльности;
2. Файл **product_codes**.csv:
    * productID — id товара;
    * price_per_one — стоимость одной единицы товара

  **Используемые библиотеки:** pandas, numpy, stats, math, matplotlib, plotly

  **Статус проекта:** завершен
  
[Дашборд в Tableau по данному проекту](https://public.tableau.com/app/profile/nadezhda.ivanova7552/viz/salesanalysiesinDIYretailshop/Dashboard1?publish=yes)
