Much better code here. 
First of all: it works.
Also, for example, the routine to generate base three number is nicer than the first one

![alt text](https://github.com/z374/100-sum/blob/master/7-July/numeribase.png)

The new method return the next number in base three-rapresentation. I like the fact that it does not use any "math" to derive the result, it's just a "language pattern". All you have to do is pass a string and it will return the next base three number. For example:
"000" --> "001" --> "002" --> "010" --> "011" --> "020" --> and so on...

About the problem: It's clear that the number of possible solution is correlated to the 3^8 combinations generated (in the begin.. i thought there were 3^9...facepalm). So u see a for cycle with a 6500 cap somewhere. In fact, the rest of the code written is still total crap. I just wanted to make it works (and it actually does).


Here is the output:

![alt text](https://github.com/z374/100-sum/blob/master/7-July/somme.png)

Ps. i would like to resize this image... but ...it's too boring to do.
