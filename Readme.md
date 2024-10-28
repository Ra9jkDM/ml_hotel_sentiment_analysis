Hotel sentiment analysis
----

Анализ тональности комментариев отелей



```Hotel sentiment analysis.ipynb``` - обучение сети распозновать положительные и отрицательные комментарии

```Math.ipynb``` - рассчет LSTM слоя и его проверка, преобразование матриц в LaTeX

Исходные данные:
- datastes/Training_data_marked.csv
- datastes/Test_data_marked.csv

Обработанные данные:
- datastes/preprocess_ds.csv - (очищенные тексты, лемматизация)
- datastes/texts_same_len.npy
- datastes/score.npy

Обученные модели:
- models/*