	Son estructuras en las que nos basamos para hacer algo

## ¿Estaríamos hablando de algo tangible?

	El software es la parte intangible que no podemos tocar... Un modelo entonces 
	será precisamente una serie de estructuras, de pasos, algoritmos inclluso que 
	nos mostrarán cómo podemos hacer las cosas.

## ¿Cómo es posible quee un dispositivo pueda comunicarse conn otro que ni si quieras está cerca de nosotros?

	Cuando empezamos a estudiar cómo es que esto es posible y sigue siendo posible, 
	pues nos vamos dando cuenta de ello.

Mucha gente en lugar de referirse a la red de computadoras utilizan la palabra **ethernet...** con cables, equipos, switches, sitio de comunicaciones, ducterías, etc.

Los primeros que crearon un red para la compañia xerox. Los padres de la red hacen referenia a la sustancia del ether, algo así como la famosa piedra filosofal. Él decía yo se como comunicar las computadoras, y se quedó ahí dentro de xerox. Ahí él creo esa red, pero llega un momento en qué se preguntó como llamar a esto que él había creado.

## Histioria del **Ethernet**

Cómo es tan maravilloso que una compuatdora sinn que pegue a otra hay una transferencia de información, porque incluso los 0's y 1's son referencias de cosas que no podemos ver o tocar, entonces eso significa que la comunicación está pasando a través de esa "sustancia", pero me permitió conectar a dos compuatoras... Una comunicación del ether, que se ejecuta en esa sustancia que no veo/que no conozco.

## ¿Qué es la comunicación?


Mensaje de origen -> *transmisor* -> tramisión medio -> *receptor*-> mensaje de destino

Una cosa importante es la *codificació del mensaje*. Que uno lo pueda emitir y el otro lo pueda entender.

Cada segmento se encapsula en una mensaje por separado y se envia a través del medio, en elhoost de destino o receptor, los mensajes sufren el proceso inverso, se desencapsulan y se vuelven a unir para su procesamiento.

Hay tres tipos:

1. Unicast
2. Multicast
3. Broadcast

Estructuras que debemos seguir que nos van a decir cómo debemos comunicarnos. Estas reglas que rigen las comunicaciones es lo que llamamos **Protocolo**.

Estos nos lleva a los modelos de referencia, aquellos que tratan de explicarnos cómo dos dispositivos se comunican entre sí.

## **OSI** (Open System Interconnection)


*Capas de host*
1. Datos
	1. Aplicación: 
	2. Presentación:
	3. Sesión:
	   
2. Segmentos
	4. Transporte:

*Capas de medios*
3. Paquetes
	5. Red:
	   
4. Tramas 
	6. Enlace de datos:
	   
5. Bits
	7. Física:


>Puedo utlizar  **OSI** o **TCP/IP** para entender/explicar como dos cosas se comunican.

## Como ingeniero de software

> Conozco el modelo TCP para segmentar los paquetes que llegan en los cables y el IP para saber a quién les enviaré las cosas.


