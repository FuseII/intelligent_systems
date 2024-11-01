# Интеллектуальные системы и технологии
Репозиторий посвящён выполнению лабораторных работ в рамках магистерской программа по курсу "Интеллектуальные системы и технологии" в МИРЭА
## 1. Поиск ассоциативных правил `lab_1_2`
Лабораторные работы №1 и №2 посвящены поиску ассоциативных правил на основе транзакций(чеков) магазинов.
Применяются алгоритмы `apriory`, `efficient_apriori` и `fpgrowth`.
Основной код находится в файле `lab_1_2/association rules/main.ipynb`<br>
В `Части №1` поиск осуществляется на вручную сформированному датасету из 30 транзакциий на основе товаров из магазина бытовой техники с расчётами - `lab_1_2.xlsx`,
в `Части №2` на основе датасета <a href="https://archive.ics.uci.edu/dataset/352/online+retail">Online Retail</a> 
## 2. Снижение размерности пространства `lab_3_4`
В лабораторных работах №3 и №4 рассмотрено применение алгоритмов снижения размерности: `t-sne`, `UMAP`, `TriMAP` и `PacMAP`.
Используются различные параметры алгоритмов и методы масштабирования данных: `MaxAbsScaler`,`MinMaxScaler`,`Normalizer`,
`PowerTransformer`,`QuantileTransformer`,`RobustScaler`,`StandardScaler`,`minmax_scale`.<br>
В файле `lab_3_4/dimension_reduce/hepatitis.ipynb`<br> проводится снижение из 19-и мерного в 2-х мерное пространство на 
примере датасета <a href="https://archive.ics.uci.edu/dataset/46/hepatitis">Hepatitis</a>.<br>
Аналогично в файле`lab_3_4/dimension_reduce/mammonth.ipynb` используется датасет `mammonth` представляющий собой набор точек в 3-х мерном пространстве
в совокупности составляющие изображение мамонта. 
## 3. Алгоритмы классификации SVM, KNN, Random Forest `lab_5_6`
В лабораторных работах №5 и №6 применены алгоритмы классифкации: Опорных векторов (SVM),
Ближайших соседей (KNN), Случайного леса (RF). Для нахождение оптимальных параметров применён GreedSearch<br>
<a href="https://scikit-learn.org/stable/modules/svm.html">SVM</a>.<br>
<a href="https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html">KNN</a><br>
<a href="https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html">Random Forest</a><br>
## 4. Алгоритмы балансировки классов SMOTE, BorderlineSmote `lab_7_8`
В лабораторных работах №7 и №8 применены алгоритмы балансировки классов для дальнейшей классификации - увеличение экземпляров миноторитарного класса<br>
<a href="https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html">SMOTE</a>.<br>

