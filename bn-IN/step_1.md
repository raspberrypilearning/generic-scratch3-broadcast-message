A `broadcast`{:class="block3events"} is a way of sending a message which can be heard by all sprites. এটিকে কোনও লাউড স্পিকারের মাধ্যমে ঘোষণার মতো মনে করুন।.

**Broadcasting spells**: Use the magic wand to click on the buttons and cast spells. What does each spell do to the characters? [See inside](https://scratch.mit.edu/projects/518413238/editor){:target="_blank"}

<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/518413238/?autostart=false" frameborder="0"></iframe>
</div>

You can create a message to be `broadcast`{:class="block3events"}. The message text can be anything you like, but it is useful to give it a sensible description.

+ Find the `broadcast`{:class="block3events"} block under `Events`{:class="block3events"}

+ ড্রপ-ডাউন মেনুতে **New Message** সিলেক্ট।.

![broadcast block dropdown](images/broadcast-block.png)

+ আপনার বার্তা বা message টি টাইপ করুন

![Create a broadcast](images/new-broadcast.png)

### একটি সম্প্রচার বার্তা বা broadcast পাঠান

You can decide when to `broadcast`{:class="block3events"} your message. For example:

```blocks3
when this sprite clicked
broadcast (shrink v)
```

```blocks3
when backdrop switches to [level 1 v]
broadcast (start v)
```

### একটি সম্প্রচার বা broadcast গ্রহণ করুন

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