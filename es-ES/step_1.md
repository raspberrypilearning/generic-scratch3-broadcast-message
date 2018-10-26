A broadcast is a way of sending a message from a sprite which can be heard by all sprites. Think of it like an announcement made over a loudspeaker.

### Enviar una transmisión

Puedes enviar una transmisión creando un bloque de envío y dándole un nombre:

+ Find the **broadcast** block under **Events**

+ Select **New Message** in the drop-down menu.

![broadcast block dropdown](images/broadcast-block.png)

+ Then type your message

![Crear una transmisión](images/new-broadcast.png)

The message text can be anything you like, but it is useful to give the broadcast a sensible description. What happens when the message is received depends on the code you write.

### Recibir una transmisión

Un objeto puede reaccionar a una transmisión usando este bloque:

![Recibir una transmisión](images/receive-a-broadcast.png)

Puedes agregar bloques debajo de este bloque para decirle al objeto qué hacer cuando recibe el mensaje enviado.

![Ejemplo de recepción](images/receive-example.png)