## Personaje-Navideño


## Nombre del personaje 

-Campesino con Cesto de Uvas 

##  Nombre Integrantes Equipo

|Nombre | Apellido Paterno | Apellido Materno |
|-|-|-|
|Fredy Alonso|Esparza|Campuzano|
|Alan Omar|Venegas|Cadena|

## Materiales a utilizar


|Nom Componente | Descripcion | Cantidad| Precio|
|-|-|-|-|
|ESP32|Microcontrolador con 30 pines con comunicacion WIFI y Bluetooth||$140.00|
|Cable dupont|Cables para conexion de prototipos de pruebas|50|$60.00|
|Sensor Pir Hc-sr501|Detector De Movimiento|2|$55.00|
|Led|Se utiliza un LED como indicador visual.|10|$70.00|





## Software a Utilizar
|Nombre|Version|Tipo Software|
|-|-|-|
|Thonny|4.2.1|Software Libre|
|SSD1602|1.8.1|Software Libre|
|PlatformIO|6.1.11|Software Libre/IDE|

## Prototipo en dibujo

![Prototipo](https://github.com/ABOK451/Personaje-Navide-o/blob/main/imagen_2023-09-30_161949978.png)


## Comunicacion


## Arquitectura 
Sensor de Movimiento (PIR HC-SR501): Cuando el sensor detecta movimiento en su campo de visión, envía una señal de activación al microcontrolador ESP32.

Microcontrolador ESP32: El ESP32, al recibir la señal del sensor de movimiento, activa el LED y controla su color. Además, coordina las acciones para el movimiento de las manos.

LED: El LED se enciende y muestra un color morado cuando se activa. La elección del color puede ser configurada en el código del microcontrolador y, en este caso, se ha elegido el color morado.

Mano con Cesto de Uvas: Se implementa un mecanismo para simular el movimiento de la mano que sostiene el cesto de uvas. Esto podría ser un motor o algún mecanismo mecánico controlado por el microcontrolador.

Otra Mano Levantada: Se utiliza otro mecanismo para simular el levantamiento de la otra mano. Al igual que con la mano que sostiene el cesto de uvas, este movimiento puede ser controlado por un motor o algún mecanismo mecánico.

## Base de datos

