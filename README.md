# ia1--Ingeniebrios---Proyecto-de-Reconocimiento-de-Emociones-Faciales-
Proyecto de Reconocimiento de Emociones Faciales


Curso: Inteligencia Artificial I - 2025-2 C1

Equipo: Ingeniebrios

Integrantes: 
###Diego Andres Barragan Ruiz 2211827
###Michael Andres Fabre Beltran 2191119
###David Alexander Sandoval Suarez 2205088



Se utilizará el dataset Facial Emotion Recognition Image Dataset disponible en Kaggle
Contiene 15500 imágenes clasificadas en 7 emociones (enojado, asustado, feliz, triste, neutral, sorprendido, disgusto). 
LINK: https://colab.research.google.com/drive/1KQUgMiHoQp7-Lb3-qGoSRdP2vB5sHXKu




El problema consiste en reconocer de manera automática las emociones humanas a partir de imágenes faciales. Esto es importante porque las emociones son importantes em la interacción social y la comunicación no verbal. El desarrollo de sistemas capaces de identificar emociones tiene aplicaciones en áreas como salud mental, educación, seguridad y atención al cliente.


La fase de EDA permite comprender las características principales del dataset, identificar posibles desbalances en las clases de emociones, verificar la calidad de las imágenes y obtener información descriptiva que guíe las decisiones de preprocesamiento y modelado.


Métricas como la distribución de imágenes por clase, el conteo de ejemplos disponibles para cada emoción y la calidad de las imágenes serán parte del trabajo del dataset. 

¿Por qué son útiles las métricas mencionadas? 
Estas métricas permiten detectar problemas de desbalance de clases, evaluar la robustez del dataset y asegurar que el modelo no favorezca ciertas emociones. 

Motivación de la elección 
El problema fue elegido porque  es interesenta comprender como tal las emociones y tambien conecta con la visión de lo que estamos viendo y por ver acerca de la inteligencia artificial, además de tener un alto potencial de aplicación práctica en distintos sectores.



Datos utilizados 
Se usó el dataset Facial Emotion Recognition Image Dataset con imágenes de rostros humanos, organizadas en formato tabular con etiquetas categóricas de emociones.

Información contenida en los datos (máx. 100 palabras)
El dataset contiene 15500 imágenes clasificadas en siete categorías emocionales: enojo, disgusto, miedo, felicidad, tristeza, sorpresa y neutralidad. Cada fila incluye la etiqueta de la emoción y la representación en píxeles de la imagen. La distribución de clases es desbalanceada, con mayor número de ejemplos en unas que otras. Este análisis inicial es clave para determinar estrategias de balanceo y asegurar un entrenamiento más justo de los modelos de clasificación.
