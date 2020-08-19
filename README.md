# polyrhythm
A Max MSP patch that first recognizes intervals between any two notes on a MIDI controller, then generates polyrhythms based off of the interval ratios.
Video explanation: https://www.youtube.com/watch?v=tjzW8zZ6xR8 

* Connect your MIDI controller to your laptop. Click the blue bang button and select your MIDI controller from the drop down menu. 
* Make sure that the [transport] object is on by turning on the purple toggle. Then choose your tempo. 
* Play any two notes on your MIDI controller, or click on any two notes on the [kslider] object on the screen. 
* The two notes that are chosen need to be pressed within 1000 milliseconds, otherwise these notes do not register. You can change the threshold of this time with the int box above the [thresh 1000] object.  
* If you want to turn the MIDI sound on/off there is a Master toggle, as well as individual toggles for each cycle. If you want to hear all three sounds, make sure the master toggle is on, and it will turn on all three toggles together. 
* If you want to have your velocity controlled via your mouse clicks or MIDI controller presses, then turn on the toggle next to the velocity. Otherwise the velocity is automattically 100. When you turn this toggle off again, the velocity will reset to 100.
