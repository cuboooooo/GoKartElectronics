# Plan

alright I don't have much here we go

## Arduino Wiring Mock up
https://wokwi.com/projects/385923683096981505

## Micro Controller

Teensy 4.1 looks sexy, with wifi and bluetooth we can host a server for our phones to connect to for data collection like top speed.

Raspberry Pi Zero W also works, more input pins to work with, screens more widely supported. Wifi and Bluetooth enabled.


## Accessories

NEO-6M module for GPS (speedometer) [here](https://www.amazon.com/Microcontroller-Compatible-Sensitivity-Navigation-Positioning/dp/B07P8YMVNT?th=1)

LONG strips of **DATA** RGB cables.  [here](https://www.amazon.com/ALITOVE-Addressable-Programmable-Waterproof-Raspberry/dp/B0CDQ2LDQH?th=1)
> (I would like these to be some COOL features. as well as sick looking. e.g. brake and throttle indicators)
> drift indicator could be pulled off by comparing the front wheel speeds to the back wheel speeds and changing the lighting while drifitng. cool af.

Tachometer using IR sensor on the main engine shaft (if we can) or any visable turning part of the engine with some math. I've seen online that hall effect sensors can also be used to detect RPMs?

Engine/motor/wheel Temperature sensor (easy peasy)

Displays. hold on im making this its own subheading.

## Displays

many routes we could go. simple small pixely OLEDs could do great [see here](https://youtu.be/gKuJxjxNP-k?t=255)

Or we could go the route of trying for a HUD using plexiglass and some reflective film. this is tougher to acheive and honestly I think its less cool because we'd have to sacrifice on picture quality to get the screen luminosity to actually reflect and stand out from the background.

LCD screens are pretty cheap and its honestly hard to find them WITHOUT touchscreen which kinda is a bonus if we rlly want it. [7" 40-pin $30 no touch](https://www.adafruit.com/product/2353) [7" HDMI $45 touch](https://www.amazon.com/Hakeeta-Capacitive-Independent-Backlight-Interface/dp/B0868P3KS8?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A378IDEIN3R157) [7" HDMI $32 no touch](https://www.ebay.com/itm/195874025131?chn=ps&mkevt=1&mkcid=28)

## other ideas

crash detection??? idk WHY but we COULD.

loss of traction detection, idk how 

g force measurement? it prolly wont be a lot 

max verstappen theme plays whenever you reach max speed (aiden idea)



## issues?? idk

i didnt know where else to put this but obviously **waterproofing** is an issue. the LED strips i put up there are weather proof, but the GPS and screens wouldnt be. how would we fix this?? idk Saran Wrap it. duct tape and ziplock bags and saran wrap.



