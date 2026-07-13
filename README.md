# Clasificador-de-tipos-de-fracturas.
# 🦴 Bone Fracture Detection using Computer Vision

Este repositorio contiene el desarrollo de un modelo de visión por computadora diseñado para la detección y localización de fracturas óseas en radiografías utilizando arquitecturas de aprendizaje profundo. El proyecto sigue la metodología **KDD (Knowledge Discovery in Databases)** para garantizar un proceso riguroso de selección, preprocesamiento y modelado de datos médicos.

---

## 📊 Metodología del Proyecto (Proceso KDD)

Para el desarrollo del cuaderno de entrenamiento (`FractureDetection.ipynb`), se implementaron las siguientes etapas del proceso KDD:

1. **Selección de Datos:** Identificación y filtrado de imágenes de rayos X pertinentes (enfoque en estructuras óseas y áreas articulares específicas).
2. **Preprocesamiento:** Limpieza de artefactos visuales, normalización de contraste y ajuste de resoluciones para homogeneizar el dataset médico.
3. **Transformación:** Aplicación de técnicas de aumentación de datos (Data Augmentation) adecuadas para radiografías, resguardando la integridad anatómica de las imágenes.
4. **Minería de Datos (Data Mining):** Configuración y entrenamiento del modelo de redes neuronales convolucionales para tareas de detección de objetos / segmentación.
5. **Evaluación e Interpretación:** Análisis de métricas de precisión, curvas de pérdida y validación visual de las predicciones frente al *ground truth*.

---

## 🛠️ Tecnologías y Librerías Utilizadas

El desarrollo del pipeline de Machine Learning se realizó en Python, utilizando las siguientes herramientas principales:

* **Lenguaje:** Python 3.x
* **Entorno:** Jupyter Notebook (`.ipynb`)
* **Procesamiento de Imágenes:** OpenCV, Pillow (PIL)
* **Modelado y Deep Learning:** PyTorch / TensorFlow (o la arquitectura específica que uses, ej: *YOLO, Ultralytics, Hugging Face*)
* **Análisis y Visualización:** NumPy, Matplotlib, Seaborn

---

## 🚀 Contenido del Repositorio

* `FractureDetection.ipynb`: Notebook principal que contiene todo el flujo de trabajo, desde la carga y exploración de los datos médicos hasta la evaluación final del modelo entrenado.
* *(Opcional - añade aquí si tienes carpetas de datos/gráficos, por ejemplo: `data/`, `models/`, `weights/`)*

---

## 📈 Próximos Pasos y Trabajo Futuro

* Optimización de hiperparámetros mediante técnicas de Fine-Tuning.
* Expansión del dataset para incluir clasificaciones específicas por tipos de fractura (ej: supracondíleas, diafisiarias, etc.).
* Integración y pruebas con arquitecturas avanzadas de segmentación para delimitar con mayor precisión el trazo de la fractura.

---
