Eine `Broadcast`{:class="block3events"} (to broadcast = senden/übertragen) ist eine Möglichkeit, eine Nachricht zu senden, die von allen Sprites gehört werden kann. Stelle es dir wie eine Ansage über einen Lautsprecher vor.

**Zaubern**: Klicke mit dem Zauberstab auf die Schaltflächen und zaubere. Was macht jeder Zauber mit den Charakteren? [Siehe das Programm an](https://scratch.mit.edu/projects/518413238/editor){:target="_blank"}

<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/518413238/?autostart=false" frameborder="0"></iframe>
</div>

Du kannst eine Nachricht erstellen, die du `senden`{:class="block3events"} möchtest. Dein Nachrichtentext kann beliebig sein. Es hat sich jedoch als nützlich erwiesen, der Nachricht eine sinnvolle Beschreibung zu geben.

+ Finde den **sende** Block unter **Ereignisse**

+ Wähle **Neue Nachricht** in der Auswahlbox aus.

![Auswahlbox des Senden Blocks](images/broadcast-block.png)

+ Gebe dann deine Nachricht ein

![Erstelle eine Nachricht](images/new-broadcast.png)

### Eine Nachricht an alle senden

Du kannst entscheiden, wann du deine Nachricht `senden`{:class="block3events"} möchtest. Zum Beispiel:

```blocks3
when this sprite clicked
broadcast (shrink v)
```

```blocks3
when backdrop switches to [level 1 v]
broadcast (start v)
```

### Empfangen einer Sendung

Ein Sprite kann auf eine `-Nachricht`{:class="block3events"} reagieren, indem du einen `-Wenn ich <eine Nachricht> empfange`{:class="block3events"}-Block verwendest. Mehrere Sprites können reagieren, wenn sie dieselbe Nachricht erhalten.

Du kannst Blöcke unterhalb des `wenn ich empfange`{:class="block3events"}-Blocks hinzufügen, um der Figur (oder mehreren) mitzuteilen, was zu tun ist, wenn sie die Nachricht empfängt.

```blocks3
when I receive [shrink v]
change size by [-10] // negative numbers decrease the size
```

```blocks3
when I receive [start v]
go to x: (100) y: (50)
show
```