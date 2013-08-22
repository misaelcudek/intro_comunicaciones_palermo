1) Se utilizan tramas discretas definidas por delimitadores conocidos como bit de start y de stop

2) Se puede llegar a recibir mal el dato debido a una mala calibracion o diferencias en la calibracion
   entre el reloj del emisor y del receptor

3) Se realiza a traves de un reloj, el cual puede estar incluido en la señal o ser compartido por el emisor
y receptor. O a traves de la utilizacion de relojes patron.

4) El bit de paridad es una medida de redundancia para detectar errores en hasta 1 bit del mensaje.

5)
  a)
     Tiempo de Transmision Pura: 33.33...
     Tiempo de Transmision con bits Suplementarios: 41.66...
     Redundancia: No hay
  b)
     Tiempo de Transmision: 33.33.. (11 tramas)
     Redundancia: 0.66%
  c)
    a)
      Tiempo de Transmision: 416.66..
      Redundancia: No hay
    b)
      Tiempo de Transmision: 336.66.. (101 tramas)
      Redundancia: 0.6%
  d)
    a)
      Tiempo de Tranmision: 10.4166...
      Redundancia: No hay
    b)
      Tiempo de Transmision: 104.1666..
      Redundancia: 0.66%

6)

   |start|-----|-----|-----|-----|stop-|________|start|-----|-----|-----|-----|stop-|

   ^--------^------^------^------^------^-------^--------^------^------^------^------^

   Si la señal tiene un tiempo entre trama y trama apreciable para que no quede
   el proximo bit de start dentro del error de la trama anterior, el receptor
   puede volver a sincronizarse

7)
  Funcionaría siempre y cuando se determine un espacio de tiempo apreciable
  entre trama y trama

8)
  Suponiendo que T0 = 0 y que Tn = (n - 1)(T ± Δ)

  Si supongo que en el ultimo instante del 10mo bit (el bit de paridad, si consideramos que tenemos un bit de start)
  hago la lectura del mismo y la transmision de cada bit es de 1 segundo

  T10 = 10
  n = 10
  T = 1

  10 = 9 * (1 ± Δ) ⇒  Δ ≅ 11%

9)
  0,4 = n ( 2 / 525600 )
  n = 105120

