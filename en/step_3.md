## Adding and animating your GIF in Scratch

--- task ---

Navigate to [rpf.io/scratch-new](rpf.io/scratch-new) to open a new Scratch project

--- /task ---

--- task ---

Click on the **trashcan** icon to remove the default Scratch Cat Sprite.

![image showing cat sprite with trashcan icon](images/delete-sprite.png)

--- /task ---

--- task ---

Now use the **Choose a Sprite** button to upload a new sprite.

![image showing the choose a sprite menu option with upload a sprite selected](images/upload-sprite.png)

--- /task ---

--- task ---

Select your GIF from the file browser and then upload it.

![image showing selection of GIF in the file browser](images/select-gif.png)

--- /task ---

--- task ---

Click on the **Costumes** tab for your new sprite and you should see all the individual frames for your GIF.

![image showing the GIF converted into individual costumes within Scratch](images/gif-costumes.png)

Make a note of the total number of costumes that you have, as this will be important in the next task.

--- /task ---

--- task ---

To play through the GIF, you can use a `repeat`{:class="block3control"} block, inside a `forever`{:class="block3control"} block. The `repeat`{:class="block3control"} block should match the number of frames from the imported GIF.

```blocks3
when flag clicked
forever
repeat (35)
next costume
```
--- /task ---

--- task ---

Your animation might be a little fast though, so add a `wait`{:class="block3control"} to slow it down a little.


```blocks3
when flag clicked
forever
repeat (35)
+wait (0.04) seconds
next costume
```

--- /task ---

--- task ---

You might also like to increase the size of the animation and reposition it to the centre of the stage.

```blocks3
when flag clicked
+set size to (150) %
forever
repeat (35)
next costume
```

--- /task ---

--- task ---

It's also helpful to make sure you always start playing the animation from the first costume.

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

Click the green flag to watch your video being displayed on the stage.

--- /task ---





