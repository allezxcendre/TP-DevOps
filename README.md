1 - Dans un premier temps, veuillez cloner le projet sur votre machine :
```
git clone https://github.com/allezxcendre/TP-DevOps/new/main?filename=README.md
```
2 - ensuite, installer les dépendances du projet :
```
npm install 
```
3 - Si vous voulez configurer un port en particulier, faites la commande suivante pour modifier la variable d'environnement, sinon laissez tel quel et le port 3000 sera utilisé:
```
$env:PING_LISTEN_PORT=5555
```
Sinon laissez tel quel et le port 3000 sera utilisé.

4 - Pour finir, lancer la page web avec la commande suivante : 
```
node dist/app.js
```
Cliquer sur le lien affiché dans le terminal pour accéder à la page web, c'est fini !
Vous pouvez bien sûr accéder à la page /ping de la page web.
