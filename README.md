The C++ code is used to make a path following bot.

-requirements:-
1. 5 IR sensors
2. 2 moters
3. ARDININO UNO
4. Breadboard

Discription:-
this is a simple project of line following bot which uses Ardino uno, an array of 5 IR sensors, 2 dc motars, a breadboard, L298N motor driver module, two dc motors.

Connections
1. IR sensors(5)

a. OUT pins- Ardino inputs
     - IR1:A0
     - IR2:A1
     - IR3:A2
     - IR4:A3
     - IR5:A4

b. VCC pins- 5V

c. GND pins-GND

3. Arduino UNO
   -USB powered by external supply
   -Other connections given above
4. L298N Motor Driver
   - IN1:D2
   - IN2:D3
   - IN3:D4
   - IN4:D5
   - OUT1 and OUT 2- left motor terminal
   - OUT3 and OUT4 - right motor terminal
   - L298N VCC(12V) -battery or seperate power supply for  motors.
   - L298N GND- Arduino GND + Battery negative terminal.

Our project is simply based on 5 IR sensors which help us detect lines. After detecting lines and getting input we simply use this info to satisfuy conditions in if-else loop. If conditions hold true for a specific input we call the functions that we have defined for that particular case. Once the function is called it runs the particular motor helping our bot to move along the line.

You can build and test this circuit in Tinkercad:
•	Add components as above

•	Wire the sensors, motor driver, motors, and Arduino

•	Copy-paste the sketch to Arduino code editor

•	Simulate line following by adjusting IR sensor “inputs”

L298N module may not be available so we may use any other similar module.

Motors require external power supply.


Secondly we have used PID algorithm in the saae code. this algorithm not only helps tto follow right path but help us do it with precision and accuracy.
   

