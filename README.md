# Segundo Parcial SPD - Sistema de incendio con Arduino
![preview-segundo-parcial-spd](https://github.com/TomasSassone/SegundoParcialSPD/assets/72427373/8cd6672f-d2e1-4957-9241-b727c0908891)


## Alumno 👦
Tomás Santiago Sassone - 1°D

## Descripción 📓
El objetivo de este proyecto es diseñar un sistema de incendio utilizando Arduino que pueda
detectar cambios de temperatura y activar un servo motor en caso de detectar un incendio.
Además, se mostrará la temperatura actual y la estación del año en un display LCD.

El circuito que creé hace uso de un sensor de temperatura para mostrar en el display LCD la temperatura
ambiente, la cual es además utilizada para determinar la estación del año.
Al alcanzar los 60°C de temperatura, el display emite un mensaje de alerta por incendio y se enciende el
servomotor, que actua a modo de "rociador" para apagar el fuego. Además, se hizo uso de dos LEDs. El LED
verde estará encendido cuando la temperatura sea segura. Caso contrario, este se apagará y se encenderá
el rojo para alertar del peligro.
Todo el sistema puede encenderse o apagarse haciendo uso del control remoto. Solamente hay que presionar
el botón rojo para controlar el circuito.

1. **Componentes necesarios:**
    • Arduino UNO
   
    • Sensor de temperatura
   
    • Control remoto IR (Infrarrojo)
   
    • Display LCD (16x2 caracteres)
   
    • Servo motor
   
    • Cables y resistencias según sea necesario
   
    • Protoboard para realizar las conexiones
   
    • Dos LEDs.
    
    
3. **Conexiones:**

    • Conecta el sensor de temperatura al pin analógico A0 de Arduino.
   
    • Conecta el control remoto IR al pin digital 11 de Arduino.
   
    • Conecta el display LCD utilizando los pines correspondientes de Arduino.
   
    • Conecta el servo motor a uno de los pines PWM de Arduino (por ejemplo, pin 9).
  
  
5. **Documentación:**

    • Deberán presentar un diagrama esquemático del circuito y explicar el funcionamiento aplicado de cada componente.
   
    • Presentar el código fuente del proyecto de Arduino listo para ser implementado.
   
    • Deberán explicar el funcionamiento integral utilizando documentación MarkDown.




## Diagrama esquemático del circuito

![diagrama](https://github.com/TomasSassone/SegundoParcialSPD/assets/72427373/a26034d1-afbb-4fdc-be5c-b8c41ce430b6)

[Link al PDF del diagrama](https://github.com/TomasSassone/SegundoParcialSPD/files/11811692/2do.Parcial.Practico.Domiciliario.-.Sassone.-.1D.pdf)

## Link al proyecto 🤖
[Tinkercad](https://www.tinkercad.com/things/9qcenp0bgle-smashing-fyyran-kieran/editel?sharecode=7R-f8tYm2bGuDb0qvD2MaP91i2xPqwNEmHte011fbn0)

[GDB](https://onlinegdb.com/IDYPrZcCG)

## Fuentes 🔍
[Controlar display LCD con control remoto IR](https://www.youtube.com/watch?v=7jjwKB-lI50&t=438s)

[Display LCD](https://naylampmechatronics.com/blog/34_tutorial-lcd-conectando-tu-arduino-a-un-lcd1602-y-lcd2004.html)

[Cómo utilizar breadboards](https://www.youtube.com/watch?v=MojSo7OtF9w)
