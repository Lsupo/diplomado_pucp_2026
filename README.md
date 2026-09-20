
# Parte 4 – NumPy [4 puntos]

# Importar NumPy
import numpy as np

# 1. Crear un array con los números del 1 al 10
array_numeros = np.arange(1, 10)
print("1. Array con números del 1 al 10:")
print(array_numeros)

# 2. Imprimir la matriz / array
print("\n2. Array:")
print(array_numeros)

# 3. Mostrar el valor máximo y mínimo
valor_maximo = np.max(array_numeros)
valor_minimo = np.min(array_numeros)
print("\n3. Valor máximo:")
print(valor_maximo)
print("Valor mínimo:")
print(valor_minimo)

# 4. Crear un array de 5 ceros
array_ceros = np.zeros(5)
print("\n4. Array de 5 ceros:")
print(array_ceros)

# 5. Crear un array de 5 unos
array_unos = np.ones(5)
print("\n5. Array de 5 unos:")
print(array_unos)

# 6. Crear la matriz
matrix = np.array([
    [1, 2, 3],
    [4, 5, 6]
])
print("\n6. Matriz:")
print(matrix)

# 7. Mostrar la matriz
print("\n7. Matriz:")
print(matrix)

# 8. Mostrar las dimensiones de la matriz
print("\n8. Dimensiones de la matriz:")
print(matrix.shape)
