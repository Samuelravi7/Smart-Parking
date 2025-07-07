# Smart-Parking
A simple IOT project - SMART PARKING SYSTEM

Electronics Needed: 
- Ultrasonic Sensor
- IR Sensor
- Servo Motor
- LCD Display
- LED's
- Buzzer
- ESP32
- Wires
- Breadboard

Once an object (car) is detected at the entrance by the ultrasonic sensor, it sends a signal to esp32 for the servo motor to raise the barrier (90 degree turn). The LCD displays the status of the barrier (open or close) and the buzzer sounds for a brief period of time to alert surroundings that a car is passing. Then, when the parking lot is occupied by the car, the IR sensor updates to esp32 that the lot is currently occupied. The whole project status (parking lot availability) can be monitored and remotely controlled via AWS IOT service.

Refer to this youtube video for guide to generate certificates, private key and public key : https://youtu.be/iQOKosuw9x4?si=SJg_owcDyqYZsIko
A AWS account by Amazon is required but optional. The project still functions fine without AWS Service as long as the connections to esp32 and the pins are in order.
