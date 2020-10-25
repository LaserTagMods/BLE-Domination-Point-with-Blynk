# BLE-Domination-Point-with-Blynk

This is an arduino based code that creates a simple blue tooth connected ESP32 base for the BRX as a domination station. 
I'm using an ESP32 D1 mini development board and a single IR receiver.

The ir sensor can simply plug into or be soldered to the V, G and pin 16. on the d1 mini esp32 the pin 16 is right next to the V/G so it is a really easy plug and play

I also have a blynk app/project that is accessible for you to use to set the options/functions. The app also receives the scor reporting live in game and
allows for you to stop/pause and reset the game when starting a new one. There are many other features as well like setting capture limitations for the 
game play as well as how the device accumulates scores based upon damage, time or the number of shots fired at the device. 

Hope you enjoy and feel free to customize the code to suit your different taggers (LTTO, Recoil, ETC) based upon their protocol. You'll want to modify the
RecieveBRXIr object in order to accomodate your specific protocol. 

I'll be likely modifying soon to allow for more points for capturing as well to have one device control the others OTA for one scoring system for multiple points.

