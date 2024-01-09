## Breast Cancer Classifier

El cáncer de mama es la forma más común de cáncer en las mujeres, y el carcinoma ductal invasivo (CDI) es la forma más común de cáncer de mama. Identificar y categorizar con precisión los subtipos de cáncer de mama es una tarea clínica importante, y pueden utilizarse métodos automatizados para ahorrar tiempo y reducir los errores.

### Contexto

El carcinoma ductal invasivo (CDI) es el subtipo más común de todos los cánceres de mama. Para asignar un grado de agresividad a una muestra de monte entero, los patólogos suelen centrarse en las regiones que contienen el IDC. Como resultado, uno de los pasos comunes de preprocesamiento para la clasificación automática de la agresividad es delinear las regiones exactas de IDC dentro de un portaobjetos de montaje completo.

Todo el tratado de las imagenes y sus clases es realizado y explicado en el [notebook](breastcancerclassifier.ipynb), junto por supuesto al CNN(Convolusional Neural Network) hecho con ayuda de librerias como tensorflow, keras y numpy. Dentro tambien se graficas las imagenes de prueba, el rendimiento del modelo y se realiza el testeo del mismo. 

### Webgrafia

- [Breast Histopathology Images](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images/data)
- [CNN Image Classifier](https://www.youtube.com/watch?v=jztwpsIzEGc&t=1577s)
- [Tensorflow](https://www.tensorflow.org/)
