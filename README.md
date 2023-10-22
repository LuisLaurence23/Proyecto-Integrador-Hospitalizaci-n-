# **Proyecto de Aprendizaje Automático para la Predicción de Hospitalización en Pacientes**

![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)



## **Introducción**

¡Bienvenidos a nuestro proyecto integrador! Durante estos días estarán poniendo en práctica sus habilidades en el campo del aprendizaje automático. Deberán entender la problemática y comprender los datos, realizar el análisis exploratorio de datos, preparar los datos, para luego experimentar con los modelos de machine learning en un contexto real. Finalmente, usarán las métricas correspondientes para medir el performance de los modelos y seleccionar el mejor. 

Vale la pena destacar, que puede realizarse por equipos y que este proyecto no será revisado. El objetivo es poner en práctica los conceptos que se van adelantando en el M6, previo a la etapa de Labs que están por comenzar. Por tanto, es un proyecto que podrán tener un su portafolio personal, pero no tiene calificación cuantitativa. 

Este proyecto constará de tres fases: `Análisis exploratorio de datos`, `Preparación de datos` y `Modelamiento y evaluación`.


### 1. Análisis exploratorio de datos

Machine Learning en Medicina: Al aplicar Machine Learning en Medicina se pueden usar las herramientas informáticas, con el fin de conseguir información a partir de los datos, por ejemplo, de historias clínicas o registros de prestadores de servicios de salud. De esta manera, se pueden emitir diagnósticos predicitivos, evaluar la efectividad de estrategias de intervención y anticipar comportamientos en escenarios relacionados con la atención. 

## **Planteamiento de la problemática**

Hemos sido contratados en el equipo de ciencia de datos en una consultora de renombre. Nos han asignado a un proyecto de estudio de atención en salud para un importante hospital. **Nuestro cliente desea saber las características más importantes que tienen los pacientes de cierto tipo de enfermedad que terminan en hospitalización.** Fue definido como caso aquel paciente que fue sometido a biopsia prostática y que en un periodo máximo de 30 días posteriores al procedimiento presentó fiebre, infección urinaria o sepsis; requiriendo manejo médico ambulatorio u hospitalizado para la resolución de la complicación y como control al paciente que fue sometido a biopsia prostática y que no presentó complicaciones infecciosas en el período de 30 días posteriores al procedimiento. Dado que tienen en su base de datos algunos datos referentes a los pacientes y resultados de exámenes diagnósticos, de pacientes hospitalizados y no hospitalizados, nos han entregado esta información.  

Para ello, nuestro departamento de datos ha recopilado `Antecedentes del paciente`, `Morbilidad asociada al paciente` y `Antecedentes relacionados con la toma de la biopsia`y `Complicaciones infecciosas`. En la siguiente tabla, se encuentra un diccionario de datos asociado:

![image](https://user-images.githubusercontent.com/118769777/220240501-8c21461d-2de5-495b-954e-10fb9bf38014.png)

El departamente de datos advierte que hay algunos problemas de calidad de datos en la información suministrada por lo que el primer reto del equipo es realizar un análisis exploratorio de los datos con el fin de transformar y preparar las datos adecuadamente. 


## **Procedimiento**

Para nuestro Proyecto Integrador, hemos dividido nuestro trabajo en tres etapas fundamentales:

1. **Análisis Exploratorio de Datos**: En esta fase inicial, comenzamos por cargar el archivo .csv que contiene nuestros datos. Aquí, realizamos un análisis general de los datos para comprender la naturaleza de la información que tenemos a nuestra disposición. Durante este proceso, identificamos los diferentes tipos de datos presentes en el conjunto, examinamos posibles valores atípicos (outliers) y evaluamos la calidad de los datos en términos de su integridad y consistencia. Este análisis nos proporciona una comprensión sólida de los datos con los que estamos trabajando y nos prepara para la siguiente etapa.

2. **Preparación de Datos**: En esta etapa, nos concentramos en la limpieza y preparación de los datos. Aquí, realizamos diversas acciones, como la corrección de tipos de datos, la gestión de valores faltantes mediante su eliminación o imputación, la atención a los valores atípicos, la creación de agrupaciones de datos relevantes y la identificación de las columnas a las que debemos aplicar codificación de variables categóricas (dummies). El objetivo principal es tener un conjunto de datos limpio, coherente y listo para ser utilizado en el proceso de modelamiento.

3. **Modelamiento y Evaluación**: En la última fase, nos enfocamos en la creación y evaluación de modelos. En particular, hemos implementado modelos de clasificación, como Árboles de Decisión y k-Vecinos más Cercanos (k-NN). Evaluamos el rendimiento de estos modelos utilizando diversas métricas de evaluación, como precisión, puntuación F1 y precisión. Estas métricas nos permiten comprender qué modelo se ajusta mejor a nuestros datos y nos proporciona información valiosa sobre su capacidad para predecir con precisión. Además, generamos informes de clasificación detallados que resumen el rendimiento de los modelos de manera completa y comprensible.

Este enfoque estructurado nos permite abordar cada fase de manera sistemática y garantizar que nuestro proyecto se desarrolle de manera efectiva desde la exploración inicial de los datos hasta la evaluación y selección de modelos.
