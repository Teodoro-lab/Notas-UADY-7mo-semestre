Para medir algo dentro del contexto de la disciplina pueden tomar muchos años. Podríamos decir que construimos barccos en la ingeiería de software y pues andan divagando en el mar y algunas veces todavía se pierde.

## ¿Qué es la medición?

**La medición en el software es crucial:** los procesos fueran mejores y por lo tanto mejorar los procesos.

La medición es un proceso por el cual asignamos un numero o un simbolo a un atributo del mundo real o fenomeno software que estamos viviendo y lo hacemos a través de reglas. En consecuencia el **valor**~~la medida es ese simbolo o numero que le asignas al atribbuto de la entidad que quieras medir.~~

	La medición de una variable es la asignación de acuerdo a una regla que 
	nosotros que adoptemos un valor al fenomeno denotado por la variable - Kaplan 
	1998

La duración está relacionada con el tiempo, entonces intetnamos asignar ciertos días, semanas, etc. pero hay que acordarlo. Si decimos que una tarea la hicimos en 30 día ¿Qué significa eso en terminos de semanas? ¿Lo podemos convertir?

Por ejemplo si trabajamos 40h a la semana, debemos dejar de contar desde que se nos aceptó el proyectto, todo eso hay que definirlo. Por ejemplo cuando trabajas 80 horas a las dos semanas te pagana las 2 semanas, no las 80 horas.

Debo ser capaz de medir el efecto que tiene la variación entre las distintas salidas del factor, tengo que medir cuál fue el facor en la variable respuiesta. Es cetroal la medicion en los **estudios empiricos**.

**La teoría de la representación de la medicion** intentar tratar de expresar de forma numérica el mundo formal, las entidades del mundo real o mundo empírico y la correspondencia entre ambos mundos.


## Entidades de ingeniería de software

En general podemos decir que donde hay recursos humanos, los ingenieros de software con sus diferentes roles, recursos económicos y los otros recursos como tecnológicos. ***Procesos, recursos y artefactos*** puedo medir.

La entidad es lo que será caracterizados y finalmente medido.

- Entidad: *Código*
	- Atributo: *Tamaño* (no es lo mismo que el tamaño del software) si mido el software pueden ser funcionalidades, si mido el código suelen ser la lineas de código.

La medida es resultado de la medición, voy a llegar a las 320 lineas de código, lo mismo que si digo otra medida como 

Si voy contando obtengo la medida, pero qué tal si hablo de la densidad de los comentarios... Tal vez tenga que calcular dos cosas, hacer una operación y obtener el valor, entonces eso es una medición.

### En IS la métrica en nuestro contexto tiene dos significados:

-  Como un termino para denotar el campo de la meidción.
-  Como medida de algo, como sinónimo de medida.

Hay métricas que están directas y otras que no son tan directas como el expertiz del desarrollador del software (Cualitativo).

Hay otras mediciones como el esfuerzo, no es cuali ni cuanti, sino que es a através de una fórmula. 

**La escala de medición**, tiene un conjunto de posibles valores que puede adquiri el atributo que estoy obteniendo a través de esa formula. Es unConjunto de valores con relgas de manipiulación, estas reglas deben de tener un significado en el mundo real. Este signficaido en el mundo real viene capturado por las transformaciones que preserven las tranformaciones de la escala.

	Mientras más tranformaciones me permita la escala, mayor información puedo   
	obtener.

	 Los valores que asignemos deberían tener sentido en el mundo real y sus 
	 transformaciones también deberían de tener setndio en el mundo real.

El conjunto de transofmraciones que son admisibles por una escala, el conjunto de sentencias que son realies cuando usas una escalay el cinjunto de oepraciones que puedes realizar entre si cuando utilizas una escala definienen ell *Nivel de medción de una escala*, 

Entonces buscamos una escala con el mayor numero de transofmraciones admisibles, el robblema es que no las podemos inventar nosotros, el fenomeno ya tiene un máximo de medición.


## Tipos de escalas 

1. **Nominal:** Diferentes fenomenos reciben etiquetas(valores) distintos, y podemos probar la (medición) si dos fenómenos han recibido la misma etiqueta o una diferente. 

> ***La tipología de la escala sí está bien como ejemplo de ecala nominal, pero no es un recurso.***
   
1. Los nombres en sí mismos no son significativos, lo importante es lo que 
	significa el color. Su identidad y diferencias sí son significativos.	   

2. Las *transformaciones admisibles* es el conjunto de las transformaciones uno 
	a uno, ya que los valores específicos no transmiten ninguna información en 
	particular, si son iguales y diferentes no te dice más, ni qué tan diferentes 
	ni qué tan iguales.

2. **Ordinal:** Establece criterio de orden, sin embargo la distancia entre los valores ordenados no tienen sentido físico. 
	- Ejemplo: **CMMI** (*Inicial*, *Gestionado*, *Definido*, *Gestionado* *Cuantitativamente*, *Optimizado*)
	- Mis tranformaciones admisibles:
		- Mayor que ...
		- Menos que ...
		- Más complejo que...

3. **Escala Intervalo**: La distania entre intervalos es conocida y siempre es la misma, la diferencia entre las medidas es significativa, pero no el valor en si. No tienen un valor inicial o cero absoluto.
	1. Hay fenomenos en los que el 0 no tienen sentido.
		- cuando hablas aquí el proyecto A inicio el 1 de sieptiembre, el proyecto B quedebería de iniciar en ahosto, se retrasó hasta el 8 de agosto. No tiene sentido decir que el proyecto B se atrasó el donle de tarde que el A.
		  
	2. Subconjunto de funciones monotonas de tipo *m' = am + b*. 

4. **Escala de razón**: Escala del nivel más alto de medición, si las medidas son signifcativas se escala proproción. Permite definir relaciones coherentes con os valores de la escala.
	1. Todas las operaciones admisibles.

En cuanto a los indicadores:
- *Nominal* puedo saber la moda.
- *De orden* puedo saber el orden
- *Intervalos* media arimética
- *Razón media* mode-median-arithmetic mean-geométrica mean

Hy cosas en las que todavía no hay métricas  y para eso tenemos que hacer nuestras métricas

## Tipos de métricas( **Directas - Indirectas** )

*Directas*: Las hacemos directamente, sin necesidad de aoyarnos de otro atributo de esa entidad. 

> Si mido la altura no mido su pelo o su peso, simplemente mido de sus pies a su cabeza

*Indirectas*: Tengo que hacer uso de otro atributo, con base en la medición de varios atributos puedo obtener la medición de esta métrica.

## Tipos de métricas( **Objetivas - Subjetivas** )

>En función del proceso

*Medidas Objetivas*: Medidas cuyo valor no depende del observador(esfuerzo).

*Medidas subjetivas*: Son aquellas en las que la persona que realiza la medición puede introducir factores de juicio en el resulatdo ___(expertiz del programador)___.

## Tipos de atributos

*Atributos internos*: pueden ser medidos a partir del producto, proceso o recurso.

*Atributos externos*: Son aquelos que los relacionan con el entorno

#### Explicación 

>Como dependen del entorno, sí son objetivos, pero tengo que hacer un mecanismo para evaluarlo, muchas cosas en el contexto dependen del humano, del uso del humano, un técnica, un método, una aplicación "¿Está fácil de usar o no?" Hasta que alguien la utilice es que te darás cuenta de ellos. El atributo interno podrá ser el numero de elementos que te muestra en un momento dado, porque si te los está mostrando en la pantalla los cuentas.

## Productos */* Artefactos

Son artefactos que se entregan al finaliza una actividad, una tarea, una fase. Son entregables.

> El producto resultante de la fase de requermientos es un documento, pero es un texto al final de cuentas... El de la fase de diseño será un documento, pero de diagramas. El producto resultante de la fase de códificación es el código. 

- Archivos ejecutables
- Código
- Texto
- Diagramas

> En el externo es porque depende de quién lee el documento, en el código es porque la solución que le das en el código... el código como tal implementa la solucion y eso puede ser sencillo o complejo, pero el diseño es un documento que vas a revisar.

## Recursos  

Cualquier entrada de una actividad

Hoy día está a $300, al que se lo van a vender no sabe ni siquiera si tiene carretera, catastral cuesta $300, te pagan menos y lo venden a más, entonces es algo que depende de quien tenga el dinero.

## Medidas del producto: atributos internos

*Tamaño del sistema:*
	LOC, Densidad de comentarios(DOC), Puntos funcion(PF).

> Los PF son indirectos, internos, objetivos.

> La complejidad ciclomática es indirecta, objetiva, ~~interna~~.

## Precisión en la medición

Dos conceptos:

1. Es el tamaño de la **unidad más pequeña de una métrica**; dicho de otra manera, es el número de digitos significativos que se pueden informar.
   
 La combinación arimética de medidas propaga y magnifica el error inherente a los valores originales. Por lo ranto **la suma de dos medidas tiene menos precisión que cualquiera de las dos**, su proporcion aún menor; esto debe tenerse en cuenta al crear una métrica compuesta.
   
2. El concepto de precisión es el inverso de variabilidad: las mediciones deben de ser **consistentes en observaciones repetidas en las mismas circunstancias**. Esta propiedad se determina **fiabilidad(confiablidad)** en la teoría de la medición.   

> Te preguntan dos veces lo mismo con palabras diferentes, si se refier a lo mismo entonces son confiables sus respuestas, son consistentes. 

## Validez
  
> Imaginense que quiero sacar la cmplejidad en base al núero de comentarios... eso no es complejidad, tal vez es legibilidad, pero no complejidad. 
> **La validez** es que lo que estás midiendo corresponde realmente a lo que estás midiendo.

- La **validez de criterio** es el grado en que una métrica refleja la relación del objetio medido con algun criterio.

- La **validez de constructo** es el grado en el que una métrica mide realmente la entidad conceptual de interés. 

## En el contexto de IS y experimentación...

... establecemos causa-efecto, y esto nos dará validez a nuestros proceso experimental, establecemos el grado de influenccia de una variable sobre otras. Para medir ese grado de influencia necesitamos utilizar alguna de esas cosas, el efecto que tiene una cosa sobre otra cosa.

Necesito que solo varien los objetos que estoy modificando. Un error comun en los estudios de correlación, cuando cambia una cambi otra, pero no porque una cambió cambió la otra.
Si soy más alto tengo más peso, pero mi altura no es una causa del peso.

Modificando los valores de una variable mido los efectos en las otras variablees, *nos interesan varaibles dependientes en una escala de razón.*

