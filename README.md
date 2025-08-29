# Practica_Merge_Sort_Lab_EDA2

## Ejercicio de Programación en C: Implementación de Merge Sort

### Descripción del Problema
Se desea implementar un programa en **C** que utilice el algoritmo **Merge Sort** para ordenar datos.  
El programa debe recibir como entrada `n` arreglos lineales, cada uno de tamaño `n`.  
La salida debe ser **un solo arreglo lineal** que contenga todos los elementos de los arreglos de entrada en **orden creciente**.

En otras palabras, si tenemos `n` arreglos de tamaño `n`, el programa debe devolver un arreglo final de tamaño `n*n` que esté completamente ordenado.

---

### Requisitos
1. Implementar la función **Merge** para combinar dos subarreglos en orden.
2. Leer los datos de entrada desde la consola:
   - Primero, el número `n`.
   - Después, los `n` arreglos de tamaño `n`.
3. Guardar todos los elementos en un único arreglo.
4. Aplicar **Merge Sort** al arreglo completo.
5. Imprimir el arreglo final ordenado.
6. Escribe tu implementación en el archivo llamado `merge_sort.c` en este repositorio.

---

### Ejemplo de Entrada
Sea $n = 3$.

$$A_1 = \{ 3, 1, 5 \}$$

$$A_2 = \{ 2, 9, 4 \}$$

$$A_3 = \{ 8, 7, 6 \}$$

La salida correspondiente es $$A = A_1 \cup A_2 \cup A_3 = \{ 1, 2, 3, 4, 5, 6, 7, 8, 9 \}$$
