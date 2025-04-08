Hi~
Play first minute of badapple!! on an esp32 devkit v1 and a ssd1306 oled 128x64
</br>
Diagram </br>
![Schema](https://electronicsinnovation.com/wp-content/uploads/2020/07/ESP32_OLED-960x486.jpg)
</br>
<h1>USAGE</h1></br>
Download the project folder, open it with ArduinoIDE, select your esp32 board, install nesscessary drivers, upload the code to the esp32 and youre good to go.</br>
The .ino file contain 736 frames of the first minute of badapple!! (taken 82% storage) along with the code to display it.</br>
<h1>HOW TO PLAY DIFFERENT VIDEOS</h1></br>
Get you video, reduce the resolution to 128x64, then extract the frames of the video (link below), then convert all frames into c arrays, put the arrays in the code (.ino) and play.</br>
<h1>Links</h1></br>
[Video Frame Extractor](https://frame-extractor.com/) </br>
[image2cpp](https://javl.github.io/image2cpp/)
