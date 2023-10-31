# Asynchronous JavaScript Application for Mathematical Formula Evaluation

This `README` provides an overview of the asynchronous JavaScript application developed for the assignment. The goal of this assignment was to create an application that calculates the sum of the first N prime numbers asynchronously. It follows the specified requirements, including the use of `async/await`, JavaScript promises, object-oriented design, user input, and display of results.

## Formula

The formula used for this assignment is the sum of the first N prime numbers:
Sum(N) = 2 + 3 + 5 + ... + P_N


## Implementation Details

The application is implemented as an HTML file with embedded JavaScript. Here are the key components of the implementation:

- **PrimeSumCalculator Class:** This class encapsulates the calculation logic. It includes methods for calculating the Nth prime number and the sum of the first N prime numbers.

- **`calculateSumOfPrimes(N)` Method:** This method calculates the sum of the first N prime numbers. It utilizes the `getNthPrime` method and an async loop to build the sum.

- **`getNthPrime(N)` Method:** This method calculates the Nth prime number using a promise-based approach. It maintains a list of prime numbers and checks for prime numbers incrementally.

- **`isPrime(num, primes)` Method:** This helper method checks whether a number is prime by verifying if it is divisible by previously found prime numbers.

- **User Input:** The user is prompted to enter the value of N using a JavaScript `prompt` dialog.

- **Display Results:** The result of the calculation is displayed in the HTML document.

- **jQuery for UI Enhancement:** jQuery is used to enhance the user interface by updating the result dynamically.

## How to Use

1. Open the HTML file in a web browser.

2. The application will prompt you to enter the value of N (the number of prime numbers to sum).

3. After entering N, the application will calculate the sum of the first N prime numbers and display the result on the web page.
