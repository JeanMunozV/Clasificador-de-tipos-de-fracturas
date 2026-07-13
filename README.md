# Clasificador-de-tipos-de-fracturas.
# 🦴 Bone Fracture Detection using Computer Vision

Este repositorio contiene el desarrollo de un modelo de visión por computadora diseñado para la detección y localización de fracturas óseas en radiografías utilizando arquitecturas de aprendizaje profundo.

---

## 🛠️ Tecnologías y Librerías Utilizadas

El desarrollo del pipeline de Machine Learning se realizó en Python, utilizando las siguientes herramientas principales:

* **Lenguaje:** Python 3
* **Entorno:** Jupyter Notebook.
* **Procesamiento de Imágenes:** OpenCV, Pillow (PIL).
* **Modelado y Deep Learning:** PyTorch / TensorFlow / Yolo26n.
* **Análisis y Visualización:** NumPy, Matplotlib, Seaborn.
* **Dataset**: Mendeley

---

## 🚀 Contenido del Repositorio

* `FractureDetection.ipynb`: Notebook principal que contiene todo el flujo de trabajo, desde la carga y exploración de los datos médicos hasta la evaluación final del modelo entrenado.

---

## 🚀 Guía de Ejecución Paso a Paso

Sigue estos pasos para configurar el entorno y ejecutar el modelo de detección de fracturas en tu máquina local:

### 1. Clonar el Repositorio
Abre tu terminal y clona este proyecto en tu computadora:
1.- git clone link_este_repo
    cd este_repo
2.- Configurar el Entorno Virtual
Windows: python -m venv venv
        .\venv\Scripts\activate
Linux: python3 -m venv venv
        source venv/bin/activate
4.- Instalar dependencias
    pip install --upgrade pip
    pip install jupyter notebook ultralytics roboflow opencv-python matplotlib seaborn

5.- Iniciar Jupyter Notebook
    jupyter notebook
