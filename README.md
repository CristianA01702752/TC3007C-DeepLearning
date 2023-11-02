# TC3007C-DeepLearning
En este repositorio se alojarán todos los archivos del Módulo 2 de la materia de IA.

Se ha desarrollado un modelo de deep learning mediante la implementación de librerías como TensorFlow y Keras.

El objetivo principal de este modelo es la clasificación de 6 categorías de vegetales. Los datos utilizados para este proyecto se obtuvieron del conjunto de datos de Kaggle denominado [Vegetables Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)

El conjunto de datos original de Kaggle contenía 15 clases de vegetales, pero para este modelo se redujo a 6, que son los siguientes:
* Bean
* Broccoli
* Cabbage
* Carrot
* Pumpkin
* Tomato

Cada clase posee 500 imágenes para la fase de train y 200 para las fases de test y validation.

El proceso de creación del modelo y las mejoras realizadas a lo largo de varias iteraciones están documentados en el Jupyter Notebook llamado *Vegetables_Classification.ipynb.

El modelo se ha guardado en dos formatos distintos debido a que [Tensorflow](https://www.tensorflow.org/tutorials/keras/save_and_load?hl=es-419) considera el formato .h5 como "legacy". Por lo tanto, para evitar futuros conflictos, se ha optado por almacenar el modelo en ambos formatos: .h5 y .keras, siendo este último el formato más actual y compatible.

Para evaluar el modelo guardado en cualquiera de estos dos formatos, se puede utilizar el Jupyter Notebook denominado *Test_Vegetables_Model.ipynb. Se han utilizado imágenes extraídas de Google Images que se encuentran en la carpeta 'examples' para realizar estas pruebas."