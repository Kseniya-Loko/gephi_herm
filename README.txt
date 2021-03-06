Template provided by InteractiveVis project
http://blogs.oii.ox.ac.uk/vis/
https://github.com/oxfordinternetinstitute/InteractiveVis/

Important. The files must be uploaded to a webserver (or run one locally) in order to be viewed. JavaScript security prevents running the pages locally without a webserver.

The InteractiveVis project of the Oxford Internet Institute with funding by JISC aims to allow easy creation of interactive visualisations for geospatial and network data using native web technologies (HTML5, CSS3, and SVG) and allow these visualisations to be self-contained so that they may run entirely offline in ebooks and other media. The project will survey existing solutions and build the necessary components to fill in missing features and smooth over incompatibilities in between existing libraries. The project will further provide online hosted wizards to allow for the easy creation of these interactive visualizations.

More information about the project is available on the project blog:
http//blogs.oii.ox.ac.uk/vis/

1. Была найдена карта-схема Государственного Эрмитажа в хорошем качестве.
2. По графической схеме в EasyLinavis были проведены связи по каждому из этажей и переходам с этажа на этаж. В результате была получена csv-таблица.
3. В QGIS была перенесена карта-схема здания и по ней с помощью инструментов программы были прочерчены расстояния между залами в условных единицах (система координат Psevdo Mercator с расположением на экваторе для наименьшего искажения расстояний).
4. Расстояния были внесены в столбец Weight (обозначение веса ребра)
5. Готовая таблица была загружена в Gephi и визуализирована. 
6. Ссылка на полученный сайт https://kseniya-loko.github.io/gephi_herm/ 

Поставленный вопрос: Какие залы наиболее доступны/наименее доступны музейному посетителю? Какие из них имеют наибольшее количество связей (переходов)?
Возможность: поиск наиболее удобного/быстрого маршрута внутри музея.

Полученные показатели:
Средняя степень вершины = 2.346 - то есть, в среднем вершина графа имеет приблизительно 2 ребра (в среднем, из каждого зала есть 2 выхода, это обусловлено анфиладным устройством залов).
Диаметр графа = 34 (это расстояние между наиболее удаленными друг от друга вершинами)
Плотность графа = 0.007 (деление имеющегося числа связей на максимально возможное число связей с имеющимся числом вершин) - граф неплотный.
