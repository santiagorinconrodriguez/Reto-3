# Repositorio reto #3

## Nombre: Brayan Santiago Rincón Rodríguez

Este repositorio nos mostrará el método pro (Criba de Erastotenes) para buscar los divisores de un número n, por medio de pseudocódigo y un diagrama de flujo.

# Pseudocódigo
``` 
Inicio:

 Declaración de variables:
n : entero
i : entero
t : entero

 Inicializar las variables:
i:=2
t : ⌊n^0.5 + 1⌋

 Iteración:
 mientras (i <= t) hacer:
    condicional:
     si modulo (n/i) == 0 entonces
       (i es divisor de n)
     sino
       (i no es divisor de n)

 i := i+1

fin si 
fin mientras

fin
``` 
