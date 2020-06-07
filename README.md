# 3D_Piezoelectric_Shoe
This repository contains the 3D models developed for better visualization of generating energy by applying pressure on a piezoelectric shoe or "SmartFeet", which in turn is made up of 25 (or 26) piezoelectric sensors embedded in each shoe, a 47 μF/ 4.50V capacitor, a full wave bridge rectifier (four 1N914 diodes), a diode (also of model 1N914), a LED (model NSPW500BS), a resistive load (1 kΩ) connected using wires. Since a piezoelectric sensor can't be used in the LTSpice directive, we have used a SINE(0 5) voltage source to replicate the same at increments of 2V, alongside a slideswitch. 

Welcome dear reader!

Here I have included a 3D model regarding energy generation by pressing piezoelectric sensors, which gets stored in a 47 μF/ 4.50 V capacitor. The 3D model can be opened by the following softwares:
- *3D Viewer (Recommended)
- *Paint 3D 

The capacity can be increased as per your wish if you choose another capacitor. When the switch is closed, the LED glows indicating that energy has been generated, stored in the capacitor and now used to power the LED. Two to five piezoelectric sensors are required to power a small LED bulb. It can also be used to power larger consumption devices like a torch, fan or even a phone on increasing the number of piezoelectric sensors. 
Pressing 50-51 piezoelectric sensors for a good amount of times can provide us with a huge voltage! But that is absolutely not possible, unless we have 25 friends pressing a sensor in each hand and they are willing to put in the unearthly work just to see how you discovered a way to charge your favourite tabletop fan or phone.
To implement that, I have designed a Piezoelectric shoe which has 25 or 26 piezoelectric sensors embedded in each shoe of the pair. Now they will get pressed whenever you walk, jog, run or even press down the paddle while playing piano! 

NOTE : This device will work efficiently ONLY if the number of presses are more. Doesn't work if you press and hold the sensor down for any matter of minutes. For any questions, head to the model and I'll answer them for you.
