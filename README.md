# End-to-End-Communications-system
In this repository we design and simulate some Deep Learning-Based End-to-End Wireless Communication Systems.
The following methods have been proposed :
1. End-to-End wireless communication system using conditional GAN as unknown channel over AWGN channel
2. End-to-End communication system over AWGN channel while the channel is known(No GANs for modeling the channel)
3. End-to-End communication system over Rayleigh channel while the channel is known(No GANs for modeling the channel)
4. Hamming coding and decoding with Maximum Likelihood Decoder in Rayleigh Fading channel
5. Hamming coding and decoding with Maximum Likelihood Decoder in AWGN channel
6. ...

Simulation Results :

The following figures compares learning based methods with some of the SOTA traditional communication systems over 3 communication channels :
1. AWGN 
2. Rayleigh Fading
3. Frequency selective multipath

It can be understood that the conditional GAN has been able to comprehend the distribution of the corresponding communication channel and even surpasses some of traditional methods.

![Screenshot](https://github.com/moeinheidari/End-to-End-Communications-system/blob/main/Results/awgn%20results.png)
![Screenshot](https://github.com/moeinheidari/End-to-End-Communications-system/blob/main/Results/rayleigh%20results.png)
![Screenshot](https://github.com/moeinheidari/End-to-End-Communications-system/blob/main/Results/multipath%20results.png)


