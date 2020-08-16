# talking-microbi

Go to the [micropython website](https://python.microbit.org/v/2.0) to enter this code

## part 1

```
# Add your Python code here. E.g.
from microbit import *
import music
import speech

while True:
    display.scroll('Hello')
    display.show(Image.HEART)
    sleep(2000)
    music.play(music.PYTHON)
    sleep(2000)
    display.show(Image.HEART_SMALL)
    speech.say("Learn to Invent,")
    speech.say("with the microbit!")
    sleep(2000)
```

## part 2
```
# Add your Python code here. E.g.
from microbit import *
import speech

display.scroll('microbit')
display.show(Image.HEART)
sleep(2000)
speech.say("I am a little robot", speed=92, pitch=60, throat=190, mouth=190)
sleep(1000)
speech.say("I am an elf", speed=72, pitch=64, throat=110, mouth=160)
sleep(1000)
speech.say("I am a news presenter", speed=200, pitch=255, throat=110, mouth=105)
sleep(1000)
speech.say("I am an old lady", speed=82, pitch=32, throat=145, mouth=145)
sleep(1000)
speech.say("I am a E.T.", speed=100, pitch=64, throat=150, mouth=200)
sleep(1000)
speech.say("I am a DALEK - EXERMINATE", speed=120, pitch=100, throat=100, mouth=200)
```
