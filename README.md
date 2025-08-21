# Reconocimiento Facial con PCA (Eigenfaces)

Este proyecto es una implementación del algoritmo de **Eigenfaces** utilizando Análisis de Componentes Principales (PCA) para el reconocimiento y reconstrucción de rostros. El análisis se realizó en un entorno de Google Colab con Python y las principales librerías de computación científica como NumPy y Matplotlib.

## Descripción del Proyecto

El objetivo es construir un sistema capaz de:
1.  Aprender las características principales de un conjunto de rostros de entrenamiento.
2.  Utilizar este conocimiento para reconocer a personas en un conjunto de imágenes de prueba.
3.  Reconstruir cualquier rostro utilizando un número variable de "eigenfaces" o componentes principales.

Este proyecto fue desarrollado como parte de la asignatura de Algebra Lineal Avanzada de la Maestría en Ciencias de la Inteligencia Artificial de la FIUNA.

## Estructura del Repositorio
-   **`PCA_faces/`**: Contiene 150 imágenes de rostros en formato `.png` (240x240 píxeles) que se utilizan para entrenar el modelo PCA.
-   **`recognition_faces/`**: Contiene 15 imágenes de los mismos sujetos que en el conjunto de entrenamiento, pero con diferentes expresiones, usadas para probar la eficacia del reconocimiento.
-   **`Codigo_PCA.ipynb`**: Es el archivo principal del proyecto. Contiene todo el código Python, las explicaciones paso a paso, los cálculos matemáticos y la visualización de los resultados.

## Requisitos e Instalación

Para ejecutar este proyecto, necesitas tener Python 3 instalado. Las librerías necesarias se pueden instalar a través de `pip`.

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    cd tu-repositorio
    ```

2.  **Crea un entorno virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

3.  **Instala las dependencias:**
    ```bash
    pip install numpy matplotlib pillow jupyter
    ```

## Cómo Ejecutar el Código

La forma más sencilla de ejecutar el proyecto es abrir el notebook de Jupyter.

1.  **Inicia Jupyter Lab o Jupyter Notebook:**
    ```bash
    jupyter lab
    ```
    o
    ```bash
    jupyter notebook
    ```

2.  **Abre el archivo `Codigo_PCA.ipynb`** en tu navegador.

3.  **Ejecuta las celdas en orden**: El notebook está diseñado para ser ejecutado celda por celda. Cada celda realiza una parte del análisis, desde la carga de datos hasta la visualización de los resultados finales.

## Resultados Principales

El notebook te guiará a través de los siguientes resultados clave:
-   Cálculo y visualización del "rostro promedio".
-   Extracción y visualización de los "eigenfaces".
-   Análisis de reconocimiento facial.
-   Reconstrucción de imágenes con 10, 50 y 100 componentes.

Observación: El código está preparado para ser descargado y subir las carpetas a utilizar en un Drive para realizar las pruebas.
---
