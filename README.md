# Proyecto de Clasificación de Zapatos con Deep Learning

Este proyecto implementa una red neuronal convolucional (CNN) para la clasificación de imágenes de zapatos en cinco categorías: **Ballet Flat**, **Boat**, **Brogue**, **Clog** y **Sneaker**. Utiliza un dataset de clasificación de zapatos con aproximadamente 13,000 imágenes divididas en las clases mencionadas, optimizado para entrenar y evaluar modelos de deep learning en tareas de clasificación de imágenes.

EL MODELO ES MUY PESADO EN KERAS, NO SE PUEDE SUBIR AL REPOSITORIO, EN FORMATO .H5 SI SE PUEDE




## Sobre el Dataset

El dataset de imágenes de zapatos está dividido en 4 secciones: 

- **Train**: contiene 2,000 imágenes de cada clase para el entrenamiento del modelo.
- **Valid**: conjunto de imágenes para la validación y ajuste de hiperparámetros.

Este dataset proporciona una base sólida para desarrollar un modelo robusto de clasificación, con imágenes de alta calidad y bien distribuidas entre las clases, ideal para evaluar la precisión de la red neuronal.

## Arquitectura del Modelo

El modelo CNN se construye con múltiples capas convolucionales y de pooling, junto con normalización y regularización para mejorar la precisión y reducir el sobreajuste. Además, se emplean callbacks como `ReduceLROnPlateau` y `EarlyStopping` para optimizar el rendimiento del modelo durante el entrenamiento.

## Aplicación

El proyecto incluye una función para cargar nuevas imágenes y clasificarlas utilizando el modelo entrenado, lo que permite su aplicación práctica en casos de uso reales de clasificación de zapatos.
