# Tendencia Central y Dispersión

## 1. Tendencia Central

Las medidas de tendencia central son valores que representan el centro o punto medio de un conjunto de datos. Su objetivo es resumir toda la información de un conjunto de datos en un solo valor representativo.

### Principales medidas:

**Media Aritmética (Promedio)**
- Se calcula sumando todos los valores y dividiendo entre el número total de datos
- Es la medida más común y sensible a valores extremos
- Fórmula: $\overline{x}=\dfrac{\sum x}{n}$

#### Tipos de Media:

**Media Poblacional ($\mu$)**
- Representa el promedio de toda la población
- Se usa cuando se tienen todos los datos de la población completa
- Fórmula: $\mu = \dfrac{\sum{x}}{n}$ (donde N es el tamaño total de la población)

**Media Muestral ($\overline{x}$)**
- Representa el promedio de una muestra extraída de una población
- Es un estimador de la media poblacional
- Fórmula: $\overline{x} = \dfrac{\sum{x}}{n}$ (donde n es el tamaño de la muestra)

**Media Posicional**
- Se refiere a medias calculadas en función de la posición de los datos
- Incluye la media truncada (eliminando un porcentaje de valores extremos)
- Media winsorizada (reemplazando valores extremos por percentiles específicos)
- Útil cuando hay valores atípicos que distorsionan la media aritmética simple
- Fórmula: $\mu = \dfrac{\sum{x_i}}{N}$ (Donde N es el tamaño de la posición)

**Media Ponderada**
- Asigna diferentes pesos o importancias a cada valor del conjunto de datos
- Útil cuando algunos valores tienen mayor relevancia que otros
- Fórmula: $\widetilde{x} = \dfrac{\sum{(w_i \times x_i)}}{\sum{w_i}}$ (donde $w_i$ es el peso del valor $x_i$)
- Aplicaciones comunes: promedios de calificaciones, índices económicos, encuestas

**Mediana**
- Es el valor que divide al conjunto de datos ordenados en dos mitades iguales
- No se ve afectada por valores extremos (es robusta)
- Para datos impares: valor central; para datos pares: promedio de los dos valores centrales

Se calcula siguiendo los siguientes 3 pasos:

1. Se ordenan los datos de forma ascendente
2. Se determina la cantidad de datos del conjunto
3. Si es impar, la mediana es central si es par la mediana es el promedio de los 2 datos centrales  

**Moda**
- Es el valor o valores que aparecen con mayor frecuencia en el conjunto de datos
- Puede no existir, ser única o múltiple
- Útil especialmente para datos categóricos

<center>

|  modas   |  ->   |   Tipo    |
| :------: | :---: | :-------: |
|    0     |  ->   |  Amodal   |
|    1     |  ->   | Unimodal  |
|    2     |  ->   |  Bimodal  |
|    3     |  ->   | Trimodal  |
| más de 3 |  ->   | Polimodal |
</center>

### Cuándo usar cada una:
- **Media**: Para datos simétricos sin valores extremos
- **Mediana**: Para datos asimétricos o con valores atípicos
- **Moda**: Para identificar el valor más común o en datos categóricos

## 2. Dispersión

Las medidas de dispersión indican qué tan esparcidos o concentrados están los datos alrededor de la medida de tendencia central. Complementan la información proporcionada por las medidas centrales.

### Principales medidas:

**Rango ó Amplitud de Variación**
- Diferencia entre el valor máximo y mínimo del conjunto de datos
- Fórmula: Rango = Máximo - Mínimo
- Es fácil de calcular pero sensible a valores extremos

**Varianza**
- Promedio de las desviaciones cuadráticas respecto a la media
- Mide la dispersión promedio de los datos
- Fórmula poblacional: $\sigma^2 = \dfrac{\sum{(x - \mu)^2}}{N}$
- Fórmula muestral: $s^2 = \dfrac{\sum{(x - \overline{x})^2}}{n-1}$ 


**Desviación Estándar**
- Raíz cuadrada de la varianza
- Está en las mismas unidades que los datos originales
- Es la medida de dispersión más utilizada
- Fórmula: $\sigma = \sqrt{\sigma^2}$ (poblacional) o $s = \sqrt{s^2}$ (muestral)

**Desviación Absoluta Media (DAM)**
- Promedio de las desviaciones absolutas respecto a la media
- Menos sensible a valores extremos que la varianza y desviación estándar
- Fórmula: $\text{DAM} = \dfrac{\sum{|x - \overline{x}|}}{n}$
- Útil cuando se quiere una medida de dispersión menos afectada por valores atípicos

**Coeficiente de Variación**
- Medida relativa de dispersión expresada como porcentaje
- Permite comparar la dispersión entre conjuntos de datos con diferentes unidades
- Fórmula: $\text{CV} = \dfrac{\sigma}{\mu} \times 100$ %

### Interpretación:
- **Dispersión baja**: Los datos están concentrados cerca del centro
- **Dispersión alta**: Los datos están muy esparcidos
- La dispersión siempre debe interpretarse junto con las medidas de tendencia central para obtener una descripción completa de los datos

### Importancia conjunta:
Tanto las medidas de tendencia central como las de dispersión son fundamentales para describir completamente un conjunto de datos. Mientras las primeras nos dicen "dónde está el centro", las segundas nos indican "qué tan dispersos están los datos alrededor de ese centro".

## 3. Ejemplo Práctico

Consideremos las calificaciones de 10 estudiantes en un examen: **7, 8, 6, 9, 5, 8, 7, 10, 6, 9**

### Cálculo de Medidas de Tendencia Central:

**Datos ordenados:** 5, 6, 6, 7, 7, 8, 8, 9, 9, 10

**Media Aritmética:**
- $\overline{x}$ = (7+8+6+9+5+8+7+10+6+9) ÷ 10 = 75 ÷ 10 = **7.5**

**Mediana:**
- Con 10 datos (par), mediana = (7º valor + 8º valor) ÷ 2 = (7+8) ÷ 2 = **7.5**

**Moda:**
- Valores que más se repiten: 6, 7, 8, 9 (cada uno aparece 2 veces)
- **Multimodal**: 6, 7, 8, 9

**Media Ponderada (ejemplo):**
- Si los primeros 5 exámenes valen 40% y los últimos 5 valen 60%:
- Grupo 1: (7+8+6+9+5) ÷ 5 = 7.0 (peso: 0.4)
- Grupo 2: (8+7+10+6+9) ÷ 5 = 8.0 (peso: 0.6)
- $\widetilde{x}$ = (7.0 × 0.4) + (8.0 × 0.6) = 2.8 + 4.8 = **7.6**

### Cálculo de Medidas de Dispersión:

**Rango o Amplitud de variación:**
- Rango = Máximo - Mínimo = 10 - 5 = **5**

**Varianza (muestral):**
- Desviaciones al cuadrado: (7-7.5)² + (8-7.5)² + (6-7.5)² + (9-7.5)² + (5-7.5)² + (8-7.5)² + (7-7.5)² + (10-7.5)² + (6-7.5)² + (9-7.5)²
- = 0.25 + 0.25 + 2.25 + 2.25 + 6.25 + 0.25 + 0.25 + 6.25 + 2.25 + 2.25 = 22.5
- $s^2$ = 22.5 ÷ (10-1) = 22.5 ÷ 9 = **2.5**

**Desviación Estándar (muestral):**
- s = $\sqrt{2.5}$ = **1.58**

**Desviación Absoluta Media:**
- Desviaciones absolutas: |7-7.5| + |8-7.5| + |6-7.5| + |9-7.5| + |5-7.5| + |8-7.5| + |7-7.5| + |10-7.5| + |6-7.5| + |9-7.5|
- = 0.5 + 0.5 + 1.5 + 1.5 + 2.5 + 0.5 + 0.5 + 2.5 + 1.5 + 1.5 = 12
- DAM = 12 ÷ 10 = **1.2**

**Coeficiente de Variación:**
- CV = (1.58 ÷ 7.5) × 100% = **21.07%**

### Interpretación del Ejemplo:
- **Tendencia Central**: Los estudiantes obtuvieron un promedio de 7.5 puntos
- **Dispersión**: Las calificaciones tienen una dispersión moderada (CV = 21%), con la mayoría de estudiantes obteniendo calificaciones entre 6 y 9 puntos
- **Comparación de medidas**: La DAM (1.2) es menor que la desviación estándar (1.58), lo que es típico ya que la desviación estándar penaliza más los valores extremos