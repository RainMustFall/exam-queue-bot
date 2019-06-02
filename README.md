# ExamQueueBot

Ну это... Telegram-бот, который сам будет генерить в нашем чатике очередь на экзамены/зачёты и так далее, чтобы препятствовать дискриминации по первой букве фамилии.

## Зачем я вообще это делаю?

Потому что очень часто приходится забивать куда-то очередь, и ужасно бесит та ситуация, когда все начинают это делать, а тебя в этот момент нет поблизости или ты медленно среагировал и оказался в конце. Или если все решают идти в алфавитном порядке, и ты всегда в самом конце/начале/другом неудобном месте.
Рандом на страже справедливости!

## Как этим пользоваться?

Запускаешь моего монстра (@exam_queue_bot) в чатик группы и развлекаешься.

### Добавить список группы:
```
/setlist
Имя1
Имя2
...
ИмяN
```
### Сгенерировать новую очередь:
```/generate```

### Показать последнюю сгенерированную очередь:
```/show```

### Поменять двух человек местами:
```/swap 1 2```

```/swap Петров Иванов```

```/swap 1 Иванов```

```/swap Петров 2```

и так далее

### Сдвинуть чувака на новую позицию:
```/move 1 2```

```/move Петров Иванов```

```/move 1 Иванов```

```/move Петров 2```