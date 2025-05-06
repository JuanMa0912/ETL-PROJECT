# SAION SMART SOLUTIONS - ETL

## Descripción del Proyecto
SAION SMART SOLUTIONS es una empresa colombiana de tecnología especializada en consultoría SAP. Con sede en Medellín, opera a nivel nacional e internacional, brindando soluciones a entidades gubernamentales, empresas de capital mixto, transporte, manufactura, energía y servicios públicos.

Este proyecto se centra en la **Extracción, Transformación y Carga (ETL)** de datos relacionados con la demanda de consultoría, permitiendo el análisis y optimización de recursos.

## Preguntas de Análisis
El notebook busca responder preguntas clave para optimizar la disponibilidad de consultores y mejorar los costos operativos:

1.	¿Qué tipo de consultoría demanda en mayor cantidad cada cliente y en que horarios para poder planear la disponibilidad de consultores ubicados en diferentes países en un esquema 7x24 y buscar disminuir costos para mejorar el precio ofertado?

2.	¿Cuáles son los tipos de consultoría de mayor demanda desde las 6pm a las 6am (Horario Soporte Nocturno On-Demand) y en que franjas de horario se tienen mayores solicitudes para mejorar el número de consultores que se encuentran disponibles en un momento determinado y poder reducir costos y mejorar precio ofertado?

3.	¿Cuáles son los meses, días y horarios valles (con menor demanda) para los diferentes tipos de consultoría que permita proponer a los clientes tarifas dinámicas?

4.	¿Qué consultores son los más requeridos por el cliente en la prestación de los servicios para generar planes de transferencia de conocimiento?

5.	¿Cuál es el tiempo de atención promedio en días de cada tipo de consultoría, el peor y mejor escenario y que consultores tiene los mejores tiempos de respuesta?

6.	¿Cuál es el esfuerzo promedio en horas para cada tipo de consultoría, el peor y mejor escenario?

## Descripción del Código
El código del notebook realiza las siguientes tareas:

- **Carga de datos** desde un archivo Excel.
- **Limpieza y preprocesamiento**:
  - Conversión de fechas y horas.
  - Creación de columnas auxiliares.
- **Análisis de demanda**:
  - Cálculo de la cantidad de solicitudes por cliente, tipo de servicio y hora.
  - Identificación del servicio más demandado por cliente en diferentes franjas horarias.
- **Generación de reportes** con estadísticas clave.

## Requisitos
Para ejecutar este notebook, se requiere:

- `Python 3`
- `Pandas`
- `Jupyter Notebook`

## Uso
1. Descarga el archivo de datos `Data.xlsx` y ubícalo en la ruta correspondiente.
2. Abre y ejecuta el notebook `ETL.ipynb` en **Jupyter Notebook** o **Visual**.
3. Analiza los resultados y ajusta los parámetros según sea necesario.
