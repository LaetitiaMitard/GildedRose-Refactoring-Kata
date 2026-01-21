# Règles JavaScript inspirées Sonar Way

Ce standard regroupe 16 règles de bonnes pratiques JavaScript, inspirées de Sonar Way, couvrant la lisibilité, la sécurité, la robustesse, la clarté et la maintenabilité du code. Les règles sont génériques, adaptées à ES5 et ES6+, et prêtes à être utilisées dans Packmind.

## Rules

* Utiliser 'const' ou 'let' au lieu de 'var' pour déclarer des variables.
* Toujours utiliser l’opérateur d’égalité stricte '===' au lieu de '=='.
* Nommer les variables et fonctions en anglais, en camelCase.
* Ne jamais laisser de console.log() dans le code de production.
* Toujours gérer les erreurs dans les blocs try/catch.
* Éviter les fonctions avec plus de 4 paramètres.
* Toujours initialiser les variables lors de leur déclaration.
* Utiliser des fonctions fléchées pour les callbacks simples.
* Ne pas utiliser de variables globales non intentionnelles.
* Toujours utiliser des accolades pour les blocs if, else, for, while.
* Éviter les fonctions anonymes dans les callbacks complexes.
* Ne jamais utiliser 'eval()'.
* Documenter les fonctions publiques avec des commentaires JSDoc.
* Utiliser '===' pour comparer à null ou undefined.
* Limiter la profondeur d’imbrication à 3 niveaux maximum.
* Un module ne doit jamais s'importer lui-même.
