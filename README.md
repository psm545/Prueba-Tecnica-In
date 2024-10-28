# Prueba Tecnica Data Analyst 

## **¡Bienvenido/a!** 

Para esta prueba técnica, queremos evaluar tus habilidades en SQL, Python (Pandas), y Power BI. La prueba está diseñada para durar alrededor de 3 horas, así que organiza tu tiempo de la mejor manera posible. A continuación, encontrarás las instrucciones y los pasos que debes seguir para completar la prueba.

## **Descripción del Caso**

Nuestra empresa **BCA Operations** opera en el sector de gambling y apuestas deportivas. Queremos analizar los datos de nuestros jugadores para entender mejor el comportamiento de los usuarios que han realizado su primer depósito (FTD) y aquellos que cumplen la condición de CPA. La condición para que un jugador sea considerado CPA es que su primer depósito sea mayor a un valor específico (ej. 100 USD). No todos los jugadores que hacen un primer depósito cumplen con esta condición, y algunos no han realizado depósitos.

### **Archivos Suministrados**
  - **players.csv:** Contiene información de los jugadores como ID, nombre, país y fecha de registro.
  - **deposits.csv:** Detalles de los depósitos de los jugadores, incluyendo el monto del depósito y la fecha.
  - **traffic_sources.csv:** Datos de adquisición de jugadores, incluyendo el costo de adquisición por jugador, el nombre del trafficker, y la fecha de registro.
  - **internal_records.csv:** Base de datos interna con registros mensuales de la cantidad de FTD y CPA que tiene la empresa para validación.

## **Objetivos de la Prueba**


**1. SQL: Creación de Base de Datos y Consultas:**
- Crea una base de datos SQL usando los archivos CSV proporcionados.
- Crea las tablas necesarias para almacenar la información y carga los datos de los CSV.
- Identifica los jugadores que hicieron su primer depósito (FTD) y filtra aquellos que cumplen con la condición de CPA (primer depósito mayor a 100 USD).
- Genera un reporte de la cantidad de FTD por mes y de CPA por mes.
  
**2.Python (Pandas) y Análisis de Calidad de Datos:**
- Extrae los datos resultantes de las consultas SQL y utiliza Pandas para analizar la calidad de los datos.
- Compara los resultados de FTD y CPA con los datos en internal_records.csv para identificar meses con discrepancias.
- Marca los meses en los que los datos de tu análisis no coinciden con los registros internos de la empresa.
- Usa Matplotlib para visualizar de manera clara cualquier discrepancia detectada.
  
**3- Power BI: Creación de un Dashboard:**
- Crea un dashboard en una sola página que incluya:
- Visualización de la cantidad de FTD por mes y CPA por mes.
- Evolución histórica de costo por registro (lead), costo por FTD, y costo por CPA.
- Identificación de los traffickers que generan más jugadores y el gasto asociado.
- Resalta cualquier hallazgo importante relacionado con las discrepancias de los datos.

## **Entregables**

**Jupyter Notebook:**

Desarrolla tu análisis en un Jupyter Notebook.
**Asegúrate de comentar cada sección del código para explicar qué estás haciendo y por qué.**
El código debe ser claro y fácil de seguir, con explicaciones de los pasos realizados.


**Informe en Notion:**

Crea un documento en Notion que incluya:

- Introducción a la prueba y al caso de análisis. 
- Explicación detallada de cada uno de los pasos realizados, con capturas de pantalla del Jupyter Notebook.
- Código utilizado en cada paso, con explicaciones de las consultas SQL, transformaciones de datos con Pandas, y visualizaciones.
- Conclusiones y hallazgos sobre el análisis realizado, incluyendo las discrepancias encontradas entre los registros y posibles explicaciones para las mismas.

**Power BI Dashboard:**

Exporta el dashboard creado en Power BI como un archivo .pbix.
Incluye capturas del dashboard en el informe de Notion y una breve descripción de las visualizaciones.

**Entrega de la Prueba**

Una vez que termines, comparte el enlace al documento de Notion y el archivo del Jupyter Notebook (en formato .ipynb).
Asegúrate de que el enlace a Notion esté configurado para que podamos visualizarlo. **(Acceso publico o seras descartado)**
Adjunta también el archivo .pbix del dashboard de Power BI.

## **Criterios de Evaluación**

- Calidad del código: Claridad, organización, y comentarios en el Jupyter Notebook.
- Exactitud de los resultados: Identificación correcta de FTD y CPA, así como las discrepancias con la base de datos interna.
- Calidad de las visualizaciones: Uso de gráficos adecuados en Python y Power BI para presentar los resultados.
- Capacidad de análisis: Profundidad de las conclusiones y explicaciones en el informe de Notion.
- Comunicación: Capacidad para explicar claramente los hallazgos y procesos.
- Presentacion
  
Tiempo Estimado: 3 horas

### **¡Buena suerte y esperamos ver tu análisis!**
