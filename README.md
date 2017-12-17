

# Your Project Title Here

My goal was to create a game-like interactive thermostat.

## Summary

This project will use a connected LCD screen to display the current temperature and change the display depending on the number read.

The most challenging part was coding the display part itself, everything else after goes pretty smoothly, granted that the thermostat works. These things seem to be pretty glitchy, and a lot of them don't give off any readings, I've found.


## Component Parts

- Arduino MEGA (input and output)
- TMP36 temperature sensor (input and output)
- 3.2' TFT LCD color screen (output)
- Jumper wires

[Fritzing diagram](https://drive.google.com/a/cca.edu/file/d/1-p4NJ48oKWVzbgLhkwBgPsI4trJ0rRzv/view?usp=sharing) (this isn't how the shield is connected since it's not the same one, but the thermometer is connected like this)

I'm using pin 15 as my analog input.

## Challenges

Except the technical difficulties of the temperature sensor not working, the coding of the display took the longest. It was also hard to figure out what exactly could and couldn't be done in Arduino compared to p5.js, so I had to backtrack on a lot of ideas and features in order to be able to make the project work.

Also, since my initial project didn't include a temperature sensor, I ended up having to order an Arduino MEGA much further into the project so it could support extra analog imputs. 

## Timeline

- Week 1: Written proposal
- Week 2: Ordered and received components of the project
- Week 3: Coded & tested
- Week 4: Coded & tested
- Week 5: Presentation

## Completed Work

[Photos and videos available here](https://drive.google.com/open?id=1eTCGgqlSSsFCVM1-Tbd6M8ubOg3NG9fo)

## References and links

[Color Picking guide](http://henrysbench.capnfatz.com/henrys-bench/arduino-adafruit-gfx-library-user-guide/arduino-16-bit-tft-rgb565-color-basics-and-selection/)

[16 Bit color generator](https://ee-programming-notepad.blogspot.com/2016/10/16-bit-color-generator-picker.html) 

[Very helpful!! Basic display commands](https://www.youtube.com/watch?v=Fj0yXP0tCLU)

[Using a temperature sensor](http://learn.adafruit.com/tmp36-temperature-sensor/using-a-temp-sensor)

[The screen I used](https://www.amazon.com/Elegoo-Inches-Screen-Technical-Arduino/dp/B01EUVJYME/ref=sr_1_7?ie=UTF8&qid=1513502111&sr=8-7&keywords=arduino+display)

Elegoo TFT and GFX libraries, since I wasn't using the original Adafruit display!



