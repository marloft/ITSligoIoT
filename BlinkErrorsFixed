/*
  BlinkErrors
  Turns an LED on for one second, then off for one second, repeatedly.

  Most Arduinos have an on-board LED you can control. 
  On the YUN it is attached to digital pin 13. 
  But you could change this to any Digital pin and use that number.

  modified 8 May 2014 by Scott Fitzgerald
  modified 2 Sep 2016  by Arturo Guadalupi
  modified 8 Sep 2016 by Colby Newman
  modified 19th Jan 2021 by Mary Loftus 

  This example code is in the public domain.
  http://www.arduino.cc/en/Tutorial/BlinkErrors
*/
int LEDPin=2;

// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LEDPin as an output.
  pinMode(LEDPin, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LEDPin, HIGH);       // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LEDPin, LOW);        // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
