# Controlar un LCD
# Simulación con Ardiuno.
## *INTRODUCCIÓN*
Esta práctica trata de comprender el funcionamiento sobre un elemento electrónico que es muy importante en la actualidad, ya que este combina la electrónica con la programación y es muy utilizado en proyectos e inventos que hay actualmente, nos enfocaremos en una practica exclusivamente para el control de un LCD, por la cual lo realizaremos mediante el simulador en línea (Tinkercad) explicando paso a paso de como se debe hacer y teniendo en cuenta la programación que es uno de los factores mas importantes para que se realice correctamente el control perfecto del LCD.
## *OBJETIVOS:*

# Objetivo general
- Diseñar un circuito electrico en el cual se pueda controlar un LCD

# Objetivos específico
- Comprender el procedimiento de como controlar un LCD y su funcionamiento con Ardiuno
- Aprender sobre este nuevo elemento electrónico.

## *LISTA DE MATERIALES:*

| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Arduino |
|  1 | Resistor de 220  |
|  1 | LED    |
| 1  | Protoboard      |
| 1  | LCD      |
| 1  | Potenciómetro     |
## *MARCO TEÓRICO*
¿Que es Ardiuno?

El ardiuno se caracteriza por ser una plataforma electrónica de código libre, la cual está basada en hardware y software libre, flexible y fácil de utilizar para los creadores y desarrolladores.Esto permite crear todo tipo de microordenadores de una sola placa, en el cual se puede dar diferentes tipos de uso.
En otras palabras tambien se lo considera como un hardware libre , donde los dispositivos y diagramas son de acceso público para toda persona, entonces puede haber réplicas de los mismos.

Se puede decir que ardiuno ofrece las bases para que cualquier persona o empresa pueda crear sus propias placas, pero siempre van a partir de la misma base.

El software libre son los programas informáticos donde los códigos son accesibles para todas las personas y esto a su vez pueden modificarse, tambien ofrece la plataforma Arduino IDE (Entorno de Desarrollo Integrado), donde se realiza todo lo antes mencionado, que tenga que ver con la programación.


![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/arduino.jpg)

Fig 1. Arduino.

¿Como funciona?

Este elemento electrónico es una placa basada en un microcontrolador ATMEL, los micocontroladores son circuitos en los cuales se pueden indicar instrucciones , pero eso se lo hace con lenguaje de programación donde utilizamos el enterno Arduino IDE. Esas instrucciones son las que nos permiten crear programas que interactúen con los circuitos dentro de la placa.

El microcontrolador de Arduino posee lo que se llama una interfaz de entrada, que es una conexión en la que podemos conectar en la placa diferentes tipos de periféricos. La información de estos periféricos que conectes se trasladará al microcontrolador, el cual se encargará de procesar los datos que le lleguen a través de ellos.

También cuenta con una interfaz de salida, que es la que se encarga de llevar la información que se ha procesado en el Arduino a otros periféricos. Estos periféricos pueden ser pantallas o altavoces en los que reproducir los datos procesados, pero también pueden ser otras placas o controladores.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/como%20funciona.jpg)

Fig 2. Funncionamiento del Arduino.

¿Que es un LCD?

Es una pantalla plana que contiene un liquido entre dos placas de vidrio , por esta pasa una corriente electrica en una zona determinada , para asi contrarestar la claridad que esta pueda tener, es decir se vuelve opaca y tiene iluminación trasera.

Estas son de color, cada pixel individual se divide en tres secciones o sub pixeles con los colores RGB (rojo, verde y azul), entonces cada pixel puede producir la variedad cualquiera de combinaciones de colores. 

![alt text](https://github.com/Kevi7k/Trabajo2derecuperacion/blob/master/Imagenes/display2x16.png)

Fig 3. LCD

Caracteristicas de un LCD.

En la actualidad existen gran variedad de proyectos con los LCD, por lo que combinar y crear a partir de sus caracteristicas es muy importante , así estas en una buena combinación, pueden crear un gran trabajo.

Tamaño:

El tamaño de un panel LCD generalmente se mide a lo lardo de su diagonal, expresado generalmente en pulgadas. Sin embargo existen más características que pueden describir las dimensiones aproximadas, como por ejemplo la LCD 16×2 se refiere a que tiene la capacidad de tener al mismo tiempo 16 caracteres de manera horizontal en y dos de manera vertical.

Resolución:

Esta se expresa con las dimensiones horizontal y vertical. las pantallas HD tienen una resolución de 1920×1080 por ejemplo. Y esta puede alcanzar con esta resolución una gran variedad de tamaño, pero si no se ocupa gran a gran detalle esta, estarías desperdiciando calidad (por no utilizar algo que tienes disponible).

Brillo:

La luminosidad de la pantalla también es importante analizarla, ya que según la aplicación en la que se encuentre esta, requerirá más luz para poder apreciarse, o viceversa. Por lo que la mayoría cuentan con una luz trasera y la posibilidad de poder controlar su luminosidad.

Contraste:

Es la relación entre la intensidad más brillante y la más oscura.

Por último los tamaños estándar que tienen los LCD son: 16×2, 20×4, 8×2.

![alt text](https://github.com/Kevi7k/Trabajo2derecuperacion/blob/master/Imagenes/caracteristicas%20LCD.png)

Fig 4. Caracteristicas de un LCD
## *PROCEDIMIENTO*

1. Entrar al programa en linea de tinkercad y colocar todos los materiales que vamos a utilizar:

![alt text](https://github.com/Kevi7k/Trabajo2derecuperacion/blob/master/Imagenes/LCD1.png)

2.Armar el circuito:

![alt text](https://github.com/Kevi7k/Trabajo2derecuperacion/blob/master/Imagenes/LCD2.png)

3.Colocar el código respectivo, para su programación:

![alt text](https://github.com/Kevi7k/Trabajo2derecuperacion/blob/master/Imagenes/LCD3.png)

4.Comprobar su funcionamiento

![alt text](https://github.com/Kevi7k/Trabajo2derecuperacion/blob/master/Imagenes/LCD4.png)


## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Trabajo2derecuperacion/blob/master/Imagenes/Diagrama.png)

Fig 5. Diagrama Modelo para controlar un LCD


## *EXPLICACIÓN DEL CIRCUITO*
Para una explicación totalmente detallada diríjase al siguiente enlace https://www.youtube.com/watch?v=JsLtotmFYs8&t=2s

## *CONCLUSIONES*

- Al realizar esta practica, se puede decir que esta es muy importante, como base para tener un concepto o idea de como la programación se mezcla con la electrónica.

- Se pudo notar la gran importancia de este dispositivo electrónico (Arduino) combinado con la LCD que nos puede llegar a hacer muchos proyectos mas interesantes.

- Esta practica, va mas allá de lo aprendido en clase, por lo que es un trabajo extra muy interesante para querer aprender más.

## *RECOMENDACIONES*
- Seguir paso a paso las indicaciones establecidas , para así realizar un buen trabajo.

- Poner en practica la teoría de clases para así relacionarlo con esta practica.
