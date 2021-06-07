# JavacodeExamples

**prime Number Check**

What is a Prime Number?
A prime number is a number that is only divisible by 1 or itself. For example, 11 is only divisible by 1 or itself. Other Prime numbers 2, 3, 5, 7, 11, 13, 17....

Note: 0 and 1 are not prime numbers. 2 is the only even prime number.

Program Logic:

We need to divide an input number, say 17 from values 2 to 17 and check the remainder. If remainder is 0 number is not prime.
No number is divisible by more than half of itself. So we need to loop through just numberToCheck/2 . If input is 17, half is 8.5 and the loop will iterate through values 2 to 8
If a numberToCheck is completely divisible by other number, flag isPrime is set to true and the loop is exited.

