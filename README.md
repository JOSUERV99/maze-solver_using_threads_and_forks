# maze-solver_using_threads_and_forks
A maze solver that reads a maze from a text file, using a walker that finds the target using threads and forks to look in other directions (called process mirroring) with C on Linux.

## project structure
```bash
.
├── Documentación
│   ├── Documentación-Proyecto1-Laberintos.pdf
│   └── Especificaciones-Laberinto.pdf
├── maze-threads-forks
│   ├── files
│   │   ├── maps
│   │   │   ├── lab1.txt
│   │   │   ├── lab2.txt
│   │   │   ├── lab3.txt
│   │   │   ├── prueba1.txt
│   │   │   ├── prueba2.txt
│   │   │   ├── prueba3.txt
│   │   │   └── prueba4.txt
│   │   └── solutions
│   │       ├── 1_map.txt
│   │       ├── 1_stats.txt
│   │       ├── 2_map.txt
│   │       ├── 2_stats.txt
│   │       └── count.txt
│   └── src
│       ├── loader
│       │   ├── loader.c
│       │   └── loader.h
│       ├── main.c
│       ├── Makefile
│       ├── memo
│       │   ├── memo.c
│       │   └── memo.h
│       ├── program
│       ├── solver
│       │   ├── solver.c
│       │   └── solver.h
│       ├── timer
│       │   ├── timer.c
│       │   └── timer.h
│       └── utils
│           ├── file_handler.c
│           ├── file_handler.h
│           ├── maze_utils.c
│           ├── maze_utils.h
│           ├── walker_utils.c
│           └── walker_utils.h
└── README.md
```

## execution
You need to compile the program using a C compiler thats works on linux (gcc) and have already installed make (to work with Makefile's)
``` bash
cd maze-threads-forks/src
make
```
to create an executable program and that's it
