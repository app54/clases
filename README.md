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
  // los pines analógicos no necesitan ser configurados
  pinMode(3, OUTPUT);
}

void loop() 
{
  int brillo = analogRead(0);
  analogWrite(3, brillo);
}
````

## Código con ultrasónico

````
void setup()
{
  pinMode(6,  OUTPUT);
  pinMode(7,  INPUT);
  pinMode(10, OUTPUT);
}

void loop() 
{
  int brillo = analogRead(0);
  analogWrite(3, brillo);
}
````
