void setup() {<br>
  // put your setup code here, to run once:<br>
pinMode(13, OUTPUT);<br>

}<br>

void loop() {<br>
  // put your main code here, to run repeatedly:<br>
  // ligar a saída 13<br>
digitalWrite (13, HIGH);<br>
// Aguardar 1,5 segundo<br>
delay(1500);<br>
// desligar a saída 13<br>
digitalWrite(13,LOW);<br>
// Aguardar 0,5 segundo<br>
delay(500);<br>

}
