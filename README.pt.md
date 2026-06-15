# Piscine Reloaded

Série de exercícios que consolida os conceitos fundamentais de C aprendidos durante a Piscine da 42 — desde shell scripting até ponteiros para funções e leitura de arquivos.

**Linguagem:** C / Shell

---

## Shell (ex00 – ex05)

Primeiros contatos com scripts de shell.

---

## Funções Básicas e Condicionais (ex06 – ex08)

Introdução à escrita de funções em C, uso de loops e estruturas condicionais.

- **ex06 — ft_print_alphabet** — Imprime o alfabeto em minúsculas usando um loop `while`
- **ex07 — ft_print_numbers** — Imprime os dígitos de 0 a 9 usando um loop `while`
- **ex08 — ft_is_negative** — Recebe um inteiro e imprime `N` se negativo ou `P` se positivo

---

## Ponteiros (ex09 – ex11)

Conceito de ponteiros: acesso e modificação de valores por referência.

- **ex09 — ft_ft** — Atribui o valor `42` a um inteiro via ponteiro
- **ex10 — ft_swap** — Troca os valores de dois inteiros via ponteiros
- **ex11 — ft_div_mod** — Calcula divisão e módulo, armazenando os resultados via ponteiros

---

## Iteração e Recursão (ex12 – ex14)

Comparação entre as duas abordagens para resolver o mesmo problema.

- **ex12 — ft_iterative_factorial** — Calcula o fatorial de forma iterativa com `while`
- **ex13 — ft_recursive_factorial** — Calcula o fatorial de forma recursiva
- **ex14 — ft_sqrt** — Retorna a raiz quadrada inteira de um número (ou 0 se não for exata)

---

## Manipulação de Strings (ex15 – ex17)

Funções fundamentais para trabalhar com strings em C.

- **ex15 — ft_putstr** — Imprime uma string caractere por caractere
- **ex16 — ft_strlen** — Retorna o comprimento de uma string
- **ex17 — ft_strcmp** — Compara duas strings lexicograficamente, retornando -1, 0 ou 1

---

## Argumentos da Linha de Comando (ex18 – ex19)

Uso de `argc` e `argv` para receber e processar argumentos no terminal.

- **ex18 — ft_print_params** — Imprime cada argumento passado ao programa em uma linha separada
- **ex19 — ft_sort_params** — Ordena e imprime os argumentos em ordem lexicográfica (bubble sort)

---

## Alocação Dinâmica de Memória (ex20 – ex21)

Uso de `malloc` para alocar memória em tempo de execução.

- **ex20 — ft_strdup** — Duplica uma string alocando memória dinamicamente
- **ex21 — ft_range** — Cria e retorna um array de inteiros entre `min` e `max`

---

## Headers, Macros e Structs (ex22 – ex23)

Organização do código com arquivos de cabeçalho, macros e tipos personalizados.

- **ex22 — ft_abs.h** — Define a macro `ABS(Value)` que retorna o valor absoluto de um número
- **ex23 — ft_point.h** — Define a struct `t_point` com campos `x` e `y` para representar um ponto 2D

---

## Makefile e Compilação (ex24)

Automação da compilação com Makefile e geração de uma biblioteca estática.

- **ex24 — libft** — Cria a biblioteca estática `libft.a` com regras `all`, `clean`, `fclean` e `re`

---

## Ponteiros para Funções (ex25 – ex26)

Funções que recebem outras funções como argumento.

- **ex25 — ft_foreach** — Aplica uma função a cada elemento de um array de inteiros
- **ex26 — ft_count_if** — Conta quantos elementos de um array de strings satisfazem uma condição

---

## I/O de Arquivos (ex27)

Leitura de arquivos usando as syscalls `open`, `read`, `write` e `close`.

- **ex27 — ft_display_file** — Lê e exibe o conteúdo de um arquivo passado como argumento

---

## Como compilar

Para exercícios com Makefile (ex24 e ex27):

```bash
cd ex24
make        # compila e gera libft.a
make clean  # remove arquivos objeto
make fclean # remove objetos e a biblioteca
make re     # recompila tudo do zero
```

Para exercícios individuais em C:

```bash
gcc -Wall -Wextra -Werror ft_iterative_factorial.c -o factorial
./factorial
```

Para scripts Shell:

```bash
chmod +x find_sh.sh
./find_sh.sh
```
