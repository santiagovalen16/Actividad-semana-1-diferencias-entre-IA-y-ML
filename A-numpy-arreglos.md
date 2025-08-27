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

## Arreglo "Array" de 1 dimencion 
   
   Crear un arreglo de una dimencion es muy facil haciendo uso de las siguientes etiquetas:

   ```python
      import numpy as np

      arr1 = np.array([1, 2, 3, 4, 5])
      print("arr1:", arr1, "shape:", arr1.shape, "dtype:",arr1.dtype)
   ```   

   Este es un Arreglo de 5 elemntos que nos imprime los elementos del array con la etiqueta "print("nombre del array",arr1)", el numero de elementos del array con "arr1.shape" y imprime el tipo de dato con "arr1.dytype".

### Comprobacion google colab
    [Evidencias fotograficas](https://github.com/santiagovalen16/Actividad-semana-1-diferencias-entre-IA-y-ML/tree/Master/pantallazos)

## Referencias

- Introducción a Inteligencia Artificial [Video]. (s.f.). YouTube. https://www.youtube.com/watch?v=CjdusCm73p0&t=745s

- Machine Learning vs Artificial Intelligence … [Video]. (s.f.). YouTube. https://www.youtube.com/watch?v=FMkxSsfvMI4

- IBM. (s.f.). ¿Qué es machine learning? IBM Think. https://www.ibm.com/mx-es/think/topics/machine-learning

- China, C. R. (20 de diciembre de 2023). Cinco tipos de machine learning que conviene conocer. IBM Think. https://www.ibm.com/es-es/think/topics/machine-learning-types       
