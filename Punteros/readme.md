# Introducción a Punteros en C++

Este programa demuestra el uso básico de punteros en C++. Se define una variable entera, se crea un puntero para almacenar su dirección de memoria, y se muestra cómo acceder tanto a la dirección como al valor utilizando el puntero.

## Descripción

1. Se declara una variable entera (`var`) y se le asigna un valor.
2. Un puntero (`ptr`) almacena la dirección de memoria de `var` utilizando el operador `&`.
3. Se imprime:
   - El valor de la variable.
   - La dirección de memoria de la variable.
   - El valor almacenado en el puntero (la dirección de `var`).
   - El valor al que apunta el puntero utilizando el operador de desreferenciación (`*`).

## Instrucciones

1. Guarda el código en un archivo llamado `Punteros.cpp`.
2. Compila el código:
   ```bash
   g++ Punteros.cpp -o Punteros

