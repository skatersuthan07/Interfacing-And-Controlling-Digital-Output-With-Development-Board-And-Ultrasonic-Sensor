# Interfacing-And-Controlling-Digital-Output-With-Development-Board-And-Ultrasonic-Sensor


## Aim

To interface an **ultrasonic sensor (HC-SR04)** with a development board using **Tinkercad Circuits** and control a **digital output (LED)** based on the distance measured by the sensor.

## Procedure

1. Open **Tinkercad Circuits** and create a new circuit.
2. Place an **Arduino Uno**, **HC-SR04 ultrasonic sensor**, LED, and suitable resistor in the workspace.
3. Connect the **VCC** pin of the ultrasonic sensor to the Arduino **5V** pin.
4. Connect the **GND** pin of the ultrasonic sensor to the Arduino **GND**.
5. Connect the **TRIG** pin of the ultrasonic sensor to a digital pin of the Arduino.
6. Connect the **ECHO** pin of the ultrasonic sensor to another digital pin of the Arduino.
7. Connect the LED to a digital output pin through a suitable resistor.
8. Write the Arduino program to generate a trigger pulse and calculate the distance using the echo time.
9. Set a suitable distance threshold in the program.
10. If the measured distance is below the threshold, turn **ON** the LED.
11. If the measured distance is greater than the threshold, turn **OFF** the LED.
12. Start the simulation in Tinkercad and observe the LED operation while changing the ultrasonic sensor distance.
13. Verify that the digital output responds correctly to the measured distance.

## Algorithm

1. **Start**
2. Initialize the ultrasonic sensor pins and LED pin.
3. Set the TRIG pin to LOW.
4. Generate a short HIGH pulse on the TRIG pin.
5. Read the duration of the signal received at the ECHO pin.
6. Calculate the distance from the echo duration.
7. Compare the measured distance with the predefined threshold.
8. If the distance is less than the threshold, turn **ON** the LED.
9. Otherwise, turn **OFF** the LED.
10. Display or monitor the measured distance.
11. Repeat the process continuously.
12. **Stop**

## Output 
<img width="1920" height="1080" alt="{2259BD1D-73F0-46E2-B87F-51A54B445701}" src="https://github.com/user-attachments/assets/8ab2e620-157b-40dc-a7e0-095c4190a88f" />
<img width="1920" height="1080" alt="{73385FD7-AEE5-4BE1-B6FD-B78EB53C086F}" src="https://github.com/user-attachments/assets/9cf9543e-9d00-4784-a792-8199bc63f527" />

**## Result**

The ultrasonic sensor was successfully interfaced with the development board in **Tinkercad Circuits**. The distance of an object was measured using the HC-SR04 sensor, and the LED was successfully controlled as a digital output according to the measured distance. The simulation worked successfully and demonstrated distance-based digital output control.
