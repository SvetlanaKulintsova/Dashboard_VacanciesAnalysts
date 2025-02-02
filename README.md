## Dashboard_VacanciesAnalysts
<https://public.tableau.com/app/profile/svetlana.kulintsova/viz/Progect_2_KulintsovaSG_v2/Dashboard>
 🛠 Стек: Tableau, фактоиды, расчетные поля, гистограмма распределения, линейный график, таблица, мнимые оси, LOD, визуализация при помощи Box Plot.

### <u>Цель<u/>: <br>
создать дашборд, содержащий сведения о вакансиях на рынке Аналитики и BI по поисковым запросам на платформе HH.ru.

**Данные:**

HH_dataset – таблица с вакансиями аналитиков.

*Описание полей*:

*archived* — актуальная или в архиве<br>
*area_name* — название региона<br>
*direction* — направление аналитики для ключевого слова<br>
*employer_name* — название работодателя<br>
*level* — уровень позиции<br>
*name* — название вакансии<br>
*published_at* — дата публикации<br>
*query_string* — поисковый запрос<br>
*type* — тип поискового запроса (навык/профессия)<br>
*url* — ссылка на вакансию<br>
*vacancy_id* — id вакансии<br>
*lat* — координаты вакансии, широта<br>
*lng* — координаты вакансии, долгота<br>
*employer_id* — id работодателя<br>
*salary, net* — средняя зарплата в указной вилке после вычета налога<br>
*salary_from* — минимальное значение зарплаты в вилке<br>
*salary_gross_flag* — 0 — вилка указана net, 1 — вилка указана gross<br>
*salary_to* — максимальное значение зарплаты в вилке


### <u>Результат<u/><br>
Создан дашборт, содержащий:<br>
- таблицу с вакансиями по поисковым запросам с зарплатой и без;
- число вакансий и гистограмму их распределения во времени;
- среднюю зарплату и гистограмму её распределения во времени;
- гистограмму с детализацией вакансий по направлению и городу; 
- линейный график распределения числа вакансий по дням недели.
