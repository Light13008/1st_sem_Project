# 1st_sem_Project
A real world working prototype of an instrument used in sound engineering for constructing Space noises. A very practical and similar use could be seen in Star wars.

A aurdino based muscial instrument was built to mimic spacial noises.
The prototype is a musical instrument that generates sound without physical contact. It uses an Arduino microcontroller to control the pitch and volume of the sound based on the position of a user's hand or any other object in proximity to the sensor.

Here's a basic explanation of how  my prototype works:

1. Hardware Setup:
   - Ultrasonic Sensor: An ultrasonic sensor is connected to the Arduino board. This sensor emits ultrasonic waves and measures the time it takes for the waves to bounce back after hitting an object.
   - Speaker: A speaker or piezo buzzer is connected to the Arduino board to generate sound.

2. Distance Measurement:
   - The Arduino board sends out ultrasonic waves from the sensor and measures the time it takes for the waves to return.
   - Based on this time measurement, the Arduino calculates the distance between the sensor and the object (such as a hand).

3. Pitch Control:
   - The distance measurement is mapped to a specific range of frequencies or musical notes.
   - As the distance between the object and the sensor changes, the Arduino adjusts the pitch of the sound output accordingly. Moving the hand closer or farther from the sensor alters the pitch of the generated sound.

4. Volume Control:
   - The Arduino also uses the distance measurement to control the volume of the sound.
   - As the distance between the object and the sensor changes, the Arduino adjusts the volume level of the sound output. Typically, moving the hand closer to the sensor increases the volume, and moving it away decreases the volume.

5. Sound Generation:
   - Based on the calculated pitch and volume values, the Arduino sends appropriate signals to the speaker or piezo buzzer.
   - The speaker converts these signals into audible sound, creating a musical tone.

Prototype allows users to interact with the instrument by moving their hand or any other object in the sensor's proximity. The movements control the pitch and volume of the generated sound, enabling the user to create music by manipulating the position of their hand or object in the air.
