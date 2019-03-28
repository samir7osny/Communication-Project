# Communication-Project
#
#
# Binary Phase Shift Keying Modulation (BPSK)
#### BPSK is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### Instructions
- Connect the original signal to the BPSK modulator and add some noises by AWGN channel block and connect the output to the BPSK demodulator 

- Connect the received signal and the original signal to the Error rate calculation block

1. Random Integer Generator
    * Initial seed = 37
    * Samples per frame = 100
2. BER diagrams are set from -10 to 10 dB and step 0.5

## - Screenshots
1. Scheme
![1. BPSK Scheme](/BPSK_Scheme.png)
## Scatter Plot:
2. BPSK Before Noise
![BPSK Before Noise](/BPSK_Before_Channel.png)
3. BPSK After Noise
![BPSK After Noise](/BPSK_After_Channel.png)
4. BPSK Error Curve
![Error Curve](/BPSK_BER_Figure.png)
------------------------------------------------------
# Quadrature Phase Shift keying Modulation (QPSK)
#### At the modulator’s input, the message signal’s even bits (i.e., 2nd bit, 4th bit, 6th bit, etc.) and odd bits (i.e., 1st bit, 3rd bit, 5th bit, etc.) are separated by the bits splitter and are multiplied with the same carrier to generate odd BPSK (called as PSKI) and even BPSK (called as PSKQ). The PSKQ signal is anyhow phase shifted by 90° before being modulated.
### The modulation Schema contains: 

### Instructions
- Connect the original signal to the QPSK modulator and add some noises by AWGN channel block and connect the output to the QPSK demodulator 

- Connect the received signal and the original signal to the Error rate calculation block

1. Random Integer Generator
    * Initial seed = 37
    * Samples per frame = 100
2. BER diagrams are set from -10 to 10 dB and step 0.5

## - Screenshots
1. Scheme
![QPSK Scheme](/QPSK_Scheme.png)
## Scatter Plot:
2. QPSK Before Noise
![QPSK Before Noise](/QPSK_Before_Channel.png)
3. QPSK After Noise
![QPSK After Noise](/QPSK_After_Channel.png)
4. QPSK Error Curve
![Error Curve](/QPSK_BER_Figure.png)
------------------------------------------------------
# Frequency Shift Keying Modulation (FSK)
#### This model simulates frequency shift keying modulation (FSK), which is a method for converting a digital signal to a complex signal. In this techinque the frequency of the carrier signal varies according to the digital signal changes.

### Instructions
- Connect the original signal to the FSK modulator and add some noises by AWGN channel block and connect the output to the FSK demodulator 

- Connect the received signal and the original signal to the Error rate calculation block

1. Random Integer Generator
    * Initial seed = 37
    * Samples per frame = 100
2. BER diagrams are set from -10 to 10 dB and step 0.5

## - Screenshots
1. Scheme
![FSK Scheme](/FSK_Scheme.png)
## Scatter Plot:
2. FSK Before Noise
![FSK Before Noise](/FSK_Before_Channel.png)
3. FSK After Noise
![FSK After Noise](/FSK_After_Channel.png)
4. FSK Error Curve
![Error Curve](/FSK_BER_Figure.png)
------------------------------------------------------

# 16-Quadrature Amplitude Modulation (QAM16)
#### QAM is a signal in which two carriers shifted in phase by 90 degrees (i.e. sine and cosine) are modulated and combined. As a result of their 90° phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or “I” signal, and the other is the quadrature or “Q” signal.

### Instructions
- Connect the original signal to the QAM16 modulator and add some noises by AWGN channel block and connect the output to the QAM16 demodulator 

- Connect the received signal and the original signal to the Error rate calculation block

1. Random Integer Generator
    * Initial seed = 37
    * Samples per frame = 100
2. BER diagrams are set from -10 to 10 dB and step 0.5

## - Screenshots
1. Scheme
![QAM16 Scheme](/QAM16_Scheme.png)
## Scatter Plot:
2. QAM16 Before Noise
![QAM16 Before Noise](/QAM16_Before_Channel.png)
3. QAM16 After Noise
![QAM16 After Noise](/QAM16_After_Channel.png)
4. QAM16 Error Curve
![Error Curve](/QAM16_BER_Figure.png)
-----------------------------------------------------------
# 64-Quadrature Amplitude Modulation (QAM64)
#### QAM is a signal in which two carriers shifted in phase by 90 degrees (i.e. sine and cosine) are modulated and combined. As a result of their 90° phase difference they are in quadrature and this gives rise to the name. Often one signal is called the In-phase or “I” signal, and the other is the quadrature or “Q” signal.

### Instructions
- Connect the original signal to the QAM64 modulator and add some noises by AWGN channel block and connect the output to the QAM64 demodulator 

- Connect the received signal and the original signal to the Error rate calculation block

1. Random Integer Generator
    * Initial seed = 37
    * Samples per frame = 100
2. BER diagrams are set from -10 to 10 dB and step 0.5

## - Screenshots
1. Scheme
![QAM64 Scheme](/QAM64_Scheme.png)
## Scatter Plot:
2. QAM64 Before Noise
![QAM64 Before Noise](/QAM64_Before_Channel.png)
3. QAM64 After Noise
![QAM64 After Noise](/QAM64_After_Channel.png)
4. QAM64 Error Curve
![Error Curve](/QAM64_BER_Figure.png)