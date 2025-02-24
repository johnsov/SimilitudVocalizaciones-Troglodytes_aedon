# Análisis de Similitud de Vocalizaciones en Troglodytes aedon

## 📌 Descripción
Este repositorio contiene el código fuente del proyecto **"Análisis de similitud de vocalizaciones en poblaciones de *Troglodytes aedon* mediante técnicas de aprendizaje no supervisado"**, desarrollado como parte de mi trabajo de grado en la Maestría en Ciencia de Datos en la Universidad Icesi.

El objetivo principal del estudio fue analizar las vocalizaciones de *Troglodytes aedon* y evaluar su similitud entre poblaciones utilizando métodos de aprendizaje no supervisado. Para ello, se procesaron y analizaron grabaciones bioacústicas mediante técnicas de procesamiento de señales y modelos de redes neuronales convolucionales.

## 🛠️ Tecnologías y Herramientas
- **Lenguaje**: Python
- **Entorno de Ejecución**: Google Colab
- **Bibliotecas Utilizadas**:
  - `librosa` (procesamiento de audio)
  - `pandas` (manejo de datos)
  - `scikit-learn` (aprendizaje no supervisado)
  - `TensorFlow/Keras` (redes convolucionales)
  - `scikit-maad` (análisis de señales acústicas)

## 📂 Estructura del Repositorio
```
📁 analisis-similitud-vocalizaciones
 ├── 📄 README.md  # Este archivo
 ├── 📄 Download_EDA.ipynb  # Obtención de los datos de fuentes externas (xenocanto) y análisis exploratorio
 ├── 📄 Processing_Segmentation.ipynb  # Preprocesamiento de las grabaciones de audio
 ├── 📄 1R_CNN.ipynb  # Redes neuronales convolucionales: VGG16, VGG19, Resnet50, InceptionV3, Xception
 ├── 📄 1R_PCA_CLUS.ipynb  # Modelos de clustering y reducción dimensional 
```

## 📥 Descarga de Datos
Las grabaciones utilizadas en este estudio fueron descargadas directamente de [Xeno-canto](https://www.xeno-canto.org/), una base de datos colaborativa de grabaciones de cantos de aves. Para obtener los datos solo asegurate de ejecutar el notebook `Download_EDA.ipynb`

## 🚀 Ejecución del Proyecto
Dado que el proyecto se desarrolló en Google Colab, puedes ejecutarlo directamente en un entorno en la nube siguiendo estos pasos:

1. **Abrir Google Colab** y cargar los notebooks en el entorno.
2. **Ejecutar las celdas de cada notebook** en el siguiente orden:
   - `Download_EDA.ipynb`
   - `Processing_Segmentation.ipynb`
   - `1R_CNN.ipynb`
   - `1R_PCA_CLUS.ipynb`
3. **Asegurarse de tener las dependencias instaladas** ejecutando:
   ```python
   !pip install librosa pandas scikit-learn tensorflow scikit-maad
   ```

## 📢 Contacto
Si tienes preguntas o sugerencias, puedes contactarme en:
📧 Email: [sebastian.ovalle@outlook.com](mailto:sebastian.ovalle@outlook.com)
🔗 [LinkedIn](https://linkedin.com/in/sebastian-ovalle)

---
Este proyecto representa un avance en el análisis de patrones acústicos en aves mediante técnicas computacionales y aprendizaje automático. ¡Gracias por visitar este repositorio!
