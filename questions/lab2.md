http://statistica.ru/theory/klasterizatsiya-metod-k-srednikh/ - тут про метод К-средних
https://habr.com/ru/company/jetinfosystems/blog/467745/ - как определить начальное количество кластеров, методы локтя и силуэта
https://bl.ocks.org/rpgove/0060ff3b656618e9136b - так же про метод локтя
https://ichi.pro/ru/metod-silueta-lucse-cem-metod-lokta-dla-poiska-optimal-nyh-klasterov-61080390822033 - тут хорошо про метод силуэта

https://habr.com/ru/post/322034/ - про DBSCAN


inertia - Inertia measures how well a dataset was clustered by K-Means. It is calculated by measuring the distance between each data point and its centroid, squaring this distance, and summing these squares across one cluster.


В **методе локтя** мы находим среднее расстояние от каждой точки кластера до его центроида и изобразите его на графике. Выберите значение k, при котором среднее расстояние резко падает .

Метод силуэта вычисляет коэффициенты силуэта каждой точки, которые измеряют, насколько точка похожа на свой собственный кластер по сравнению с другими кластерами. Вычислите коэффициенты силуэта для каждой точки и усредните их для всех образцов, чтобы получить оценку силуэта 

