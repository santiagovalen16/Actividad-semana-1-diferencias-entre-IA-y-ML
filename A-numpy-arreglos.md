# NumPy – Creación y Manipulación de Arreglos  

## Introducción  

NumPy (Numerical Python) es una de las bibliotecas de código abierto más importantes en Python, cuya función principal es trabajar con arreglos multidimensionales (ndarrays). Su gran ventaja es que permite procesar datos de manera eficiente y realizar cálculos matemáticos y lógicos de gran complejidad, lo que resulta especialmente útil en ciencia de datos, análisis numérico e investigación.  


# Creacion de arreglos "ARRAYs"

   Antes de empezar tenemos que conocer como importar la libreria, para importar la
   libreria debemos utilizar el siguiente codigo: 

   ```python
      import numpy as np
   ```  

   Con las etiquetas "import numpy" estamos importando y llamando a la libreria "Numpy",
   para que sea mas dinamico al momento de su uso utilizamos las etiquetas "as np" para que "numpy" se renombre como "np".

## Arreglo "Array" de 1 dimension 
   
   Crear un arreglo de una dimension es muy facil haciendo uso de las siguientes etiquetas:

   ```python
      import numpy as np

      arr1 = np.array([1, 2, 3, 4, 5])
      print("arr1:", arr1, "shape:", arr1.shape, "dtype:",arr1.dtype)
   ```   

   Este es un Arreglo de 5 elemntos especificados en "np.arry[(1,2,3,4,5)]"; Que nos imprime los elementos del array con la etiqueta "print("nombre del array",arr1)", el numero de elementos del array con "arr1.shape" y imprime el tipo de dato con "arr1.dytype".

   El resultado que obtenemos es el siguiente:

   ```python
      arr1: [1 2 3 4 5] shape: (5) dtype: int64
   ```  
## Arreglo "Array" de 2 dimension 
   
   Crear un arreglo de dos dimension es muy facil haciendo uso de las siguientes etiquetas:

   ```python
      import numpy as np

      mat = np.array([[1, 2, 3], [4, 5, 6]])
      print("mat:\n", mat,)

   ```   

   Este arreglo cambia ya que el en "np.arry[(contenido)]" no solo tenemos uno, tenemos dos separados por una coma de la siguiente forma "np.array([[1, 2, 3], [4, 5, 6]])"; Que nos imprime los elementos del array con la etiqueta "print("nombre del array",mat)".

   El resultado que obtenemos es el siguiente:

   ```python
      mat:
        [[1 2 3]
         [4 5 6]] 
   ```  
## Reshape (cambiar la forma de un arreglo)
 
  ```python 
   import numpy as np

arr3 = np.arange(1, 13)  # Arreglo del 1 al 12
arr3_reshape = arr3.reshape(3, 4)
print("Arreglo original:", arr3)
print("Reshape 3x4:\n", arr3_reshape)
 ```
+ np.arange(1,13) genera un arreglo del 1 al 12.
+ reshape(3,4) transforma ese arreglo en una matriz de 3 filas por 4 columnas.

  Resultado:

```python
   Arreglo original: [ 1  2  3  4  5  6  7  8  9 10 11 12]
Reshape 3x4:
 [[ 1  2  3  4]
  [ 5  6  7  8]
  [ 9 10 11 12]]
```

## Concatenación de arreglos

   ```python
      import numpy as np

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
concat = np.concatenate((a, b))
print("Concatenación 1D:", concat)
   ```
Resultado:

   ```python
      Concatenación 1D: [1 2 3 4 5 6]
   ```
## Concatenación en 2D:

      ```python
      import numpy as np

c = np.array([[1, 2], [3, 4]])
d = np.array([[5, 6]])
concat2 = np.concatenate((c, d), axis=0)
print("Concatenación en 2D:\n", concat2)
   ```
Aquí unimos c y d a lo largo de las filas (axis=0), lo que nos da como resultado:

   ```python
Concatenación en 2D:
 [[1 2]
  [3 4]
  [5 6]]
   ```
## Operaciones básicas con arreglos

   ```python
      import numpy as np

x = np.array([10, 20, 30, 40])
y = np.array([1, 2, 3, 4])

print("Suma:", x + y)
print("Resta:", x - y)
print("Multiplicación:", x * y)
print("División:", x / y)
print("Potencia:", x ** 2)

# Operaciones estadísticas
print("Máximo de x:", np.max(x))
print("Mínimo de x:", np.min(x))
print("Promedio de x:", np.mean(x))
print("Desviación estándar de x:", np.std(x))
   ```

 Las operaciones (+, -, *, /) se aplican elemento por elemento, igualemte los "np.max, np.min, np.mean y np.std" permiten obtener estadísticas rápidamente dando como resultado:

   ```python
      Suma: [11 22 33 44]
Resta: [ 9 18 27 36]
Multiplicación: [10 40 90 160]
División: [10. 10. 10. 10.]
Potencia: [100 400 900 1600]

Máximo de x: 40
Mínimo de x: 10
Promedio de x: 25.0
Desviación estándar de x: 11.180339887498949
   ``` 

## Fuentes  

- Array creation — NumPy v2.3 manual. (s/f). Numpy.org. Recuperado el 23 de agosto de 2025, de https://numpy.org/doc/stable/user/basics.creation.html  

- Linear algebra — NumPy v2.3 manual. (s/f). Numpy.org. Recuperado el 23 de agosto de 2025, de https://numpy.org/doc/stable/reference/routines.linalg.html  

- Statistics — NumPy v2.3 manual. (s/f). Numpy.org. Recuperado el 23 de agosto de 2025, de https://numpy.org/doc/stable/reference/routines.statistics.html  

- Sherrill, D. [@CodeWithDerrick]. (s/f). Introduction to NumPy arrays for beginners - learn NumPy series [Video]. Youtube. Recuperado el 23 de agosto de 2025, de https://www.youtube.com/watch?v=9fcTq8PDWWA

### Evidencia fotografica
      
<img width="554" height="189" alt="image" src="https://github.com/user-attachments/assets/22e5d49e-a4c8-4996-82d9-33a5e0dcc6b6" />
<img width="393" height="191" alt="image" src="https://github.com/user-attachments/assets/d6eddfdb-f857-49e4-a748-4ac7bde8e5e6" />
<img width="474" height="256" alt="image" src="https://github.com/user-attachments/assets/c9236cce-ff30-4308-a596-1402060850a0" />
<img width="472" height="261" alt="image" src="https://github.com/user-attachments/assets/fc35e244-a2ba-4ba6-a22d-30198d15e1ad" />
<img width="306" height="178" alt="image" src="https://github.com/user-attachments/assets/b30e41af-60b1-4bef-8ac8-6120954443d9" />
<img width="356" height="235" alt="image" src="https://github.com/user-attachments/assets/d43c0d56-0fd5-449f-a65a-29b14d49b945" />
<img width="457" height="508" alt="image" src="https://github.com/user-attachments/assets/ea0db7e0-3beb-4fcf-8c08-e1ad3bdc2469" />
