# Block 18 Workshop

## Unit Tests:
1. ***multiplication()***
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

2. ***concatOdds()***
  - Expectations
    1. The function should take in two arrays and output a new array.
    2. The array elements should be integers. 
    3. The function should loop through both arrays and add the input to the new array if:
      - it is an odd number
      - that number is not already contained in the new array
    4. The function should return the new array in ascending order.

  - Specifications
   1. Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be an **array**
   2. Expect concatOdds(["one"], ["two"]) to be an **error**
   3. Expect concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) to be **[-1, 1, 3, 9, 15]**

## Functional Tests:
1. ***Shopping Cart***
  - Specifications
    1. User should be able to click buttons that say "Log-in" or "Check out as Guest" when cart contains items, otherwise they should receive an error.  
    2. If user presses log-in they should proceed to the log-in screen which should also have a space for creating an account.
    3. If user clicks "Check out as Guest" they should be given the option to create an account before proceeding.
    4. If user enters incorrect or incomplete log-in information they should be shown an error and asked to try again. 
    5. Once user inputs correct log-in information or navigates as a guest they should be allowed to input payment information.
    6. If the user signs into their account they should be allowed to use previous/stored payments. 
    7. The payment information should be validated and the user should receive an error if their is a problem with the payment. 
    8. Users should input valid address information and receive an error if address is incomplete or not valid. 
    9. Users should see a page with all entered information and make final confirmation. 
    10. User should receive a notification about whether or not the order went through as planned and a confirmation. 