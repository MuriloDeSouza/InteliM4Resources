//Segue o código para que o led fique piscando em um intervalo de 0,2 segundos.
//

void setup() {
  // setando qual pino eu vou usar e como que eu vou usar
  pinMode(13, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(13, HIGH);  // fornece a energia no pino 13
  delay(200);                      // Espera 0,2 segundos
  digitalWrite(13, LOW);   // suspende a energia no pino 13
  delay(200);                      // Espera 0,2 segundos
}
