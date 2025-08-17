# TelecomX_LATAM

Proyecto Telecom X Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) y preparar un conjunto de datos de clientes de Telecom X para el modelado predictivo de la cancelación de servicios (churn).

Estructura del Notebook El notebook está dividido en las siguientes secciones:

Extracción: Carga de los datos desde un archivo JSON. Transformación: Limpieza y transformación de los datos, incluyendo la corrección de tipos de datos, manejo de valores nulos y renombre de columnas. Carga y Análisis: Visualización de datos para identificar patrones y relaciones, centrándose inicialmente en la relación entre el tipo de contrato y la tasa de cancelación. Informe Final: Resumen de los hallazgos iniciales y la preparación del conjunto de datos para análisis posteriores. Datos El conjunto de datos TelecomX_Data.json contiene información sobre clientes de una empresa de telecomunicaciones, incluyendo detalles de sus servicios, información demográfica y si han cancelado el servicio (Churn).

Requisitos Este notebook utiliza las siguientes librerías de Python:

pandas json matplotlib seaborn Estas librerías están preinstaladas en Google Colab.

Uso Clonar o descargar el notebook. Subir el archivo TelecomX_Data.json al entorno de Colab. Ejecutar las celdas del notebook secuencialmente. Resultados El análisis inicial muestra una fuerte correlación entre el tipo de contrato y la tasa de churn, con los clientes con contratos mes a mes presentando una mayor propensión a cancelar. El dataframe transformado (df_transformed) está listo para ser utilizado en la construcción de modelos predictivos de churn.

Próximos Pasos El equipo de Data Science puede tomar el dataframe df_transformed y realizar un análisis más profundo, aplicar técnicas de ingeniería de características y entrenar modelos de clasificación para predecir la probabilidad de churn de los clientes.
