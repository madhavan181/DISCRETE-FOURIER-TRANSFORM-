# EXP 1 A : COMPUTATION OF DFT USING DIRECT AND FFT

# AIM: 

# To Obtain DFT and FFT of a given sequence in SCILAB. 

# APPARATUS REQUIRED: 
PC installed with SCILAB. 

# PROGRAM: 
// DISCRETE FOURIER TRANSFORM 
```
clc;
clear;

x = [1 4 0 8];
N = length(x);
X = fft(x, -1);

subplot(2,1,1);
plot2d3(0:N-1, x);
xtitle("Original Sequence x(n)", "n", "Amplitude");

subplot(2,1,2);
plot2d3(0:N-1, abs(X));
xtitle("Magnitude Spectrum |X(k)|", "k", "Magnitude");
```

# OUTPUT: 
![WhatsApp Image 2025-09-01 at 15 24 39_9802c260](https://github.com/user-attachments/assets/6bc1db20-df07-49bd-91da-14b8ee49d8c6)

# RESULT: 
Thus the desired result is obtained
