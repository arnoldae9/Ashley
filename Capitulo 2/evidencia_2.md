# EVIDENCIA 2 - SOLUCIONES

## Problema 1

**Tabla de frecuencias:**

| CLASES | fi  | Fi (acumulada) |
| ------ | --- | -------------- |
| 0-9    | 15  | 15             |
| 9-18   | 10  | 25             |
| 18-27  | 26  | 51             |
| 27-36  | 10  | 61             |
| 36-45  | 8   | 69             |

**Procedimiento:**

1. Total de datos: $n = 15 + 10 + 26 + 10 + 8 = 69$
2. Posición de la mediana: $\frac{n}{2} = \frac{69}{2} = 34.5$
3. Buscamos la clase donde $F_i \geq 34.5$
4. La clase mediana es 18-27 ($F_i = 51 \geq 34.5$)

**Respuesta: 18**

---

## Problema 2

**Tabla de frecuencias:**

| CLASES | fi  |
| ------ | --- |
| 0-9    | 15  |
| 9-18   | 10  |
| 18-27  | 26  |
| 27-36  | 10  |
| 36-45  | 8   |

**Procedimiento:**

1. Identificamos la clase con mayor frecuencia
2. La clase modal es 18-27 ($f_i = 26$, la más alta)

**Respuesta: 18**

---

## Problema 3

**Tabla de frecuencias:**

| CLASES    | fi     | xi (marca de clase) | fi·xi     | (xi - $\bar{x}$) | (xi - $\bar{x}$)² | fi·(xi - $\bar{x}$)² |
| --------- | ------ | ------------------- | --------- | ---------------- | ----------------- | -------------------- |
| 10-20     | 10     | 15                  | 150       | -19.06           | 363.28            | 3,632.80             |
| 20-30     | 15     | 25                  | 375       | -9.06            | 82.08             | 1,231.20             |
| 30-40     | 19     | 35                  | 665       | 0.94             | 0.88              | 16.72                |
| 40-50     | 11     | 45                  | 495       | 10.94            | 119.68            | 1,316.48             |
| 50-60     | 9      | 55                  | 495       | 20.94            | 438.48            | 3,946.32             |
| **Total** | **64** |                     | **2,180** |                  |                   | **10,143.52**        |

**Procedimiento:**

1. Media: $\bar{x} = \frac{\sum f_i \cdot x_i}{n} = \frac{2,180}{64} = 34.06$
2. Calculamos $(x_i - \bar{x})$ para cada marca de clase
3. Calculamos $(x_i - \bar{x})^2$ para cada clase
4. Calculamos $f_i \cdot (x_i - \bar{x})^2$ para cada clase
5. Varianza: $s^2 = \frac{\sum[f_i \cdot (x_i - \bar{x})^2]}{n-1} = \frac{10,143.52}{63} = 160.99$
6. Desviación estándar: $s = \sqrt{160.99} = 12.69$

**Respuesta: 12.69**

---

## Problema 4

**Tabla de frecuencias:**

| CLASES    | fi     | xi (marca de clase) | fi·xi     |
| --------- | ------ | ------------------- | --------- |
| 10-20     | 12     | 15                  | 180       |
| 20-30     | 17     | 25                  | 425       |
| 30-40     | 29     | 35                  | 1,015     |
| 40-50     | 11     | 45                  | 495       |
| 50-60     | 9      | 55                  | 495       |
| **Total** | **78** |                     | **2,610** |

**Procedimiento:**

1. Media muestral: $\bar{x} = \frac{\sum f_i \cdot x_i}{n} = \frac{2,610}{78} = 33.46$

**Respuesta: 33.46**

---

## Problema 5

**Tabla de frecuencias:**

| CLASES    | fi     | xi (marca de clase) | fi·xi     |
| --------- | ------ | ------------------- | --------- |
| 0-10      | 2      | 5                   | 10        |
| 10-20     | 12     | 15                  | 180       |
| 20-30     | 12     | 25                  | 300       |
| 30-40     | 15     | 35                  | 525       |
| 40-50     | 9      | 45                  | 405       |
| **Total** | **50** |                     | **1,420** |

**Procedimiento:**

1. Media: $\bar{x} = \frac{\sum f_i \cdot x_i}{n} = \frac{1,420}{50} = 28.40$

**Respuesta: 28.40**

---

## Problema 6

**Tabla de frecuencias:**

| CLASES | fi  | Fi (acumulada) |
| ------ | --- | -------------- |
| 0-10   | 2   | 2              |
| 10-20  | 12  | 14             |
| 20-30  | 12  | 26             |
| 30-40  | 15  | 41             |
| 40-50  | 9   | 50             |

**Procedimiento:**

1. $n = 50$, $\frac{n}{2} = 25$
2. Clase mediana: 30-40 ($F_i = 41 \geq 25$)
3. Fórmula: $Me = L_i + \frac{\frac{n}{2} - F_{i-1}}{f_i} \times h$
4. $Me = 30 + \frac{25 - 26}{15} \times 10 = 30 + (-0.067) \times 10 = 29.33$

**Respuesta: 29.33**

---

## Problema 7

**Tabla de frecuencias:**

| CLASES | fi  |
| ------ | --- |
| 0-10   | 2   |
| 10-20  | 12  |
| 20-30  | 12  |
| 30-40  | 15  |
| 40-50  | 9   |

**Procedimiento:**

1. Clase modal: 30-40 ($f_i = 15$, la mayor frecuencia)
2. Fórmula: $Mo = L_i + \frac{d_1}{d_1 + d_2} \times h$
3. $d_1 = 15 - 12 = 3$, $d_2 = 15 - 9 = 6$
4. $Mo = 30 + \frac{3}{3 + 6} \times 10 = 30 + \frac{3}{9} \times 10 = 33.33$

**Respuesta: 33.33**

---

## Problema 8

**Tabla de frecuencias:**

| CLASES | fi  |
| ------ | --- |
| 0-8    | 4   |
| 8-16   | 11  |
| 16-24  | 16  |
| 24-32  | 9   |

**Procedimiento:**

1. Límite superior de la última clase: 32
2. Límite inferior de la primera clase: 0
3. Amplitud de variación = $L_{sup} - L_{inf} = 32 - 0 = 32$

**Respuesta: 32**

---

## Problema 9

**Datos:** 10, 90, 85, 74, 15, 17, 20, 34, 87, 96, 75, 79, 36, 45, 47, 50, 67, 98, 99, 100, 73, 98, 100, 59, 71, 70, 80, 90, 76, 93

**Datos ordenados:** 10, 15, 17, 20, 34, 36, 45, 47, 50, 59, 67, 70, 71, 73, 74, 75, 76, 79, 80, 85, 87, 90, 90, 93, 96, 98, 98, 99, 100, 100

**Rango:** $R = 100 - 10 = 90$
**Número de clases:** $k = \sqrt{30} \approx 5.5 \rightarrow 6$ clases
**Amplitud de clase:** $h = \frac{90}{6} = 15$

**Tabla de frecuencias:**

| CLASES    | fi     | xi   | fi·xi     | (xi - $\bar{x}$) | (xi - $\bar{x}$)² | fi·(xi - $\bar{x}$)² |
| --------- | ------ | ---- | --------- | ---------------- | ----------------- | -------------------- |
| 10-25     | 4      | 17.5 | 70        | -46.00           | 2,116.00          | 8,464.00             |
| 25-40     | 3      | 32.5 | 97.5      | -31.00           | 961.00            | 2,883.00             |
| 40-55     | 4      | 47.5 | 190       | -16.00           | 256.00            | 1,024.00             |
| 55-70     | 3      | 62.5 | 187.5     | -1.00            | 1.00              | 3.00                 |
| 70-85     | 8      | 77.5 | 620       | 14.00            | 196.00            | 1,568.00             |
| 85-100    | 8      | 92.5 | 740       | 29.00            | 841.00            | 6,728.00             |
| **Total** | **30** |      | **1,905** |                  |                   | **20,670.00**        |

**Procedimiento:**

1. Media: $\bar{x} = \frac{\sum f_i \cdot x_i}{n} = \frac{1,905}{30} = 63.50$
2. Calculamos $(x_i - \bar{x})$ para cada marca de clase
3. Calculamos $(x_i - \bar{x})^2$ para cada clase
4. Calculamos $f_i \cdot (x_i - \bar{x})^2$ para cada clase
5. Varianza: $s^2 = \frac{\sum[f_i \cdot (x_i - \bar{x})^2]}{n-1} = \frac{20,670.00}{29} = 712.76$
6. Desviación estándar: $s = \sqrt{712.76} = 26.70$
7. Mediana (posición 15-16): $Me = \frac{74 + 75}{2} = 74.50$

**Respuestas:**
- **Media: 63.50**
- **Mediana: 74.50**
- **Desviación estándar: 26.70**

---

## Problema 10

**Tabla de frecuencias:**

| CLASES    | fi     | xi  | fi·xi     | xi²   | fi·xi²      | Fi  |
| --------- | ------ | --- | --------- | ----- | ----------- | --- |
| 30-38     | 1      | 34  | 34        | 1,156 | 1,156       | 1   |
| 38-46     | 8      | 42  | 336       | 1,764 | 14,112      | 9   |
| 46-54     | 9      | 50  | 450       | 2,500 | 22,500      | 18  |
| 54-62     | 15     | 58  | 870       | 3,364 | 50,460      | 33  |
| 62-70     | 14     | 66  | 924       | 4,356 | 60,984      | 47  |
| 70-78     | 20     | 74  | 1,480     | 5,476 | 109,520     | 67  |
| 78-86     | 3      | 82  | 246       | 6,724 | 20,172      | 70  |
| 86-94     | 10     | 90  | 900       | 8,100 | 81,000      | 80  |
| **Total** | **80** |     | **5,240** |       | **359,904** |     |

**Procedimiento:**

**Media:** $\bar{x} = \frac{5,240}{80} = 65.50$

**Mediana:** $\frac{n}{2} = 40$, clase mediana 62-70 ($F_i = 47 \geq 40$)
$Me = 62 + \frac{40-33}{14} \times 8 = 62 + 4.00 = 66.00$

**Moda:** Clase modal 70-78 ($f_i = 20$)
$d_1 = 20-14 = 6$, $d_2 = 20-3 = 17$
$Mo = 70 + \frac{6}{6+17} \times 8 = 70 + 2.09 = 72.09$

**Desviación estándar:**
$s^2 = \frac{\sum f_i \cdot (x_i - \bar{x})^2}{n-1} = \frac{16,784}{79} = 212.46$
$s = \sqrt{212.46} = 14.58$

**Respuestas:**
- **Media: 65.50**
- **Mediana: 66.00**
- **Moda: 72.09**
- **Desviación estándar: 14.58**