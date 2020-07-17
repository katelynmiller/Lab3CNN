# Lab3CNN
Lab 3 EAI 


Assessment 3

P= (2,2)
Result = (3,3) for size

Assessment 4

O = ((I -F + 2P) / S) + 1
I = 100,100 f = 2,2 S = 1 , P = 0

(100 - 2 + 2*0) / 1) + 1

(98/1) + 1 = 99

(99,99)

Input (99,99)

Conv(2_24) = (2,2) * 24 = 96
conv(2_25) = (2,24) * 24 = 1,152


Solve for Padding : 

O = ((I - F + 2P)/S) + 1
O+1 = ((I - F + 2P)/S)
S*(O+1) - I + F = 2P
((S*(O+1) - I + F) / 2) = P



