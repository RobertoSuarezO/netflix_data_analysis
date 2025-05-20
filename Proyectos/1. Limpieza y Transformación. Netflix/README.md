# Análisis de Datos de Netflix

Este proyecto realiza un análisis exploratorio de datos sobre el catálogo de contenido de Netflix, utilizando Python y diversas bibliotecas de análisis de datos y visualización.

## 📋 Descripción

El proyecto se centra en la limpieza, transformación y análisis de datos del catálogo de Netflix para obtener insights sobre el contenido disponible en la plataforma.

## 🔍 Proceso de Limpieza y Transformación de Datos

### 1. Configuración Inicial
- Importación de bibliotecas necesarias (pandas)
- Configuración de pandas para mostrar todas las columnas

### 2. Limpieza de Datos
- Manejo de valores nulos en la columna 'director'
- Eliminación de duplicados en el dataset
- Normalización de formatos de fecha
- Limpieza de categorías y géneros

### 3. Transformación de Datos
- Creación de nuevas columnas para análisis temporal
- Extracción de información de fechas (año, mes, día)
- Procesamiento de texto para análisis de descripciones
- Normalización de categorías y etiquetas

### 4. Preparación para Visualización
- Agrupación de datos para análisis específicos
- Creación de métricas derivadas
- Preparación de datos para gráficos y dashboards

### 5. Creación del Dashboard en Power BI
- Desarrollo de un dashboard interactivo en Power BI para visualizar los insights clave del análisis.
- Inclusión de visualizaciones como conteos totales (países, shows, series, películas), distribución por año de lanzamiento, desglose por clasificación de edad, categorías/géneros más frecuentes y distribución geográfica por país.
- Word Cloud para detectar temas recurrentes en las descripciones de los shows.
- El dashboard permite una exploración visual de los datos limpios y transformados.

## 🚀 Configuración del Entorno

### Prerrequisitos

- Python 3.12 o superior
- Jupyter Notebook
- pip (gestor de paquetes de Python)

### Instalación

1. Clona este repositorio o descarga los archivos

2. Crea un entorno virtual (recomendado):
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. Instala las dependencias necesarias:
```bash
pip install -r requirements.txt
```

## 📦 Dependencias Principales

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## 📊 Estructura del Proyecto

```
├── netflix_analysis.ipynb     # Notebook principal con el análisis
├── README.md                  # Este archivo
└── requirements.txt           # Archivo de dependencias
```

## 🛠️ Uso

1. Activa el entorno virtual si lo creaste
2. Inicia Jupyter Notebook:
```bash
jupyter notebook
```
3. Abre el archivo `netflix_analysis.ipynb`

## 📈 Análisis Incluidos

- Limpieza y preparación de datos
- Análisis exploratorio
- Visualizaciones de datos
- Insights sobre el contenido de Netflix

## 👥 Autor

[Roberto Suárez]

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo `LICENSE` para detalles