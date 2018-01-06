# virtual-garage-temp
So I have a Samsung SmartThings Multipurpose Sensor that I use on my garage door. The multipurpose sensor does more than just measure if it is open or closed; it also measures things like the temperature in my garage.

I wanted to view the Garage temperature in my SmartThings app without it being buried under the status of my garage door being opened or closed. To do this, I needed to do the following:

1. Create a virtual sensor
2. Use the CoRE SmartApp to copy the "temperature" variable from my Multipurpose Sensor to the Virtual Sensor anytime the value changed.

My GitHub code accomplishes item 1 - creates a virtual sensor. I could have used the generic "Simulated Temperature Measurement" but I liked having more control over things such as the icon, tile display, etc, so I made my own.
