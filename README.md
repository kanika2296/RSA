# RSA

This is a simple implementation of RSA algorithm in pure python

## Algorithm
1. Select two prime numbers, p and q.
2. Calculate n=pq.
3. Calculate f(n)=(p-1)(q-1).
4. Select e  such  that  e  is  relatively  prime  to  f(n)  and  less  than  f(n). Determine d  such  that demod f(n) = 1 mod f(n).d  can  be  calculated  using  the extended Euclid’s algorithm (used in this code)

### Input
This program takes input :
1. prime number p
2. prime number q
3. Message m

This program inputs message as string, convert each character to their ASCII value for RSA.
