# project-of-iccfdvfrrvr
import os
import sys

p = input()
p_part = p.split(",")
n = int(p_part[0])
m= int(p_part[1])
lista = []
if n > 0:
    if n >= m > 0:
        for i in range(n):
            x = int(input())
            lista.append(x)
            q = lista[n-m:]
        print(tuple(q))
    else:
        print("Invalid input")
más:
    imprimir ("Entrada inválida") 
