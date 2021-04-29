# Blumen_Touch
O projeto Blumen Touch, é uma solução IoT baseada no ESP8266 com o objetivo de popularizar sistemas de automação residencial de baixo custo.
<h2><b>Introdução</b></h2>
Blumen Touch é um interruptor wi-fi baseado no ESP8266 suportando até 3 botões e 3 relés de estado sólido que suportam 2A cada, 
permitindo controlar até 3 circuitos de iluminação independentes. O Blumen touch foi desenvolvido para ser instalado em caixinhas
4x2, padrão brasileiro, substituindo assim o interruptor padrão que esteja instalado. O controle pode ser feito via comando de voz, via web, smartphone ou manualmente pelos botões.
<h2><b>Diagrama de fiação </b></h2>
<u1>
  <li> Ligação dos fio para os modelos B1, B2 e B3 </li>
  <img src="https://user-images.githubusercontent.com/76061000/115427318-c0d29980-a1d7-11eb-839f-0ce94e1b56d8.png" height="500" width="800">
  
  <u1>
   <h2>


<h2><b>Bibliotecas necessárias</b></h2>

|  <b>Nome</b> |  <b>Link</b> |
|---|---|
| ArduinoJson  |<a href="https://github.com/bblanchon/ArduinoJson/">GIT</a>  |     
|  WebSockets | <a href="https://github.com/Links2004/arduinoWebSockets/">GIT</a>  |  
| Sirincpro  |  <a href="https://github.com/sinricpro/esp8266-esp32-sdk/">GIT</a> |   
| WifiManager  |<a href="https://github.com/tzapu/WiFiManager/">GIT</a> |   

<h2><b>Hardware</b></h2>
<u1>
  <li> Blumen Touch Placa 1, 2 e 4 teclas frente e trás</li>
  <img src="https://user-images.githubusercontent.com/76061000/116568709-147f6a00-a8df-11eb-8aea-b58aba7be3df.png?w=512" height="407" width="1408">
  <img src="https://user-images.githubusercontent.com/76061000/116570529-b784b380-a8e0-11eb-9eb2-932ed905539e.png?w=512" height="380 width="1408">
  
  <u1>
   <h2><b>Suporte para placa</b></h2
     
 <u1>
  <li> Suporte (PLA) e espelho (acrilico) </li>
<img src="https://user-images.githubusercontent.com/76061000/116569564-e2bad300-a8df-11eb-94ad-c3b87ec8adff.png?w=512" height="400" width="380">
 <u1>
   <h2><b>Esquemáticos</b></h2>
     
<u1>
  <li> Esquematico frente </li>
  <img src="https://user-images.githubusercontent.com/76061000/115423539-4b18fe80-a1d4-11eb-89be-5eee69b26868.jpg" height="500" width="750">
  <li> Esquematico trás </li>
   <img src="https://user-images.githubusercontent.com/76061000/115423648-6257ec00-a1d4-11eb-9435-b9a8a9f41430.jpg" height="500" width="750">
  
  <u1>
   
  <h2><b>GPIO's</b></h2>

|  <b>GPIO</b> |  <b>PINO</b> |
|---|---|
|16  | BOTÃO 1  |     
|  14 | BOTÃO 2  |  
| 12  |  BOTÃO 3|
| 05  |  RELÉ 1|   
| 04  |  RELÉ 2|   
| 02  |  RELÉ 3|   

 

  <h2><b>Software necessário</b></h2>
 <b>Sirinc Pro</b>: O Sirinc Pro é um serviço de nuvem para dispositivos inteligentes, onde de forma gratuita podemos hospedar até 3 dispositivos gratuitamente e a partir dele fazer o acionamento dos interruptores pelo aplicativo ou comando de voz.


