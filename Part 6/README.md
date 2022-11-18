# ESE5190_LAB2B_PART1-10

In part 6, we have implemented a pioscope by modifying the logic analyser in order to record a timestamped trace of an RP2040-APDS9960 exchange whenever the boot button is pressed. The timestamped trace is attached below. 22 stands for SDA and 23 for SCL. 


![Logic Analyser 1](https://user-images.githubusercontent.com/114092868/202714353-17d981c2-48cb-4834-abc5-449200add033.png)


We then connected one Qtpy board to the APDS9960 sensor and connected that to another QtPy board. We were running the code of our logic analyser on the first QtPy and the code of our Lab 1 on the second QtPy board. The Lab 1 code basically did the following function. It made the neopixel LED blink whenever the light falling on the APDS9960 sensor crossed a threshold value. This exchange was recorded on the serial terminal Putty as shown in the image below.


![Logic Analyser with python code](https://user-images.githubusercontent.com/114092868/202714421-130c820a-9c9f-4087-89e3-7b48d8ef030e.png)
