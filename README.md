                                                 SUMADOR - RESTADOR DE DOS NÚMEROS DE 8 BITS


1.PLANTEAMIENTO DEL PROBLEMA

Un sumador es un circuito digital que realiza la adición de números, este tipo de circuito también nos puede ayudar a la resta de dos números. Es por ello que se desea implementar los ya mencionados circuitos sumadores en el diseño de un circuito capaz de realizar estas dos operaciones (suma - resta), para dos números de 8 bits cada uno. Este diseño conlleva el reto de poder visualizar hasta los 9 bits de salida en 3 displays de 7 segmentos, que se podrá tener en nuestro circuito sumador- restador, además de mostrar el signo en el caso que el resultado sea negativo.  


2.OBJETIVOS

Objetivo general

- Implementar un circuito sumador – restador, para dos números de 8 bits, mostrando el resultado en displays de 7 segmentos..

Objetivo específicos

-	Visualizar el signo del resultado (en el caso que el resultado sea negativo).

- Multiplexar las salidas para poder escoger que resultado se desea ver, ya sea suma o resta en los displays de 7 segmentos.

- Comprobar el funcionamiento del diseño del contador mediante la simulación en proteus e implementada en Tinkercad (laboratorio virtual).


3.ESTADO DEL ARTE

En 2019 LOAIZA AGUILAR ANGEL DANILO de la UNIDAD ACADÉMICA DE INGENIERÍA CIVIL CARRERA DE INGENIERÍA DE SISTEMAS ubicada en Machala-Ecuador diseño y construcción de un circuito electrónico que permita realizar las dos operaciones principales que son la suma y la resta entre dos palabras digitales, siendo cada palabra digital un número como máximo de dos cifras. Para la obtención de las operaciones matemáticas requeridas en el presente proyecto he utilizado como método principal la suma binaria, realizando todas las tablas de verdad necesarias para controlar el correcto funcionamiento del circuito, la elección de los datos a mostrar se ha realizado con la ayuda de multiplexores, he utilizado una memoria SRAM para almacenar los resultados, la visualización de la primera palabra digitales, de la segunda palabra digital, del resultado obtenido en la operación y del datos almacenado se presentara en números confeccionados a base de cinta led de alta luminosidad que requieren de un voltaje mayor al del circuito, es por ello que he utilizado transistores en unión bipolar para lograr esta visualización, para construir el circuito físico se recomienda utilizar los circuitos integrados que estén en buen estado ya que si alguno esta imperfecto podría ocasionar que no obtengan los resultados esperados, también se recomienda leer el voltaje máximo que soporta cada uno de los circuitos integrados en sus respectivas hojas de datos y utilizar la fuente de energía adecuada. (LOAIZA AGUILAR ANGEL DANILO, 2019, p.1) [1].

REYES ERAZO, CRISTHIAN EDUARDO de la FACULTAD DE EDUCACIÓN TÉCNICA PARA EL DESARROLLO CARRERA DE INGENIERÍA EN TELECOMUNICACIONES de la Universidad Católica Santiago de Guayaquil El presente trabajo de titulación consiste en realizar la evaluación de las plataformas de simulación SIMULINK y QUARTUS II para la asignatura de Sistemas Digitales. La idea del trabajo es fundamental y formativa, porque existe otra herramienta de simulación que no se ha considerado en el programa de estudios de la asignatura Sistemas Digitales I y II. Por lo general, en estas asignaturas los estudiantes utilizan Isis Proteus y Multisim, ambas plataformas son amigables. En la búsqueda de información se pudo constatar que Simulink de MatLab, también permite desarrollar simulaciones de sistemas digitales. Los estudiantes de V Ciclo de Telecomunicaciones, Electrónica en Control y Automatismo y Eléctrico-mecánico pueden hacer uso del presente trabajo como guía y así profundizar más en el tema usando Simulink. Quartus II, es una plataforma que permite realizar programación en VHDL, diseño esquemático y diseño por máquinas de estados y esto a su vez se implementa en la FPGA de Altera disponible en el laboratorio de electrónica. Cabe mencionar que tanto Simulink como Quartus II, realizan múltiples aplicaciones para aplicaciones en telecomunicaciones. (REYES ERAZO, CRISTHIAN EDUARDO, 2019, p.1) [2]. 

4.MARCO TEÓRICO


![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/marco%20teorico%201.png)

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/marco%20teorico%203.png)

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/marco%20teorico%202.png)

5.DIAGRAMAS

•Diagramas de bloques.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/2.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/3.jpeg)

•Diagramas esquemáticos.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/4.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/5.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/6.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/7.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/8.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/9.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/10.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/11.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/12.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/13.jpeg)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/14.jpeg)


•Diagramas eléctricos.

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/diagrama3.jpg)









6.LISTA DE COMPONENTES

- Simulador Proteus version 8.9.
- Laboratorio virtual Tinkercad.
- Compuertas NOR, OR, AND, X-OR.
- 2 comparadores 74LS85
- 6 sumadores 74LS283
- 4 multiplexores 74LS157
- 7 decodificadores 74LS48
- 7 Displays 7 segmentos (cátodo común).
- 2 Dip-switch de 8 entradas
- 1 Dip- switch de 2 entradas
- 4 inversores 74LS04



7.MAPA DE VARIABLES

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/mapa%20variables.jpg)


8.EXPLICACIÓN DEL DISEÑO

Contador en código binario.

En esta etapa es necesario indicar que se utilizará un generador de señal de reloj (CLK) para los FLIP FLOP (FF), de igual forma usaremos una frecuencia aproximada de 1 Hz dados los valores de las resistencias R1 y R2 (330 Ohmios ).
Tomaremos en cuenta que:
- Un contador asíncrono tiene como principal característica que cada flip flop que lo compone tiene diferente señal de reloj (clk).
- El temporizador está configurado a una frecuencia de 1 Hz, es decir que el contador aumentará de valor cada segundo.
- Los integrados usados para los contadores con flip flops D serán el CD4013 y el 74hHC74. En nuestro caso usaremos el integrado 74HC74.

Para empezar nuestro análisis tendremos que plantear los estados, en este caso de 4 bits será de 0000 a 1111 es decir un conteo de de 0 a 15.

En esta parte vemos como se pasa de un estado al otro nuestra cuenta, lo que nos indica que las salidas de nuestros fip flops tendran una salida de 0 o 1. 

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Tablas%20de%20transicion.PNG)

                     Tabla de verdad de cambio de estados 

Tabla de excitación del flip flop D

Ya que estamos usando un flip flop tipo D, tenemos la siguiente tabla, la cual nos muestra la respuesta a los cambios de estado que sufre el flip flop.

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Tabla%20de%20exitacion.PNG)

          Tabla de exitacion de un flip flop tipo D
 
 Analizando el cambio de estado de cada columna tenemos el siguiente diagrama:
 
 ![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Cambio%20de%20estados.png)
 
Una vez analisado los cambios de estado procedemos a implementar el circuito en el simulador proteus, para implementar nuestro circuito debemos tomar en cuenta lo siguiente:

-Necesitaremos 4 flip flops, uno por cada bit requerido en este caso seran 4 flip flops, seguido conectaremos la señal de reloj a nuestro primer flip flop, la salida de este significa el bit menos significativo de nuestro conteo.

-Cada entrada de reset y clear deberá estar conectada a Vcc, ya que se activan en bajo y nos las utilizaremos.

-Conectamos cada terminal D a Q’ y también a los clock’s. Con esto haremos que la salida anterior se duplique hacia la entrada del siguiente flip flop.

Implementación en proteus:

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/dise%C3%B1o%201.PNG)

                            Simulación en proteus
                  
Ahora veremos la implementación en tinkercad                 
                  
![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/dise%C3%B1o%202.png)

                                                                  Simulación en Tinkercad
                
                 
9.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

EL diseño de nuestro contador asincróno de 4 bits se lo realizó mediante el uso de flip flops tipo D. Es por ello que se tomó en cuenta la revisión de nuestro circuito integrado, en este caso es el modelo 74HC74, el cual presentamos un fragmento a continuación:

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Data1.PNG)


Es necesario que el usuario revise el datasheet de todos los circuitos integrados utilizados para que tenga una idea de que voltajes o corrientes soportan cada integrado, ademas de poder reconocer cada pin y cual es su función.
En el datasheet podemos obervar todas las especificaciones que se tomó en cuenta en el diseño, todo esto con el objetivo de no mostrar errores en la simulación del circuito, y tomando en cuenta a una posible implementación con integrados reales en un futuro,

Si el ususario desea comprobar el diseño del circuito lo puede hacer abriendo el archivo de la simulación en proteus o entrando a la plataforma Tinkercad en la cual se encuentra guardado el diseño implementado, tomando en cuenta que no prodrá modificar ninguna parte del circuito ya que ello conllevaria a fallas del circuito.

Nota: Es necesario tener instalado la versión 8.9 de proteus ya que si se desea abrir la simulación en versiones antiguas puede ocurrir errores o no abrir el archivo.

10.APORTACIONES

Conversión de código binario de cuatro (4) bits a BCD.
Al tener cuatro bits es posible manejar quince (15) combinaciones de entrada e igual número de combinaciones de salida. La tabla de valores para las posibles combinaciones es la siguiente:


![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Binario%20a%20BCD.PNG)

Mediante estas tablas es posible observar que los valores de las salidas son iguales hasta el número nueve (9) decimal y de ahí en adelante el código de salida aparece incrementado en seis (6) decimal respecto al código de entrada. Dado lo anterior es posible concebir un sumador que reciba como entradas A los valores del código binario y como entradas B el número seis (6) en binario (0 1 1 0) pero solo cuando la salida B4 tenga un valor de uno (1). Para obtener la expresión que brinde esta posibilidad se realizó el mapa de Karnaught para la salida B4, con el siguiente resultado:

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Karnauth.PNG)

Por lo tanto, se obtiene para B4 la siguiente expresión:

B4 = A3A2 + A3A1 = A3(A2 + A1)

El resultado de esta implementación se llevará a las entradas B3 y B2 del sumador con el fin de obtener el resultado deseado.

Nota: Es necesario recordar que en la anterior descripción no tiene significado el hecho de no tener una secuencia consecutiva de valores. Así mismo en los valores de las entradas A serán ubicados los valores de salida de cada FF.

“Decodificación” y presentación del resultado.
Cada una de las salidas del sumador deben ser las entradas del decodificador/manejador que en este caso es el circuito 4511. A su vez este circuito arroja las salidas a, b, c, d, e, f  y g  a nivel alto que representan los siete (7) segmentos de un Display y específicamente uno de cátodo común. El Display utilizado es de la serie 5161 que tiene la siguiente distribución:

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/display.PNG)

Simulación.
Para llevar a cabo la simulación de la implementación del circuito se utilizó la herramienta proteus. Como se muestra a continuación:

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Aporte1.png)


Para la demostración también se implemento en la plataforma Tinkercad como se muestra a continuación:


![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/aporte2.png)





11.CONCLUSIONES

•	La implementación del circuito Sumador/Restador nos ayudó a comprender no solo el funcionamiento de los integrados sumadores como el 74HC283, ya que también observamos como mediante   el   uso   de   los   elementos   MSI   podemos   llevar   a   cabo   procesos   más complejos de una forma más rápida y sencilla que al utilizar elementos SSI. Es por ello que se utilizó multiplexores y comparadores que nos ayudaron a reducir el tamaña del circuito.
  
•	Mientras más bits de código se quiera mostrar en displays, se requiere de un proceso más complicado, y en la vida real no existe integrados decodificadores de código binario a BCD.

•	En la realización de la simulación se pudo ratificar el funcionamiento de nuestro circuito sumador – restador, de entrada, tenemos dos números de 8 bits, lo cual nos dará una salida de hasta 9 bits en la mayor suma que se puede realizar.


12.RECOMENDACIONES

•	Debemos ser ordenados para armar el circuito para que si tenemos alguna falla podamos encontrar rápido el error.

•	Se recomienda no mezclar integrados de tecnología TTL con tecnología Cmos ya que sus diseños admiten diferentes valores de voltajes y corriente, en este diseño de lo realizo debido a la escasez de modelos de integrados en la plataforma de Tinkercad. 

•	Se recomienda tener conocimientos previos sobre circuitos sumadores y sus tablas de verdad, en conjunto con el datasheet de cada elemento que se usa en el circuito. 

•	Es preciso planificar un cronograma con diagramas de Grant en las diferentes aplicaciones que existen y para el desarrollo se recomienda el software Project. 



13.CRONOGRAMA

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/Cronograma.PNG)


14.BIBLIOGRAFÍA

Alulema, D. (2020). Circuitos Digitales. Quito, Ecuador.

Floyd, T. (2006). Fundamentos de sistemas digitales. Madrid: Pearson.

Ricoy, A. (14 de Junio de 2020). Appinventor en español. Obtenido de https://sites.google.com/site/contadorasincrono/flipflop

Siliceo, R. (2018). Algoritmo de las operaciones aritmeticas aplicadas a los codigos binarios, octal, hexadecimal y BCD con sus respectivas conversiones. Ciudad de Mexico.



15.ANEXOS

15.1 MANUAL DE USUARIO

Para poder usar el contador sincrónico se debe tener instalado si es posible la versión más actual de proteus.
Abriremos el archivo de la simulación

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/manual1.png)

Nos presenta la interfaz de usuario del simulador:

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/manual2.png)

Procedemo a realizar la simulación hacuendo click en el botón de la parte inferior izquierda.

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/manual3.png)


Nota: tomar en cuenta que no se debe cambiar la frecuencia de la entrada de reloj. Ni cambiar el voltaje de entrada Vcc ya que podemos quemar los integrados.

Si queremos usar la implementación en tinkercad procederemos a entrar al siguiente link:

https://www.tinkercad.com/things/jxkNseHqJ4V-contador-asincronico/editel?sharecode=qnTRplA-JvCfeY6Auv5toNln4Gi4wd6hVyGVvV7Ki40

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/manual4.png)


Nos presenta la interfaz de usuario

Ahora procedemos a simular para observar nuestro circuito:

![alt text](https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Img/manual5.PNG)

Nota: tomar en cuenta que es debido registrarse antes en la plataforma Tinkercad para poder tener acceso, no se debe cambiar la frecuencia de la entrada de reloj. Ni cambiar el voltaje de entrada Vcc ya que podemos quemar los integrados. Evitar mover las conexiones ya que dañaría el diseño.


15.2 HOJAS TÉCNICAS

Datasheet 74HC293

https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Hojas%20tecnicas/Datasheet74283.pdf

Datasheet 74HC32

https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Hojas%20tecnicas/Datasheet7432.pdf

Datasheet 74HC74

https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Hojas%20tecnicas/Datasheet7474.pdf

Datasheet 74HC08

https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Hojas%20tecnicas/datasheet7408.pdf

Datasheet 4511

https://github.com/Proyecto-Digitales/INFORME-N.2/blob/master/Hojas%20tecnicas/Datasheetcd4511b.pdf
