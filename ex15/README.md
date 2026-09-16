
---

# Exercice 15 — Appeler une fonction ASM depuis C

## Objectif
Écrire une fonction en assembleur NASM et l'appeler depuis un programme C, en respectant la convention d'appel System V.

## Fichiers
- `ex15.asm` : code source NASM.

## Compilation
- `nasm -f elf65 ex15.asm -o ex15.o`
- `gcc ex15.o -o ex15`

## Exécution
- `./ex15`

## Output
Affichage du résultat retourné par la fonction ASM (par exemple une opération sur un entier).