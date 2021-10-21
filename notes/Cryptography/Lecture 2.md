#Cryptography 
# Lecture 2

## Hamming Code
### Hamming(7,4) Code 
single error correcting code
4 binary bits + 3 extra parity bits
### How to encode in Hamming(7,4)
p1 = (d1+d2+d4) mod 2,  p2 = (d1+d3+d4) mod 2,  p3 = (d2+d3+d4) mod 2
Encoded codeword 	p1p2d1p3d2d3d4
### How to correct an error in Hamming(7,4)
s3 = (p1+d1+d2+d4) mod 2 	 s1 s2 s3 = 000 means no error	
s2 = (p2+d1+d3+d4) mod 2           otherwise convert s1 s2 s3  to decimal n
s1 = (p3+d2+d3+d4) mod 2	 the error is at nth position	     
#### Hamming(8,4) Code – adding an extra parity check bit for all 7 bits, double error detecting
#### As a homework, workout what is the hamming distance for Hamming(7,4)
