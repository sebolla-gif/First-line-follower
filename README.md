# First-line-follower

## Descripción

Este proyecto consiste en un seguidor de línea básico que utiliza cinco sensores infrarrojos digitales para detectar una línea negra sobre una superficie blanca. Dependiendo de la lectura de los sensores, el robot ajusta la velocidad y dirección de sus motores para seguir la línea.

## Código

El código se encuentra en el archivo `Linefollower.ino`. A continuación se muestra una explicación de las partes más importantes del código:

### Definiciones de Pines

```c
#define m1 4  // Motor Derecho MA1
#define m2 5  // Motor Derecho MA2
#define m3 2  // Motor Izquierdo MB1
#define m4 3  // Motor Izquierdo MB2
#define e1 9  // Habilitación del Motor Derecho EA
#define e2 10 // Habilitación del Motor Izquierdo EB

//********** Conexión de los Sensores IR de 5 Canales **********//
#define ir1 A0
#define ir2 A1
#define ir3 A2
#define ir4 A3
#define ir5 A4
//************************************************************//
