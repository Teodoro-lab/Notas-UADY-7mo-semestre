
Dirección de local host, pruebas de conectividad: *120.0.0.0*.

En nuestras casa hay algunos de los direccionamientos privados que se manejan para darle dirección a nuestras redes:

- 10.0.0.0 - 10.255.255.255
- 192.0.0.0 - 192.168.255.255 -> sería de clase C poreque el rango es de **192-223**, pero a su vez es una dirección privada de la clase C.
- 172.16.0.0 - 172.16.0.0.

Hay un rango de direcciones privadas en clase A, si es de clase A para empezar con 10 en el primer octeto y si es ded clase B con 172.

Por definiciónn del protocolo IP estas son direcciones privadas, pueden ser utilizadas dellado de nuestra red. Del otro lado la coneción del internet service provider nos permite conectarnos con internet.

**¿Qué permite esto?** Que se utilicen direcciones del protocolo IP, que hacen que toda una red privada pueda funcionar sin tener que usar direcciones IP ublicas las cuales al ser privadas no van a hacer tomadas en cuenta enn el lado publico(internet). incluso puede ser un tema si logramos filtrar alguna direccion privada y es que el network address translator(NAT) es lo que permite que estas direcciones que están del lado privado no puedan pasar hacia el lado publico que es internnet.

El nat lo va a destruir si es que la IP privada llega a pasar.

Enotonces como es que tenemos internet en el lado privado, eso es por el modem que además de ser demodulador también es enrutador y network address translator. Cualquier dirreción que pueda tener nuestra computadora, cuando hace petición a un servidor een el lado publico primero llega al modem.

Entonces el paquete que esta le envio para intentar contactar a google, en la parte correspondiente al host origen cambia la IP a una dirección publica. Llegando a su desstino le ocntentas con la información que esta requiriendo, llega al modem, como el modem sabe qué computadora pidió la información se la da.

de 1 a 126 identificamos que es de clase A, el 127 reservado, B si es ...

El identificador de la red es el primer numero de la IP, para la B son los dos primeros dos numeros y para la C los primeros 3 numeros de la dirreción Ip son los identificadores de la red, el resto identifican el HOST.

La caracteristica entonces el identificador de la red para todas las computadoras de la red tiene que ser el mismo y no puede cambiar, eso es lo que nos dice que están en la misma red.

En una clase podemos tener 126 redes, porque tenemos disponible el primer numero, pero como el rango tiene que ser hasta 126 entonces podemos tener esas 126 redes.

Tenemos una estructura que nosotros tenemos que dar, por lo tannto si el primer numero w representa el Idd de la red en una clase a entonces la estructura de este identificador de la red será w.0.0.0 es por eso que podemos tener hasta 126 identificadores de red...

1.0.0.0
2.0.0.0
3.0.0.0
4.0.0.0
...
126.0.0.0 

12.0.0.0 es mi red numero 12 de clase A, porque está entre los 126 nummeros para el primer octeto.

En cambioo en una clase B me sirvven los numeros 128 a 191 en el primer octeto, porque el primer numero esta en el ranggo de las clases B, aquí también habrá que mencionar a los primeros dos digitos para identificar a la red.

en al red 172.16.0.0, la dirección 172.16.53.46 es un host identificado por los numeros 53.46.

Una red de clase C sería con la w.x.y para la red y la z será para el host.

## subnetting

