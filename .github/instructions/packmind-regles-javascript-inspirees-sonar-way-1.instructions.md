---
applyTo: '**/*.ts, **/*.js, **/*.tsx, **/*.jsx'
---
## Standard: Règles JavaScript inspirées Sonar Way

Define JavaScript coding rules inspired by Sonar Way for ES5/ES6+ in Packmind to improve readability, security, robustness, clarity, and maintainability. :
* Documenter les fonctions publiques avec des commentaires JSDoc.
* Éviter les fonctions anonymes dans les callbacks complexes.
* Éviter les fonctions avec plus de 4 paramètres.
* Limiter la profondeur d’imbrication à 3 niveaux maximum.
* Ne jamais laisser de console.log() dans le code de production.
* Ne jamais utiliser 'eval()'.
* Ne pas utiliser de variables globales non intentionnelles.
* Nommer les variables et fonctions en anglais, en camelCase.
* Toujours gérer les erreurs dans les blocs try/catch.
* Toujours initialiser les variables lors de leur déclaration.
* Toujours utiliser des accolades pour les blocs if, else, for, while.
* Toujours utiliser l’opérateur d’égalité stricte '===' au lieu de '=='.
* Un module ne doit jamais s'importer lui-même.
* Utiliser '===' pour comparer à null ou undefined.
* Utiliser 'const' ou 'let' au lieu de 'var' pour déclarer des variables.
* Utiliser des fonctions fléchées pour les callbacks simples.

Full standard is available here for further request: [Règles JavaScript inspirées Sonar Way](../../.packmind/standards/regles-javascript-inspirees-sonar-way-1.md)