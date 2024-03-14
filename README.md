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
flowchart TD
    A(Inicio)-->B[numerp n]
    B-->C[lista desde 2 hasta √n+1]
    C-->D[i=2]
    D-->E{ ¿i es primo? }
    E-->|no| F[i ni es primo]
    E-->|si| G[i es primo]
    F-->H[i=i+1]
    G-->H
    H-->I{¿i<n?}
    I-->|si| E
    I-->|no| J(fin)
