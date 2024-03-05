Robot Motor Control Arduino Code

This Arduino code controls a robot's movements based on input from two sensors. It defines pins for motor control, initializes speeds, and sets up sensor inputs. The loop continuously reads sensor values and executes movements (forward, backward, right, left, or stop) accordingly. Customize motor speeds and pin configurations as needed.

Usage:

Connect motors and sensors to specified pins.
Adjust motor speeds and rotation speeds as per requirements.
Pin Configuration:

Motor 1: ENA (10), IN1 (9), IN2 (8)
Motor 2: ENB (5), IN3 (7), IN4 (6)
Sensors: Left (A0), Right (A1)
Customization:

Modify M1_Speed and M2_Speed for motor speeds.
Adjust LeftRotationSpeed and RightRotationSpeed for rotation speeds.
Customize pin assignments if necessary.
