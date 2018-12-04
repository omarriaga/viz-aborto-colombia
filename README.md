# ABORTO EN COLOMBIA 

## Cifras de aborto legal en Colombia (2009 - 2017) 

 

## OBJETIVO (PROBLEMATICA): 

Visualizar los datos sobre el aborto legal en Colombia, exponiendo la problemática en el ámbito nacional. 


## ALTERNATIVAS: TAREAS A RESOLVER: 

De los 10.000 abortos legales realizados en Colombia hasta el año 2017, se pretende analizar cuál de los tres escenarios en los que es legal este procedimiento, es el más predominante, entre un rango especifico de edad. 

Analizar el tipo de diagnóstico que se han hecho sobre los abortos realizados en cada departamento del país. 

## FRAMEWORK TAMARA 

## WHAT 

Dataset:  

Tabla -> Cada ítem determina el tipo de aborto diagnosticado, por ciudad y año, y cada atributo, los datos registrados por paciente 

Temporal -> El dataset con el que se cuenta, contiene la información relacionada con la cantidad de abortos anuales realizados de forma legal. 


Dataset de agregación: 

Tabla -> cada ítem es una agregación por alguno de los campos descritos en el dataset original. 


Tipo de Datos: 

Categóricos -> Departamento, Municipio, Prestador, Diagnóstico, edad, año (2009 - 2017) 

Cuantitativo-Secuencial -> Cantidad de abortos 

 
Disponibilidad de dataset: 

Dinámica -> El dataset permite recolectar datos de otros años y aumentar la cantidad de información para el respectivo análisis, enriqueciendo y modificando la visualización realizada. 

## WHY 

- Tareas Principales  

Resumir la distribución del número de abortos por rango de edades sobre el tiempo. [Summarize - Distribution] 

Presentar la distribución a nivel departamental de la cantidad de abortos legales en Colombia [Present - Distribution] 

- Tareas Secundarias  

Explorar los principales motivos de aborto para cada uno de los años. [Explore - Features] 

Agrupar la información a partir de las características que se seleccionen [Derive – Features] 

Identificar la correlación que existe entre el aborto y el embarazo de mujeres en edades tempranas [Identify - Correlation] 

Agrupar la información a partir de las características que se seleccionen [Derive – Features] 

 
## HOW 

- Tarea principal 1 

Marcas: Líneas para codificar las edades y años de los abortos 

Encode: Express - Separate 

Canales: 

El canal Tono de color para cada rango de edad 

El canal Posición en escala común para la cantidad de abortos en el tiempo 

Manipulación: Selección 

 
- Tarea principal 2 

Marcas: Línea para codificar la cantidad de abortos por departamento 

Encode: Express - Order - Align 

Canales: 

El canal Tono de color para el departamento 

El canal Posición en escala común para la cantidad de abortos por motivo 

Manipulación: Selección 

 
## INSIGHTS 

El aborto espontáneo ha sido el diagnóstico más común en los centros de salud autorizados para realizar la interrupción del embarazo de forma legal. En cuanto a los abortos inducidos, se puede observar que la extracción menstrual ha sido el medio más utilizado para realizar la interrupción del embarazo. 

En los abortos inducidos, la extracción menstrual ha sido el medio más utilizado para realizar la interrupción del embarazo. 

Las mujeres que más han acudido a realizar un aborto de forma legal en los centros de salud están en el rango de edad de 21 a 30 años. 

En el año 2014 se presentó un pico elevado en la cantidad de abortos, la cifra más preocupante se presentó en las mujeres de 21 a 30 años con un total de 9.537 abortos. 

En la mayoría de los departamentos el año en que se presentaron más abortos fue en 2014, en departamentos como Arauca se evidencia un pico bastante grande, triplicando la cantidad respecto de los demás años. 

## LINK CLASS WEBSITE 

## LINK PROJECT DEMO 

## LINK PAPER 

## License

The code is available under the [MIT license](LICENSE.txt).
