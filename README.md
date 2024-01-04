![PR2_logo](https://github.com/LuciaBlancV/Tipologia_PR2/assets/148953141/ab2348c8-a18e-47ef-81d1-6feca4de663d)

***

## Proyecto Analítico Práctica 2 - Heart Attack Analysis & Prediction dataset

Este proyecto es una práctica de la asignatura "Tipología y ciclo de vida de los datos" del Máster en Ciencia de Datos de la UOC.

## Grupo de trabajo:

+ Sergi Sánchez Romero
+ Lucia Blanc Velázquez


## Objetivo
El objetivo el presente proyecto es realizar un análisis de las propiedades de una gran cantidad de variables que predicen los infartos del corazón, con el fin de evaluar cuales son las características que mayor predicen si alguien desarrollará o no una enfermedad cardíaca, y en consecuente sufrirá o no un infarto. 

## Dataset

El conjunto de datos escogido para esta práctica, se titula: *“Heart Attack Analysis & Prediction dataset”*, el cual tiene como objetivo detectar aquellos factores que pueden actuar como potenciales precursores de las enfermedades cardiovasculares, y así ayudar a la detección y gestión temprana mediante la creación de un modelo. En el conjunto de datos se contemplan un total de 14 características importantes que pueden ayudar a la predicción de desarrollar o no una enfermedad cardíaca. Según la información encontrada, se sabe que las enfermedades cardiovasculares ocupan un porcentaje del 31% en relación a las muertes que se producen en el mundo cada año, por lo que supone una de las causas principales de muerte. Es importane tener en cuenta cuales son los atributos que pueden conllevar a un mayor riesgo cardiovascular o al desarrollo de enfermedad cardiovascular, por lo que, el objetivo es predecir que variables influyen más en este desarrollo.

Información encontrada en la web de [kaggle](https://www.kaggle.com/datasets),
concretamente en el siguiente enlace: https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset


A continuación se describe brevemente cada una de las columnas del dataset: 

+ **age**: Edad del paciente
+ **sex**: Sexo del paciente (F=0; M=1)
+ **cp**: Tipo dolor torácico
  - **Value 1**: Angina típica (TA)
  - **Value 2**: Angina atípica (ATA)
  - **Value 3**: Dolor no-anginal (NAP)
  - **Value 4**: Asintomático (ASY)
   
+ **trtbps**: Presión arterial en reposo (in mm Hg)
+ **chol**: Colesterol en mg/dl obtenido a través del sensor de IMC
+ **fbs**: (Glucemia en ayunas > 120 mg/dl) (1 = true; 0 = false)
+ **restecg**: Resultados del electrocardiograma en reposo
  - **Value 0**: Normal
  - **Value 1**: Presentar anomalías de la onda ST-T (inversión de la onda T y/o elevación o depresión del ST de > 0,05 mV)
  - **Value 2**: Hipertrofia ventricular izquierda probable o definida según los criterios de Estes
   
+ **thalachh**: Frecuencia cardiaca máxima alcanzada
+ **exng**: Angina inducida por el ejercicio (1 = si; 0 = no)
+ **oldpeak**: Pico previo
+ **slp**: Pendiente del segmento ST máximo del ejercicio
+ **caa**: Número de grandes buques (0-3)
+ **thall** : Tasa de mortalidad
+ **output**: 0= menor probabilidad de infarto 1= mayor probabilidad de infarto



## Archivos

| Nombre         | Descripción           | 
| ------------- |-------------| 
| **heart_PR2.Rmd**      | El documento contiene toda la información referente al código en lenguaje de programación R empleado para ejecutar en análisis de datos de la presente práctica. | 
| **heart_PR2.html**    | Contiene toda la información generada en el codigo en lenguaje de programación R, en un formato de tipo .html, de tal forma que facilite la visualización de la información.      | 
| **heart_PR2.pdf**    | Contiene toda la información generada en el codigo en lenguaje de programación R, en un formato de tipo .pdf, de tal forma que facilite la visualización de la información.      | 
| **heart.xlsx** | Archivo de tipo .xlsx que contiene toda la información original relacionada en la base de datos.      | 
| **heart_clean.xlsx** | Archivo de tipo .xlsx que contiene información ya habiendo aplicado metodos de limpieza de datos.      | 



## Contribuciones 
| Investigación previa        | Lucia Blanc Velázquez y Sergi Sánchez Romero          | 
| Redacción de las respuestas |Lucia Blanc Velázquez y Sergi Sánchez Romero    | 
| Desarrollo del código        |Lucia Blanc Velázquez y Sergi Sánchez Romero             | 
| Participación en el vídeo |Lucia Blanc Velázquez y Sergi Sánchez Romero       |




## Recursos:

+ *Calvo M., Subirats L., Pérez D. (2019)*. **Introducción a la limpieza y análisis de los datos**. Editorial UOC. 
+ *Megan Squire (2015)*. **Clean Data. Packt Publishing Ltd**. Jiawei Han, Micheine Kamber, 
+ *Jian Pei (2012)*. **Data mining: concepts and techniques**. 
+ *Morgan Kaufmann. Jason W. Osborne (2010)*. **Data Cleaning Basics: Best Practices in Dealing with Extreme Scores. Newborn and Infant Nursing Reviews; 10 (1): pp. 1527-3369.** 
+ *Peter Dalgaard (2008)*. **Introductory statistics with R. Springer Science & Business Media**. 
+ *Wes McKinney (2012)*. **Python for Data Analysis**. O’Reilley Media, Inc.
