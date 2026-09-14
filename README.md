# Self-Balancing-Height
The primary goal is about to achieve the required height maintenance using three different terminologies i.e, PID control, fuzzy logic and ANN.
1- Purpose of Project
As the project is relying on self-balancing mechanism, the feedback will be controlled by the system itself. For this, the sensor measures the distance between the current height and target height and transmit the data to the controller. Then the controller will actuate the motor and set the thrust either high or low depending on the current position of the wooden frame to maintain the equilibrium. 

2- Methodologies

I-  By Proportional-Integral-Derivative
     Closed loop-based system to maintain the setpoint by reducing the distance error.
     
II- By Fuzzy logic
    Based on rules to mimic human-like decision-making.
    
III- By Artificial Neural Network
    A data-driven approach that adapts based on training and error correction.

3- Components
* Wooden Frame
* ESP32 Wroom 32
* A2212 BLDC Motor
* Ultrasonic Sensor
* Arduino IDE (for software purpose)

4- Practical Implementation
▪ ESP32 boots the code successfully while BLDC motor and ultrasonic sensor perform well in execution in accordance with the objective.
▪ The system achieves output and gives a better response.
▪ Motor starts with base throttle 1250 us and set its PWM whatever the current height is measured.
▪ Ultrasonic sensor reads the current height and transmits the data to controller to compare it with the target.
▪ Apply the terminologies of PID, fuzzy logic and ANN to maintain the height effectively with minimum error

5- Summary
This venture effectively illustrates the usage and comparison of ID, Fuzzy logic, and ANN-based control for a 1-DOF self-balancing helicopter utilizing an ESP32, BLDC engine, and ultrasonic sensor control shows preferences and trade-offs. This extend serves establishment for progressed implanted control frameworks in mechanical technology, rambles, and computerization.
