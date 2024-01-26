Assure-toi d'avoir les lignes de code suivantes dans ton programme Python pour établir la connexion avec ton Sense HAT. Il n'est pas nécessaire de les ajouter plus d'une fois.

```python
from sense_hat import SenseHat
sense = SenseHat()
```

+ Ajoute ce code pour afficher un message sur la matrice LED du Sense HAT.

```python
sense.show_message("Bonjour le monde")
```

Le message "Bonjour le monde" va maintenant défiler sur l'écran LED.

+ Change les mots entre guillemets (`""`) pour voir un message différent.

Tu peux l'essayer ici : <iframe src="https://trinket.io/embed/python/224b71fc28" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
