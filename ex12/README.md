
---

# Exercice 12 — Implémenter strcpy

## Objectif
Copier une chaîne source vers une chaîne destination, caractère par caractère, jusqu'au `0` final.

## Fichiers
- `ex12.asm` : code source NASM.

## Compilation
- `nasm -f elf64 ex12.asm -o ex12.o`
- `gcc ex12.o -o ex12`

## Exécution
- `./ex12`

## Output
Affichage de la chaîne copiée (identique à la source).