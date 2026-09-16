
---

# Exercice 02 — Exit code personnalisé

## Objectif
Terminer le programme avec un code de sortie spécifique en utilisant le syscall `exit`.

## Fichiers
- `ex02.asm` : code source NASM.

## Compilation
- `nasm -f elf64 ex02.asm -o ex02.o`
- `ld ex02.o -o ex02`

## Exécution
- `./ex02`
- `echo $?`

## Output
Le code de sortie affiché par `echo $?` doit correspondre à la valeur choisie dans le registre rdi.