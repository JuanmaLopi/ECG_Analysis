# Clasificación de Arritmias Cardíacas mediante ECG con IA

![ECG Sample](https://www.oxfordmedicaleducation.com/wp-content/uploads/2014/07/ECG-Question-5-normal.jpg) <!-- Puedes agregar una imagen representativa -->

Proyecto de inteligencia artificial para la clasificación automática de arritmias cardíacas mediante señales de electrocardiografía (ECG), implementado en un pipeline completo desde el procesamiento de datos hasta el modelado predictivo.

## 📌 Objetivo

Desarrollar un modelo de deep learning capaz de clasificar distintos tipos de arritmias cardíacas utilizando el dataset PTB-XL, uno de los conjuntos de datos públicos de ECG más grandes disponibles.

## 🗃️ Dataset

Utilizamos el [PTB-XL ECG Dataset](https://physionet.org/content/ptb-xl/1.0.3/):
- 21,837 registros ECG de 10 segundos
- 12 derivaciones estándar
- 5 categorías diagnósticas principales
- Frecuencia de muestreo: 500Hz

## 📂 Estructura simplificada  

```plaintext
data/
├── raw/
│   ├── ptbxl_database.csv      # Metadatos completos
│   ├── scp_statements.csv      # Códigos diagnósticos SCP 
│   └── records500/             # Señales ECG en 500Hz 

notebooks/
├── ECG_EDA.ipynb               # Análisis Exploratorio Inicial

```

## 📜 Licencia
Este proyecto utiliza la licencia MIT.

> [!NOTE]  
> 🚧 **Este proyecto está en desarrollo.** Algunas secciones pueden cambiar o estar incompletas.
