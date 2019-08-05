Un envoyer à tous est une façon d'envoyer un message depuis un sprite et qui peut être reçu par tout les sprites. Pense à cela comme à une annonce faite par haut-parleur.

### Envoyer un envoyer à tous

Tu peux faire un envoyer à tous en créant un bloc envoyer à tous et en lui attribuant un nom:

+ Cherche le bloc **envoyer à tous** dans **Évènements**

+ Sélectionne **Nouveau message** dans le menu déroulant.

![menu déroulant du bloc envoyer à tous](images/broadcast-block.png)

+ Puis entre ton message

![Créer un envoyer à tous](images/new-broadcast.png)

Le texte du message peut être ce que tu veux, mais il est utile de donner à l'envoyer à tous une description sensée. Ce qui se passe quand le message est reçu dépend du code que tu as écrit.

### Recevoir un envoyer à tous

Un sprite peut réagir à un envoyer à tous en utilisant ce bloc:

![Recevoir un envoyer à tous](images/receive-a-broadcast.png)

Tu peux ajouter des blocs en dessous de celui-ci pour indiquer au sprite ce qu'il doit faire lorsqu'il reçoit un message envoyer à tous.

![Recevoir un exemple](images/receive-example.png)