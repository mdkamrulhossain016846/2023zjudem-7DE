<h3 align="center">ARDUINO</h3>

### Basic
To learn about arduino basic click <a href="https://www.nexmaker.com/doc/5arduino/arduino_basic.html">here</a>

### Homework 
<h2>LED control with switch</h2>
Controlling two LEDs with a switch using an Arduino is a common beginner project that demonstrates input and output interfacing. Below is a step-by-step process to achieve this:

Components Required:

- Arduino board
- Two LEDs (different colors)<br>
- Two 220-ohm resistors (or appropriate resistors for your LEDs)
- one 1040 kΩ Resistor
- Momentary push-button switch

Step 1: Circuit Connection

- Place your Arduino board on the breadboard.
- Connect the longer leg (anode) of the first LED to digital pin 2 on the Arduino. Use a 220-ohm resistor in series with this LED to limit the current.
- Connect the anode of the second LED to digital pin 3 on the Arduino, also with a 220-ohm resistor.
- Connect the shorter leg (cathode) of both LEDs to the Arduino's ground (GND) pin.
- Connect one terminal of the momentary push-button switch to digital pin 4 on the Arduino.
- Connect the other terminal of the push-button switch to the Arduino's ground (GND) pin.

Step 2: Write the arduino Code
<pre>
    <Code>
    const int LED1=12;
const int LED2=13;
int val=0; 
void setup()
{ 
  pinMode(LED1, OUTPUT); 
  pinMode(LED2, OUTPUT); 
  pinMode(7, INPUT);     
}
void loop(){
val=digitalRead(7);
  if(val==HIGH)
{
    digitalWrite(LED1,HIGH);
    digitalWrite(LED2,LOW);
}
else
{ 
    digitalWrite(LED2,HIGH);
    digitalWrite(LED1,LOW);  
}
delay(1000);
}
    </code>
</pre>

Step 3: Upload the Code

- Open the Arduino IDE on your computer.
- Select the appropriate Arduino board and port from the "Tools" menu.
- Copy and paste the code into the Arduino IDE.
- Click the "Upload" button (right arrow) to upload the code to your Arduino board.

Step 4: Test the Circuit

After uploading the code, the LEDs will start in the OFF state. Press the push-button switch, and both LEDs should toggle between ON and OFF states with each press.
<br>

Simulation in Arduino software
<img src="img/arduino/ar_simulation.png">
<style>
video-container {
            text-align: center;
        }
        video {
            max-width: 100%;
            max-height: 100%;
        }

</style>
Project video
<div id="video-container">
        <video controls>
            <source src="video/video_arduino/ar_s_video.mp4" type="video/mp4">
        </video>
    </div>

This project demonstrates the basic concept of digital input (reading the switch) and digital output (controlling the LEDs) using an Arduino..
