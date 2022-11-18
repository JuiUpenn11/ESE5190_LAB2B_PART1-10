# ESE5190_LAB2B_PART1-10

In Part 7, we modified our sequencer code to use PIO as its primary I/O engine. When we press the boot button of QtPy, it captures the data which we have shown using both serial terminal Putty and PySerial. We used the code from part 6 of logic analyser and integrated it with our sequencer code from part 3 to implement PioSequencer. We record boot button presses on QtPy which are then played on neopixel while simultaneously capturing the data using the logic analyser. The capture on the serial terminal Putty and Pyserial is as shown below. 


Putty:


![Capture 1](https://user-images.githubusercontent.com/114092868/202811801-ce37e53f-d721-4510-93d1-dc62a848f6e4.png)


![Capture 2](https://user-images.githubusercontent.com/114092868/202811870-f6260f23-f6fe-423c-b60a-73e8885f0a64.png)


PySerial:


![Capture using Pyserial](https://user-images.githubusercontent.com/114092868/202811902-978832d9-df55-4610-b5fb-3430744470f6.png)


Gif:


![Piosequencer](https://user-images.githubusercontent.com/114092868/202811953-db4f0c23-26f8-4c99-b4ee-aa433e653ebf.gif)






