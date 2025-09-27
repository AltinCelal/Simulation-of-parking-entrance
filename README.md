# Simulation-of-parking-entrance
STM32, HC-SR04 ultrasonic distance sensor, and SG90 servo motor based parking entrance simulation

You can find the source code in the main.c file. You may need to configure it according to your own microcontroller (such as timer PWM pin, clock frequency, etc.). The DWT library has been used to achieve microsecond-level precision (required for reading data from the HC-SR04 sensor – though this is not the only way!). You can also visit https://youtube.com/shorts/gV2ycn5vlXs
