**Taller**

Modelado

**Asignatura**

Fundamentos de Analitica de Datos

**Tema**

3

**Semestre**

2024 - 1

**Objetivo**

Implementar un esquema de modelamiento de datos para resolver un problema de base analitica.

Ustedes hacen parte de un equipo de datos que trabajan en una clinica de ginecobstetricia, en la que cuentan con la informacion de 2.126 histogramas a fetos. Ante esto, se les pide construir un modelo de clasificacion que sea capaz de determinar si un feto es normal, sospechoso o cuenta con alguna patologia cardiaca.

El conjunto de datos cuenta con el siguiente diccionario:

-------

Variable: Descripción

baseline: Tasa cardiaca base fetal

accelerations: Número de aceleraciones por segundo

fetal_movement: Número de movimientos fetales por segundo

uterine_contractions: Número de contracciones del útero por segundo

light_decelerations: Número de desaceleraciones leves por segundo

severe_decelerations: Número de desaceleraciones fuertes por segundo

prolongued_decelerations: Número de desaceleraciones profundas por segundo

abnormal_short_term_variability: Porcentaje del tiempo con variabilidad anormal de corto plazo

mean_value_of_short_term_variability: Promedio de la variabilidad de corto plazo

percentage_of_time_with_abnormal_long_term_variability: Porcentaje del tiempo con variabilidad anormal de largo plazo

mean_value_of_long_term_variability: Promedio de la variabilidad de largo plazo

histogram_width: Rango del electrocardiograma

histogram_min: Mínimo del electrocardiograma

histogram_max: Máximo del electrocardiograma

histogram_number_of_peaks: Número de picos del electrocardiograma

histogram_number_of_zeroes: Número de ceros del electrocardiograma

histogram_mode: Moda del electrocardiograma

histogram_mean: Media del electrocardiograma

histogram_median: Mediana del electrocardiograma

histogram_variance: Varianza del electrocardiograma

histogram_tendency: Tendencia del electrocardiograma

fetal_health:

Estado de salud fetal:
- 1: Normal
- 2: Sospechoso
- 3: Patológico

-------


Con esto en cuenta realice lo siguiente:
- Haga una exploracion basica de los datos:
  - Tipos de datos
  - Medidas de tendencia central 
  - Identificacion de datos nulos 
  - Factor de correlacion
- Si cuenta con datos nulos, realice una imputacion de datos.
- Construya un modelo de datos que le permita obtener lo planteado en el problema.
- Haga una presentacion donde muestre los resultados (puede ser modo presentacion o un notebook ordenado).