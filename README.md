Estás escribiendo una IA para un juego de mapa 2D. Estás en algún lugar de una cuadrícula 2D, y hay monedas esparcidas por el mapa.

Dada la posición de todas las monedas y tu posición actual, encuentra la moneda más cercana a ti en términos de distancia de Manhattan. Es decir, puedes moverte hacia arriba, abajo, izquierda y derecha, pero no en diagonal. Si hay varias monedas más cercanas posibles, devuelve cualquiera de ellas.

Por ejemplo, dado el siguiente mapa, donde tú eres x, las monedas son o y los espacios vacíos son . (arriba a la izquierda es 0, 0):
```
---------------------

| . | . | x | . | o |
---------------------
| o | . | . | . | . |
---------------------
| o | . | . | . | o |
---------------------
| . | . | o | . | . |
---------------------
```
devuelve (0, 4), ya que esa moneda es la más cercana. Este mapa estaría 
