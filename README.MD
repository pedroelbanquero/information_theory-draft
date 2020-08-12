Posible aplications in encoding system who keep the value of the factors in the product , coding the numbers as a representation of (SUM FACTORS), GoldBach Counting with finite solutions depending the bits of the number, at expenses of increase the computation cost for the encoding.

377 = 13 * 29 

SUM FACTORS = 13+29 = 42

The goldbach finite probabilities of 42 are 3, to solve the goldbach conjecture who says , any even number can be composed at least by the sum of two primes. 


````
*Nss> goldbach 42

[(5,37),(11,31),(13,29),(19,23),(23,19),(29,13),(31,11),(37,5)]


````


Probability 1 of glodbach 42 - 5+37 = 42
Posibility 2 of glodbach 42 - 11+31= 42
Posibility 3 of glodbach 42 - 13+29 = 42


By the way can encode 377 --> (42,3) , 9 bits  vs 6+2+1 bits structure.

You lose a bit to know if the number is odd or even. because the conjecture just apply to even numbers. Not bad to encode privatekeys and public keys in the same bits of space than just the public key.

To decode just make goldbach of the first parameter 42 get the option 3, make the product 13 * 29(P Q)  and you have the 377 (N) 

By this way in information terms in a product of primes (the most of the numbers) you can keep the information about wich factors have in N with more or less the same bits than just N.


# Information theory


*In perfect encoding, all diferent symbols. If all symbols are different you can't compress nothing. If the data are encoded at the perfect base for N symbols.


Normal bits for N in information theory b information = logBase 2 N = number of bits

Normal bits in N + P + Q in Sum Factors NSE = logBase 2 N = number of bits
