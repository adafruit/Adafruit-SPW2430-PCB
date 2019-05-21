## Adafruit Silicon MEMS Microphone Breakout SPW2430 PCB
<a href="http://www.adafruit.com/products/2716"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

Listen to this good news - we now have a breakout board for a super tiny MEMS microphone. Just like 'classic' electret microphones, MEMS mics can detect sound and convert it to voltage, but they don't need a bias resistor or amplifier, its all in one! The SPW2430 is a small, low cost MEMS mic with a range of 100Hz - 10KHz, good for just about all general audio recording/detection.

This breakout is best used for projects such as voice changers, audio recording/sampling, and audio-reactive projects that use FFT. To keep the breakout small and simple, we only added a 3V voltage regulator (the microphone requires 3.3V DC) and filter capacitors. No additional opamp is included, the output peak-to-peak voltage has a 0.67V DC bias and about 100mVpp (peak-to-peak) when talking near the microphone, which is good for attaching to something that expects 'line level' input without clipping. The peak-to-peak can be as high as 1Vpp if there's a very loud sound. If you are If you need a microphone with adjustable gain or auto-gain control, check out our mic+amplifier options. If you need a higher peak-to-peak, a rail-to-rail op-amp and some resistors can get you boosted up!

Using it is simple: connect GND to ground, Vin to 3.3-5VDC. For the best performance, use the "quietest" supply available (on an Arduino, this would be the 3.3V supply). The audio waveform will come out of the DC pin. The output will have a DC bias of 0.67V so when its perfectly quiet that's what you'll read, there's a little drift. If the audio equipment you're using requires AC coupled audio, you can grab the signal out of the AC pin, which has a 10uF capacitor in series.

This repo contains the PCB files for the Adafruit SPW2430 Breakout

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional information.
