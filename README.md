# Wing Folding System with New GLDAB & ppm to PWMout

1) This system combines a New GLDAB by Arduino with convert PPM to PWM signal output and a system that folds the wings on the upstroke.

![250129 Wing motion](/image/250129%20Wing%20motion.jpg)


2) This was devised to make it more similar to the flapping of a real bird.

 The wings are folded by combining thin carbon plate parts.

 ![250208 Frame  Falcon141 Folding Wing SystemwithAGLDAB](/image/250208%20Frame%20%20Falcon141%20Folding%20Wing%20SystemwithAGLDAB.jpg)

 For this Ornithopter to fly, wings suitable for this system must be developed.

3) By flipping a switch, you can turn off the folding or keep the wings folded at all times (stoop).

4) The magnet sensor detects when the wings are entering the upstroke, and the servo folds the wings to the specified wing folding level for 1/4 of the flapping period. The wings then spread out by the top of the flapping and continue the downstroke with the wings spread out.

5) By operating the Aileron, one wing is folded, allowing the Ornithopter to turn left or right.

6) The two tail servos are set to Inverted VTail mixing in the CODE. It moves by operating the Rudder and Elevator, and you can control turning left and right and ascending and descending.



# How to operate

Ornithopter can fold its wings like a real bird

1) The wings fold when the wings are upstroke and spread when the wings are downstroke.

2) The magnet sensor detects when the wings are at their lowest position, and the wings are folded for 1/4 of a flapping cycle, and when the wings are downstroke, the wings are spread and swung down.

The time the wings are folded can be adjusted. Ch 6

The length of time the wings are folded is longer when the flapping frequency is low and shorter when the flapping frequency is high.

3) Stoop (stoop posture) can be switched on ch5.

There are three modes---Wing Folding mode, No Wing Folding Mode, Stoop mode

4) The degree of folding of the wings can be adjusted. CH7

5) NewGLDAB is built in, so the wings can be easily fixed in the gliding position.

6) The tail can be operated with two servos to control the Inverted Vtail.





##  Falcon141 Folding Wing System : Flap test ( with Making photos)

https://www.youtube.com/watch?v=LzfnhL0PMvs

## Falcon141 Folding Wing System : Flap test 2 with Wing Membrane

https://www.youtube.com/watch?v=vdpKn6cjO1Q

## List of Falcon141 Folding Wing System

https://www.youtube.com/playlist?list=PLErvdRrwWuPolGrbgrTzQfxIgkow6od_m


## Wiring

 ![250126 FoldingWingSystemwithPWMout&Arduino GLDAB](/image/250126%20FoldingWingSystemwithPWMout&Arduino%20GLDAB.jpg)


##  reference : 

New GLDAB by Arduino with convert PPM to PWM signal output 

https://github.com/KazuKaku/New-GLDAB-Arduino-with-PWM-output

A Novel Actuation Strategy for an Agile Bioinspired FWAV Performing a Morphing-Coupled Wingbeat Pattern 

https://ieeexplore.ieee.org/document/9849140

## My YouTube channel 
 Various Ornithopters have been uploaded.
(https://www.youtube.com/@BZH07614)

## My Website of ornithopter
 (http://kakutaclinic.life.coocan.jp/HabatakE.htm)

## Request site for production of Kazu Ornithpter
(http://kakutaclinic.life.coocan.jp/KOrniSSt.html)

