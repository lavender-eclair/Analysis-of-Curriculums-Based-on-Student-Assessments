# Analysis of Curriculums Based on Student Assessments
Неотъемлемой частью работы менеджеров на факультетах является постоянная корректировка учебных планов. Это необходимо для улучшения учебного процесса и повышения качества образования. 
Для анализа планов учебных дисциплин используются различные подходы (визуализация, кластеризация, обработка естественного языка и так далее). В данной работе анализ образовательной программы 
проводится с помощью алгоритма, который ищет зависимости между дисциплинами на основе оценок студентов. Целью данной работы является алгоритм поиска зависимостей между предметами. 
Полученная информация в последующем может использоваться для усовершенствования уже существующих планов учебных дисциплин. 

Репозиторий устроен следующим образом:
- файл All_data.ipynb содержит информацию о работе алгоритмов DBSCAN и HDBSCAN на всех данных ПМИ ФКН НИУ ВШЭ за 2021-2022 учебный год
- файл First_course.ipynb содержит информацию о работе с данными только за первый курс ПМИ ФКН НИУ ВШЭ за 2021-2022 учебный год
- файл Stream_2018.ipynb содержит информацию о работе алгоритмов DBSCAN и HDBSCAN на данных  об оценках студентов ПМИ ФКН НИУ ВШЭ 2018 года набора
- файл Similarity_algorithm.ipynb содержит информацию о  разработанном алгоритме нахождения тематической схожести между предметами
