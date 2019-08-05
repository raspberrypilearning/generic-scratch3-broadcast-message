Un envoyer à tous est une façon d'envoyer un message depuis un sprite et qui peut être reçu par tout les sprites. Pense à cela comme à une annonce faite par haut-parleur.

### Envoyer un message à tous

Tu peux faire un envoi à tous en créant un bloc envoyer à tous et en lui attribuant un nom:

+ Cherche le bloc **envoyer à tous** dans **Évènements**

+ Sélectionne **Nouveau message** dans le menu déroulant.

![menu déroulant du bloc envoi à tous](images/broadcast-block.png)

+ Puis entre ton message

![Créer un envoi à tous](images/new-broadcast.png)

Le texte du message peut être ce que tu veux, mais il est utile de donner à l'envoi à tous une description sensée. Ce qui se passe quand le message est reçu dépend du code que tu as écrit.

### Recevoir un envoi à tous

Un sprite peut réagir à un envoi à tous en utilisant ce bloc:

![Recevoir un envoi à tous](images/receive-a-broadcast.png)

Tu peux ajouter des blocs en dessous de celui-ci pour indiquer au sprite ce qu'il doit faire lorsqu'il reçoit un message envoi à tous.

![Recevoir un exemple](images/receive-example.png)