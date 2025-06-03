# Clase de Robótica

## Código base

````
void setup()
{
  pinMode(13, OUTPUT);
}

void loop() 
{
  digitalWrite(13, HIGH);
  delay(800);
  digitalWrite(13, LOW);
  delay(800);
}
````

## Código con potenciómetro

````
void setup()
{
  pinMode(3, OUTPUT);
}

void loop() 
{
  brillo = analogRead(0);
  analogWrite(3, brillo);
}
````
