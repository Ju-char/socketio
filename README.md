# Challenge : Chat en NodeJS

Du front, du front, du front.  
En vanilla, avec React, avec Redux, avec React-Redux… :scream:

On fait une pause, et on fait un peu de back :yum:

---

Le but du jeu, c'est de **créer une chatroom** avec NodeJS et Socket.io.

Le back est propulsé par NodeJS, à l'aide d'[Express](http://expressjs.com/)
pour le serveur web, et [Socket.io](https://socket.io/) pour le websocket.

## Instructions

Le site de présentation de [Socket.io](https://socket.io/) contient un tutorial pour découvrir
pas à pas comment mettre en place un tel serveur, ainsi que le bout de front-end
nécessaire pour tester l'application.

Ça se passe par ici : https://socket.io/get-started/chat/

## Conseils

### Nodemon

Le tutorial vous fait utiliser la commande `node monFicher.js` pour lancer
votre serveur. Contrairement à PHP, il faudra redémarrer le serveur à chaque
fois que le fichier change. Pour un site en production, ce n'est pas genant.
Pour le développement en revanche, c'est casse pied d'aller killer le serveur
(`Ctrl + C`) et de le relancer à chaque fois.

Il existe donc [`nodemon`](https://github.com/remy/nodemon),
qui permet de faire un "démon" (watch) : chaque fois que vous sauvegardez
votre fichier, il coupe et relance le serveur :smiley:

Pour l'installer :
```
sudo npm install -g nodemon
```

Il suffira alors de lancer `nodemon monFicher.js` pour lancer votre serveur.

### ES2015

N'essayez pas d'utiliser d'ES2015 ou d'utiliser le modèle pour compiler votre
code NodeJS. Non pas que ne soit pas possible, mais c'est pas si simple :)

Bref, un peu d'ES5 ne fait jamais de mal !
