title: Bash command line movement and deletion shortcuts
tags: unix,bash

If you have typed in

```
Man I was mean, but I'm changing my scene
```

And then press `alt shift b` (the shift may not be needed) twice the cursor will go back to the `m` of `my`. 

(`alt shift f` moves in the opposite direction, incidentally)

Press `alt shift d` it will delete the word `my`. Press it again and it will then delete `scene`.

Press `ctl d` and you will delete not the word but a single character under the cursor.

Press `ctl k` and you will delete everything after the position. `ctl u` everything before.

Press `ctl _` and you will undo your command line edits.
