## Setting the start position

- Now much of the setup of your program is over, you can start to build up the script. Return to the `Scripts` tab.

- Open the `Control` blocks area and begin by dragging a `When green flag clicked` block into the main script area.

- To make sure that Mooncake starts at the top of the screen at the start of the program, you will need to set the coordinates. Use a `go to x: 0  y: 0` block from the `Motion` blocks area. Drag it over and clip it beneath `When green flag clicked`, then enter `x` as `0` and `y` as `148`.

- Next, you will need to store some data inside your variable blocks. To do this, use a `set gravity to 0` block from the `Variables` area and replace the value with `-9.81`, which is the calculation of the force of gravity on Earth.

- Similarly, set the `velocity` variable to `0`.

