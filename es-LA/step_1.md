Asegúrate de tener las siguientes líneas de código en el programa Python para configurar la conexión con el Sense HAT. Basta con añadirlos una vez.

```python
from sense_hat import SenseHat
sense = SenseHat()
```

+ Agrega este código para mostrar el mensaje en la matriz de LED de Sense HAT.

```python
sense.show_message("Hola mundo")
```

El mensaje "Hola mundo" ahora se desplazará por la pantalla LED.

+ Cambia las palabras en las comillas (`""`) para ver un mensaje diferente.

Puedes probarlo aquí: 

<iframe src="https://trinket.io/embed/python/25207e575e" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
