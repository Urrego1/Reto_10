# Reto_10

***1. Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.***


```python
def Promedio_reales(lista):
    #Suma y cantidad de elementos
    suma = sum(lista)
    numero_elementos = len(lista)
    
    #Promedio
    promedio = suma / numero_elementos
    
    return promedio

arreglo_reales = [1.06, 2, 3.9, 4.4, 5, 6.5]
promedio = Promedio_reales(arreglo_reales)
print(f"El promedio del arreglo ingresado es: {promedio}")
```


***2. Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.***

```python

def producto_punto(arreglo1, arreglo2):
	producto = 0
	for i in range(len(arreglo1)):
		producto += arreglo1[i] * arreglo2[i]
	return producto

arreglo1 = [1, 3, 5]
arreglo2 = [4, 8, 9]
producto = producto_punto(arreglo1, arreglo2)
print(f"El producto punto de los arreglos ingresados es {producto}")  

```

***3. Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.***



```python
def ceros_arreglo(arreglo):
	return [x for x in arreglo if x != 0] + [x for x in arreglo if x == 0]

arreglo = [1, 0, 2, 0, 3, 0, 4]
arreglo_ceros_final = ceros_arreglo(arreglo)
print(f"El arreglo con los ceros al final es {arreglo_ceros_final}") 

```






