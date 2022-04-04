# CS410P Music, Sound & Computers
**Name: Carson Hansen**



**Project Name: HW 1 Clipped **


**Description**
To generate the sine and clipped wave, I used the built-in sin function that is in the math.h library.
I used the SFML library to do the heavy lifting of converting the sine-waves into .wav files. I then used 
the sound functionality of SFML to play the sound of the clipped wave.

**How it went**
The project started a bit rocky, as I had a hard time initially getting libsndfile to properly link in visual studio.
I eventually gave up and decided to use SFML instead and had a much easier time getting it linked properly. This library
was easy to use once I got everything set up and running.

**What needs to be done**
This program does everything that is required. It generates a sine wave that has 1 channel, uses a 16-bit sample size, has a
one-second duration, has a frequency of 440Hz, and a sample size of 48000. The sine wave has an amplitude of 1/4 of the maximum possible
16-bit amplitude range of -8192 - 8192. The clipped wave can generate 1/2 the maximum possible 16-bit amplitude range of -16384 - 16384 and
will clip any samples to a minimum of -8192 and a maximum of 8192. This program also *does not* use an external program to play the audio and 
instead uses the audio player the SFML library provided.

