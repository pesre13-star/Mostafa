# Mostafa
const int motorPin1 = 9; 
const int motorPin2 = 10; 

void setup() {
  pinMode(motorPin1, OUTPUT); 
  pinMode(motorPin2, OUTPUT);
}

void loop() {
  digitalWrite(motorPin1, HIGH); 
  digitalWrite(motorPin2, LOW); 
  delay(5000);

  digitalWrite(motorPin1, LOW);
  digitalWrite(motorPin2, LOW);
  delay(2000); 
  

  digitalWrite(motorPin1, LOW); 
  digitalWrite(motorPin2, HIGH); 
  delay(5000); 

  digitalWrite(motorPin1, LOW);
  digitalWrite(motorPin2, LOW);
  delay(2000); 
}
