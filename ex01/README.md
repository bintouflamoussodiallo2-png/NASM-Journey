
---

# Exercice 01 — Hello World (syscall)

## Objectif
Afficher un message simple sur la sortie standard en utilisant le syscall `write`.

## Fichiers
- `ex01.asm` : code source NASM.

## Compilation
nasm -f elf64 ex01.asm -o ex01.o
ld ex01.o -o ex01

## Exécution
./ex01

## Output
Hello, world!
