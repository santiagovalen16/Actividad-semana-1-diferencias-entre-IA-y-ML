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

### Comprobacion google colab
    [Evidencias fotograficas](https://github.com/santiagovalen16/Actividad-semana-1-diferencias-entre-IA-y-ML/tree/Master/pantallazos)

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

### Comprobacion google colab
    [Evidencias fotograficas](https://github.com/santiagovalen16/Actividad-semana-1-diferencias-entre-IA-y-ML/tree/Master/pantallazos)
 
## Arreglo "Array" de 3 dimension 
   
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

### Comprobacion google colab
    [Evidencias fotograficas](https://github.com/santiagovalen16/Actividad-semana-1-diferencias-entre-IA-y-ML/tree/Master/pantallazos)
 