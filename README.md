                                             SUMADOR - RESTADOR DE DOS NÚMEROS DE 8 BITS


1.PLANTEAMIENTO DEL PROBLEMA

Un sumador es un circuito digital que realiza la adición de números, este tipo de circuito mediante el método de complemento A1, también nos puede ayudar a la resta de dos números. Es por ello que se desea implementar los ya mencionados circuitos sumadores en el diseño de un circuito capaz de realizar estas dos operaciones (suma - resta), para dos números de 8 bits cada uno. Este diseño conlleva el reto de poder visualizar hasta los 9 bits de salida en 3 displays de 7 segmentos, estos 9 bits es lo máximo que podrá tener nuestro circuito sumador- restador en la salida, además de mostrar el signo en el caso que se realice una resta y el resultado sea negativo.  


2.OBJETIVOS

Objetivo general

- Implementar un circuito sumador – restador, para dos números de 8 bits, mostrando el resultado en displays de 7 segmentos.

Objetivo específicos

-	Visualizar el signo del resultado (en el caso que el resultado sea negativo).

- Multiplexar las salidas para poder escoger que resultado se desea ver, ya sea suma o resta en los displays de 7 segmentos.

- Comprobar el funcionamiento del diseño del contador mediante la simulación en proteus e implementada en constructor virtual (laboratorio virtual).


3.ESTADO DEL ARTE

En 2019 LOAIZA AGUILAR ANGEL DANILO de la UNIDAD ACADÉMICA DE INGENIERÍA CIVIL CARRERA DE INGENIERÍA DE SISTEMAS ubicada en Machala-Ecuador diseño y construcción de un circuito electrónico que permita realizar las dos operaciones principales que son la suma y la resta entre dos palabras digitales, siendo cada palabra digital un número como máximo de dos cifras. Para la obtención de las operaciones matemáticas requeridas en el presente proyecto he utilizado como método principal la suma binaria, realizando todas las tablas de verdad necesarias para controlar el correcto funcionamiento del circuito, la elección de los datos a mostrar se ha realizado con la ayuda de multiplexores, he utilizado una memoria SRAM para almacenar los resultados, la visualización de la primera palabra digitales, de la segunda palabra digital, del resultado obtenido en la operación y del datos almacenado se presentara en números confeccionados a base de cinta led de alta luminosidad que requieren de un voltaje mayor al del circuito, es por ello que he utilizado transistores en unión bipolar para lograr esta visualización, para construir el circuito físico se recomienda utilizar los circuitos integrados que estén en buen estado ya que si alguno esta imperfecto podría ocasionar que no obtengan los resultados esperados, también se recomienda leer el voltaje máximo que soporta cada uno de los circuitos integrados en sus respectivas hojas de datos y utilizar la fuente de energía adecuada. (LOAIZA AGUILAR ANGEL DANILO, 2019, p.1) [1].

REYES ERAZO, CRISTHIAN EDUARDO de la FACULTAD DE EDUCACIÓN TÉCNICA PARA EL DESARROLLO CARRERA DE INGENIERÍA EN TELECOMUNICACIONES de la Universidad Católica Santiago de Guayaquil El presente trabajo de titulación consiste en realizar la evaluación de las plataformas de simulación SIMULINK y QUARTUS II para la asignatura de Sistemas Digitales. La idea del trabajo es fundamental y formativa, porque existe otra herramienta de simulación que no se ha considerado en el programa de estudios de la asignatura Sistemas Digitales I y II. Por lo general, en estas asignaturas los estudiantes utilizan Isis Proteus y Multisim, ambas plataformas son amigables. En la búsqueda de información se pudo constatar que Simulink de MatLab, también permite desarrollar simulaciones de sistemas digitales. Los estudiantes de V Ciclo de Telecomunicaciones, Electrónica en Control y Automatismo y Eléctrico-mecánico pueden hacer uso del presente trabajo como guía y así profundizar más en el tema usando Simulink. Quartus II, es una plataforma que permite realizar programación en VHDL, diseño esquemático y diseño por máquinas de estados y esto a su vez se implementa en la FPGA de Altera disponible en el laboratorio de electrónica. Cabe mencionar que tanto Simulink como Quartus II, realizan múltiples aplicaciones para aplicaciones en telecomunicaciones. (REYES ERAZO, CRISTHIAN EDUARDO, 2019, p.1) [2]. 

4.MARCO TEÓRICO


![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/marco%20teorico%201.png)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/marco%20teorico%202.png)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/marco%20teorico%203.png)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/marco%20teorico%204.png)

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/marco%20teorico%205.png)

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

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Diagrama%20electrico.png)



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

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/mapa_Variables_2.PNG)


8.EXPLICACIÓN DEL DISEÑO

Diagrama de bloques del circuito a diseñar:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Diagrama%20electrico.png)

Entradas

Variables de entrada:

Números A y B cada uno de 8 bits donde A0 y B0 son los menos significativos respectivamente:

A7,A6,A5,A4,A3, A2, A1, A0  ;  B7,B6,B5,B4,B3, B2, B1,B0

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%201.png)

Las operaciones están codificadas con un bit de manera que tengamos las dos operaciones: 

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%202.PNG)

Variables de salida:

Signo, E8,E7,E6,E5,E4,E3,E2,E1,E0

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%203.png)

Operación Suma

Para realizar la operación de suma de dos números de 8 bits utilizamos 2 sumadores conectados el primer acarreo de salida al acarreo de entrada del siguiente sumador para obtener un sumador de 8 bits 

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%204.png)

Operación resta

Para realizar la operación resta primero usamos dos comparadores de 4 bits conectados de forma que nos de uno de 8 bits que utilizaremos en la siguiente etapa

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%205.png)

A continuación, se utiliza 8 multiplexores 2 a 1 para la primera comparación A<B donde entra al selector del multiplexor presentado en el lado izquierdo y así obtener el número mayor cuando sea el caso
Y lo mismo con la segunda comparación A>B para obtener el número menor

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%206.png)

Una vez ordenado el número mayor procedemos a utilizar dos sumadores de 4 bits conectados de forma que obtengamos uno de 8 bits donde las entradas será el número mayor sumado al complemento del número menor con un acarreo inicial de 1 para así obtener la resta

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%207.png)

Signo
Para el signo utilizamos una compuerta And donde vemos que si el número A es menor a B y en la operación Op está en resta entonces este se activara indicándonos el signo

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%208.png)

Salidas con multiplexores

Para presentar las salidas utilizamos 10 multiplexores 2 a 1 conectados de la siguiente manera donde S son los bits del resultado de la suma y R son los bits del resultado de la resta controlados por OP que es la operación seleccionada y así indicándonos la respuesta de la operación que deseamos

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%2010.png)

Transformación de binario a BCD 

Para esta última etapa el resultado obtenido máximo será de 9 bits más el signo para presentar este número en displays es necesario transformar el binario a BCD para esto usamos el método de transformación por desplazamiento el cual tiene de base desplazar bit a bit desde el más significativo hasta el menos significativo comparando si es mayor o igual a 5 si no lo es desplaza un bit caso contrario se suma 3 y a la respuesta se le compara igual que antes así hasta llegar al bit menos significativo
Se utiliza circuitos integrados de comparados sumadores y NOR para dicha transformación los comparadores son la entrada de los 3 bits más significativos comparados con el numero 5 si es mayor o igual se suma 3 en el siguiente sumador y se desplaza un bit al siguiente comparador con las salidas del sumados a las entradas del comparador donde queda un bit flotando que se utilizara más adelante para seguir desplazando las centenas de la misma forma y así obtener la transformación

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%2011.png)

Salida en displays 

Para esto se utiliza 4 displays y 3 decodificadores de BCD a 7 segmentos el primer display es el signo conectado directamente el segundo display con su respectivo codificador nos indica las centenas el tercer display nos indica las decenas y el cuarto nos indica las unidades todos estos decodificadores están conectados a las salidas de la transformación binaria a BCD

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/dise%C3%B1o%2012.png)
                 
9.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

EL diseño de nuestro circuito sumador restador de 8 bits se lo implemento tanto en el simulador proteus como en el laboratorio virtual llamado constructor digital. Es por ello que el ususario que requiera revisar el funcionamiento debe tener instalado los dos simuladores, en la carpeta llamada instaladores se encuentra el archivo que se podrá descargar para poder visualizar el circuito implementado:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%201.PNG)

Como se observa ya solo es necesario iniciar la aplicación del constructor virtual no necesita instalación, para abrir el archivo del diseño, tambien se encuentra en la carpeta instaladores, donde solo es un bloc de notas el cual contiene el codigo del circuito implementado, ese es el archivo que se debe abrir.

Aqui observamos la imagen del circuito en el laboratorio virtual:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%203.PNG)

Nota: Es necesario tener instalado la versión 8.9 de proteus ya que si se desea abrir la simulación en versiones antiguas puede ocurrir errores o no abrir el archivo.

Aqui observamos la imagen del circuito en el simulador proteus:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%202.PNG)


Es necesario que el usuario revise el datasheet de todos los circuitos integrados utilizados para que tenga una idea de que voltajes o corrientes soportan cada integrado, ademas de poder reconocer cada pin y cual es su función.
En el datasheet podemos obervar todas las especificaciones que se tomó en cuenta en el diseño, todo esto con el objetivo de no mostrar errores en la simulación del circuito, y tomando en cuenta a una posible implementación con integrados reales en un futuro. Estos documentos los puede encontrar en la carpeta llamada fichas tecnias, del repositorio.


10.APORTACIONES

Además de la implementación en el laboratorio virtual se realizó una simulación en el programa proteus, para comprobar el funcionamiento del circuito.

En la carpeta instaladores se encuentra el archivo que contiene la simulación en proteus.

Aquí observamos el circuito terminado en el simulador:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%202.PNG)

En esta simulación podemos observar cada bloque del sumador restador.

Ejemplo de simulación:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/aporte.PNG)

Suma de 11111111 + 11111111 (255 + 255).


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

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/cronograma.JPG)


14.BIBLIOGRAFÍA

Alulema, D. (2020). Circuitos Digitales. Quito, Ecuador.

Floyd, T. (2006). Fundamentos de sistemas digitales. Madrid: Pearson.

Siliceo, R. (2018). Algoritmo de las operaciones aritmeticas aplicadas a los codigos binarios, octal, hexadecimal y BCD con sus respectivas conversiones. Ciudad de Mexico.



15.ANEXOS

15.1 MANUAL DE USUARIO

Para poder usar el circuito sumador - restador es necesario que el usuario este familiarizado con el código binario natural, a continuación dejamos una imagen en la que se puede observar una parte del cógido con sus equivalentes en decimal, ademas de el link para que el usuario pueda ver una la tabla completa del codigo binario natural.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%201.PNG)


En esta tabla se encuentran los números del 1 al 10, esto es necesario ya que para usar el circuito debera ingresar los números en código binario.

Aquie dejamos el link donde se encuentra una tabla más completa:

https://es.convertbinary.com/numeros/

Ahora para poder ingresar los números en código binario se lo hará mediante 8 switch, que corresponden a los 8 bits de que el usuario tiene permitido usar, es decir solo se puede sumar o restar números que no sobrepasen el valor de 255 (1111 1111), esto aplica tanto para la simulación en proteus y en el lab virtual.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%202.PNG)

Observamos la ubicación con su etiqueta donde el usuario debe ingresar los números en proteus.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%203.PNG)

Observamos la ubicación donde el usuario debe ingresar los números en el constructor virtual, en este caso el conjunto de switchs de la derecha corresponden al prmer número y el conjunto de la izquierda de la pantalla corresponden al segundo número.

Nota: Se debe tomar en cuenta que el switch final ubicado a la derecha corresponde al bit más significativo, y el switch final ubicado a la izquierda corresponde al bit menos significativo de los números a ingresar.

Para que el usuario puede observar el resultado ya sea de la suma o resta se debe escoger en un switch el cual controla la operación como vemos a continucación:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%204.PNG)


Para el caso de proteus.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%205.PNG)


Para el caso del constructor virtual. En este caso solo se encuentra habilitado el switch de la derecha, para el uso del control de operación.

Nota: El switch de control en estado abierto significa que el circuito mostrará la operación resta, si el switch se encuentra cerrado, el circuito mostrará la operación suma.


En el simulador proteus el usuario puede observar el resultado en displays de 7 segmentos como mostramos continuación:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%206.PNG)


En el caso del constuctor virtual se observará en leds que corresponden al resultado en binario natural.


![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%207.PNG)



15.2 HOJAS TÉCNICAS

Datasheet 74HC4511

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/Datasheetcd4511b.pdf

Datasheet 7404

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet7404.pdf

Datasheet 7408

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet7408.pdf

Datasheet 74157

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet74157.pdf

Datasheet 74283

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet74283.pdf

Datasheet 7485

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet7485.pdf
