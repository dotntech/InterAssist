![InterAssist](https://github.com/dotntech/InterAssist/blob/main/header.png)
# InterAssist
Intercom companion hardware PCB and based software for add more remote possibilities for basic HousePhone\Intercom devices like  
"Tuya Smart HousePhone \ DoorPhone" "DoorHan" "EagleEYE" And etc.  
They used 4-wire panel with integrated relay for electro doorlock.  
This companion device can added to exiting doorphone \ housephone. 2 door panels max + gate remote.  
Connection are parralel, and later can be used across other smart home systmes like Home Assistant (uses ESPHOME framework).
Gerber of PCB are provided. tested on prototype.  
J3 select relay power. I use 5v relays such as G6S-2 3v3 power is enough.  
EXPERIMENTAL: Call detection. Uses IN power from cental panel or Audio line (selectable by J1\J2)  
D5 - Door-1  
D6 - Door-2  
D7 - Gate  
My bad, i not complete citcuit for call tetection. In voltage divider such as R10+R9 and R6+R5 between line must be calculated and connected to any free digital pin or A0 with setup different level of deetection.  
you need to know what level (power or Audio line levels used and using) used and setup this for output not greater than 3.3v pin voltage of ESP8266digital pins.  
Reference image below:  
![InterAssist](https://github.com/dotntech/InterAssist/blob/main/Screenshot_6.png)  
Assembled:  
![InterAssist_Assembled](https://github.com/dotntech/InterAssist/blob/7cf597e411476bddfe169925f33fdcf8942a7b5c/assembled_view.jpg)
