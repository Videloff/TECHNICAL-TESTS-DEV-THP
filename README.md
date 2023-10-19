
# TECHNICAL-TESTS-DEV-THP

<a href="https://www.thehackingproject.org/">
    <img src="https://www.thehackingproject.org/packs/media/images/logo/20210910-THP-Logo_color_transparent-7bcda2eebdfc9e089cfe84bda563a4e7.png" style="height:100px">
</a>
<br/>

Suite de questions techniques qui pourraient survenir lors d'entretiens d'embauches pour des postes comme développeur Front, Back ou même Fullstack.


## Catégorie Frontend :

### 1. HTML/CSS :

- Comment pouvez-vous optimiser les performances d'un site Web en termes de chargement des ressources ?
```
Utilisez la compression, la mise en cache, la réduction de la taille des images,
le chargement asynchrone des scripts, et minimisez les requêtes HTTP.
```
- Qu'est-ce que Flexbox et comment l'utilisez-vous pour la mise en page ?
```
Flexbox est un modèle de mise en page CSS qui simplifie le positionnement des
éléments en ligne ou en colonne.
Utilisez "display: flex" sur le conteneur pour créer une disposition flexible.
```
- Comment implémenteriez-vous un design responsive dans un site Web ?
```
Utilisez des requêtes media CSS (media queries) pour adapter la mise en page
en fonction de la taille de l'écran, et assurez-vous que les éléments
s'adaptent en utilisant des unités relatives comme %, em ou rem.
```

### 2. JavaScript :

- Quelle est la différence entre "undefined" et "null" en JavaScript ?
```
"undefined" signifie qu'une variable existe mais n'a pas de valeur définie,
tandis que "null" est une valeur délibérément affectée pour représenter
l'absence de valeur.
```

- Comment gérer les erreurs en JavaScript ?
```
Les erreurs JavaScript peuvent être gérées à l'aide de try...catch pour
intercepter et gérer les exceptions.
```

- Expliquez ce que sont les closures en JavaScript et pourquoi elles sont utiles.
```
Les closures sont des fonctions qui capturent des variables de leur portée
environnante, permettant de créer des environnements privés et de maintenir
des données à l'intérieur d'une fonction.
```

- Pouvez-vous expliquer l'utilisation de "Promises" et "Async/Await" en JavaScript ?
```
Les Promises sont des objets permettant de gérer des opérations asynchrones.
"Async/Await" est une syntaxe qui simplifie la gestion des Promises en
rendant le code asynchrone plus lisible.
```

### 3. React :

- Qu'est-ce que Redux et quand devriez-vous l'utiliser avec React ?
```
Redux est un gestionnaire d'état pour React, utile lorsque l'état doit être
partagé entre plusieurs composants.
```

- Expliquez ce que sont les "refs" dans React.
```
Les "refs" sont utilisés pour accéder directement aux éléments du DOM
ou aux composants React et sont généralement évités, sauf en cas de nécessité.
```

- Qu'est-ce que le cycle de vie d'un composant dans React et quelles sont ses phases ?
```
Le cycle de vie d'un composant dans React représente les différentes phases de vie
d'un composant React, de sa création à sa suppression.
Ses phases sont le montage, la mise à jour et le démontage.
```
## Catégorie Backend :

### 1. Ruby/Ruby on Rails :

- Expliquez la différence entre Ruby et Ruby on Rails.
```
Ruby est un langage de programmation, tandis que Ruby on Rails est un framework
pour le développement web basé sur Ruby.
```

- Comment gérer les dépendances et les packages dans Ruby on Rails ? Comment sont appelés les packages de Ruby ?
```
Ruby on Rails utilise Bundler pour gérer les dépendances et les packages.
Les packages en Ruby sont les Gems.
```

- Expliquez l'utilisation de "migrations" dans Ruby on Rails.
```
Les migrations sont des scripts Ruby on Rails permettant de gérer la structure
de la base de données.
Elles permettent de créer, ajouter, éditer ou supprimer des classes ou des attributs
de classe.
```
- Pouvez-vous expliquer l'utilisation des "before_action" dans Ruby on Rails et dans quelle mesure est-ce intéressant ?
```
le "before_action" est utilisé pour exécuter du code avant certaines actions de contrôleur.
Il permet de sécuriser des éléments dans les controllers et donc l'application.
```

### 3. Git :

- Expliquez la différence entre "git merge" et "git rebase".
```
"git merge" fusionne une branche dans une autre avec un nouveau commit, tandis que
"git rebase" récrit l'historique du commit pour sembler linéaire.
```
- Comment annuler le dernier commit dans Git sans perdre les modifications ?
```
Utilisez "git reset HEAD~1" suivi de "git stash" pour annuler le dernier commit sans perdre
les modifications.
```

- Quelle est la différence entre "git fetch" et "git pull" ?
```
"git fetch" récupère les modifications distantes sans les fusionner au local, tandis que
"git pull" les fusionne automatiquement.
```

- Comment créer et fusionner des branches dans Git ?
```
 Utilisez "git branch" pour créer des branches et "git merge" pour les fusionner.
```

- Comment résoudre un conflit de fusion (merge conflict) dans Git ? Est-ce possible de le faire automatiquement ?
```
Éditez manuellement les fichiers en conflit, ajoutez-les avec "git add," puis utilisez
"git commit" pour terminer la fusion.
Non, un édition manuelle est nescessaire.
```
