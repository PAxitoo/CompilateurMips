# Projet : Compilateur en OCaml vers du MIPS

## Utilisation
### Compilation
```bash
$ make
```

### Utilisation
```bash
$ ./main.byte {fichier source} > sortie.s
```
Une fois le fichier assembleur créé, il est possible d'utiliser spim : 
```bash
$ spim -file sortie.s
```

## Tests
Pour lancer les tests, exécutez la commande suivante :
```bash
$ make test
Certains tests doivent passer, certains non : cf. le contenu des tests.

## Fonctionnalités
- Type int
- Type bool
- Type string
- Déclaration / assignation de variables
- Librairie standard (multiplication, addition, comparateur, print, ...)
- Conditions
- Boucles
- Fonctions utilisateurs récursives (arguments et valeur de retour typé)

## Améliorations
- Les fonctions de la baselib sont inlinées

## Problèmes connus
- Pas de parenthèses pour les calculs
