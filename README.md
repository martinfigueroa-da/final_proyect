# final_proyect
📊 Proyecto RappiPlus: De datos a decisiones de negocio.

RappiPlus es un servicio de suscripción dentro del ecosistema de Rappi diseñado para aumentar la frecuencia de compra y el valor generado por usuario.
Sin embargo, el equipo de negocio no tiene claro si el servicio está cumpliendo su objetivo.

Existen dudas clave:

¿Los usuarios realmente compran más?
¿El modelo está generando ganancias?
¿Se están perdiendo oportunidades en el proceso de compra?

🎯 Objetivo del proyecto
A lo largo de este proyecto se tuvieron que responder las preguntas:

¿Podemos confiar en los datos?
¿Estamos ganando dinero?
¿Dónde se pierden los usuarios?
¿Los usuarios regresan?
¿Los cambios generan impacto?
¿Cómo comunicamos todo esto?

Se presenta el diagrama de flujo de trabajo para que se entienda el proceso:
<img width="544" height="453" alt="image" src="https://github.com/user-attachments/assets/2b94d5a3-b63e-4061-b867-fa1076ca7020" />
🔹 Paso 1: Preparación y calidad de datos con Python
Se cargan las librerias correspondientes, se cargan los datasets, cambiando los dataframes para facilidad de uso, se detecta y se estandarizan valores, eliminando duplicados, revisando datos numericos consistentes, revisar variables numericas.
dejando 3 datasets limpios para su exportacion y comenzar con el paso 2.

🔹 Paso 2: Análisis de rentabilidad del negocio con Python
En este paso el equipo quiere saber si el negocio esta generando realmente ganancias, por el cual se calculan los indicadores de valores clave para evaluar ingresos, costos y rentabilidad, utilizando los 3 dtasets ya limpios y exportados.

🔹 Paso 3: Análisis del funnel de conversión con SQL
El planteamiento es "en donde los usuarios abandonan y no completan la compra", Analizar el comportamiento de los usuarios para identificar en qué etapa del proceso se pierden.
⚙️**Conexión a la base de datos**:  
Se ejecuta la línea de configuración para conectar con la base de datos y aplicar consultas SQL en la tabla **events**.
se procede a hacer la construccion del funnel, y se hace la conexion.

🔹 Paso 4: Análisis de retención por cohortes con SQL
Analizar la retención de usuarios para entender si regresan después de registrarse.

🔹 Paso 5: Validar si los cambios generan impacto (test estadístico)
 Evaluar si la modificación en la UI del checkout impacta la **tasa de conversión de compra**

 🔹 Paso 6: Comunicar los resultados (Dashboard en BI)
 Crear un dashboard que muestre de manera clara y visual los resultados del análisis de ventas, costos, marketing y conversión. 
 Se usarán los CSVs previamente limpiados y exportados


