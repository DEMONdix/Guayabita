# Guayabita
  Juego implemetado en python con programacion imperativa

## Codigo
<pre><code>
def juego(pool1, pool2, Apuesta1, Apuesta2, mesa):
  import random
  
  if pool1 == 0 or pool2 == 0:
    print ('Se acabo el juego')
  else:
        
        if random.randint(1, 6) == (1 or 6):
            mesa = Apuesta1 + mesa
        else:
            random.randint(1, 6)
        if random.randint(1, 6) > random.randint(1, 6):
            mesa = Apuesta1 + mesa
        else:
            pool1 = pool1 + mesa
        if Apuesta2 > 0:
            random.randint(1, 6)
        else:
          if random.randint(1, 6) == 1 or random.randint(1, 6) == 6:
            mesa = Apuesta1 + mesa
          else:
            random.randint(1, 6)
          if random.randint(1, 6) > random.randint(1, 6):
            mesa = Apuesta2 + mesa
          else:
            pool2 = pool2 + mesa
