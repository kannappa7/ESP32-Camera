# ESP32-Camera
To store camera webserver, image processing etc

My experiences:
- first I wanted to write bare metal programmer in Linux. Since I had a spare Raspberry Pi module, I installed Raspbian, etc. AFter a few tries I decided to use Arduino to start programming the esp32-cam with the esp32-cam-db daghter board. I read about wh I needed the daughter board. This will tell you how much I knew about microcontroller-) I connected the esp32 to the rpi module, started arduino, installed esp32 espressif sdks, selected the board AI-thinker-esp32-cam. This was way down in the tools/board list. When I tried to sketch/upload, it didn't work. It gave some errors. After a few hours, I decided to cut the time loss and moved to a windows machine. M goal was to learn firmware coding and hence I didn't want to spend time on other things. I installed the arduino setup in windows. In the example code, I had to change the #define to the AI thinker board. I had to change the network ssid and password. sketch/upload worked nicely. When I tried to see the ipaddress of the esp32-cam board in putty serial monitor, I cpuld not. After I read about how to find it, I read that there is a serial monitor in the Arduino ide itself. dah. When I switched to the serial monitor, there it was. Once I got the ip address, I was able to see the stream in a browser in my phone.
- 7/2/25
  - Successfully loaded a web streaming video server on the esp32-cam module - using the example code
  - connected the board to a power source and used it as a securit camera :-)
- 
