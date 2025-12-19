# child_labor_rate_over_world
This project aimed to analise child_labor_rate from multiple countries and regions , using SQl
Рассматриваем проблему детского труда с помошью датасета от Kaggle.com
Технологии котрые были использованы:
1.PostgreSQl(pgAdmin4)
2.SQL: joins,agregate functions, group by.
3.ИНструменты: pgAdmin ERD
###Ключевые задачи и SQL-решения
--Вывести топ-5 стран с самым высоким процентом детского труда  за 2011 год.
```sql
select *from country1
order by child_labor_rate_percent desc
limit(5);
```
