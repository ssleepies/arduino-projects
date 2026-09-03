void setup() {
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);         // this sets up the pins and lets them be used as outputs
  pinMode(11, OUTPUT); 
}

void loop() {
  digitalWrite(13, HIGH); // Turn LED on
  delay(1000);            // Wait for 1 second
  digitalWrite(13, LOW);  // Turn LED off
  delay(1000);            // Wait for 1 second

  digitalWrite(12,HIGH);
  delay(1000);
  digitalWrite(12,LOW);
  delay(1000);
  
  digitalWrite(11,HIGH);
  delay(1000);
  digitalWrite(11,LOW);
  delay(1000);
}
