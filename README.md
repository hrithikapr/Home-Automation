# *Project - Voice Controlled   Home Automation*

**Introduction** -   Raspberry Pi based Voice Controlled Home Automation System that can listen, respond, and control AC loads as per our voice commands. We have directly performed Speech Recognition on Raspberry Pi, so we can directly connect a microphone to our Pi and speak into it. This avoids the need for external devices like a mobile phone. Also, the system can be kept turned on all the time, waiting for a particular voice command. Here, we have programmed the Pi to respond for a keyword _“hello”_ after which we can control our lights to be on or off.
**Components Required**
1.	Raspberry Pi
2.	Mic
3.	Speaker
4.	Relay
5.	Jumper wires
We are using a 3.5 mm jack male connector to connect with the speaker and USB mic to connect with the raspberry pi. The bulb’s connection with the relay module is simple, one terminal of the bulb is connected to the AC supply (neutral) and the phase of the AC supply is connected to the “NO” of the relay. The common terminal of the relay is connected to the bulb’s other terminal.
In our project, the USB microphone, which we are using, does this (A/D) precise operation and it also has an inbuilt amplifier which makes it unnecessary to use an external preamplifier circuit. So, by using a USB microphone, we can directly connect it with a computer, and in our case to a raspberry pi.
The speaker works on the same mechanism as a microphone but in reverse. A microphone converts the sound waves to electrical signals while the speaker converts the electrical signals to soundwaves. Cone, an electromagnetic coil, and a permanent magnet are the main components of the speaker. The permanent magnet is fixed to one end while the electromagnet is movable. 
After complete the project,
Say clearly light on. The LED should turn on
Say clearly light off. The LED should turn off
