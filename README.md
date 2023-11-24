Arduino IDE + NodeMCU ESP8266 + P10 LED Panel | NodeMCU ESP8266 controls P10 LED Panel using Arduino IDE (including text set in P10 with Web Server). In this project video I use Arduino IDE 1.8.9 , Notepad++ V7.7.1 , NodeMCU ESP8266 V3 and P10 LED Panel.

Download source code and installation image here : https://github.com/777Kaliking/NodeMCU-ESP8266-P10

Download the DMDESP Library by busel7 (Bonny Useful) : https://github.com/busel7/DMDESP

Note :
The drawback of this library (DMDESP) is that there is a slight flicker in the Text display that doesn't move (doesn't scroll). But in my opinion it's still good. Flicker does not occur on the scrolling text.

The code file is saved in the .rar file format. I created a .rar file using Winrar V5.50, so to extract it, make sure you use the same version of Winrar that I use or the latest version or use the winrar extractor online.

| Tutorial | Example |
|----------|---------|
| <a href="https://youtube.com/playlist?list=PLKuQ-UWqAt3OseL7NHUupuKpr04o4ReUD" target="_blank"><img src="https://i.ytimg.com/vi/W6BT-Ju3rFg/hqdefault.jpg" alt="Playlist Tutorial DMDESP" width="240" height="180" border="10" /></a> | <a href="http://www.youtube.com/watch?feature=player_embedded&v=cDKsBYR1Nps" target="_blank"><img src="[http://img.youtube.com/vi/cDKsBYR1Nps/0.jpg](https://github.com/777Kaliking/NodeMCU-ESP8266-P10/blob/main/Installation.jpg)" alt="JWSP10 NodeMCU ESP8266" width="240" height="180" border="10" /></a> |



### Pin on DMD LED P10 Panel

| DMD P10 | NODEMCU | 
| ------- | ------- |
| A       | D0      |
| B       | D6      |
| CLK     | D5      |
| SCK     | D3      |
| R       | D7      |
| NOE     | D8      |
| GND     | GND     |



## Software

- Arduino IDE
  Download & Install : https://www.arduino.cc/en/software
- ESP8266 Board
  Files > Preferences > Settings > Additional Boards Manager URLs : https://arduino.esp8266.com/stable/package_esp8266com_index.json

### Terimakasih Kepada
- dmk007 (HJS589 DMD porting for ESP8266)
- rweather (https://github.com/rweather/arduino-projects/blob/master/libraries/DMD)

### Catatan : 
- Perlu Power Eksternal 5V ke LED P10.

> email :Ronitpaikray6@gmail.com


