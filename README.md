# IoTHeartRateMonitor
An IoT heart rate monitor comprised of a Particle Photon computing board and a custom modeled, 3D ABS printed plastic encasing. An RGB light sensor attached to the particle photon receives color from your finger. RGB values are signal processed on the Photon using a combination of peak finding, standard deviation filtering, and adaptive zero crossing. The Photon is conveniently build for IoT projects and I was able to access the variable data on the physical chop through particle's IoT backend and provided APIs. A jQuery script on my webpage grabbed the variable data and made it availible for the user on their mobile device. 