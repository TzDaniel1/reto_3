# reto_3

## Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

#### Seudocódigo
```
Inicio
  Leer n
  Para cada número desde 2 hasta n:
    Si numero <= 1:
    Devolver Falso
  Para cada divisor desde 2 hasta la raíz cuadrada de numero:
    Si numero es divisible entre divisor:
      Devolver Falso
    sino:
      devolver verdadero
  Para cada divisor desde 2 hasta el número - 1:
        Romper el bucle
  Si es Verdadero:
    Imprimir el número
 Fin
Fin
```
![Diagrama de flujo](https://www.mermaidchart.com/raw/f1b68877-8a67-405f-86ee-f3ce654d54cb?theme=dark&version=v0.1&format=svg)

