# NASM x86_64 Learning Journey

## Objectif du dépôt

Ce dépôt regroupe une série de 15 mini-exercices en assembleur NASM x86_64 sous Linux.

L'objectif est de documenter et suivre la progression d'apprentissage de l'assembleur, en partant de bases simples (syscalls, boucles, registres) jusqu'à des concepts plus avancés (manipulation de tableaux, fonctions type `strlen`, `atoi`, et appel d'une fonction ASM depuis un programme C).

Chaque exercice est conçu pour être court, ciblé et facilement testable.

## Structure du dépôt

```text
nasm-learning/
│
├── README.md                        # README général (ce fichier)
│
├── General/
│   ├── nasm_journey.tex              
│   └── nasm_journey.pdf             # Document LaTeX décrivant les 15 exercices
│
├── ex01_hello/
│   ├── ex01.asm
│   └── README.md
│
├── ex02_exitcode/
│   ├── ex02.asm
│   └── README.md
│
├── ex03_printf/
│   ├── ex03.asm
│   └── README.md
│
├── ex04_scanf/
│   ├── ex04.asm
│   └── README.md
│
├── ex05_add/
│   ├── ex05.asm
│   └── README.md
│
├── ex06_compare/
│   ├── ex06.asm
│   └── README.md
│
├── ex07_loop/
│   ├── ex07.asm
│   └── README.md
│
├── ex08_while/
│   ├── ex08.asm
│   └── README.md
│
├── ex09_array/
│   ├── ex09.asm
│   └── README.md
│
├── ex10_max/
│   ├── ex10.asm
│   └── README.md
│
├── ex11_strlen/
│   ├── ex11.asm
│   └── README.md
│
├── ex12_strcpy/
│   ├── ex12.asm
│   └── README.md
│
├── ex13_atoi/
│   ├── ex13.asm
│   └── README.md
│
├── ex14_calc/
│   ├── ex14.asm
│   └── README.md
│
└── ex15_from_c/
    ├── ex15.asm
    ├── main.c
    └── README.md
