# 📁 Análisis de Imágenes: Natalie Portman vs Scarlett Johansson  
Proyecto de análisis de datos y preprocesamiento utilizando dos clases del dataset de celebridades: **Natalie Portman** y **Scarlett Johansson**.  
Se desarrolló un pipeline completo de exploración, análisis estadístico, detección de duplicados, outliers y preprocesamiento para modelos de Deep Learning.

---

## 📌 Contenido del proyecto

Este repositorio incluye:

- Exploración general del dataset:
  - Número total de imágenes por clase
  - Formatos y resoluciones
  - Imágenes corruptas o vacías
  - Balance de clases
  - Variabilidad (iluminación, fondo, orientación, ruido, etc.)
- Análisis estadístico:
  - Media RGB por canal
  - Desviación estándar por canal
  - Detección de imágenes muy oscuras o muy brillantes (outliers)
- Limpieza del dataset:
  - Detección de imágenes duplicadas con hashing perceptual
  - Identificación de archivos corruptos
  - Imágenes incorrectamente etiquetadas (según outliers/errores)
- Preprocesamiento:
  - Redimensionamiento
  - Normalización
  - Conversión a tensores
  - Preparación para redes neuronales (PyTorch / TensorFlow)
- Aumento de datos (Data Augmentation)

---

## 📦 Dataset

Debido al tamaño del dataset, no se incluye directamente en el repositorio.  
Puedes descargarlo desde:
https://drive.google.com/file/d/1mML0Tm4_F_I__uQ4xYWOKDm5Z5u6yBmq/view?usp=sharing

🔗 **Enlace a Google Drive:**  
*Añade aquí tu enlace cuando lo tengas*  
## 🚀 Cómo ejecutar el análisis (Google Colab)

1. Abre este enlace (o sube el notebook al Colab):
2. Sube tu archivo `archive.zip`
3. Ejecuta todas las celdas del notebook:

```python
# Ejecutar análisis completo
!python analisis_dataset.ipynb

##**Requerimientos del proyecto**

numpy
matplotlib
pillow
torch
torchvision
tensorflow
Si deseas instalarlos localmente:

pip install numpy matplotlib pillow torch torchvision tensorflow

📊 Resultados obtenidos

El análisis genera:

✔ Resumen del dataset
✔ Estadísticas RGB por clase
✔ Outliers detectados
✔ Lista de duplicados
✔ Imagen aumentada (Data Augmentation Example)
✔ Preprocesamiento listo para redes neuronales

Los resultados se muestran directamente en Colab.
