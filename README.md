# Project-Euler-Files
Files I have used to solve problems from Project Euler

Problem 1

I didn't use the most effecient algorithm to solve this. I've seen the explanations for faster solves posted, but since I don't understand the math, I wasn't going to use it.

The code for this was very short. I ran a for loop up to 1000 (starting at 3) and incremented it, summing the results that were either multiples of 3 or 5. I used modulus to test if a number was a multiple.

Problem 2

Very short program. I created a Fibonacci sequence up to 4,000,000 and summed the even results as the sequence ran. 

Problem 3

This program was a mess. I took a sledgehammer approach since I couldn't even begin to comprehend the math required to do advanced factorization techniques on large numbers. I made an array of prime numbers with which to test my number against. I put in lots of break statements in case I got stuck in an infinite loop (which happened too many times...).

I've got ideas for improvement on this one but solving this problem has turned my brain into jelly and I need to leave it alone for a bit. 

If you can't evenly divide a number "n"  by 2, the largest prime factor must be smaller than n/2
Likewise, if you can't evenly divide n by 3, the largest prime factor must be smaller than n/3

If I'm not using an array of primes to attack the number, and instead I'm itterating numbers, this could be useful
