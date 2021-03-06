# Teaching CircuitPython with Code Kitty

Dylan Miracle

![Code Kitty](ck22.jpg)

## The Problem

- Kids need access to robotics and coding experiences that are not overly intimidating, but also are not single function, non-extensible toys.
- Teachers need support introducing coding and robotics to students.
- Teachers and students need robots they aren't afraid to break and that they can easily and cheaply fix.

## [Code Kitty - the Organization](codekitty.org)

- Brain child of Jill and Jason Woyak
- Education non-profit ~17mos old
- Mission to make a cheap robot that offers a real coding experience
- All volunteer

## [Code Kitty - the Robot](https://www.thingiverse.com/thing:3059371)

- 3D printed
- Trinket M0
- some servos, batteries, screws and a custom breakout board
- Open Source / Open Source Hardware
- Curriculum, grades 2 and up

## [CircuitPython](https://learn.adafruit.com/welcome-to-circuitpython/overview)

- Adafruit fork of MicroPython
- Runs on a variety of microcontrollers
- Insanely easy to get working
- Runs on major OSes (even Chrome)
- Tons of documentation and projects
- [Mu editor](https://codewith.mu/)
- ChromeOS: text and beagle term
- [codekitty.py](https://github.com/MnCode-CodeKitty/codekitty)

```python
print("Code Kitty v2.2 online")
from codekitty import *
from time import sleep
while True:
    if(sensor.value < 6000):
        led("purple")
        beep()
    else:
        led("red")
    
    if(touch.value == True):
        go(.2)
        led("blue")
        sleep(.1)

```
- REPL

## Events

- Classroom Workshops
- Brews and Bots
- Badges and Bots
- Roll your own
- Seminar: \$50 per person, keep your bot, price breaks at volume
- You can do it without us (but you should at least send us a picture)

## Future

- [Circuit Playground Express](https://www.adafruit.com/product/3333)
- Get better at CircuitPython
- Need more volunteers!