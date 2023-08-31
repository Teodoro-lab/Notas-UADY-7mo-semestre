## Redes y Topología

### Modems que tienen la capacidad de ser routers

Los **modems** tienen la capacidad de funcionar como routers.

### Servidores y Topología física

En un lugar donde se encuentra el router, también hay **servidores de correo**, de archivos, web, y un **hub de aula** que concentra las computadoras de las aulas de clase.

### Diseño y cantidad de conexiones

¿Cuántas líneas de cable y cuántas computadoras hay?

### Topología lógica y protocolos

La **topología lógica** de una red involucra el direccionamiento de los protocolos que las redes utilizan, como TCP para formar los paquetes e IP para enviarlos (TCP/IP).

### Direcciones IP y enrutamiento

En el aula de clase, cada equipo tiene su **dirección IP**, lo que significa que no es necesario indicar el número de computadoras. Todo está concentrado en un equipo de tipo internet con dirección...

### Máscara de sub-red y ventajas

El **redireccionamiento IP** puede ubicar físicamente cercanos pero lógicamente en redes distintas debido a la **máscara de sub-red**, que tiene ventajas y desventajas de estar o no en la misma red.

### Tipos de Redes

- **LAN** (Red de Área Local): Red del laboratorio, área de laboratorios y facultad de matemáticas del campus de ciencias exactas.
- **WAN** (Red de Área Amplia): Interconexión de LANs separadas geográficamente, generalmente a través de un router.
- **MAN** (Red de Área Metropolitana): Conexión de LANs en un área metropolitana.

## Cableado y Estándares

### Cableado estructurado

El **cableado estructurado** es fundamental para el crecimiento de las redes. Debe cumplir con estándares como la norma TIA 568, que establece pautas para su instalación.

### Parámetros de Calidad

- Atenuación: Pérdida de señal en el cable debido a diversos factores. Es crucial mantenerla dentro de límites aceptables para una comunicación confiable.
- Diafonía: Interferencia entre cables cercanos. Debe ser controlada para evitar errores de transmisión.

### Condiciones Ambientales

El cableado debe mantenerse en un ambiente con temperatura y humedad controladas para garantizar su óptimo rendimiento.

## Medios de Transmisión

### Par Trenzado

El **cable de par trenzado no blindado (UTP)** y el **cable de par trenzado blindado (STP)** son comunes en redes. Los pares trenzados reducen la diafonía.

### Coaxial

El cable **coaxial** ha sido utilizado para transmisión de imágenes. Aunque tiene ciertas ventajas, su velocidad y ancho de banda son limitados.

### Fibras Ópticas

Las **fibras ópticas** permiten transmisión de datos a alta velocidad mediante pulsos de luz. Son inmunes a interferencias electromagnéticas.

## Estándares y Consideraciones

### Temperatura y Humedad

Los cables deben mantenerse en un rango de temperatura (18-24°C) y humedad (30%-55%) específico para asegurar su funcionamiento adecuado.

### Iluminación

El área de instalación debe tener una iluminación adecuada, siguiendo las recomendaciones de luminosidad.

### Codificación de Colores

Cada hilo en un cable de red tiene un color diferente, lo que facilita la identificación y conexión correcta de los cables.

### Normas de Seguridad

Hay que tener vigilancia continua, todo lo que esté dentro del sitio de comunicaciones, como los rags, todos los tornillos y as casacaras de los servidores, todo debe de estar conetado a tierra, de forma que si hay una descarga eléctrica, no se dañe el equipo.

Todo sobre voltaje debería de irse a la tierra física. La tierra física es algo que tiene una resistencia muy baja, para que si hay una descarga eléctrica, la corriente se vaya a tierra.

También podemos evitarlo utilizando reguladores, el rack es una estructura pasiva que no está conectada de forma que si chocamos con un cable con corriente puede elecrocutarnos.

### Conector RJ-45

El conector RJ-45 tiene 8 canales o microcanales por los que debemos introducir los 8 hilos de cobre del cable, pero no vamos a poder introducir los 8 cables como nosotros querramos sino como nos dedica el estandar 168 de IAEIA, es una forma de saber cómo debemos de meter los cables para meterlos en el RJ-45.

El RJ-11 También lo podemos utilizar para redes, pero no es tan común, es más común para teléfonos.

Hay cables directos ethernet, esa es su denominació general, ethernet es sinonimo de red ethernet, de cable ethernet(utp, stp, rj-45, red de cable) y cable cruzado ethernet. Si nosotros queremos conectar dos computadoras entre ellas no podemos tener una caable directo de ethernet, cable naranja con cable naranja sino que tenemos que hacer un "cruzado ethernet", que en un extremo el 568A y en el otro el 568B.

Cuando haces plug de dos computadoras con un cable que viene hecho a veces no funciona es porque no están configurados los extremos.

El par 1 se mantiene siempre en su lugar, el par 2 y el par 3 se cruzan, el par 4 se mantiene en su lugar.

Los pares en el cableado UTP que cambian son precisamente donde se transmite y donde se recive. Si están uno a uno, cuando una máquina ponga info en el par que transmite pues estará llegando en el par que transmite del otro lado.

Esto solo ocurre cuando los conectas directamente, si te preguntas porque no ocurre cuando tienes multiples computadoras conectadas a un switch, es porque precisamente es el swith el que se encargar de hacer el cruce.

### Fibra Óptica

Estos cables tienen un nucleo, que es el filamento de vidro por el que va a pasar la luz. Tiene un recubrimiento de protección, material de refuerzo y finalmente el revestimento.

- **Mono-modo**: Un solo rayo de luz. Tine un diametro de 9 micrones.
- **Multi-modo**: Varios rayos de luz. Tiene un diametro de 50 o 62.5 micrones.

1 micra = 1 micrometro = 1 millonésima de metro = 1/1000 de milimetro.

La luz ya no se transmite por medio de electrones, sino por medio de fotones, que son partículas de luz. La luz se transmite por medio de pulsos de luz, que son los que se encargan de transmitir la información.

Si no tenemos cuidado al cortar la fibra optica, por ser tan delgado puede que entre a nuestro cuerpo y ni lo vamos a sentir, pero es un pedazo de vidrio que si entra a nuestro cuerpo pues muy fácilmente entra a nuestro torrente sanguineo y corta alguna de nuestras venas y empieza a viajar... sus puntos van haciendole cortes al lugar donde esté viajando.

> Si vemos que están haciendo ensambles y muchas veces tenemos que hacer que se conecten los acopladores de las fibras de vidrio, para hacer esto tenemos que hacer cortes del revestimiento de la fira que es lo que nosotros vemos.

Hay cables multifibras, lo que estamos viendo de colores no es la fibra, sino el revestimientos del filamento de vidrio que está adentro. La fibra es todavía más delgado que esto.

### Medios inalambricos

- #### Bluethot

  - Para cortas distancias, no puede tener mayores alcances que 100 metros .

- #### WiFi

  - Wireless Fidelity: Podemos alcanzar grandes anchos de banda a través del aire.

### Jack RJ-45

En estos es donde el plug RJ-45 entra. Esto es lo que se tendría que hacer cuando tenemos un corte de cablle UTP. Podemos unir los 8 cables, pero no conviene, en un extremos cono car uno y otro y hacer el acoplamiento.
