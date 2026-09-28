int pir = 2;
int buzzer = 8;

void setup() {
  pinMode(pir, INPUT);
  pinMode(buzzer, OUTPUT);
}

void loop() {
  if (digitalRead(pir) == HIGH)
    tone(buzzer, 1000);
  else
    noTone(buzzer);
}
# Motion-Detection-Alarm
