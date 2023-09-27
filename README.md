# Sist.Embebidos-Invernadero
Simulación de Sistema de Riego y Ventilación de un Invernadero con Arduino y Proteus.

Objetivo:

Aprender a implementar distintos dispositivos de E/S en Arduino IDE y simularlo en Proteus, adquiriendo conocimientos en programación de microcontroladores y simulación de sistemas embebidos.

Requisitos mínimos:

Computadora con Arduino IDE y Proteus instalados
Arduino UNO 
Leds (Verde y rojo)
Resistencias (220 Ω)
Relays
Motor AC
LCD 16x2
DHT 11

![image](https://github.com/Gisecy/Sist.Embebidos-Invernadero/assets/96145942/a74ce71d-0a1a-4f5e-96af-6d5bc9beb3a7)

Programación:

El estudiante en el desarrollo de su programación deberá tener las siguientes consideraciones:

•	El objetivo del proyecto es poder automatizar un invernadero que, de forma automática, controlará el estado de la temperatura y la humedad del lugar.

•	El sistema testeará de forma continua la temperatura y humedad mediante el sensor DHT11.

•	Si la temperatura es igual o superior a 25 grados centígrados, deberá encenderse de manera automática un motor ventilador. Cuando la temperatura descienda el motor se apagará.

•	Si la humedad del lugar es menor o igual a 40%, deberá encenderse de manera automática el sistema de riego (bomba de agua) y paralelamente el verde. Cuando la humedad ascienda el sistema de riego se apagará y paralelamente se apagará el led verde y se encenderá el led rojo.



