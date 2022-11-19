# ESE5190_LAB2B_PART1-10

In Part 9, we implemented the APDS9960 support on our system in a way such that the neopixel on the QtPy board would glow red, green or blue as per the light falling on it. This is shown in the video below:


https://user-images.githubusercontent.com/114092868/202834268-cf4f3ac5-b0af-4cee-9b2e-28748ca74feb.mp4


While moving the APDS9960 sensor across the light and dark modes we observed that there is a misalignment due to the delay between the input received by the APDS9960 sensor and the output given by the neopixel. This is because the PWM module is not in alignment with the PIO RGB packets and this could be identified as jitter. We have shown this in the videos attached below.


Red:

https://user-images.githubusercontent.com/114092868/202834283-c7018b10-455b-4fea-bfeb-7aee3de469f2.mp4


Green:

https://user-images.githubusercontent.com/114092868/202834308-4024dc83-186c-448a-8c59-71030507c9dc.mp4


Blue:

https://user-images.githubusercontent.com/114092868/202834321-73979dd3-9302-408b-9ee7-785b988ff2ba.mp4

We took reference from Dang0v.
