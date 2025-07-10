# Problemas de Distribución Normal

## Problema 1 (Original)

**Enunciado:** La media de los pesos de 500 estudiantes de cierto colegio es de 151 lb y la desviación típica es de 15 lb. Suponiendo que los pesos se distribuyen normalmente, hallar cuántos estudiantes pesan entre 120 y 155 lbs.

### Solución:

**Datos:**
- $n = 500$ estudiantes
- $\mu = 151$ lb (media)
- $\sigma = 15$ lb (desviación típica)
- Queremos encontrar: número de estudiantes con peso entre 120 y 155 lb

**Paso 1:** Estandarizar los valores usando $Z = \frac{X - \mu}{\sigma}$

Para $X = 120$ lb:
$$Z_1 = \frac{120 - 151}{15} = \frac{-31}{15} = -2.07$$

Para $X = 155$ lb:
$$Z_2 = \frac{155 - 151}{15} = \frac{4}{15} = 0.27$$

**Paso 2:** Calcular las probabilidades usando la tabla de distribución normal estándar

$P(Z < -2.07) = 0.0192$
$P(Z < 0.27) = 0.6064$

**Paso 3:** Encontrar la probabilidad entre los dos valores

$$P(120 < X < 155) = P(-2.07 < Z < 0.27) = P(Z < 0.27) - P(Z < -2.07)$$
$$P(120 < X < 155) = 0.6064 - 0.0192 = 0.5872$$

**Paso 4:** Calcular el número de estudiantes

Número de estudiantes = $500 \times 0.5872 = 293.6 \approx 294$ estudiantes

**Respuesta:** Aproximadamente 294 estudiantes pesan entre 120 y 155 libras.

---

## Problema 2 (Nuevo)

**Enunciado:** En una fábrica de bombillas, la duración promedio es de 800 horas con una desviación estándar de 50 horas. Si se producen 1000 bombillas y la duración sigue una distribución normal, ¿cuántas bombillas durarán entre 750 y 900 horas?

### Solución:

**Datos:**
- $n = 1000$ bombillas
- $\mu = 800$ horas (media)
- $\sigma = 50$ horas (desviación típica)
- Queremos encontrar: número de bombillas que duran entre 750 y 900 horas

**Paso 1:** Estandarizar los valores

Para $X = 750$ horas:
$$Z_1 = \frac{750 - 800}{50} = \frac{-50}{50} = -1.00$$

Para $X = 900$ horas:
$$Z_2 = \frac{900 - 800}{50} = \frac{100}{50} = 2.00$$

**Paso 2:** Calcular las probabilidades

$P(Z < -1.00) = 0.1587$
$P(Z < 2.00) = 0.9772$

**Paso 3:** Encontrar la probabilidad entre los dos valores

$$P(750 < X < 900) = P(-1.00 < Z < 2.00) = P(Z < 2.00) - P(Z < -1.00)$$
$$P(750 < X < 900) = 0.9772 - 0.1587 = 0.8185$$

**Paso 4:** Calcular el número de bombillas

Número de bombillas = $1000 \times 0.8185 = 818.5 \approx 819$ bombillas

**Respuesta:** Aproximadamente 819 bombillas durarán entre 750 y 900 horas.

---

## Problema 3 (Adicional)

**Enunciado:** Las calificaciones de un examen siguen una distribución normal con media 75 y desviación estándar 12. Si 300 estudiantes presentaron el examen, ¿cuántos obtuvieron una calificación superior a 90?

### Solución:

**Datos:**
- $n = 300$ estudiantes
- $\mu = 75$ (media)
- $\sigma = 12$ (desviación típica)
- Queremos encontrar: número de estudiantes con calificación > 90

**Paso 1:** Estandarizar el valor

Para $X = 90$:
$$Z = \frac{90 - 75}{12} = \frac{15}{12} = 1.25$$

**Paso 2:** Calcular la probabilidad

$P(Z < 1.25) = 0.8944$

Por lo tanto:
$$P(X > 90) = P(Z > 1.25) = 1 - P(Z < 1.25) = 1 - 0.8944 = 0.1056$$

**Paso 3:** Calcular el número de estudiantes

Número de estudiantes = $300 \times 0.1056 = 31.68 \approx 32$ estudiantes

**Respuesta:** Aproximadamente 32 estudiantes obtuvieron una calificación superior a 90.

---

## Fórmulas Importantes

### Estandarización
$$Z = \frac{X - \mu}{\sigma}$$

### Probabilidad entre dos valores
$$P(a < X < b) = P\left(\frac{a - \mu}{\sigma} < Z < \frac{b - \mu}{\sigma}\right)$$

### Número esperado
$$\text{Número esperado} = n \times P(\text{evento})$$