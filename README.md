PRIMER-PARCIAL-SPD
Primer parcial SPD 2023

Este código está hecho para funcionar en un proyecto en arduino UNO, si la temperatura y la luz ambiental están dentro de los requerimientos, el motor va a funcionar permitiendo que los pulsadores y el interruptor se habiliten. Estos botones tienen la capacidad de aumentar o disminuir los numeros mostrados en los displays, pero si el interruptor se activa, el display se reiniciará a 0 y mostrara el siguiente o anterior numero primo mas cercano.

Para su correcto funcionamiento, es necesario que a la placa arduino UNO esten conectados dos displays 7 segmentos, con sus respectivos leds conectados desde los pines 7 al 13. los displays tienen que estár configurados como catodo común, y para poder controlarlos individualmente como decena y centena el común del display de las unidades debe estar conectado al pin A5, y el de las decenas al pin A4. 
Para poder controlar la suma, la resta y el reinicio de los displays son necesarios 3 pulsadores, el de reset conectado al pin 5, el de aumento al pin 3, y el de disminución al pin 1. El interruptor deberá estar conectado a el pin 6. 
El sensor de temperatura deberá estar conectado a el pin analogico A0, y el Fotodiodo al pin A2.
El motor deberá estar conectado al pin 2.
