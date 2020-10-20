# Euler's Twisted Machine
Prime Generator based on Mathologer's video

The method is as follows: Generate an sequence where each index in the array is the sum of that number's prime factors.
Then, subtract the index number from each element. 
If the number is 1, then it is a prime number (because only prime numbers factor into 1 and itself).

Now, to generate that sequence is more complicated. 
It relies on partition numbers, and to get that sequence requires another sequence, which itself requires a sequence.

Basically, the Spaces sequence makes the Arr sequence, which in turn creates the Sequence described above.

