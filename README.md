# Wing Folding System with New GLDAB & ppm to PWMout

1) This system combines a New GLDAB by Arduino with convert PPM to PWM signal output and a system that folds the wings on the upstroke.

2) This was devised to make it more similar to the flapping of a real bird.

3) By flipping a switch, you can turn off the folding or keep the wings folded at all times (stoop).

4) The magnet sensor detects when the wings are entering the upstroke, and the servo folds the wings to the specified wing folding level for 1/4 of the flapping period. The wings then spread out by the top of the flapping and continue the downstroke with the wings spread out.

5) By operating the Aileron, one wing is folded, allowing the Ornithopter to turn left or right.

6) The two tail servos are set to Inverted VTail mixing in the CODE. It moves by operating the Rudder and Elevator, and you can control turning left and right and ascending and descending.


New GLDAB by Arduino with convert PPM to PWM signal output 

https://github.com/KazuKaku/New-GLDAB-Arduino-with-PWM-output