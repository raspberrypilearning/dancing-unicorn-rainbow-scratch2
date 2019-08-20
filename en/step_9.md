## Make a unicorn dance to your rainbow

In this step, you will program a unicorn in Scratch that dances to the rhythm of your rainbow. You will use a button to program your rainbow and dancing unicorn.

### Unicorn sprite

Choose one of the following options to create a unicorn sprite:

1. Use the Scratch unicorn sprite
1. Upload a unicorn image from somewhere else and use it as your sprite
1. Draw your own unicorn sprite in Scratch or another program (like the lovely green unicorn on the right).

Examples:

| (1) Scratch sprite:                          | (2) Upload your own:                         | (3) Draw your own:                           |
| :------------------------------------------: | :------------------------------------------: | :------------------------------------------: |
| ![Scratch Unicorn](images/scratchunicorn.png)| ![Web Unicorn](images/webunicorn.png)        | ![Draw Unicorn](images/drawunicorn.png)      |

+ If you picked option 1, click here:
[[[generic-scratch-sprite-from-library]]]

+ If you picked option 2 because you want to upload a unicorn image you found somewhere else, click below first to learn about image permissions, and then use the instructions in the second box to upload your file:
[[[images-permissions-to-use]]]

[[[generic-scratch-add-sprite-from-file]]]

+ If you're going with option 3, click below for instructions on how to draw your own unicorn in Scratch:
[[[generic-scratch-draw-sprite]]]

### Unicorn costumes

Your unicorn needs **costumes** to be able to dance. A costume is one of a set of appearances of a sprite, which means sprites can change their look by changing costumes. Therefore, you can use costumes to make a sprite look like it's moving whenever you want to create an animation.

Here, we will be creating a dancing unicorn animation, so each costume will represent a dance move of your unicorn.

+ Decide how many costumes you want your unicorn sprite to have for the dance, and edit your costumes accordingly.

Click for a reminder on how to add costumes in Scratch:
[[[generic-scratch-add-costume]]]

Click for a reminder on how to duplicate costumes in Scratch:
[[[generic-scratch-duplicate-costumes]]]

It is up to you how many costumes you want to add for your dancing unicorn. For this dancing green unicorn, we have used five costumes:

|   ![Dancing Unicorn Gif](images/dancingunicorn.gif)   |    ![Five Costumes](images/fivecostumes.png)   |

### Unicorn dance

To create your dancing animation, you need to program the unicorn to switch costumes.

+ Switch between the first two costumes to start the unicorn dance.

To switch from the first to the second costume use:
```blocks  
  switch costume to [costume 2 v]
```

Unicorns are generally good dancers, so make sure you time your unicorn's dance to the speed of your rainbow pattern. You can use the `wait`{:class="blockcontrol"} block to match the unicorn's wait time to your rainbow's wait time.
```blocks  
  wait (0.5) secs
  switch costume to [costume 2 v]
```

+ To create your dancing unicorn, switch between all costumes continuously. What kind of loop do you need to do this?

--- hints ---
--- hint ---

Use a forever loop:
```blocks
  forever
```

--- /hint ---
--- hint ---

Use this block to switch to the next costume each time you go through the loop:
```blocks
  next costume
```

--- /hint ---
--- hint ---

Your code should look like this:
```blocks
  forever
  wait (0.5) secs
  next costume
```

--- /hint ---
--- /hints ---
