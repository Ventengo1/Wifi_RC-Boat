This is a simple, low-cost RC boat that uses two brushed DC motors controlled via Wi-Fi using an ESP32. It works by using using differential thrust for steering and turning. The boat is controlled through a web interface hosted directly on the ESP32, so no external app is needed.

I made this project because I have always liked robotics and remote control things. For my prior highway project I made a servo controlled model rocket with fins for guidance. This time however, I wanted to do something similar but with water which is how this idea was born.

The project is made for and funded by Hack Club's Highway program.


The project is built with:

ESP32 for Wi-Fi access point + web interface

L298N motor driver for dual brushed DC motors

2x 6–12V brushed DC motors connected to propeller shafts

7.4v Li-ion battery pack for powering motor driver

3.7v Li-ion battery pack for ESP32

No steering servo — direction is controlled via motor speed

Waterproofing is handled with a basic plastic enclosure for electronics

🚧 Disclaimer
Some code for this project was adapted using tutorials, forums, and online references, as well as with the help of artificial intelligence. These portions are not covered by the GNU GPL v3 license under which the rest of this project is released.

Link to BOM: https://docs.google.com/spreadsheets/d/e/2PACX-1vSZY3Rild4j8GjO4YpfYta51ACEuZQuzVf8SXvvIFWEaKeo-5W_QqL5SFOygLZC2wBmDybPTQcTunmU/pubhtml?gid=0&single=true

![Screenshot 2025-07-03 171323](https://github.com/user-attachments/assets/6dae81c1-f2d5-4ef6-8bf4-6765eda1cb08)
![Screenshot 2025-07-03 171315](https://github.com/user-attachments/assets/845c0109-a676-41e8-b9a5-dc40a261997a)

In the BOM I am not including the cost of filament as I am only uisng about 200 grams so I am okay without finding for that.
![image](https://github.com/user-attachments/assets/a2ead1fb-fe5c-4fd7-9c6a-5e2637e7828c)

In the future I want to add a camera to the boat with the ESP Cam module and maybe make your phones gimbal the control.

