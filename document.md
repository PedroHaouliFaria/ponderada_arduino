### Parte 1: Blink Led Interno  
> Essa `Parte 1` deverá ser realizada **antes da sua instrução de programação**. 

 Após instalar o Arduino IDE no meu computador. Realizei o "blink" com o LED Interno, as imagens estão na pasta assets, mas você também pode visualizar por aqui: 

 <img src='../assets/arduino_off.jpg'>
 <img src='../assets/arduino_on.jpg'>

Além dessas imagens, coloquei também um vídeo de demonstração:

[Assista ao vídeo](./assets/ponderada_arduino.mp4)


<br>
<br>

### Parte 2: Simulando Blink Externo
> Essa `Parte 2` pode ser realizada até sexta-feira.

Aqui está o link do meu projeto do Tinkercad:

[Acesse o TinkerCad aqui](https://www.tinkercad.com/things/l1tUoWue9Gp/editel?sharecode=_YbZGekHWwjFXWMxnF41u0DXea0W1tgicjHLPIhLsnc)


 E aqui está o código do Tinkercad:

 ```cpp
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
 ```


