## Dodaj trochę dźwięku

--- task ---

Kliknij zakładkę **Dźwięki** twojego duszka.

![image showing sounds tabs selected for the sprite](images/sounds-tab.png)

--- /task ---

--- task ---

W lewym dolnym rogu ekranu najedź kursorem na **Wybierz dźwięk** i wybierz opcję **Nagraj** aby nagrać nowy dźwięk.

![image showing sounds button selected with record a sound highlighted](images/record-sound.png)

--- /task ---

--- task ---

Może być konieczne zezwolenie przeglądarce na dostęp do mikrofonu. Aby to zrobić, kliknij **Udostępnij**.

![image showing web browser prompt to enable access to microphone](images/allow-mic.png)

--- /task ---

--- task ---

Kliknij przycisk**Nagraj**, aby rozpocząć nagrywanie twojego głosu. Kiedy skończysz swoją wiadomość dla adresata twojej e-pocztówki, kliknij **Zatrzymaj nagrywanie**, a później kliknij **Zapisz**.

![image showing the record dialogue box within Scratch](images/record.png)

--- /task ---

--- task ---

Aby odtworzyć dźwięk, możesz użyć blok `nadaj komunikat`{:class="block3control"} podczas uruchamiania pętli animacji.

```blocks3
when flag clicked
switch costume to (ezgif v)
set size to (150) %
forever
+broadcast (message1 v)
repeat (35)
next costume
```

--- /task ---

--- task ---

Then, use a `when I receive`{:class="block3control"} block to start playing the sound.

```blocks3
when I receive (message1 v)
play sound (recording1 v) until done
```

--- /task ---

--- task ---

You might like to use a `wait`{:class="block3control"} block to control when the sound starts being played.

```blocks3
when I receive (message1 v)
+wait (0.4) seconds
play sound (recording1 v) until done
```

--- /task ---



