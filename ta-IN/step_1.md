A `broadcast`{:class="block3events"} is a way of sending a message which can be heard by all sprites. ஓர் ஒலிபெருக்கி மூலம் வெளியிடப்பட்ட ஓர் அறிவிப்பைப் போல நினைத்துப் பாருங்கள்.

**Broadcasting spells**: Use the magic wand to click on the buttons and cast spells. What does each spell do to the characters? [See inside](https://scratch.mit.edu/projects/518413238/editor){:target="_blank"}

<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/518413238/?autostart=false" frameborder="0"></iframe>
</div>

You can create a message to be `broadcast`{:class="block3events"}. The message text can be anything you like, but it is useful to give it a sensible description.

+ Find the `broadcast`{:class="block3events"} block under `Events`{:class="block3events"}

+ கீழ்விரி பட்டியில் (drop-down menu) உள்ள **New Message** -ஐத்(புதிய செய்தி) தேர்ந்தெடுக்கவும்.

![broadcast block dropdown](images/broadcast-block.png)

+ பின்னர், உங்கள் செய்தியைத் தட்டச்சு செய்க

![Create a broadcast](images/new-broadcast.png)

### ஓர் ஒலிபரப்பை அனுப்பவும்

You can decide when to `broadcast`{:class="block3events"} your message. For example:

```blocks3
when this sprite clicked
broadcast (shrink v)
```

```blocks3
when backdrop switches to [level 1 v]
broadcast (start v)
```

### ஓர் ஒலிபரப்பைப் பெறுக

Sprite can react to a `broadcast`{:class="block3events"} by using a `when I receive`{:class="block3events"} block. Multiple sprites can respond when they receive the same message.

You can add blocks below a `when I receive`{:class="block3events"} block to tell the sprite(s) what to do when they receives the message.

```blocks3
when I receive [shrink v]
change size by [-10] // negative numbers decrease the size
```

```blocks3
when I receive [start v]
go to x: (100) y: (50)
show
```