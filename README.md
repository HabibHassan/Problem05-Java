Euclid's algorithm, is an efficient method for computing the greatest common divisor (GCD) of two integers, the largest number that divides them both without a remainder. It is named after the ancient Greek mathematician Euclid, and is often considered the first algorithm!

Algorithm:
If A = 0 then GCD(A,B)=B, since the GCD(0,B)=B, and we can stop.  
If B = 0 then GCD(A,B)=A, since the GCD(A,0)=A, and we can stop.  
Else GCD(B,A%B)

Example:
<br/>
A: 78, B:36
<br/>
A: 36, B:6 (78%36)
<br/>
A: 6,  B:0 (36%6)
<br/>
Answer: 6
