# exobot
**ExoBot** est une application clé en main pour les développeurs de Bots Discord. Le projet est écrit entièrement en Javascript, documenté et commenté en français. Il est fournit avec des commandes de bases et un exemple permettant d'en ajouter de nouvelles.
Il utilise le module [discord.io](https://github.com/izy521/discord.io).

**NodeJS est obligatoire pour que le Bot puisse fonctionner.**

Documentation disponible :
 - [Installation](https://github.com/ewauq/exobot/wiki/Installation)
 - [Les commandes (ajout, suppression...)](https://github.com/ewauq/exobot/wiki/Commandes)
 - [Les fonctions](https://github.com/ewauq/exobot/wiki/Fonctions)
 - [Les formats de réponses](https://github.com/ewauq/exobot/wiki/Formats-de-r%C3%A9ponses)
 - [Documentation de Discord.io](https://izy521.gitbooks.io/discord-io/content/)

### Où héberger le Bot ?

Libre à vous de choisir la méthode d'hébergement qui vous convient le mieux. Il existe de nombreux fournisseurs d'hébergements de serveurs NodeJS sur internet. Vous pouvez également l'héberger sur votre machine personnelle ou encore sur un Raspberry Pi.

### Comment ajouter des commandes ?

Un fichier `example.js` est disponible dans le répertoire `commands`. Il constitue une bonne base pour le développement d'une commande simple impliquant un message de retour de la part du Bot.

Vous trouverez une [documentation](https://github.com/ewauq/exobot/wiki/Commandes) complète sur l'ajout et le fonctionnement des commandes.

### Mises à jour

**Attention !** L'application ne sera pas ou peu mise à jour, pour une raison évidente : **il est difficilement possible de maintenir à jour des fichiers qui peuvent être modifiés sans écraser votre propre code.** Ce projet reste avant tout une base de développement pour la création de Bots. Il n'a pas vocation à évoluer dans le temps.

Si toutefois vous souhaitez quand même mettre à jour Exobot, prenez soin de bien identifier les morceaux de code à conserver et à réintégrer à l'application après la mise à jour.
