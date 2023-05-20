**DeepVogue - Taller 2 de Introducción a Redes Neuronales y Deep Learning**

Proyecto de Deep Learning en el que se busca entrenar redes para categorizar fotos de prendas de ropa. El problema se divide en 3 partes: 

-Categorización multiclase: Predecir tipos de prenda (Chaqueta, Shorts, Parka, etc).

-Categorización multietiqueta: Predecir atributos en base a un csv, hay 1000 atributos distintos que describen distintas características de cada prenda.

-Búsqueda de proximidad: Tras predecir las categorías y los atributos para todos los datos de test, se debe hacer una archivo csv en que, para cada foto en el dataset de test, se haga una lista con las 100 fotos que más se le parezcan.

Cosas por hacer:<br />
-Correr el classification report con más datos (puede ser sobre el reduced train)<br />
-Crear un custom data generator para clasificar tener los atributos como labels (ver https://medium.com/analytics-vidhya/write-your-own-custom-data-generator-for-tensorflow-keras-1252b64e41c3)<br />
-Probar una weighted_binary_crossentropy para poder predecir atributos<br />
--De lo contrario, buscar una solución alternativa, como sólo buscar predecir los atributos más frecuentes
