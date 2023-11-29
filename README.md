# Gráfica de Distribución Gaussiana y Aproximación de la Integral

Este breve script en Python visualiza una distribución gaussiana y calcula la integral aproximada dentro de un rango definido por el usuario.

## Dependencias
- `numpy`
- `sympy`
- `scipy`
- `matplotlib`

## Uso
1. Ejecuta el script.
2. Ingresa los valores para la media (\(\mu\)), desviación estándar (\(\sigma\)), límite inferior (\(a\)) y límite superior (\(b\)).
3. El script grafica la distribución gaussiana y sombrea el área bajo la curva entre \(a\) y \(b\).
4. Imprime el valor aproximado de la integral utilizando la función `quad` de `scipy`.

## Ejemplo
```python
# Ejemplo de entrada:
# mu_value = 0.0, sigma_value = 1.0, a_limit = -1.0, b_limit = 1.0
# Resultado: Una gráfica de la distribución gaussiana y la aproximación de la integral.

# Ejecuta el script e ingresa los valores según se te indique.
```

---

# Integración Numérica de la Función Gaussiana

## Resumen

Este script en Python realiza la integración numérica de una función gaussiana e imprime los resultados para varios límites superiores.

## Dependencias
- `numpy`
- `sympy`
- `scipy`
- `matplotlib`

## Uso
1. Ejecuta el script.
2. Ingresa el límite superior (\(b\)) cuando se te solicite.
3. El script realiza la integración acumulativa desde un valor inicial hasta \(b\) con un incremento especificado.
4. Imprime los resultados para cada paso.

## Ejemplo
```python
# Ejemplo de entrada:
# Ingrese el límite superior (b): 2.0
# Resultado: Imprime las integrales acumulativas para cada paso hasta b.

# Ejecute el script e ingrese el límite superior según se le indique.
```
