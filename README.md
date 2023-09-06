# Melodicade Void
A portable 8+ octave, 3D printed, velocity sensitive MIDI keyboard and synthesizer, using Hall Efect mechanical key-switches (<a href="https://github.com/riskable/void_switch">Void Switches</a>) arranged in the Wicki-Hayden button layout.


# In Development
## Code
I am still doing some experimentation at the breadboard level Uploaded code is not current.

## Buttons
Analog buttons are likely to diverge from Void_Switch model due to unliked snap that is very unpiano like. 

## Display
I settled on the (<a href="https://learn.adafruit.com/adafruit-3-5-color-320x480-tft-touchscreen-breakout/overview"> adafruit-3-5-color-320x480-tft-touchscreen-breakout</a>). 
It's not ideally what i wanted but the 2.5 inch screen I got from NewHaven was not SPI. I could probably convert it but that's too much hassle. the downside is the adafruit screen is not daylight readable...

## Key Layout
I have 10 16bit MUX chips. I can actually squeeze in 8.5 octaves though a standard 88 Key == 7.25 Octaves. With the Hexagon Keyshape I can keep the overall depth of the board somewhat shallow but you can see how this is starting to diverge. I suppose the question is ultamately Why? and I have to answer that with, Why Not? Music is about creativity and exploration ans much as it is about just playing everyday music. There are 8 octave Pianos in the world and it could be interesting to see what we can do with it. Alternatively if it doesn't work the way i like then we can always reprint the model and shorten up the key layout to something more standard. 

