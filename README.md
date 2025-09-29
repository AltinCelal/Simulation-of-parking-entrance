# Simulation-of-parking-entrance
STM32, HC-SR04 ultrasonic distance sensor, and SG90 servo motor based parking entrance simulation

You can find the source code in the main.c file. You may need to configure it according to your own microcontroller (such as timer PWM pin, clock frequency, etc.). The DWT library has been used to achieve microsecond-level precision (required for reading data from the HC-SR04 sensor – though this is not the only way!). You can also visit https://youtube.com/shorts/gV2ycn5vlXs

In addition, the STM32 board was communicated with Qt via serial communication, and a user interface was developed.
<img width="1007" height="784" alt="resim" src="https://github.com/user-attachments/assets/7850369f-aae9-4e56-80ba-e3309340ad07" />



When the entrance is open, it lights green, and when it is closed, it lights red.
<img width="1002" height="792" alt="resim" src="https://github.com/user-attachments/assets/d10c5a76-570f-4388-a427-e8206b88b883" />

Additionally, you can watch the demonstration video at https://youtu.be/ZVM2jiHmuH8.”
