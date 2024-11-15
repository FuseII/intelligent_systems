## 2. Снижение размерности пространства `lab_3_4`
В лабораторных работах №3 и №4 рассмотрено применение алгоритмов снижения размерности: `t-sne`, `UMAP`, `TriMAP` и `PacMAP`.
Используются различные параметры алгоритмов и методы масштабирования данных: `MaxAbsScaler`,`MinMaxScaler`,`Normalizer`,
`PowerTransformer`,`QuantileTransformer`,`RobustScaler`,`StandardScaler`,`minmax_scale`.<br>
В файле `lab_3_4/dimension_reduce/hepatitis.ipynb`<br> проводится снижение из 19-и мерного в 2-х мерное пространство на 
примере датасета <a href="https://archive.ics.uci.edu/dataset/46/hepatitis">Hepatitis</a>.<br>
Аналогично в файле`lab_3_4/dimension_reduce/mammonth.ipynb` используется датасет `mammonth` представляющий собой набор точек в 3-х мерном пространстве
в совокупности составляющие изображение мамонта. 