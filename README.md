# Arduino-HC-05-RC-Car
- This repository contains the code to create a functional RC car using two arduino uno R3s, two HC-05 bluetooth modules that are hard paired to each other, a brushless motor with an ESC for driving wheels, and a servo motor for the steering.
- In order for this code to work the two HC-05 modules must be hard paired to each other (as stated above) this can be accomplished by entering commands to the module using the serial monitor on an empty sketch. As this process can be touchy I have linked
  below a youtube tutorial that simply and effectively demonstrates how to pair the two modules.
  https://www.youtube.com/watch?v=BXXAcFOTnBo&t=157s
  **All credit for the content in the YouTube video above goes to the original creator PatchBOTS**
- The master file should be uploaded to the transmitter for the car, which in this case uses two joysticks as the control method
- The slave file should be uploaded to the arduino found in the car
