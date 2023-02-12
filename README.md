# Mini-Quiz

<img src="https://rustacean.net/assets/rustacean-flat-happy.png" width="300px">

### Explication :
Réalisation d'un petit questionnaire en rust qui se lance d'une manière générique avec différents thèmes au choix.
Les questions proposées sont choisies de manière aléatoire par l'algorithme à l'aide des bibliothèques choisies.

### Bibliotheques Utilisées : 

- Rand : https://docs.rs/rand/latest/rand/
- Version-compare : https://docs.rs/version-compare/latest/version_compare/

### Commandes utiles : 

- Récupérer les différentes dépendances ainsi que build le projet : ```cargo build```
- Lancer le projet : ```cargo run```
- Lancer les test unitaires : ```cargo test```
     - 4 test réalisés et passés:
        - 2 sur des questions simples
        - 2 sur des questionnaires à 3 questions
- Generer la cargo doc à partir des commentaires dans le main : ```cargo doc```
