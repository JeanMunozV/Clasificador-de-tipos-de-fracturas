# Clasificador-de-tipos-de-fracturas.
# 🦴 Bone Fracture Detection using Computer Vision

Este repositorio contiene el desarrollo de un modelo de visión por computadora diseñado para la detección, localización y clasificación de tipo de fracturas óseas en radiografías utilizando arquitecturas de deep learning. Utilizando un dataset del repositorio Mendeley Data.

---

## 🛠️ Tecnologías y Librerías Utilizadas

El desarrollo del pipeline de Machine Learning se realizó en Python, utilizando las siguientes herramientas principales:

* **Lenguaje:** Python 3
* **Entorno:** Jupyter Notebook.
* **Procesamiento de Imágenes:** OpenCV, Pillow (PIL).
* **Librerias:** PyTorch / TensorFlow / NumPy, Matplotlib, Seaborn.
* **Modelo utilizado:** Yolo26n con 100 epocas.

## Dataset
Se utilizó Mendeley Data para la búsqueda de datasets previos respecto al área. Nuestro dataset tiene 567 imagenes compuesto por dos clases SIMPLES y CONMINUTAS.
# Data Augmentation realizada al dataset previo:
* Rotation: Between -8° and +8°
* Brightness: Between -20% and +20%
# Fragmentación del dataset (75% / 15% / 10%)
* 852 train images (75%)
* 170 valid images (15%)
* 113 test images (10%)

---

## 🚀 Contenido del Repositorio

* `FractureDetection.ipynb`: Notebook principal que contiene todo el flujo de trabajo, desde la carga y exploración de los datos médicos hasta la evaluación final del modelo entrenado.

---

## 🚀 Guía de Ejecución Paso a Paso

Sigue estos pasos para configurar el entorno y ejecutar el modelo de detección de fracturas en tu máquina local:

### 1. Clonar el Repositorio
Abre tu terminal y clona este proyecto en tu computadora:
    git clone link_este_repo
    cd este_repo
### 2.- Configurar el Entorno Virtual
Windows: python -m venv venv
        .\venv\Scripts\activate
Linux: python3 -m venv venv
        source venv/bin/activate
### 4.- Instalar dependencias
pip install --upgrade pip
pip install jupyter notebook ultralytics roboflow opencv-python matplotlib seaborn

### 5.- Iniciar Jupyter Notebook
jupyter notebook
