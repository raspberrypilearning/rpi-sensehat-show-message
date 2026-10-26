Make sure you have the following lines of code in your Python program to set up your connection with the Sense HAT. There is no need to add them more than once.

```python
from sense_hat import SenseHat
sense = SenseHat()
```

+ Add this code to display a message on the Sense HAT's LED matrix.

```python
sense.show_message("Hello world")
```

The message "Hello world" will now scroll across the LED screen.

+ Change the words in the quotes (`""`) to see a different message.

You can try it out here:

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/rpi-sensehat-show-message-example" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

The Code Editor shows the Sense HAT on its side, so the picture is turned a quarter-turn clockwise.

[Open this code in the Code Editor](https://editor.raspberrypi.org/en/projects/rpi-sensehat-show-message-example){:target="_blank"}
