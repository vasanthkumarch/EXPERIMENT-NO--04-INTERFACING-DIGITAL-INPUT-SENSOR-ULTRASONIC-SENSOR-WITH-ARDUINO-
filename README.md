# EXPERIMENT-NO--04-INTERFACING-DIGITAL-INPUT-SENSOR-ULTRASONIC-SENSOR-WITH-ARDUINO-





EXPERIMENT NO -04
INTERFACING DIGITAL INPUT SENSOR (ULTRASONIC SENSOR) WITH ARDUINO 
AIM:  To interface an Digital input (Ultrasonic sensor) and measure the distance of the obstacle.
COMPONENTS REQUIRED:
1.	Ultrasonic pair  HR-S04
2.	1 KΩ resistor 
3.	Arduino Uno 
4.	USB Interfacing cable 
5.	Connecting wires 
6.	LED of choice 
THEORY
Ultrasonic waves are basically sound waves which is beyond the human audibility ie., above 20Khz, and travels with a velocity of 340m/sec.
An ultrasonic sensor comprises of 2 individual sensors
 1. Emitter 
2. Receiver
Distance measurement principle is based on the travel time of the sound wave in the air. Distance Measurement formula is expressed as:
 L = C X T
L is the measured distance, 
 C is the ultrasonic spreading velocity in air and
 T represents time




HR-S04



![image](https://user-images.githubusercontent.com/36288975/163531726-7d3880a5-a1c9-40d7-8c76-5ff72699d6fc.png)

**Figure-01 ULTRASONIC PAIR HC- SR04
**
PIN DESCRIPTION  
Pin no 	Pin symbol	Pin function description 
1	Vcc	5v power supply
2	Trig 	Trigger pin 
3	Echo 	Receive pin 
4	Gnd 	Power ground

Ultrasonic ranging module HC - SR04 provides 2cm - 400cm non-contact measurement function, the ranging accuracy can reach to 3mm. The module includes ultrasonic transmitters, receiver and control circuit. The basic principle of work:
(1) Using IO trigger for at least 10us high level signal,
(2) The Module automatically sends eight 40 kHz and detect whether there is a pulse signal back.
(3) IF the signal back, through high level , time of high output IO duration is the time from sending ultrasonic to returning.
Test distance = (high level time X velocity of sound (340M/S) / 2)






![image](https://user-images.githubusercontent.com/36288975/163531726-7d3880a5-a1c9-40d7-8c76-5ff72699d6fc.png)

**Table no -01 pin description of HR-S04
**
ELECTRIC PARAMETERS


![image](https://user-images.githubusercontent.com/36288975/163531640-7c4f6e7d-fdc2-4624-8dae-ad3de9bd36b6.png)
 


**PROCEDURE:**
1.	Connect the circuit as per the circuit diagram 
2.	Connect the board to your computer via the USB cable.
3.	If needed, install the drivers.
4.	Launch the Arduino IDE.
5.	Select your board (If you the board is arduino uno, select accordingly).
6.	Select your serial port, accordingly ( E.g. COM5 )
7.	Open the file of the program  and verify the error , clear if any errors that are existing 
8.	Upload the program and check for the physical working. 
9.	Ensure safety before powering up the device.

**
CIRCUIT DIAGRAM**


![image](https://user-images.githubusercontent.com/36288975/163531582-305baaa0-cd55-4b35-a6b9-7a40f95e9374.png)




**PROGRAM**
 

OBSERVATIONS
Sl No 	Obstacle Location On Measuring Scale  (S)	Measured value using HC- SR04 (M)	Deviation 
X=S-M
1			
2			
3			
4			
5			

**AVERAGE VALUE OF  X= Σ( S-M)/ Total No. Of Readings **
	
RESULT:  Arduino uno interfacing with HC-SR04	 is learned and obstacle distance is measured , average deviation is found to be _________________






