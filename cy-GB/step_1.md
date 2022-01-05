Mae `darlledu`{:class="block3events"} yn ffordd o anfon neges y gall pob corlun ei chlywed. Meddylia amdano fel cyhoeddiad dros uchelseinydd.

**Darlledu swynion**: Defnyddia'r wialen hud i glicio ar y botymau a bwrw swynion. Beth mae pob swyn yn ei wneud i'r cymeriadau? [Gweld tu mewn](https://scratch.mit.edu/projects/518413238/editor){:target="_blank"}

<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/518413238/?autostart=false" frameborder="0"></iframe>
</div>

Galli di greu neges i'w `darlledu`{:class="block3events"}. Gall y testun fod yn unrhywbeth yr hoffet ti, ond mae'n ddefnyddiol i roi disgrifiad synhwyrol iddo.

+ Tyrd o hyd i'r bloc **darlledu** yn yr adran **Digwyddiadau**

+ Dewisa **Neges Newydd** yn y gwymplen.

![cwymplen bloc darlledu](images/broadcast-block.png)

+ Yna teipia dy neges

![Creu darllediad](images/new-broadcast.png)

### Anfon darllediad

Wedyn galli di benderfynu pryd i `ddarlledu`{:class="block3events"} dy neges. Er enghraifft:

```blocks3
when this sprite clicked
broadcast (crebachu v)
```

```blocks3
when backdrop switches to [level 1 v]
broadcast (dechrau v)
```

### Derbyn darllediad

Gall corlun ymateb i `ddarlledu`{:class="block3events"} drwy ddefnyddio bloc `pan rwy'n derbyn`{:class="block3events"}. Gall sawl corlun ymateb pan fyddan nhw'n derbyn yr un neges.

Gelli di ychwanegu blociau o dan y bloc hwn i ddweud wrth y corlun beth i'w wneud pan fydd yn derbyn y darllediad.

```blocks3
when I receive [shrink v]
change size by [-10] // mae niferoedd negyddol yn lleihau'r maint
```

```blocks3
when I receive [dechrau v]
go to x: (100) y: (50)
show
```