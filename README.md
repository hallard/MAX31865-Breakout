MAX31865 PT100, PT1000 RTD sensors Breakout board
=================================================

It's not the first time I want to measure sensors but one of the most used in industry are the PT100 and PT1000, and a friend of mine asked me several times to be able to easily measure temperature with these sensors. Here that breakout board


Detailed Description
====================

Everything is documented on this dedicated [post][1]

### Schematic  
![schematic](https://raw.githubusercontent.com/hallard/MAX31865-Breakout/master/MAX31865-sch.png)  

### Boards  
<img src="https://raw.githubusercontent.com/hallard/MAX31865-Breakout/master/MAX31865-brd.png" alt="board V1.0" width="30%" height="30%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/MAX31865-Breakout/master/MAX31865-top.png" alt="top V1.0" width="30%" height="30%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/MAX31865-Breakout/master/MAX31865-bot.png" alt="bottom V1.0" width="30%" height="30%">

##Library
When I created the MAX31865 breakout board, I needed a library to be able to read results. I then found one which was working file. I just added on it some features I needed, thank to Original library author olewolf.
- you can find the forked libray and sample code [here][3]

##Action
When all is fine
<img src="https://raw.githubusercontent.com/hallard/MAX31865-Breakout/master/pictures/max31865-oled-temp.jpg" alt="No breakout board connected" width="50%" height="30%">

and when there is a problem
<img src="https://raw.githubusercontent.com/hallard/MAX31865-Breakout/master/pictures/max31865-oled-nortd.jpg" alt="No sensor connected" width="50%" height="50%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/MAX31865-Breakout/master/pictures/max31865-oled-noboard.jpg" alt="No breakout board connected" width="40%" height="40%">&nbsp;

##License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">MAX31865 PT100, PT1000 RTD Sensors Breakout Board</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://hallard.me/max31865" property="cc:attributionName" rel="cc:attributionURL">Charles-Henri Hallard</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/hallard/MAX31865-Breakout" rel="dct:source">https://github.com/hallard/MAX31865-Breakout</a>.

##Misc
See news and other projects on my [blog][2] 
 
[1]: http://hallard.me/max31865/
[2]: http://hallard.me
[3]: https://github.com/hallard/arduino-max31865/
