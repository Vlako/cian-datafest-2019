# cian-datafest-2019

1. Изображения загружались размером 25x25 в RGB и HSV и добавлялась аугментация горизонтальным флипом
2. Для каждой цветовой моделе происходило разложение через PCA и потом брались по 250 главных компонент
3. Коэффициенты линейной модели подбирались методом наименьших квадратов ```np.linalg.lstsq```
4. Чтобы привести предикты к значениям от 0 до 1, применялся MinMax scaling
