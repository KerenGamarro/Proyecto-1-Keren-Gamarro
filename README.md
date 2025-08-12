# Proyecto-1-Keren-Gamarro
# Utilizando el microcontrolador ESP32
Con este proyecto se busca que el estudiante experimente y aplique los
conocimientos adquiridos del curso integrando un sistema de monitoreo de
temperatura.
# Parte 1 Sensor de Temperatura. 
Diseñe e implemente una rutina en el cual
mediante un botón pueda adquirir la señal de un sensor de temperatura LM35
utilizando un ADC.
# Parte 2 Semáforo de Temperatura. 
Diseñe e implemente tres señales PWM para
controlar un LED RGB o en su defecto 3 leds de color Rojo, Verde y Azul en donde
dependiendo de la temperatura colocará un color indicador.
     Temperatura        Color de semáforo
t < 22.0 °C                 Verde
22.0 °C < t < 25.0 °C      Amarillo
t < 25.0 °C                 Rojo
# Parte 3 Reloj del semáforo de temperatura. 
Diseñe e implemente una rutina la
cual dependiendo del valor de la temperatura obtenida mueva la posición del eje
de un servo motor modelando un reloj de temperatura que vaya de la mano con
el semáforo de temperatura.
# Parte 4 Despliegue de temperatura:
Diseñe e implemente una rutina para desplegar el valor de temperatura en 3
displays de 7 segmentos. Utilice el punto del primer display para desplegar un
decimal. Utilice multiplexeo para poder desplegar en los 3 displays con ayuda de
transistores. Tome en cuenta que el circuito puede llegar a cambiar dependiendo
si tiene displays de ánodo común o cátodo común.
https://deepbluembedded.com/multiplexing-7-segment-displays-3-digit-7-
segment-interfacing-with-pic-microcontrollers/
# Parte 5 Dashboard Adafruit IO:
Diseñe una interfaz en los servidores de Adafruit IO, en donde pueda mostrar el
resultado de los valores obtenidos del sensor de temperatura.
# Parte 6 ESP32 WIFI:
Implemente la comunicación entre el ESP32 y los servidores de Adafruit IO,
utilizando WIFI. El ESP32 deberá ser capaz de mandar los valores obtenidos del
sensor de temperatura y el reloj de temperatura.

