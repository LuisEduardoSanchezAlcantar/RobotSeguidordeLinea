# RobotSeguidordeLinea

ALUMNOS:

ALEJANDRA ESTHER SANTES SANTIAGO

MONJARAS VIVANCO ELIZABETH

JOEN ALLEN SOTO AMEZQUITA

JUAN MANUEL PEREZ GONZALEZ

LUIS EDUARDO SANCHEZ ALCANTAR

ESTEBAN JESUS SECUNDINO GUILLEN

--------------------------------------------------------------------------------------------------------
OBJETIVOS:

•	Construir un robot seguidor de línea, que funcione mediante sensores Usando componentes básicos de electrónica.

•	Profundizar en el estudio y desarrollo tecnológico, despertando la Creatividad e imaginación de cada uno de los integrantes del equipo.

•	Conocer más acerca de la robótica, así como analizar las ventajas y desventajas de los robots.

--------------------------------------------------------------------------------------------------------
CONTIENE:

![Componentes](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/COMPONENTES.png)

--------------------------------------------------------------------------------------------------------
DIAGRAMA:

![Diagrama](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/diagrama.png)

--------------------------------------------------------------------------------------------------------

COMPONENTES BASICOS DE UN ROBOT:

Los robots seguidores de línea (o robots rastreadores) cumplen una única misión: Seguir una línea marcada en el suelo (normalmente una línea negra sobre un fondo blanco o línea blanca en fondo negro).

Estos robots pueden variar desde los más básicos (van tras una línea única) hasta los robots que recorren laberintos. Todos ellos, sin embargo, poseen (por lo general) ciertas partes básicas comunes entre todos:

Sensores

Un rastreador detecta la línea a seguir por medio de sensores. Hay muchos tipos de sensores que se pueden usar para este fin; sin embargo, por razones de costos y practicidad los más comunes son los sensores infrarrojos (IR), que normalmente constan de un LED infrarrojo y un fototransistor.

Receptor infrarrojo.

Este tipo de receptores son la contraparte de los emisores, encargados de recibir la luz infrarroja y convertirla en un voltaje análogo, estos cuentan con un filtro de luz de día, por eso es su color aparentemente negro, lo cual indica que reciben menos interferencia de cualquier fuente de luz externa.

LED Emisor infrarrojo.

Este tipo de emisores genera luz en el espacio infrarrojo, por lo cual no lo podemos ver a simple vista, en la actualidad se utilizan en la mayoría de aplicaciones de control remoto, porque son baratos y no le causan daño al usuario, su desventaja es que está restringido a distancias cortas de trabajo y ángulos predeterminados.

Transistor BC547.

Este elemento consta de tres terminales, es un transistor de uso general el cual está hecho de silicio y actúa en el robot como interfaz de potencia, es decir, cuando hay una señal proveniente del amplificador esta dispara a la base de este transistor y toda la energía de la fuente pasa vía colector emisor hacia los motores y dependiendo cual es el que tenga señal será el que se active.
 
Resistencias.

Las resistencias en cualquier circuito electrónico son de gran utilidad ya que como se nombre lo indica estas son las encargadas de limitar la corriente que fluye de la fuente hacia los elementos y así evitar un corto, estas son de un valor fijo, dependiendo los colores de las franjas que tienen.

Motor Mitsubichi.

Son los encargados del trabajo mecánico del robot, estos motores son de bajo Consumo y encienden con un voltaje de 3.4Volts, están enganchados mediante el Termo fijo a la lámina que se adhiere a la placa del robot, mediante estos se le da orientación y nivelación correcta al robot para que este tenga un óptimo desempeño.

Potenciómetro de 50 kΩ.

Estos dispositivos en realidad son resistencias variables, de los cuales pueden haber distintos tipos y valores, dependiendo la aplicación para la que van a ser usados, en el caso del robot, este elemento marca un voltaje de referencia el cual es introducido en la entrada no inversor del comparador LM393, y por lo cual se determina la sensibilidad de nuestro robot.

Circuito Integrado (CI) LM393.

El circuito integrado LM393 es un amplificador operacional doble, el cual esta Específicamente diseñado para funcionar como un comparador de alta precisión, rápida respuesta y bajo consumo, este circuito es el encargado de decidir, cuál de los motores activar, en base a los estímulos recibidos vía los receptores infrarrojos, en otras palabras, cambia una señal análoga en una señal de tipo digital, para el encendido o apagado de los motores.

LM 7805.

El 7805 es un regulador de voltaje positivo fijo, el cual es capaz de entregar 5Volts a la salida con una corriente máxima de primera, normalmente se utiliza para mantener un voltaje constante independiente del voltaje de entrada, ideal para aplicaciones dentro de circuitos de lógica combinacional o microcontroladores.

Capacitores.

Estos capacitores son del tipo electrolítico, por lo que tienen polaridad, es decir, un lado positivo y otro negativo, las principales aplicaciones de estos se dan como filtros de señales, ya sea de audio o para fuentes de alimentación, para el caso de nuestro robot, estos sirven para limpiar la señal del 7805, además de almacenar voltaje, para que los dispositivos puedan tomarlo en los picos que se dan al encender algún motor.

PIN simple.

El PIN simple es un conector ideal para cables, ampliamente utilizado en la mayoría de dispositivos de computadoras, impresoras y tarjetas electrónicas, su contraparte es el header hembra.


--------------------------------------------------------------------------------------------------------

FUNCIONAMIENTO

Todos los rastreadores basan su funcionamiento en los sensores. Sin embargo, dependiendo de la complejidad del recorrido, el robot debe ser más o menos complejo Los rastreadores más simples utilizan 2 sensores, ubicados en la parte inferior de la estructura, uno junto al otro. Cuando uno de los 2 sensores detecta el color blanco, significa que el robot está saliendo de la línea negra por ese lado. En ese momento, el robot gira hacia el lado contrario hasta que vuelve a estar sobre la línea. Esto en el caso de los seguidores de línea negra, ya que también hay seguidores de línea blanca.

Las 2 maneras más comunes de armar los rastreadores son: OPAMS, o con simples transistores (sin necesidad de programar nada). Esto dependiendo de la complejidad con la que se quiera armar el circuito. Podemos utilizar un pic 16f84 para guarda en El un recorrido de x pista.

--------------------------------------------------------------------------------------------------------

COMPONENTES ELECTRONICOS.

	2 Emisores infrarrojos de 5mm.
	2 Receptor infrarrojos de 5mm.
	2 LED´s verdes mini de 3.5mm.
	2 Header hembra.
	2 Pines macho.
	1 Liga.
	1 Clip de baterías de 9v.
	2 Motores de 3000rpm.
	1 Placa de circuito impreso.
	2 Potenciómetros de 50k.
	2 Cables.
	Termofijo en varios tamaños.
	2 Engranes.
	2 Micas.
	2 Capacitores de 10 μf.
	2 Transistores BC547.
	2 Resistencias de 270 Ohms.
	2 Resistencias de 560 Ohms.
	2 Resistencias de 1k Ohms.
	2 Resistencias de 10k Ohms.
	1 Transistor 7805.
	2 Alambres de cobre.
	1 Base para CI de 8 pines
	1 CI LM393.

1 part.
![parte1](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/PIEZAS%2CRESISTENCIAS%2CLED%C2%B4S%2CETC.jpg)
![parte2](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/PIEZAS%202.jpg)
![parte3](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/PORTA%20PILA.jpg)
--------------------------------------------------------------------------------------------------------
HERRAMIENTAS UTILIZADAS.

Cautín de lápiz.
Pinzas de punta.
Pinzas de corte.
Soldadura.
Cable delgado para electrónica.
Kolaloka.
Encendedor.
Cloruro Férrico.
Taladro.
Brocas.

![Herramientas](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/herramientas.png)


--------------------------------------------------------------------------------------------------------
El procedimiento que se siguió fue el siguiente:

1.-Creación de las pistas del circuito sobre la placa fenólica.

Sobre la placa fenólica y del lado donde se encuentra el cobre se trazan las pistas según el circuito con un plumón negro. Una vez hecho esto se vacía el cloruro férrico sobre un recipiente donde se colocara la placa para poder obtener las pistas grabadas en cobre.

![PAART1](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/PART1.png)

--------------------------------------------------------------------------------------------------------

2.-Montar los componentes y soldar correctamente.

Con la placa fenólica correctamente grabada y totalmente seca y libre de asperezas, se procede a montar los componentes uno a uno y soldar correctamente. Se tiene que tener mucho cuidado con al saldar ya que un error o distracción puede traer serias consecuencias como posibles cortos o falsos.

![PAART2](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/PART2.png)
--------------------------------------------------------------------------------------------------------
3.-Ajuste de motores y engranes.

Los motores del robot se ajustaran a los extremos de una lámina de metal que se pegara a la placa principal. A cada uno de los motores previamente se les ajusto los engranes que son los que van a dar la tracción sobre la superficie donde se coloque dicho robot.

![PAART3](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/PART3.png)

La parte de los sensores no es menos importante, se debe tener en cuenta la Distancia entre emisores y receptores, así como la polaridad adecuada en base al circuito.

Una vez soldadas correctamente todas las piezas se debe colocar la pila de 9Volts, y hay que verificar que los motores giren y en el sentido hacia dentro del robot. El Prototipo debe colocarse en un lugar plano asegurándose de que los engranes de los motores toquen totalmente la superficie así como los alambres que van en la parte frontal


![PAART4](https://github.com/LuisEduardoSanchezAlcantar/RobotSeguidordeLinea/blob/master/PIEZAS%20MONTADAS.jpg)


NOTA 1: Es importante que el fototransistor Q1 se encuetre protegido con algún plastificado, esto para que no sea afectado por las señales que generan los diodos que se encuentran a su alrededor.


NOTA 2: Los 2 sensores QRD deben de estar colocados a una distancia de ½ cm de distancia con ell piso, esto para que pueda realizar la lectura correcta de las líneas marcadas en la superficie.




