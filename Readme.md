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
# Diagrama de flujo
```
---
config:
  theme: redux
---
flowchart TD
    A(["Inicio"]) --> B["número n"]
    B --> C["t = ⌊n^0,5 + 1⌋"]
    C --> D["i = 2"]
    D --> E["n/i"]
    E --> F{"¿residuo=0?"}
     F -- Sí --> G["i es divisor de n"] 
     F -- No -->H["i no es divisor de n"]
    G --> I["i = i+1"]
    H --> I
    I --> J["¿i = t?"]
    J -- Sí -->n1(["Fin"])
    J -- No -->E
```

### Autor
Brayan Santiago Rincón Rodríguez

### curso
Programación de computadores