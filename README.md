# Lista doblemente ligada: FIFO y LIFO

Dos programas en C que implementan una lista ligada con nodos
centinela, usada para manejar registros de personas (nombre, edad,
dirección, estado civil, país de residencia y comida favorita).

- `fifo.c`: la lista se comporta como una cola (el primero que entra
  es el primero que sale).
- `lifo.c`: la lista se comporta como una pila (el último que entra
  es el primero que sale).

## Cómo compilar

```bash
gcc -Wall -o fifo fifo.c
gcc -Wall -o lifo lifo.c
```

## Cómo ejecutar

```bash
./fifo
./lifo
```

Cada programa carga 3 registros de ejemplo, muestra la lista completa
y luego va sacando los registros uno por uno mostrando el orden en
que salen (FIFO o LIFO, según el programa).
