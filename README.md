# Speech music discriminator

This code implements a method for a speech/music discriminator based on RMS and zero-crossings.

Matlab Code: https://www.mathworks.com/matlabcentral/fileexchange/42092-a-speech-music-discriminator-based-on-rms-and-zero-crossings

This code is a simple implementation of [1], [2]. The function trmszc implements the main algorithm. The input of the method is a .wav file.

Instructions about the parameters of trmszc and how to run it, are given as comments in the start of trmszc.m.
It yields a sound segmentation and classification with 20 msec accuracy.

Classes: Music, Voice(Speech), Silence
You can use this software for non commercial purposes. Please, cite the articles [1], [2].

If you want to use the software for commercial purpose you have to contact with the authors of [1].

[1]. C. Panagiotakis and G. Tziritas, A speech/music discriminator based on
RMS and zero-crossings, IEEE Transactions on Multimedia, Vol. 7, No. 1, Feb. 2005.

[2] C. Panagiotakis and G. Tziritas, A Speech/Music Discriminator using
RMS and Zero-crossings, European Signal Processing Conference, 2002.

For more details visit: www.csd.uoc.gr/~cpanag
www.csd.uoc.gr/~tziritas
