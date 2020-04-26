Zorg ervoor dat je de volgende coderegels in je Python-programma hebt om je verbinding met de Sense HAT in te stellen. Het is niet nodig om ze meerdere keren toe te voegen.

```python
from sense_hat import SenseHat
sense = SenseHat ()
```

+ Voeg deze code toe om een bericht op de LED-matrix van de Sense HAT weer te geven.

```python
sense.show_message("Hallo wereld")
```

Het bericht "Hallo wereld" zal nu over het LED-scherm scrollen.

+ Wijzig de woorden tussen de aanhalingstekens (`""`) om een ander bericht te zien.

Je kunt het hier proberen: 
<iframe src="https://trinket.io/embed/python/278f70b0af" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>