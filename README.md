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
## 5. Эволюционные алгоритмы оптимизации `lab_9_10`
В лабораторных работах №9 и №10 рассматривается применение  
<a href="https://pypi.org/project/geneticalgorithm/">генетического алгоритма</a>,
<a href="https://pypi.org/project/bees-algorithm/">роя пчёл</a> и
<a href="https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.newton.html">метода Ньютона</a> для нахождения 
глобального минимума 
<a href="https://ru.wikipedia.org/wiki/Функция_Растригина">функции Растригина</a>  - `evolution.ipynb`, 
а также для поиска оптимальных параметров в задаче классификации SVM, KNN и RF - `evolution_optim_params.ipynb` .<br>
## 6. Алгоритмы кластеризации `lab_11_12`
В работе применены алгоритмы кластеризации `KMeans`,`fuzzy-c-means`,
`DBSCAN` для трёх наборов данных: `hepatitis` - `clustering_hepatitis.ipynb`,`FMA` - `clustering_FMA.ipynb`,`mammonth` - `clustering_mamonth.ipynb`. <br>.
Построен график индекса кластерного силуэта, оценено оптимальное кол-во кластеров по методу локтя,
расчитана мартица связей и отображена дендрограмма.
Выведены значения показателей качества кластеризации: Homogeneity, Completness, V-measure,
Adjusted Rand Index, Adjusted Mutual Information, Silhouette score.
Выполнена визуализация со снижением размерности данных до и после кластеризации.
## 7. Рекуррентные нейронные сети  RNN, LSTM, GRU `lab_13_16`
В работе решается задача прогнозирования выведения из строя авиационного двигателя по показаниям его
сенсоров с использованием рекуррентных нейронных сетей: RNN, LSTM (Long short-term memory)  и GRU
(Gated recurrent unit) - `RNN_LSTM_GRU.ipynb`.<br> 
За основу взят код `Deep Learning Basics for Predictive Maintenance.ipynb` из https://github.com/Azure/lstms_for_predictive_maintenance/tree/master <br>
Данные из - https://www.kaggle.com/code/ngocbe643/predict-maintenance-21-sensor/input
