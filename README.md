# A propos
Projet 9 - Débuggez et testez un SaaS RH
- Billed, une entreprise qui produit des solutions Saas destinées aux équipes de ressources humaines.

### Objectif
Lancer officiellement la feature team "note de frais", fiabiliset et améliorer le parcours employé.

### Contraintes techniques
- [Respect des fonctionnalité](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P7+Tests/Billed+-+Description+des+fonctionnalite%CC%81s.pdf)
- [Completer et tester le code](https://github.com/OpenClassrooms-Student-Center/Billed-app-FR)
- Code Robuste / Lisible
- Validation W3C sans erreur

## Bug - Test
[Bug - report] - Fixer les bugs identifiés dans le rapport de bug fourni par Jest. J’en ai mis une copie dans le [kanban Notion](https://www.notion.so/openclassrooms/a7a612fc166747e78d95aa38106a55ec?v=2a8d3553379c4366b6f66490ab8f0b90). 

[Bug - hunt] - Fixer les bugs identifiés par Leila notre QA sur le parcours employé. Ils sont décrits dans le kanban également.

[Tests unitaires et d’intégration]
Ajouter des tests unitaires et d’intégration pour les fichiers Bills et NewBill : ces tests vont permettre d’éliminer ces bugs et éviter toute régression lors des prochaines évolutions de la solution. Certains tests sont déjà développés (pour le Login, et pour le Dashboard des administrateurs RH) : ils sont déjà cochés sur le kanban, tu peux t'en inspirer pour les restants. Comme la démo est seulement dans une semaine, nous n’avons pas le droit à l’erreur. Pour cette raison, il faut que tu assures une couverture de branche de 100 % (en dehors des appels au back-end firebase : ces derniers sont indiqués en commentaire dans le code). Tu peux t’appuyer sur le rapport de couverture de Jest (lance l’application avec live-server pour pouvoir le lire et va à l’adresse  http://127.0.0.1:8080/coverage/lcov-report/  : tout est indiqué dans le [readme](https://github.com/OpenClassrooms-Student-Center/P6-front-end-testing)).

[Test E2E]
Puisque l’on n’a pas le temps d’automatiser des tests End-to-End, les tests seront effectués manuellement par Leila. Il faut donc que tu lui fasses un plan de test End-to-End pour la guider. Tu peux t’inspirer du plan End-to-End que Garance a déjà rédigé sur le parcours administrateur RH.

### Technlogies
HTML, CSS (Sass, Bootstrap 4), Javascript

### Hébergement
[#Projet 9 - Feature team “note de frais”](https://google.fr)

## Run
npm install
live-server
npm run test
npm i -g jest-cli
jest src/__tests__/your_test_file.js
http://127.0.0.1:8080/coverage/lcov-report/


**Comment lancer l'application en local** :

Clonez le projet :
```
$ git clone https://github.com/OpenClassrooms-Student-Center/Billed-app-FR.git
```

Allez au repo cloné :
```
$ cd Billed-app-FR
```

Installez les packages npm (décrits dans `package.json`) :
```
$ npm install
```

Installez live-server pour lancer un serveur local :
```
$ npm install -g live-server
```

Lancez l'application :
```
$ live-server
```

Puis allez à l'adresse : `http://127.0.0.1:8080/`


**Comment lancer tous les tests en local avec Jest :**

```
$ npm run test
```

**Comment lancer un seul test :**

Installez jest-cli :

```
$npm i -g jest-cli
$jest src/__tests__/your_test_file.js
```

**Comment voir la couverture de test :**

`http://127.0.0.1:8080/coverage/lcov-report/`


