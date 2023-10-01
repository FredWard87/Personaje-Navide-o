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
|Placa Arduino|Placa Arduino grande para la conexión de placas y sensores|2|$360.00|
|SSD1306 pantalla OLED con Arduino|Controlador SSD1306 para pantalla OLED con Arduino y ESP8266. Las pantallas OLED no son más que eso| 1 | $89.00|
|Pack 5 servomotores|servomotor con movimiento de 180 grados para el brazo|2|$50.00|
|Soldador|kit de soldador para los motores y las piezas del muñeco|1| $90.00|
|WINGONEER 25 Valores 16V 25V 50V 1uF a 2200uF | Condensadores electrolíticos | 10 pz| $40.00|





## Software a Utilizar
|Nombre|Version|Tipo Software|
|-|-|-|
|Thonny|4.2.1|Software Libre|
|SSD1602|1.8.1|Software Libre|
|PlatformIO|6.1.11|Software Libre/IDE|

## Prototipo en dibujo

![Prototipo](https://github.com/ABOK451/Personaje-Navide-o/blob/main/imagen_2023-09-30_161949978.png)


## Comunicacion
El objetivo principal de este proyecto es llevar la tradición navideña y la representación del pesebre a un nivel tecnológico, brindando un ambiente cálido y festivo en la Universidad Tecnológica del Norte de Guanajuato. La idea es construir un pesebre interactivo en el que destaque un campesino con un cesto de uvas, incorporando movimiento y luces LED. Este proyecto no solo busca decorar el entorno, sino también cumplir con responsabilidades de enseñanza y aprendizaje.

## Arquitectura 
Sensor de Movimiento : Cuando el sensor detecta movimiento en su campo de visión, envía una señal de activación al microcontrolador ESP32.

Microcontrolador ESP32: El ESP32, al recibir la señal del sensor de movimiento, activa el LED y controla su color. Además, coordina las acciones para el movimiento de las manos.

LED: El LED se enciende y muestra un color morado cuando se activa. La elección del color puede ser configurada en el código del microcontrolador y, en este caso, se ha elegido el color morado.

Mano con Cesto de Uvas: Se implementa un mecanismo para simular el movimiento de la mano que sostiene el cesto de uvas. Esto podría ser un motor o algún mecanismo mecánico controlado por el microcontrolador.

Otra Mano Levantada: Se utiliza otro mecanismo para simular el levantamiento de la otra mano. Al igual que con la mano que sostiene el cesto de uvas, este movimiento puede ser controlado por un motor o algún mecanismo mecánico.

## Base de datos

