# Block 18 Workshop

## Unit Tests
1. multiplication()
  - Expectations
    1. The function should take in two numbers and return the product of those two numbers as a number. 
    2. The function should return an error if the user gives more than two parameters.
    3. The function should return the value of the parameter if only one is given. 
    4. The function should return an error if input is NaN.

  - Specifications
    1. Expect multiplication(2, 3) to be a **number**
    2. Expect multiplication(2, 3) to be **equal to 6**
    3. Expect multiplication(2, 3, 4) to be an **error**
    4. Expect multiplication(2) to be **equal to 2**
    5. Expect multiplication("2", "3") to be an **error**

2. concatOdds()
  - Expectations
    1. The function should take in two arrays and output a new array.
    2. The array elements should be integers. 
    3. The function should loop through both arrays and add the input to the new array if:
      - it is an odd number
      -that number is not already contained in the new array
    4. The function should return the new array in ascending order.

  - Specifications
   1. Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an **array**
   2. Expect concatOdds(["one"], ["two"]) to be an **error**
   3. Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be **[-1, 1, 3, 9, 15]**