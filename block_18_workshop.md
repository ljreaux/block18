# Block 18 Workshop

## Unit Tests
1. multiplication()
  - Expectations

    1. The function should take in two numbers and return the product of those two numbers as a number. 
    2. Should return an error if the user gives more than two parameters.
    3. Should return the value of the parameter if only one is given. 
    4. Should return an error if input is NaN.

  - Specifications
    1. Expect multiplication(2, 3) to be a number
    2. Expect multiplication(2, 3) to be equal to 6
    3. Expect multiplication(2, 3, 4) to be an error
    4. Expect multiplication(2) to be equal to 2
    5. Expect multiplication("2", "3") to be an error
