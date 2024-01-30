int red=10;
int orange=8;
int green=4;

void setup()
{
  pinMode(red, OUTPUT);
  pinMode(orange, OUTPUT);
  pinMode(green, OUTPUT);
}

void loop()
{
  digitalWrite(red, HIGH);
  delay(1000);
  digitalWrite(orange,HIGH);
  delay(550);
  digitalWrite(orange,LOW);
  delay(550);
  digitalWrite(orange,HIGH);
  delay(550);
  digitalWrite(orange,LOW);
  delay(550);
  digitalWrite(orange,HIGH);
  delay(550);
  digitalWrite(red, LOW);
  
  digitalWrite(orange,LOW);
  delay(1000);
  digitalWrite(green,HIGH);
  delay(1000);
  digitalWrite(green, LOW);
  delay(1000);
}
