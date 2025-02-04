## Fork from Alicja Musiał great Rocket model!

I only made crude stl modifications to improve:
- the thread strength of the bottom part 
- a shorter center core to conserve weight for flying weak A6-4 motors.
  (With the these motors it will just work. Flies 35m and opens half way down just in time)

New files:
- `rocket_A-1_short.ork`: simulation model for shorter verion, please adapt your weights!
- `3D_printable_components\Body_short.stl`: shorter version of center core

To conserve weight I printed it with a single perimeter and 10% infill, and reduced the infill anchor lenght to a quarter.
I used 5mm brims on the bottom part to keep it attached to the print bed. Printed on X1Carbon and Vyper
If the recovery wadding is properly reinstalled after the first flight, the center core will survive a couple of starts.

Will try to print it in LW-PLA at some point in time.

Copyright 2021 @alicjamusial. 

- This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. 
- http://creativecommons.org/licenses/by-sa/4.0/ 
- Attribution-ShareAlike 4.0 International 
- Website from Alicja: https://alicja.space/projects/rocket-a-1/

Original text:
# Rocket A-1 - 3D printed flying model rocket

![schema](images/rocket_model.png)

### ◾ About the project

**A-1** is a fully 3D-printable flying model rocket. It is threaded, so it doesn't require any glue to be assembled (except a little drop to attach the parachute or streamer cord to the cone (but I'll probably add a hook in the cone in incoming version to avoid this inconvenience)).

It is compatible with **Klima motors** (18mm diameter and 70mm length). It was tested with Klima C6-7 motor and flew nicely - the same model is ready to fly one more time.

Feel free to modify the model and create your own version best suited for your motor :). I'd love to see more A-1 fly!

![schema](images/a1_rocket.png)

### ◾ Files
This project consists of:
- `rocket_A-1.ork` file - rocket model and simulation created with [Open Rocket](http://openrocket.info/) software
- `Rocket A-1.f3d` file - rocket 3D printable model created in Autodesk Fusion 360
- `3D_printable_components` folder with three parts in `*.stl` format, ready to be printed

![schema](images/rocket_project.png)

### ◾ How high will it fly?
- Simulation from the OpenRocket (included below) shows something about 220m. I didn't put the altimeter inside **yet**, but I guess it could have been something around it.

![schema](images/flight_simulation.png)

- So just give it a try...
- ...or see how it takes off in action:

<p align="center">
  <img src="https://github.com/alicjamusial/rocket-a-1/blob/master/images/flight.gif?raw=true" />
</p>

### ◾ 3D printer hints
1. I printed the rocket on Ender 5 Pro. There's a possibility that your printer will require some adjustments in `*.stl` files to be able to print them properly.
2. It's good to use quite a big brims while printing fins - unfortunately they are quite likely to collapse and create not-so-nice PLA spaghetti 😬
3. I used PLA to print it, but ABS should be fine too. The rocket survived its first flight and it's getting ready for the next one, so PLA seems to be tough enough :).

![schema](images/rocket_section.png)

### ◾ Known issues
1. The nose cone lacks a hook to attach the cord from the parachute or streamer, so it's unavoidable to use a bit of glue.
2. Launch lug should be placed on the bottom component, between two fins (not on the middle component).
