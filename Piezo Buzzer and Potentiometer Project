int buzzPin = A1;
int dt = 2000;
int potPin = A0;
int myNumber;
float realNumber;
void setup()
{
  Serial.begin(9600);
  pinMode(buzzPin, OUTPUT);
  pinMode (potPin, INPUT);
}

void loop()
{
  myNumber = analogRead(potPin);
  realNumber = 0.2492668622 * myNumber;
  //Serial.println(myNumber);
  Serial.println(realNumber);
  
  analogWrite(buzzPin, realNumber);
  
}