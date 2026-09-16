
---

# Exercice 11 — Implémenter strlen

## Objectif
Compter le nombre de caractères dans une chaîne terminée par `0` (null terminator).

## Fichiers
- `ex11.asm` : code source NASM.

## Compilation
- `nasm -f elf64 ex11.asm -o ex11.o`
- `gcc ex11.o -o ex11`

## Exécution
- `./ex11`

## Output
Longueur: 5
(par exemple pour "Hello").