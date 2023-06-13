# PRÀCTICA 5: Sensor de temperatura i humitat
<div align=right>
Victòria Blanco Bosch
<div>
<div align=right>
Marcel Farelo de la Orden
<div> 
<div align="justify">

<div align="justify">
Esta práctica consiste en un sensor de temperatura y humedad que muestra los datos por un display y al mismo tiempo por una web asíncrona.
</div>

***

# Ejercicio 2
Se nos pide que realicemos un programa que utilice algún dispositivo I2C. En nuestro caso hemos montado un sensor de temperatura y humedad que muestra sus datos por un display y también por una web asíncrona. 
El sensor de temperatura HTU21D está constantemente leyendo valores por tanto la web debe ser asíncrona para que se vaya actualizando en todo momento.

## Material
- Sensor de temperatura y humedad HTU21D
- Display
- Cables 
- ESP32

## Montaje

<div align="justify">

 Hemos montado el dispositivo en una protoboard. Hemos hecho la siguiente asignación de pines: 

  - SDA del display y DA del Sensor --> 21
  - CLK del SDA y del Sensor --> 22
  - VCC a 3.3V

  No ha sido necesario conectar resistencias.
</div>

## Funcionamiento 

<div align="justify">
Cuando se pulsa en *Upload and Monitor* y se ejecuta el programa nos aparece por pantalla la IP de la web. A continuación tanto en la pantalla del ordenador como en el display podemos ir viendo cómo va variando la temperatura y la humedad en cada instante. Si escribimos la IP en el buscador podemos acceder a la web y ver también los datos que lee el sensor.
