# PraticaNumpy
NumPy é uma biblioteca do Python usada para trabalhar com arrays (listas de números organizadas em linhas e colunas). Ela é muito mais rápida e eficiente do que listas comuns do Python quando lidamos com grandes quantidades de dados.

import numpy as np
arr = np.array([10, 20, 30, 40])
print(np.median(arr))  # 25.0 média
print(np.std(arr))     # 11.18... desvio padrão
print(np.var(arr))     # 125.0 variância
print(np.max(arr))	   # máximo

import numpy as np

arr = np.array([1, 2, 3, 4, 5])
print(np.std(arr))


import numpy as np

arr = np.array([2, 4, 6, 8])   # agora arr existe
print(np.sum(arr))             # soma dos elementos
print(np.max(arr))             # valor máximo

import numpy as np

arr = np.array([3, 6, 9, 12])
print(np.mean(arr))
print(np.min(arr))

matriz = np.array([[1, 2, 3],
                   [4, 5, 6]])
print(matriz.shape)

import numpy as np

arr = np.arange(12)        # cria [0 1 2 3 4 5 6 7 8 9 10 11]
matriz = arr.reshape(3, 4) # transforma em matriz 3x4
print(matriz)

import numpy as np

arr = np.arange(9)
matriz = arr.reshape(3, 3)
print(matriz)

import numpy as np

arr = np.arange(12)
matriz = arr.reshape(4, 3)
print(matriz)

import numpy as np

arr = np.array([10, 20, 30, 40])
print(arr[0])    # primeiro elemento
print(arr[1:3])  # do índice 1 até 2

import numpy as np

matriz = np.array([[10, 20, 30],
                   [40, 50, 60],
                   [70, 80, 90]])

print(matriz[0, 0])  # linha 0, coluna 0 → 10
print(matriz[1, 2])  # linha 1, coluna 2 → 60
print(matriz[2, 1])  # linha 2, coluna 1 → 80

import numpy as np

print(matriz[0:2, 1:3])
print(matriz[2, 2])
print(matriz[1])   # segunda linha inteira
print(matriz[:, 2])   # todas as linhas, coluna 2
print(matriz[:, 0])   # todas as linhas, coluna 0
print(matriz[1, 1])
print(matriz[0:2, 1:3])
print(matriz[1:3, 0:2])
print(matriz[:, 1])
print(matriz[1:3, 2:3])
print(matriz[0:2, :])
