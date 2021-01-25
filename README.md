# Display (Output) Arduino Project

This is a simple project in Arduino that uses 
the breadboard, the microcontroller, 
a 7-segment display and basic programming.

## The Arduino UNO Board

![board](https://raw.githubusercontent.com/xdvrx1/single-display-arduino-project/main/res/src1.png?token=ALHJF4G3P5I36AWVB5IPUGTABY432)

The Arduino UNO Board is the basic board
for beginners doing project in Arduino.

As from the previuos project, without
a microcontroller, you're only control is 
through an external switch. And you
are just limited to that.

The microcontroller will enable you to
program electronic components so that you
can build digital devices that you want
to build.

### The Digital Pins
The digital pins are the very first to be 
encountered because they can be used by
components in several ways.

### The GND
The GND is the floating ground to complete
the circuit. Remember, in an electrical setup
the earth ground is used extensively. In
electronics, it's the convenience to use
a floating ground.

## The BreadBoard
Breadboards are convenience for you to
simply put things in place. Plus,
it provides connections either horizontally
or vertically for further ease. Because
of this, you avoid overlapping wires:
the metal strip at the bottom of a breadboard
will do the job.

## The 7-segment Display
![display](https://raw.githubusercontent.com/xdvrx1/single-display-arduino-project/main/res/src2.png?token=ALHJF4AUK36KCLDJMPZEJADABY5LI)

To not complicate things, we just use one 7-segment
Display for the output. Remember, computer monitors 
concept of display is the same: the dot-and-no-dot
pattern to create a display, whether an image
or letter or numbers. You can do the same thing
by using LEDs to serve as pixels.

But here in our project, we want to use the 7-segment
display as an upgrade from the LEDs.

The 7-segment display will either use `cathode` or 
`anode`. Make sure you got it right.

## The Arduino Code
There are just two default functions in Arduino:
`void setup` and `void loop`.

`void setup` is where you tell the Arduino board about
the common setup just like whether a digital pin will
be used as output or input.

`void loop` is where the Arduino board executes
all the commands you put there just like
`digitalWrite` whether high or low.

## Project Guide
Using the TinkerCAD, 
here are the steps to create the project:

1. Follow the proper wiring:

2. Close the circuit by the GND. Use a resistor
that is exactly --- 

3. Copy paste the program below:

4. Of course, simulate the program! 

5. Challenge: add a border using LEDs and 
display letters instead of numbers.
