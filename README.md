# I2C-Repository
Repo for I2C task SIT210

For this task, i did not have any specialised sensors for working with I2C.
Instead, i decided to use I2C to bridge between the RPi (working as a Master) and the Particle Photon (working as a slave).
The light Sensor that i used was connected to the Photon, and the final program result was printed on the RPi.
Whilst they were physically connected using a USB (for powering the Photon), the data transfer all happened through I2C.
