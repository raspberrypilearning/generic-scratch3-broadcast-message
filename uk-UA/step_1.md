`Оповіщення`{:class="block3events"} — це спосіб передачі повідомлення, яке можуть почути всі спрайти. Уяви, що це оголошення через гучномовець.

**Чарівні оповіщення**: Натискай на кнопки чарівною паличкою та вимовляй заклинання. Що кожне заклинання робить із персонажами? [Переглянути код](https://scratch.mit.edu/projects/752264639/editor){:target="_blank"}

<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/752264639/?autostart=false" frameborder="0"></iframe>
</div>

Ти можеш створити повідомлення, яке `оповістить`{:class="block3events"} спрайти. Текст повідомлення може бути будь-яким, але бажано дати йому зрозумілий опис.

+ Знайди блок `оповістити`{:class="block3events"} у меню блоків `Події`{:class="block3events"}

+ Вибери **Нове повідомлення** у спадному меню.

![Спадне меню блоку оповіщення](images/broadcast-block.png)

+ Введи своє повідомлення

![Створення оповіщення](images/new-broadcast.png)

### Відправлення оповіщень

Ти можеш вирішити, коли `оповіщувати`{:class="block3events"} своїм повідомленням. Наприклад:

```blocks3
when this sprite clicked
broadcast (зменшувати v)
```

```blocks3
when backdrop switches to [рівень 1 v]
broadcast (старт v)
```

### Отримання оповіщень

Спрайт може відреагувати на `оповіщення`{:class="block3events"} за допомогою блока `коли я отримую`{:class="block3events"}. Декілька спрайтів можуть відреагувати на одне і те ж повідомлення.

Ти можеш додавати інші блоки під блоком `коли я отримую`{:class="block3events"}, щоб сказати спрайту, що він має робити при отриманні повідомлення.

```blocks3
when I receive [зменшувати v]
change size by [-10] // негативні числа зменшують розмір
```

```blocks3
when I receive [старт v]
go to x: (100) y: (50)
show
```
