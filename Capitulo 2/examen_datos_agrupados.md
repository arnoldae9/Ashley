# Examen de Repaso - Estadística Descriptiva

## **PARTE I: DATOS NO AGRUPADOS**

### Problema 1
Calcular las **3 medidas de tendencia central** para el siguiente conjunto de datos:

**{75, 92, 88, 96, 105, 78, 112, 85, 91, 102}**

a) **Media Aritmética**
b) **Mediana**
c) **Moda**

### Problema 2
Para el mismo conjunto de datos del problema 1, calcule las siguientes **medidas de dispersión**:

a) **Desviación Absoluta Media**
b) **Varianza Muestral**
c) **Desviación Estándar Muestral**

---

## **PARTE II: DATOS AGRUPADOS**

### Problema 3
Calcular las **medidas de tendencia central** y las **medidas de dispersión** para la siguiente tabla de frecuencias:

| Clase | Límites | Marca de Clase (Xi) | Frecuencia (fi) |
| ----- | ------- | ------------------- | --------------- |
| 1     | 20-30   | 25                  | 8               |
| 2     | 30-40   | 35                  | 12              |
| 3     | 40-50   | 45                  | 18              |
| 4     | 50-60   | 55                  | 15              |
| 5     | 60-70   | 65                  | 10              |
| 6     | 70-80   | 75                  | 7               |

**Total n = 70**

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

## **FÓRMULAS DE REFERENCIA:**

### Datos No Agrupados:
- **Media:** X̄ = Σx/n
- **Mediana:** Valor central ordenado
- **DAM:** Σ|Xi - X̄|/n
- **Varianza:** s² = Σ(Xi - X̄)²/(n-1)
- **Desviación Estándar:** s = √s²

### Datos Agrupados:
- **Media:** X̄ = Σ(Xi × fi)/n
- **Mediana:** Li + [(n/2 - Fi-1)/fi] × h
- **Moda:** Li + [(d1)/(d1 + d2)] × h
- **Varianza:** s² = [Σ(Xi² × fi) - n(X̄)²]/(n-1)

**Tiempo sugerido:** 90 minutos

---

# SOLUCIONARIO

## **PARTE I: DATOS NO AGRUPADOS**

### Datos: {75, 92, 88, 96, 105, 78, 112, 85, 91, 102}

### Problema 1: Medidas de Tendencia Central

**a) Media Aritmética (X̄)**
```
X̄ = Σx/n = (75+92+88+96+105+78+112+85+91+102)/10
X̄ = 924/10 = 92.40
```

**b) Mediana (Me)**
```
Datos ordenados: {75, 78, 85, 88, 91, 92, 96, 102, 105, 112}
n = 10 (par)
Me = (X₅ + X₆)/2 = (91 + 92)/2 = 91.50
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

|75-92.40| = 17.40    |85-92.40| = 7.40
|92-92.40| = 0.40     |91-92.40| = 1.40
|88-92.40| = 4.40     |102-92.40| = 9.60
|96-92.40| = 3.60     |105-92.40| = 12.60
|78-92.40| = 14.40    |112-92.40| = 19.60

DAM = (17.40+0.40+4.40+3.60+14.40+7.40+1.40+9.60+12.60+19.60)/10
DAM = 90.80/10 = 9.08
```

**b) Varianza Muestral (s²)**
```
s² = Σ(Xi - X̄)²/(n-1)

(75-92.40)² = 302.76    (85-92.40)² = 54.76
(92-92.40)² = 0.16      (91-92.40)² = 1.96
(88-92.40)² = 19.36     (102-92.40)² = 92.16
(96-92.40)² = 12.96     (105-92.40)² = 158.76
(78-92.40)² = 207.36    (112-92.40)² = 384.16

s² = (302.76+0.16+19.36+12.96+207.36+54.76+1.96+92.16+158.76+384.16)/9
s² = 1234.40/9 = 137.16
```

**c) Desviación Estándar Muestral (s)**
```
s = √s² = √137.16 = 11.71
```

---

## **PARTE II: DATOS AGRUPADOS**

### Problema 3: Tabla de Frecuencias

| Clase     | Límites | Xi  | fi     | Fi  | Xi·fi     | Xi²·fi      |
| --------- | ------- | --- | ------ | --- | --------- | ----------- |
| 1         | 20-30   | 25  | 8      | 8   | 200       | 5,000       |
| 2         | 30-40   | 35  | 12     | 20  | 420       | 14,700      |
| 3         | 40-50   | 45  | 18     | 38  | 810       | 36,450      |
| 4         | 50-60   | 55  | 15     | 53  | 825       | 45,375      |
| 5         | 60-70   | 65  | 10     | 63  | 650       | 42,250      |
| 6         | 70-80   | 75  | 7      | 70  | 525       | 39,375      |
| **Total** |         |     | **70** |     | **3,430** | **183,150** |

#### A) Medidas de Tendencia Central:

**1. Media Aritmética**
```
X̄ = Σ(Xi × fi)/n = 3,430/70 = 49.00
```

**2. Mediana**
```
n/2 = 70/2 = 35
La mediana está en la clase 4 (50-60), ya que Fi-1 = 38 > 35

Li = 40 (límite inferior de la clase 3)
Fi-1 = 20 (frecuencia acumulada anterior)
fi = 18 (frecuencia de la clase mediana)
h = 10 (amplitud del intervalo)

Me = 40 + [(35-20)/18] × 10 = 40 + (15/18) × 10 = 40 + 8.33 = 48.33
```

**3. Moda**
```
Clase modal: Clase 3 (40-50) con fi = 18 (mayor frecuencia)

Li = 40
d1 = 18 - 12 = 6
d2 = 18 - 15 = 3
h = 10

Mo = 40 + [6/(6+3)] × 10 = 40 + (6/9) × 10 = 40 + 6.67 = 46.67
```

#### B) Medidas de Dispersión:

**1. Varianza**
```
s² = [Σ(Xi² × fi) - n(X̄)²]/(n-1)
s² = [183,150 - 70(49.00)²]/(70-1)
s² = [183,150 - 70(2,401)]/(69)
s² = [183,150 - 168,070]/69
s² = 15,080/69 = 218.55
```

**2. Desviación Estándar**
```
s = √s² = √218.55 = 14.78
```

**3. Coeficiente de Variación**
```
CV = (s/X̄) × 100 = (14.78/49.00) × 100 = 30.16%
```

---

## **INTERPRETACIÓN DE RESULTADOS:**

**Datos No Agrupados:**
- La media es 92.40, con una desviación estándar de 11.71, indicando moderada variabilidad
- La mediana (91.50) es ligeramente menor que la media, sugiriendo una ligera asimetría positiva

**Datos Agrupados:**
- La media es 49.00, con la mediana (48.33) y moda (46.67) cercanas, indicando distribución relativamente simétrica
- El coeficiente de variación del 30.16% sugiere variabilidad moderada en los datos