Open Source Technologies (CEC21) Lab Project

# Indoor Navigation Android App

The aim of this project is to develop an android application for pinpointing the location of the android device in indoor surroundings. This can be useful for Indoor Navigation Systems which require the exact location of the device inside a building as for indoor navigation systems, the most challenging task is localising the phone. The level of accuracy required can't be achieved with the present GPS systems which are at max 5 meters accurate which is not good enough for indoor navigation. GPS also doesn't work in underground buildings. Many solutions have been proposed for this like using WiFi and Bluetooth devices (placed inside a building) to localise the phone. On the other hand, this android app uses the inbuilt gyroscope, magnetometer and accelerometer in the phone to localise the phone. Given the start position of the phone, these motion sensors are used to estimate the change in position (this process is called Dead Reckoning) and localise the phone with a very high accuracy of upto 4 feet.
