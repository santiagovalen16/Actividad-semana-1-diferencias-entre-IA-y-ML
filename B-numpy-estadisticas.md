# Datasheet: NumPy – Operaciones estadísticas y funciones avanzadas

**Sección B – Elaborado por Laura Bernal**  
> Ejemplos ejecutados en Google Colab

---

## 1. Operaciones estadísticas básicas

### 1.1. Promedio (`mean`)
```python
import numpy as np

arr = np.array([10, 20, 30, 40])
promedio = np.mean(arr)
print(promedio)
```
**Resultado:**
```
25.0
```

### 1.2. Desviación estándar (`std`)
```python
std = np.std(arr)
print(std)
```
**Resultado:**
```
11.180339887498949
```

### 1.3. Suma de elementos (`sum`)
```python
suma = np.sum(arr)
print(suma)
```
**Resultado:**
```
100
```

---

## 2. Creación de secuencias y valores aleatorios

### 2.1. Secuencia con `arange`
```python
secuencia = np.arange(0, 10, 2)
print(secuencia)
```
**Resultado:**
```
[0 2 4 6 8]
```

### 2.2. Secuencia equiespaciada con `linspace`
```python
espaciados = np.linspace(0, 1, 5)
print(espaciados)
```
**Resultado:**
```
[0.   0.25 0.5  0.75 1.  ]
```

### 2.3. Números aleatorios con `np.random`
```python
aleatorios = np.random.rand(3)
print(aleatorios)
```
**Resultado (varía):**
```
[0.355 0.807 0.602]
```

---

## 3. Álgebra lineal con NumPy

### 3.1. Producto punto (`dot`)
```python
a = np.array([1, 2])
b = np.array([3, 4])
producto_punto = np.dot(a, b)
print(producto_punto)
```
**Resultado:**
```
11
```

### 3.2. Matriz identidad y multiplicación de matrices
```python
matriz = np.array([[1, 2], [3, 4]])
identidad = np.eye(2)
multiplicacion = np.matmul(matriz, identidad)
print(multiplicacion)
```
**Resultado:**
```
[[1. 2.]
 [3. 4.]]
```

### 3.3. Determinante de una matriz
```python
det = np.linalg.det(matriz)
print(det)
```
**Resultado:**
```
-2.0000000000000004
```

### 3.4. Inversa de una matriz
```python
inversa = np.linalg.inv(matriz)
print(inversa)
```
**Resultado:**
```
[[-2.   1. ]
 [ 1.5 -0.5]]
```

---

## Fuentes

- [Documentación oficial de NumPy](https://numpy.org/doc/)
- [Tutorial Google Colab](https://colab.research.google.com/)

----------
# Evidencia con pantallazos de la ejecución del codigo en google colab
**Aqui logramos ver los resultados obtenidos

--------

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/9f20d848-6d1b-4411-a74d-9b06acf0fb7f" />

---------

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/9cb6db53-7466-426a-9540-23a8077db725" />

--------

<img width="1366" height="720" alt="image" src="https://github.com/user-attachments/assets/b1e10065-5769-4dfd-8469-6a01f9af2ef6" />

------

