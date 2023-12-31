# prime
Prime numbers are defined as whole numbers greater than 1, whose only factors are 1 and itself. 

## Implementation Details
The easiest way to check if a number is prime, is to try dividing it by every number from 2 up to, but not including, the number itself. If any number divides into it with no remainder, that number is not prime.

The main function in the distribution code contains a for loop that iterates through the range specified by the user, with both ends inclusive. For example, if the user types in 1 for min and 100 for max, the for loop will test each number, 1 to 100. Each of these numbers is passed to a function, prime, that you will implement to return either true or false depending on whether the number is prime.