# Proyecto de Procesamiento de Imágenes con NeRF

Este proyecto implementa funciones de procesamiento de datos y representación gráfica utilizando NeRF (Neural Radiance Fields), PyTorch, NumPy y otras dependencias en un entorno Jupyter Notebook. Su objetivo es predecir cómo se vería un objeto desde distintas perspectivas basándose en imágenes de entrada y parámetros de cámara. El proyecto está diseñado para trabajar con un conjunto de imágenes y sus respectivos archivos de parámetros de cámara, que incluyen matrices de "intrinsics" y "pose". Estos archivos contienen datos importantes sobre la configuración y orientación de la cámara para cada imagen.

## Estructura del Proyecto

- **Notebook**: El archivo principal del proyecto es un Jupyter Notebook que incluye las implementaciones de las funciones de procesamiento de imágenes. 

- **Dependencias**: Este proyecto utiliza PyTorch para la creación de tensores y operaciones de redes neuronales, y NumPy para la manipulación de datos. 

- **Imágenes y Archivos de Parámetros**: Cada imagen en el conjunto de datos cuenta con dos archivos de parámetros: uno para "intrinsics" y otro para "pose". Estos archivos permiten configurar la cámara y definir su orientación espacial en cada captura.

## Descripción de Archivos

Cada imagen en el proyecto cuenta con archivos correspondientes de "intrinsics" y "pose", los cuales contienen datos importantes para la configuración de cámara y orientación espacial.

- **Intrinsics**: Define los parámetros internos de la cámara para cada imagen. Estos parámetros suelen incluir la distancia focal y el punto principal en la imagen.

- **Pose**: Define la orientación de la cámara en el espacio tridimensional y su posición relativa a un sistema de referencia.
