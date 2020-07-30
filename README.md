## [Project Euler Files](https://dkallen78.github.io/Project-Euler-Files/projectEulerIndex.html)

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

Problem 4 - Largest Palindrome Product

This solution turned out to be much easier than I had at first thought it would be. The goal was to find the largest Palindrome Number that is the product of two 3-digit numbers. 

My first step was to create a JavaScript function that would turn a number around to test if the number was a palindrome. I achieved this by the liberal application of modulus and a simple if statement.

The next part was to decide whether or not to test a series of 3-digit numbers to multiply, or to try and find factors of Palindrome Numbers. While I did find some interesting patterns in sequential Palindrome Numbers, finding factors was such a hassle that I opted for brute force. 

At first I was worried about testing over hundreds of thousands of combinations of 3-digit numbers, I quickly realized that I should just test the larger 3-digit numbers. This turned out to be a lot less code than I initially thought I would use. 
