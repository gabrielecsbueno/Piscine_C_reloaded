# Piscine Reloaded

Serie de ejercicios que consolida los conceptos fundamentales de C aprendidos durante la Piscine de 42 — desde scripting en shell hasta punteros a funciones y lectura de ficheros.

**Lenguaje:** C / Shell

---

## Shell (ex00 – ex05)

Primeros contactos con scripts de shell.

---

## Funciones Básicas y Condicionales (ex06 – ex08)

Introducción a la escritura de funciones en C, uso de bucles y estructuras condicionales.

- **ex06 — ft_print_alphabet** — Imprime el alfabeto en minúsculas usando un bucle `while`
- **ex07 — ft_print_numbers** — Imprime los dígitos del 0 al 9 usando un bucle `while`
- **ex08 — ft_is_negative** — Recibe un entero e imprime `N` si es negativo o `P` si es positivo

---

## Punteros (ex09 – ex11)

Concepto de punteros: acceso y modificación de valores por referencia.

- **ex09 — ft_ft** — Asigna el valor `42` a un entero mediante un puntero
- **ex10 — ft_swap** — Intercambia los valores de dos enteros mediante punteros
- **ex11 — ft_div_mod** — Calcula la división y el módulo, almacenando los resultados mediante punteros

---

## Iteración y Recursión (ex12 – ex14)

Comparación entre los dos enfoques para resolver el mismo problema.

- **ex12 — ft_iterative_factorial** — Calcula el factorial de forma iterativa con `while`
- **ex13 — ft_recursive_factorial** — Calcula el factorial de forma recursiva
- **ex14 — ft_sqrt** — Devuelve la raíz cuadrada entera de un número (o 0 si no es exacta)

---

## Manipulación de Cadenas (ex15 – ex17)

Funciones fundamentales para trabajar con cadenas en C.

- **ex15 — ft_putstr** — Imprime una cadena carácter a carácter
- **ex16 — ft_strlen** — Devuelve la longitud de una cadena
- **ex17 — ft_strcmp** — Compara dos cadenas lexicográficamente, devolviendo -1, 0 o 1

---

## Argumentos de Línea de Comandos (ex18 – ex19)

Uso de `argc` y `argv` para recibir y procesar argumentos en el terminal.

- **ex18 — ft_print_params** — Imprime cada argumento pasado al programa en una línea separada
- **ex19 — ft_sort_params** — Ordena e imprime los argumentos en orden lexicográfico (bubble sort)

---

## Asignación Dinámica de Memoria (ex20 – ex21)

Uso de `malloc` para asignar memoria en tiempo de ejecución.

- **ex20 — ft_strdup** — Duplica una cadena asignando memoria dinámicamente
- **ex21 — ft_range** — Crea y devuelve un array de enteros entre `min` y `max`

---

## Cabeceras, Macros y Structs (ex22 – ex23)

Organización del código con ficheros de cabecera, macros y tipos personalizados.

- **ex22 — ft_abs.h** — Define la macro `ABS(Value)` que devuelve el valor absoluto de un número
- **ex23 — ft_point.h** — Define la struct `t_point` con los campos `x` e `y` para representar un punto 2D

---

## Makefile y Compilación (ex24)

Automatización de la compilación con Makefile y generación de una biblioteca estática.

- **ex24 — libft** — Crea la biblioteca estática `libft.a` con las reglas `all`, `clean`, `fclean` y `re`

---

## Punteros a Funciones (ex25 – ex26)

Funciones que reciben otras funciones como argumento.

- **ex25 — ft_foreach** — Aplica una función a cada elemento de un array de enteros
- **ex26 — ft_count_if** — Cuenta cuántos elementos de un array de cadenas satisfacen una condición

---

## E/S de Ficheros (ex27)

Lectura de ficheros usando las llamadas al sistema `open`, `read`, `write` y `close`.

- **ex27 — ft_display_file** — Lee y muestra el contenido de un fichero pasado como argumento

---

## Cómo compilar

Para ejercicios con Makefile (ex24 y ex27):

```bash
cd ex24
make        # compila y genera libft.a
make clean  # elimina ficheros objeto
make fclean # elimina objetos y la biblioteca
make re     # recompila todo desde cero
```

Para ejercicios individuales en C:

```bash
gcc -Wall -Wextra -Werror ft_iterative_factorial.c -o factorial
./factorial
```

Para scripts de Shell:

```bash
chmod +x find_sh.sh
./find_sh.sh
```
