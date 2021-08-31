## What goes up must come down

In your gravity simulator, the **Dot** sprite falls and lands. Dogs also like to jump, so create a second script to simulate a jump on Earth. 

--- task ---

Drag a `when space key pressed`{:class="block3events"} block to the Code area and create a new script.  Use an `if`{:class="block3control"} block and `touching color`{:class="block3sensing"} block to detect if the **Dot** sprite is on land. 

```blocks3
when [space v] key pressed 
if <touching color (#34B561) ?> then
```

--- /task ---

--- task ---

Inside the `if`{:class="block3control"} block, add a `set y to`{:class="block3motion"} block and a `set velocity to`{:class="block3variables"} block. The `set y to`{:class="block3motion"} block will have the current `y`{:class="block3motion"} value of the **Dot** sprite.


```blocks3
when [space v] key pressed 
if <touching color (#34B561) ?> then
+ set y to (-56) 
+ set [velocity v] to (10)

```

--- /task ---

--- task ---

Click on the green flag to run your project. When the **Dot** sprite stops moving, look at the `y`{:class="block3motion"} value in the Sprite pane. 

![The y value displayed in the Sprite pane.](images/y-sprite-pane.png)

With this value, the **Dot** sprite will not jump as they are touching land. Change the value in the `set y to`{:class="block3motion"} block so that the **Dot** sprite moves above the land before jumping. 

```blocks3
set y to (-49) 
```

**Tip:** Experiment by changing the number then pressing <kbd>space</kbd> until you find the number that makes the **Dot** sprite jump on your backdrop. The number will probably be between five and ten higher than the current `y`{:class="block3motion"} position. So if your `y`{:class="block3motion"} position is `-56`, a good starting value is  `-49`.

--- /task ---

--- save ---
