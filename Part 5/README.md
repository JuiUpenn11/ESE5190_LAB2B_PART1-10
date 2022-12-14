# ESE5190_LAB2B_PART1-10

Description of Lab:

In Part 5 we were asked to use the LAb 1 code of Firefly and generate I2C traffic and display it on a lab oscilloscope. As we had erased the memory of our RP2040 QtPy board for the previous lab sessions, we first had to download CircuitPython.UF2 file and then we had to burn it to our board. After that we were able to upload the Firefly code we had previously used for Lab 1. I will quickly go over what our Firefly code does before proceeding to the I2C part. The components used for this lab session are RP2040 microcontroller and APDS9960 sensor board. The aim of this lab session was to turn on the LED on RP2040 when the APDS9960 color sensor senses bright light and turn off the LED when there is no bright light falling on the LED thus enabling the blinking of the LED. With respect to the attached video and GIF, it can be seen that the Color and ALS detection feature of RP2040 provides data regarding Red, Blue, Green and Clear light intensity. We set a threshold value for the clear light and when the light source was flashed at the sensor, the serial monitor printed the data for Red, Blue, Green and Clear light and the LED on RP2040 turned on. When the light source was dimmed and could not cross the threshold, the monitor printed data for Red , Blue, Green and Clear light which were lesser than the previously printed values thus showing a difference in the intensity and the LED on RP2040 was also turned off. This behavior of the LED mimics the behavior of a Firefly. 

Description of connections:

Having described the aim of our Firefly code, we can now move on to generate APDS9960 I2C traffic on a lab oscilloscope. For this purpose we used the Agilent Technologies 7000 series oscilloscope and a logic analyzer. As we are using a logic analyzer, set the mode to digital on the oscilloscope. Select D1 and D0 on the oscilloscope. Then make the connections such that the SCL pin  is connected to the D0 and the SDA pin is connected to D1 of the logic analyzer probe and the ground pin to the ground probe of the logic analyzer. This gave us the output as shown in the following images. 

Description of images:

Our images show 4 waveforms out of which the green and yellow ones are produced using a normal probe which is why they are a bit noisy and the red and blue ones are clear as we used a digital analyzer. Finally we used a pendrive to copy our images. In this lab session we observed that a lot more data was being passed when light was falling on the LED versus when light was not falling on the LED.


