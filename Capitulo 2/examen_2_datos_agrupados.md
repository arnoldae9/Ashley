# Examen de Repaso - Estadística Descriptiva

## **PARTE I: DATOS NO AGRUPADOS**

### Problema 1
Calcular las **3 medidas de tendencia central** para el siguiente conjunto de datos:

**{68, 84, 95, 72, 108, 89, 76, 115, 93, 81}**

a) **Media Aritmética**
b) **Mediana**
c) **Moda**

### Problema 2
Para el mismo conjunto de datos del problema 1, calcule las siguientes **medidas de dispersión**:

a) **Desviación Absoluta Media (DAM)**
b) **Varianza Muestral**
c) **Desviación Estándar Muestral (s)**

---

## **PARTE II: DATOS AGRUPADOS**

### Problema 3
Calcular las **medidas de tendencia central** y las **medidas de dispersión** para la siguiente tabla de frecuencias:

| Clase | Límites | Marca de Clase (Xi) | Frecuencia (fi) |
| ----- | ------- | ------------------- | --------------- |
| 1     | 15-25   | 20                  | 6               |
| 2     | 25-35   | 30                  | 14              |
| 3     | 35-45   | 40                  | 20              |
| 4     | 45-55   | 50                  | 18              |
| 5     | 55-65   | 60                  | 12              |
| 6     | 65-75   | 70                  | 8               |
| 7     | 75-85   | 80                  | 5               |

**Total n = 83**

#### A) Medidas de Tendencia Central:
1. **Media Aritmética para datos agrupados**
2. **Mediana para datos agrupados**
3. **Moda para datos agrupados**

#### B) Medidas de Dispersión:
1. **Varianza para datos agrupados**
2. **Desviación Estándar para datos agrupados**
3. **Coeficiente de Variación**

---

## **INSTRUCCIONES GENERALES:**

- Muestre todos los procedimientos y fórmulas utilizadas
- Redondee los resultados a 2 decimales
- Para datos agrupados, use las fórmulas correspondientes
- Interprete brevemente los resultados obtenidos

---

# SOLUCIONARIO

## **PARTE I: DATOS NO AGRUPADOS**

### Datos: {68, 84, 95, 72, 108, 89, 76, 115, 93, 81}

### Problema 1: Medidas de Tendencia Central

**a) Media Aritmética (X̄)**
```
X̄ = Σx/n = (68+84+95+72+108+89+76+115+93+81)/10
X̄ = 881/10 = 88.10
```

**b) Mediana (Me)**
```
Datos ordenados: {68, 72, 76, 81, 84, 89, 93, 95, 108, 115}
n = 10 (par)
Me = (X₅ + X₆)/2 = (84 + 89)/2 = 86.50
```

**c) Moda (Mo)**
```
No hay moda (todos los valores aparecen una sola vez)
Mo = No existe
```

### Problema 2: Medidas de Dispersión

**a) Desviación Absoluta Media (DAM)**
```
DAM = Σ|Xi - X̄|/n

|68-88.10| = 20.10    |89-88.10| = 0.90
|84-88.10| = 4.10     |76-88.10| = 12.10
|95-88.10| = 6.90     |115-88.10| = 26.90
|72-88.10| = 16.10    |93-88.10| = 4.90
|108-88.10| = 19.90   |81-88.10| = 7.10

DAM = (20.10+4.10+6.90+16.10+19.90+0.90+12.10+26.90+4.90+7.10)/10
DAM = 119.00/10 = 11.90
```

**b) Varianza Muestral (s²)**
```
s² = Σ(Xi - X̄)²/(n-1)

(68-88.10)² = 404.01    (89-88.10)² = 0.81
(84-88.10)² = 16.81     (76-88.10)² = 146.41
(95-88.10)² = 47.61     (115-88.10)² = 723.61
(72-88.10)² = 259.21    (93-88.10)² = 24.01
(108-88.10)² = 396.01   (81-88.10)² = 50.41

s² = (404.01+16.81+47.61+259.21+396.01+0.81+146.41+723.61+24.01+50.41)/9
s² = 2068.90/9 = 229.88
```

**c) Desviación Estándar Muestral (s)**
```
s = √s² = √229.88 = 15.16
```

---

## **PARTE II: DATOS AGRUPADOS**

### Problema 3: Tabla de Frecuencias

| Clase     | Límites | Xi  | fi     | Fi  | Xi·fi     | Xi²·fi      |
| --------- | ------- | --- | ------ | --- | --------- | ----------- |
| 1         | 15-25   | 20  | 6      | 6   | 120       | 2,400       |
| 2         | 25-35   | 30  | 14     | 20  | 420       | 12,600      |
| 3         | 35-45   | 40  | 20     | 40  | 800       | 32,000      |
| 4         | 45-55   | 50  | 18     | 58  | 900       | 45,000      |
| 5         | 55-65   | 60  | 12     | 70  | 720       | 43,200      |
| 6         | 65-75   | 70  | 8      | 78  | 560       | 39,200      |
| 7         | 75-85   | 80  | 5      | 83  | 400       | 32,000      |
| **Total** |         |     | **83** |     | **3,920** | **206,400** |

#### A) Medidas de Tendencia Central:

**1. Media Aritmética**
```
X̄ = Σ(Xi × fi)/n = 3,920/83 = 47.23
```

**2. Mediana**
```
n/2 = 83/2 = 41.5
La mediana está en la clase 4 (45-55), ya que Fi-1 = 40 < 41.5 < Fi = 58

Li = 45 (límite inferior de la clase 4)
Fi-1 = 40 (frecuencia acumulada anterior)
fi = 18 (frecuencia de la clase mediana)
h = 10 (amplitud del intervalo)

Me = 45 + [(41.5-40)/18] × 10 = 45 + (1.5/18) × 10 = 45 + 0.83 = 45.83
```

**3. Moda**
```
Clase modal: Clase 3 (35-45) con fi = 20 (mayor frecuencia)

Li = 35
d1 = 20 - 14 = 6
d2 = 20 - 18 = 2
h = 10

Mo = 35 + [6/(6+2)] × 10 = 35 + (6/8) × 10 = 35 + 7.50 = 42.50
```

#### B) Medidas de Dispersión:

**1. Varianza**
```
s² = [Σ(Xi² × fi) - n(X̄)²]/(n-1)
s² = [206,400 - 83(47.23)²]/(83-1)
s² = [206,400 - 83(2,230.67)]/(82)
s² = [206,400 - 185,145.61]/82
s² = 21,254.39/82 = 259.20
```

**2. Desviación Estándar**
```
s = √s² = √259.20 = 16.10
```

**3. Coeficiente de Variación**
```
CV = (s/X̄) × 100 = (16.10/47.23) × 100 = 34.09%
```

---

## **INTERPRETACIÓN DE RESULTADOS:**

**Datos No Agrupados:**
- La media es 88.10, con una desviación estándar de 15.16, indicando moderada variabilidad
- La mediana (86.50) es ligeramente menor que la media, sugiriendo una ligera asimetría positiva

**Datos Agrupados:**
- La media es 47.23, con la mediana (45.83) y moda (42.50) mostrando una distribución ligeramente asimétrica positiva
- El coeficiente de variación del 34.09% sugiere variabilidad moderada-alta en los datos