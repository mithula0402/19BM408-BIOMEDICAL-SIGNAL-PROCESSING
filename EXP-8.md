# HAMMING WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Hamming Window and study its frequency characteristics.
# THEORY:

Hamming window is defined as:

w(n)=0.54-0.46cos⁡(2πn/N)

Characteristics:
Reduced side lobes

Better stopband attenuation (~41 dB)

Slightly wider main lobe than rectangular

Reduced ripple

Design Equation:

h(n)=h_d (n)⋅w(n)

Where hd(n) is ideal impulse response.

# ALGORITHM:
1.	Choose N and ωc
2.	Compute ideal impulse response
3.	Generate Hamming window
4.	Multiply and obtain h(n)
5.	Plot magnitude & phase

# MATLAB CODE :
<img width="1079" height="965" alt="image" src="https://github.com/user-attachments/assets/bfc9054d-c1bc-4e88-b92f-90c66d6aeac4" />

# OUTPUT GRAPH :
<img width="1600" height="1201" alt="image" src="https://github.com/user-attachments/assets/d8d27e4e-620e-4bfd-9ef2-7a63ea791c72" />
<img width="1600" height="1201" alt="image" src="https://github.com/user-attachments/assets/a5135472-33f1-4b01-aaff-f38785ccf658" />


# RESULT :
The FIR filter was designed using Hamming window .

