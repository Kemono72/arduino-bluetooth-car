# Arduino Bluetooth RC Car - Pseudocode

1. Initialize serial communication at 9600 baud.
2. Define motor driver control pins (e.g., IN1, IN2, IN3, IN4).
3. Set all motor pins as OUTPUT.
4. In loop():
   a. If serial data is available:
      - Read incoming character.
      - If character is 'F', move forward.
      - If character is 'B', move backward.
      - If character is 'L', turn left.
      - If character is 'R', turn right.
      - If character is 'S', stop.
5. Define functions:
   - moveForward()
   - moveBackward()
   - turnLeft()
   - turnRight()
   - stopMotors()