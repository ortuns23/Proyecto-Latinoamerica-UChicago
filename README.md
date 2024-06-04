# Proyecto-Latinoamerica-UChicago

Aplicación de Modelos de Machine Learning e Inteligencia Artificial a datos macroeconómicos de Latinoamérica 

Miembros del equipo:
Este proyecto será desarrollado por estudiantes del curso Inteligencia Artificial y Machine Learning - septiembre 2023 de la Universidad de Chicago y se listan a continuación:

1.	Camilo Andres Cruz Nieves
2.	Alejandro Magos
3.	Álvaro Ortuzar
   
Descripción del caso:
El Fondo Latinoamericano de Reservas (FLAR), es el resultado de un acuerdo financiero regional entre Bolivia, Ecuador, Colombia, Perú y Venezuela que se constituyó con el propósito de que estos países tuvieran una institución financiera propia para facilitar el proceso integración regional y afrontar problemas derivados de desequilibrios externos a sus economías. Con los años y como resultado de su loable gestión su misión se ha extendido a otros países de Latinoamérica contando en este momento con nueve países miembros.
Como parte de los servicios financieros que el FLAR ofrece a sus países miembros corresponde a diferentes líneas de crédito de acuerdo a ciertas condiciones (por ejemplo, apoyo a la balanza de pagos), para poder estudiar y determinar “el comportamiento crediticio” de sus países miembros y de la región inicio la recolección, estandarización y publicación de los datos macroeconómicos mediante el Sistema de Información Económica SIE.
Es de gran interés tanto para la academia como para la operación del FLAR obtener insigths basado en estos datos, sin embargo, a la fecha no se ha establecido un proyecto que implique el uso de machine learning o inteligencia artificial sobre estos datos, por lo cual es de interés para la organización poder experimentar y obtener conclusiones de los datos SIE.
En síntesis, contamos con alrededor de 90.000 valores observados de un indicador (dinero, porcentaje o índice), por país y por una fecha determinada (series de tiempo con datos periódicos según el indicador).
Proponemos realizar una exploración inicial de estos datos para determinar si es posible con esta información lograr alguno de estos dos posibles casos:

1.	Agrupar los países de Latinoamérica, de acuerdo a su información macroeconómica y nos permita encontrar clúster de “países similares” que para el FLAR puedan tener prioridad o no en el proceso de membresía. (algoritmo de clasificación y clustering) 
2.	Predecir los próximos valores de cada indicador según los datos históricos que le permita al FLAR anticiparse a posibles situaciones de urgencia que puede caer un país y que requiera el acompañamiento del FLAR.
3.	Algún otro resultado de impacto para el FLAR y que sea obtenido mediante machine learning e inteligencia artificial que encontremos en la exploración inicial de los datos.

 
Propuesta esquemática del trabajo

Para realizar el proyecto propuesto se han definido cinco fases que nos permitan seleccionar el caso, modelar, obtener resultados y documentar de la siguiente manera:
Fase 1: Diseño del Proyecto

Recopilación de Datos y Exploración Inicial: 

•	Obtener datos del Sistema de Información Económica del FLAR (SIE).
•	Realizar una exploración inicial para comprender la estructura y contenido de los datos.

Definición de Objetivos: 

•	Determinar claramente si el objetivo es clasificar o predecir datos.

La fase de "Definición de Objetivos" es esencial para orientar el enfoque y los métodos utilizados en un proyecto de Machine Learning. Aquí, se busca establecer de manera clara y precisa lo que se espera lograr con el análisis de datos. Esta fase se compone de dos aspectos clave:

Clasificación: Si el objetivo es clasificar, significa que estamos tratando de asignar una etiqueta o categoría a los datos. Por ejemplo, identificar si un correo electrónico es spam o no.
Predicción: Si el objetivo es predecir, buscamos estimar o anticipar valores futuros basándonos en patrones históricos. Por ejemplo, predecir el precio de las acciones en el próximo mes.

•	Identificar qué se busca lograr con el análisis.

Se trata de entender la finalidad o el propósito más amplio del análisis de datos.
Puede ser la toma de decisiones más informada, la identificación de patrones ocultos, la optimización de procesos, entre otros.
La identificación clara de este propósito guiará las etapas posteriores del proyecto, desde la selección de modelos hasta la interpretación de resultados.

Ejemplo Práctico:

Supongamos que estamos trabajando en un proyecto para el Fondo Latinoamericano de Reservas (FLAR) y tenemos datos macroeconómicos. Aquí, podríamos definir nuestros objetivos de la siguiente manera:
Objetivo Principal: Predecir el comportamiento futuro de indicadores económicos clave (como PIB, inflación, déficit fiscal) para que el FLAR pueda anticiparse a situaciones de urgencia.
Objetivo Secundario: Identificar patrones o similitudes entre países latinoamericanos basándonos en su información macroeconómica, lo que podría ser útil para priorizar acciones o membresías.
Estos objetivos claros proporcionan una guía para las siguientes fases del proyecto, desde la selección de modelos hasta la presentación de los resultados.

Preparación de Datos: 

•	Limpieza y preprocesamiento de los datos, si es necesario.
•	Transformación de datos, como creación de características adicionales.
•	Manejo de series de tiempo y frecuencia de datos.

Fase 2: Machine Learning en Python

Selección de Modelo:
•	Elegir algoritmos de machine learning adecuados en función de los objetivos y los tipos de datos.
Entrenamiento del Modelo:
•	Dividir los datos en conjuntos de entrenamiento y prueba.
•	Entrenar el modelo utilizando los datos de entrenamiento.
Evaluación del Modelo:
•	Evaluar el rendimiento del modelo utilizando métricas apropiadas (precisión, precisión, F1-score, etc.).
•	Ajustar el modelo si es necesario.
Visualización de Resultados:
•	Generar visualizaciones que ayuden a interpretar los resultados.
•	Utilizar gráficos de series temporales si corresponde.


Fase 3: Documentación y Presentación

Creación del Informe Final:
•	Documentar todo el proceso, desde la recopilación de datos hasta la evaluación del modelo.
•	Incluir hallazgos clave y decisiones tomadas.
Entrega del Cuaderno de Jupyter: 
•	Preparar un cuaderno Jupyter que muestre el código y los pasos seguidos.
•	Incluir un archivo "predicciones.csv" si corresponde.
Presentación de PowerPoint:
•	Preparar una presentación de PowerPoint concisa con hasta 10 diapositivas.
•	Destacar los aspectos más importantes del proyecto.

Fase 4: Evaluación y Revisión

Revisión del Proyecto: 
•	Evaluar el proyecto en términos de claridad, originalidad, contenido y corrección.
•	Asegurarse de que todas las partes del proyecto estén bien documentadas.
Presentación del Proyecto: 
•	Preparar para la presentación del proyecto, vestirse de manera profesional y estar preparado para responder preguntas.
Entrega Final: 
•	Enviar todas las entregas en el plazo establecido.

Fase 5: Retroalimentación y Mejoras (Opcional)

Análisis de Retroalimentación:
•	Considerar cualquier retroalimentación recibida y aprender de la experiencia.
Identificar Mejoras:
•	Identificar áreas de mejora en el proyecto y en las habilidades de machine learning.

Roles de cada miembro del equipo

Camilo Cruz (Acceso a datos y experto en la información): Responsable de conseguir, procesar, explorar y otras actividades iniciales de los datos del SIE, así como establecer las reuniones o aclaraciones con los economistas expertos de la dirección de estudios económicos del FLAR, esto implica acompañamiento a la selección del caso y análisis de los resultados del modelo.
Álvaro Ortuzar (Científico de datos): Responsable de la prueba y selección de los modelos, evaluación y muestra de resultados de los modelos. 
Alejandro Magos (Documentador): responsable de la creación de la documentación definida en la fase 4
Esta definición de roles ayuda a determinar la responsabilidad de cada miembro del equipo, pero también nos ilustra que hay algunas actividades transversales donde todos seremos participes por ejemplo las fases de Evaluación y retroalimentación y mejoras deberíamos intervenir todos.




