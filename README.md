# Datascience-Challenge2
Challenge Telecom X: análisis de evasión de clientes - Parte 2

 Este README proporciona instrucciones para ejecutar el cuaderno de Google Colab  para analizar el churn de clientes usando datos_tratados.csv. 
 El cuaderno incluye preprocesamiento, análisis exploratorio, entrenamiento de modelos (Regresión Logística y Bosque Aleatorio) y recomendaciones estratégicas.
 El cuaderno predice el churn basado en características como customerID, Churn, gender, tenure, Charges.Monthly, entre otras.
 Realiza:Preprocesamiento (manejo de valores faltantes,     codificación, SMOTE).
 
Análisis exploratorio con visualizaciones.
Entrenamiento y evaluación de modelos.
Análisis de importancia de características y estrategias de retención.

Requisitos Previos 
Google Colab

Instrucciones de Configuración

1. Abrir el CuadernoDescarga TelecomX2_LATAM.ipynb.
Abre Google Colab.
Sube el cuaderno: Archivo > Subir cuaderno y selecciona el archivo.

2. Instalar BibliotecasEjecuta esta celda al inicio del cuaderno:python

!pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn.

3. Cargar el Dataset
   Opción 1: Subir a ColabEn Colab, haz clic en Archivos > Subir y carga datos_tratados.csv.


data = pd.read_csv('/content/datos_tratados.csv')

Opción 2: Google DriveMonta tu Drive:python

from google.colab import drive
drive.mount('/content/drive')

Copia datos_tratados.csv a tu Drive ( MyDrive/datasets/).
Actualiza la ruta:

data = pd.read_csv('/content/drive/MyDrive/datasets/datos_tratados.csv')




