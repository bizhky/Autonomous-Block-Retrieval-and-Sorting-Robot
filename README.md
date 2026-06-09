Designed and programmed a four-wheel robotic vehicle controlled by a PlayStation 2 controller using an Arduino microcontroller. The system utilizes the PS2X controller library to receive wireless controller inputs and translate them into motor and servo commands.

The robot uses four DC motors for movement and steering, allowing forward, reverse, left-turn, and right-turn operation. Motor control is achieved through digital output pins connected to motor driver circuitry. A servo-powered grabber mechanism is mounted on the robot and can be opened and closed remotely using controller buttons, enabling the robot to pick up and manipulate objects.

The software includes controller connection verification, automatic reconnection attempts if communication is lost, and real-time processing of joystick and button inputs. The left analog stick controls vehicle movement while designated controller buttons operate the grabber mechanism. Safety features stop all motors whenever controller communication is interrupted.

Technologies Used:

Arduino Mega/Microcontroller
C++ (Arduino IDE)
PS2X Controller Library
Servo Library
PlayStation 2 Wireless Controller
DC Motors and Motor Drivers
Servo Motor Gripper System

Key Features:

Wireless PS2 controller operation
Four-wheel drive motor control
Remote-controlled grabber/claw
Real-time joystick navigation
Automatic controller reconnection
Safety shutdown on signal loss
Object pickup and transport capability
