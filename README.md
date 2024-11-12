# TB444-LED-Slave-Strip
Mirror of TheoryBoard 444 firmware LED key colour assignment as a strip of LEDs across a conventional keyboard 

I am currently building a MIDI-to-LED interceptor box to have a dynamic colour 60 LED strip directly above my 5 octave keyboard.
When you set a scale on the TB, only the LEDs above the keys that can be played, light up dimly, but go bright when a TB key is pressed.

This is darn close to what it will look like:-  https://youtu.be/4NerqZ8Fpcw

The circuit takes only one pin on the Arduino, and the project is documented here :- https://www.instructables.com/id/MIDI2LED/

To do this myself, would involve taking the MIDI feed form the TheoryBoard 333 hardware with the TB444 firmware (in development here :- https://github.com/Miq1/FredBoard/issues)
build a combination of the two projects above, and write code to map a table of colours created from the ones used in the firmware.

The biggest headache for me is that as the TB444 colours can be customised. To capture the table assignment would require the developer to issue a SYSEX data block of the note and colour codes per note to be able to match them.
To create this manually, well....

I am currently in discussions with the developer so I have created this project here as a place marker for discussions. 
