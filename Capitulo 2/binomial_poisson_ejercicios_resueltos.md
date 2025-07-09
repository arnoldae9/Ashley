# Distribución de Poisson - Problema de Llamadas Telefónicas

## Datos del problema
- Promedio de llamadas por minuto: $\lambda = 2.5$
- Distribución: Poisson

La función de probabilidad de Poisson es:
$$P(X = k) = \frac{e^{-\lambda} \lambda^k}{k!}$$

donde $\lambda = 2.5$ y $k$ es el número de llamadas.

## Solución

### a) Probabilidad de exactamente 3 llamadas

$$P(X = 3) = \frac{e^{-2.5} \cdot 2.5^3}{3!}$$

$$P(X = 3) = \frac{e^{-2.5} \cdot 15.625}{6}$$

$$P(X = 3) = \frac{0.0821 \cdot 15.625}{6} = \frac{1.2828}{6} = 0.2138$$

**Respuesta:** $P(X = 3) = 0.2138$ o **21.38%**

### b) Probabilidad de más de 3 llamadas

$$P(X > 3) = 1 - P(X \leq 3)$$

$$P(X \leq 3) = P(X = 0) + P(X = 1) + P(X = 2) + P(X = 3)$$

Calculando cada término:

- $P(X = 0) = \frac{e^{-2.5} \cdot 2.5^0}{0!} = \frac{0.0821 \cdot 1}{1} = 0.0821$

- $P(X = 1) = \frac{e^{-2.5} \cdot 2.5^1}{1!} = \frac{0.0821 \cdot 2.5}{1} = 0.2052$

- $P(X = 2) = \frac{e^{-2.5} \cdot 2.5^2}{2!} = \frac{0.0821 \cdot 6.25}{2} = 0.2565$

- $P(X = 3) = 0.2138$ (calculado anteriormente)

$$P(X \leq 3) = 0.0821 + 0.2052 + 0.2565 + 0.2138 = 0.7576$$

$$P(X > 3) = 1 - 0.7576 = 0.2424$$

**Respuesta:** $P(X > 3) = 0.2424$ o **24.24%**

### c) Probabilidad de a lo más 3 llamadas

$$P(X \leq 3) = 0.7576$$ (calculado en el inciso anterior)

**Respuesta:** $P(X \leq 3) = 0.7576$ o **75.76%**

## Resumen de resultados

| Evento                 | Probabilidad | Porcentaje |
| ---------------------- | ------------ | ---------- |
| Exactamente 3 llamadas | 0.2138       | 21.38%     |
| Más de 3 llamadas      | 0.2424       | 24.24%     |
| A lo más 3 llamadas    | 0.7576       | 75.76%     |