En hændelse er en måde, at sende en besked fra en sprite, som kan høres af alle sprites. Tænk på det som en meddelelse over en højttaler.

### Send en meddelelse

Du kan sende en meddelelse ved at oprette en send-blok og give den et navn:

+ Find the **broadcast** block under **Events**

+ Vælg ** Ny besked ** i rullemenuen.

![broadcast block dropdown](images/broadcast-block.png)

+ Then type your message

![Opret en meddelelse](images/new-broadcast.png)

Meddelelsesteksten kan være nøjagtig det, du synes, men det er nyttigt at give hændelsen en fornuftig beskrivelse. What happens when the message is received depends on the code you write.

### Modtag en meddelelse

En sprite kan reagere på en meddelelse ved at bruge denne blok:

![Modtag en meddelelse](images/receive-a-broadcast.png)

Du kan tilføje blokke under denne blok for at fortælle spriten, hvad den skal gøre, når den modtager meddelelsen.

![Modtag eksempel](images/receive-example.png)