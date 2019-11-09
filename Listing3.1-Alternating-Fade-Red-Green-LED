/*Alternates the brightning of a red and green LED.
I am trying to make an e-Christmas tree for my girlfriend.
This was a modified version of the code found on Arduino Sketches
called Listing 3.1 on page [59].
*/

int ledRed = 9;
int ledGreen = 10;
int brightness = 0;
int fadeAmount = 5;


void setup() 
{
  pinMode(ledRed, OUTPUT);
  pinMode(ledGreen, OUTPUT);
}

void loop() 
{
  analogWrite(ledRed, brightness);
  analogWrite(ledGreen, -brightness);
  brightness = brightness + fadeAmount;
  if (brightness == 0 || brightness == 255)
    {
      fadeAmount = -fadeAmount;
    }
  delay(30);
}
