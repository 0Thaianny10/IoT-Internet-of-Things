void setup() {
  // put your setup code here, to run once:
pinMode(13, OUTPUT);

}

void loop() {
  // put your main code here, to run repeatedly:
  // ligar a saída 13
digitalWrite (13, HIGH);
// Aguardar 1,5 segundo
delay(1500);
// desligar a saída 13
digitalWrite(13,LOW);
// Aguardar 0,5 segundo
delay(500);

}