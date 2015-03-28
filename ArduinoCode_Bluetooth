const int analogIn = A0;
float SensorValue  = 0;
float VoltageValue = 0;

void setup(){
  Serial.begin(9600);
}

void loop(){
  SensorValue = analogRead(analogIn);
  VoltageValue = ((SensorValue/1023) * 5);
  Serial.print("Voltage =");
  Serial.println(VoltageValue);
}
