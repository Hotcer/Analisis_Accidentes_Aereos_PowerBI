
# Análisis de Accidentes Aéreos 🛩️

## Descripción del Problema y Rol Desarrollado 👨‍💻

La Organización de Aviación Civil Internacional (OACI) quería investigar en profundidad los accidentes aéreos ocurridos desde inicios del siglo XX. El objetivo era obtener un análisis de datos y un dashboard visual para comprender mejor las causas de los accidentes y mejorar la seguridad en la aviación.

En este proyecto asumí el rol de analista de datos de una consultora contratada por la OACI. Mi tarea fue realizar un exhaustivo análisis de los datos de accidentes aéreos y crear un dashboard interactivo para presentar los hallazgos.

## Contenido del Repositorio 🗂️

- `Notebooks/` 📓

  - `01_EDA.ipynb`: Análisis exploratorio de datos en Python/Pandas 

- `Src/` 🖥️

  - `processing.py`: Scripts de limpieza y procesamiento de datos

  - `visualization.py`: Scripts para creación de gráficos y visualizaciones

- `Data/` 📊

  - `airplane_accidents.csv`: Dataset de accidentes aéreos

  - `processed_data.csv`: Datos limpios y procesados
  
- `Docs/` 📑

  - `EDA_Report.pdf`: Informe detallado del EDA

  - `Dashboard_Guide.pdf`: Guía de uso del dashboard

- `Dashboard/` 📊

  - `Airplane_Dashboard.pbix`: Archivo de Power BI con el dashboard

  - `Screenshots/`: Capturas del dashboard

- `README.md`: Este archivo

## Análisis Exploratorio de Datos 🕵️‍♂️

El EDA (en el notebook `01_EDA.ipynb`) incluyó:

- Revisión de datos faltantes

- Detección y tratamiento de outliers 

- Análisis de duplicados

- Análisis de distribución y correlación de variables

- Documentación detallada de hallazgos y conclusiones

## Dashboard Interactivo 📈

El dashboard en Power BI permite:

- Filtrar por país, aerolinea, año, etc. 🗺️

- Visualizar accidentes por región geográfica 🌎

- Comparar tasa de fatalidad por década ⚰️

- Analizar causas raíz de accidentes 🕵️

- Exportar e imprimir visualizaciones 🖨️

## KPIs Propuestos 📊

- Disminución de 10% en tasa de fatalidad de tripulación 👨‍✈️

- Accidentes por región en los últimos 20 años 🌎

Ambos KPIs fueron medidos, graficados y analizados en detalle en el dashboard.

## Base de Datos 🗄️

Se creó una base de datos SQLite para almacenar los datos procesados y utilizarla como origen en el dashboard.

## Scripts de Python 🐍 

Se incorporaron scripts en Python para las tareas de procesamiento y visualización de datos.

## Conclusiones ✅

El proyecto permitió aplicar habilidades de limpieza, análisis y visualización de datos. El dashboard interactivo facilita la exploración de insights para mejorar la seguridad aérea.

