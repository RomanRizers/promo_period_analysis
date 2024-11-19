# Анализ промопериодов и оптимизация базы данных

## Описание
Цель работы — провести анализ данных о продажах магазинов и предложить рекомендации по улучшению структуры базы данных для упрощения аналитики. 

## Задачи
1. **Общее количество промопериодов (во всех магазинах)**  
   Промопериод — это непрерывный отрезок времени, когда в рамках одного магазина велись продажи.

2. **Медиана продолжительности промопериода (количество недель)**  
   Необходимо рассчитать медианную продолжительность всех промопериодов в неделях.

3. **Объем продаж по каждому промопериоду**  
   Рассчитать общий объем продаж для каждого уникального промопериода.

4. **Медиана количества промопериодов на один магазин**  
   Определить медианное количество промопериодов для магазинов.

5. **Рекомендации по доработке структуры базы данных**  
   На основе анализа текущей структуры данных предложить оптимизации, которые упростят анализ и ускорят запросы.

## Условия
- Данные хранятся в базе данных с таблицами:  
  - `sales`: содержит данные о продажах (store_id, period_id, sales_volume).
  - `store_chars`: характеристики магазинов (store_id, store_type_id).
  - `store_types`: типы магазинов (type_id, type_name).  

- Промопериод определяется как последовательные периоды с продажами в рамках одного магазина.

- Обработка данных и вычисления производятся с использованием Python (библиотека pandas).

## Формат работы
1. **SQL-запросы**  
   Разработка запросов для извлечения данных из базы с минимальными затратами времени.

2. **Обработка данных**  
   Использование pandas для преобразования данных и выполнения вычислений.

## Зависимости
Для выполнения задания требуются следующие библиотеки:
- Python 3.8+
- pandas
- SQLAlchemy
- SQLite



