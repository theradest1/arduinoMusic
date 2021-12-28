# arduinoMusic

connect a *real speaker* (peizo will sound really bad) to ground and digital pin 11

-------------

if you want to do it yourself: http://highlowtech.org/?p=1963

synapsis (fast explination for advanced folks with no time):
-------------

arduino library:

https://github.com/damellis/PCM/zipball/master
-------------

install these (unzip):

Windows (ew): https://highlowtech.org/wp-content/uploads/2011/12/EncodeAudio-windows.zip

Mac OS X (ew): https://highlowtech.org/wp-content/uploads/2011/12/EncodeAudio-macosx.zip

Linux (nice): https://highlowtech.org/wp-content/uploads/2011/12/EncodeAudio-linux.zip
-------------

get an audio (like 20 secs at most), make the quality 16 and the sample rate 8 (audacity works well), save that somewhere and open it with the program above. replace that big ass array in the example program by pasteing (sometimes pasting doesnt work with a huge array so just shorten the audio a bit) then cut down on the end of the array untill it fits in the arduino storage (just compile to test). have lots of funzies (:
