# Color-Detection-using-HuskyLens
This project uses a HuskyLens AI camera connected to an Arduino board to detect and recognize three specific colors: Yellow, Green, and Blue.

The HuskyLens is pre-trained to recognize these colors using its color recognition function.

Once the HuskyLens detects a color, it sends the color ID to the Arduino via the UART (Serial) interface. The Arduino then processes this data to trigger different outputs or behaviors based on the detected color.

Main Components:

HuskyLens AI Camera

Arduino Uno 

Jumper wires (for TX/RX, 5V, GND)

Power supply or USB connection

Features:

Detects and differentiates between Yellow, Green, and Blue colors

Sends detection results to Arduino via serial communication

Allows Arduino to respond in real-time to the color detected

Can be expanded for more colors or actions
