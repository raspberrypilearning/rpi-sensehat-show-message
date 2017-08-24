+ Make sure you have these lines of code in your program to set up your connection with the Sense HAT. If you already have these, there is no need to add the code more than once.

```python
from sense_hat import SenseHat
sense = SenseHat()
```

+ Add this code to display a message on the LED matrix

```python
sense.show_message("Hello world")
```

The message "Hello world" will scroll across the screen. Change the words in quotes (`""`) to see a different message.

You can try it out here:

<iframe src="https://trinket.io/embed/python/224b71fc28" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
