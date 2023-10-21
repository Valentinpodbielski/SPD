# SPD

Abajo se dispone de todos los links a los proyectos en el Tinkercad, sus explicaciones y usos. La parte 1 es la del contador en los displays con los tres interruptores, la Parte 2 es la de la modificacion del interruptor dezlizante con los numeros primos, la Parte 3 que en si no habia parte 3, yo lo dividi como parte para ser mas prolijo, es lo mismo que la parte 2, pero con el motor CC integrado y la parte 4 es en la que incorporamos el sensor de fuerza. 



# Integrantes

--------------------------Alejo Valentin podbielski--------------------------

--------------------------Matias Gabriel Wolf--------------------------

--------------------------Enzo Paredes VEron--------------------------


# Links a los tinkercad

--------------------------Parte 1 = https://www.tinkercad.com/things/apv1Z6WQKdl   ----------------------------------

--------------------------Parte 2 = https://www.tinkercad.com/things/9FTrGU9f1I2   ----------------------------------

--------------------------Parte 3 = https://www.tinkercad.com/things/5JMzziEWGIy   ----------------------------------

--------------------------Parte 4 = https://www.tinkercad.com/things/dlmMG9l5IXh   ----------------------------------


# Explicacion de cada Parte


.Parte 3 (Motor CC):
Un motor de corriente continua ("CC" o "DC", por sus iniciales en ingles direct current) es una maquina que convierte energia electrica en mecanica, lo cual provoca un movimiento rotatorio debido a la accion de un campo magnetico.Este mismo esta conformado principalmente por dos partes:
*El estátor, el cual es la parte fija/carcasa exterior de la maquina que permite crear un campo magnético.
*El rotor, es la parte interior de la maquina, el cual gira, alimentado con corriente directa a traves de delgas (laminas de cobre), que estan en contacto alternante con escobillas fijas.
Estos componentes juntos forman el conjunto fundamental para la transmision de potencia en el motor.
El principio de funcionamiento basico de un motor de CC se basa en una espira de material conductor (rotor) inmersa en un campo magnetico (creado por el estátor), a la cual se le aplica una diferencia de potencial entre sus extremos, permitiendo que circule por la misma una corriente. A partir de ello, la espira presenta fuerzas en sus dos segmentos laterales, permitiendo el giro del mismo, hasta que en cierto punto las fuerzas se oponen a continuar con el movimiento, y en ese punto es en el que se alterna la polaridad del voltaje aplicado, lo que invierte el sentido de la fuerza y vuelve a impulsar el giro de la espira.
Nuestro grupo penso en integrar el motor CC de manera que se prenda unicamente cuando el contador sea algún numero múltiplo de 10 y el 0. Asi, a la hora de encender el motor, se prende durante un segundo generando una leve vibracion y alertando al usuario de que llego a tal numero. su borne positivo lo conectamos al pin 12 y su negativo al gnd ,y ademas, los configuramos como salida para su optimo funcionamiento.

.Parte 4 (Sensores):
En la parte del proyecto en la que habia que agragar un sensor, optamos por el sensor de fuerza, en la que junto con los dos displyas, se Logran mostrar 3 fuerzas en equivalencias diferentes. Es decir, que al prender el arduino se muestra en los display la fuerza que se esta ejerciendo en el sensor en kilogramos, si apretamos el interruptor se muestra la lectura del sensor en libras y se apreta otra vez, se muestra en onzas. Si se quiere apretar de nuevo, la fuerza a mostrar vuelve a ser en kilogramos. El sensor tiene limitaciones, y su rango de peso es de 30 gramos a 1 kilogramo. Se puede decir que esta fabricado de dos capas separadas por un espaciador, cuanto mas se preciona mas puntos de elemento activo tocan el semiconductor.

# Practico del Parcial

Lo que hice en este proyecto es agregar al arduino un Sensor de luz Ambiental, en la que su funcion es prender o apagar los Display depende de la intensidad de luz que capte. Al haber poca luz se encienden los Display y si hay mucha luz se apagan. El funcionamiento del sensor no modifica lo otro, ya que el valor del contador sigue intacto y los numeros primos siguen aumentando.

![image](https://github.com/Valentinpodbielski/SPD/assets/124207059/3075c615-e4bf-45ba-93b3-938ac2889ee8)
Tinkercad = https://www.tinkercad.com/things/6cTvgqJFkVc
