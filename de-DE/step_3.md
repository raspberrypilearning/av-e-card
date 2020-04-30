## Füge dein GIF zu Scratch hinzu und animiere es

--- task ---

Navigiere zu [rpf.io/scratch-new](https://rpf.io/scratch-new), um ein neues Scratch-Projekt zu öffnen.

--- /task ---

--- task ---

Klicke auf das **Papierkorb**-Symbol, um die aktuelle Katzenfigur zu löschen.

![image showing cat sprite with trashcan icon](images/delete-sprite.png)

--- /task ---

--- task ---

Bewege den Mauszeiger nun über die **Wähle ein Figur** Schaltfläche und klicke dann auf **Figur hochladen**, um eine neue Figur hochzuladen.

![image showing the choose a sprite menu option with upload a sprite selected](images/upload-sprite.png)

--- /task ---

--- task ---

Wähle dein GIF im Dateibrowser aus und lade es hoch.

![image showing selection of GIF in the file browser](images/select-gif.png)

--- /task ---

--- task ---

Klicke auf den Reiter **Kostüme** für deine neue Figur und du solltest alle einzelnen Frames in deinem GIF sehen.

![image showing the GIF converted into individual costumes within Scratch](images/gif-costumes.png)

Notiere dir die Gesamtzahl der Kostüme, die du hast, da dies bei der nächsten Aufgabe wichtig sein wird.

--- /task ---

--- task ---

Um das GIF durchzuspielen, kannst du einen `wiederhole`{:class="block3control"} Block in einem `wiederhole fortlaufend`{:class="block3control"} Block verwenden. Der `wiederhole`{:class="block3control"} - Block sollte mit der Anzahl der Frames aus dem importierten GIF übereinstimmen.

```blocks3
wenn die Flagge angeklickt wird
fortlaufend
wiederhole (35)
nächstes Kostüm
```
--- /task ---

--- task ---

Deine Animation ist möglicherweise etwas schnell, füge also einen `warte`{:class="block3control"} Block hinzu, um es etwas zu verlangsamen.


```blocks3
when flag clicked
forever
repeat (35)
+wait (0.04) seconds
next costume
```

--- /task ---

--- task ---

Du kannst die Animation auch vergrößern und in der Mitte der Bühne neu positionieren.

```blocks3
when flag clicked
+set size to (150) %
forever
repeat (35)
next costume
```

--- /task ---

--- task ---

Es ist auch hilfreich sicherzustellen, dass du die Animation immer vom ersten Kostüm an abspielst.

```blocks3
when flag clicked
+switch costume to (ezgif v)
set size to (150) %
forever
repeat (35)
next costume
```

--- /task ---


--- task ---

Click the green flag to watch your video being played on the Stage.

--- /task ---





