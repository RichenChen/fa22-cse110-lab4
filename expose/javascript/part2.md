1. Line 12 prints:
   ```
   3
   ```
   This is because we created i with *var* so it has function scope. Therefore, we will print 3 after the for loop ends.

2. Line 13 prints:
   ```
   150
   ```
   This is because we created i with *var* so it has function scope. Therefore, we will print the last value of discountedPrice after the loop ends, which is 150.

3. Line 14 prints:
   ```
   0.5
   ```
   This is because we assigned finalPrice to discountPrices * 100 / 100, which is 0.5.

4. The function will return:
   ```
   [ 0.5, 0.5, 0.5 ]
   ```
   This is because we pushed finalPrice, which is 0.5, three times to the array.
5. Line 12 causes an error, because i is out of scope.
   
6. Line 13 prints:
   ```
   [Function: discountPrices]
   ```
   This is because discountPrices is out of scope, we cannot print the elements in it.

7. Line 14 prints:
   ```
   0.5
   ```
   The console is in the same scope with the variable.

8. The function will return:
   ```
   [ 0.5, 0.5, 0.5 ]
   ```
   The return statement is in the same scope with the variable.

9.  Line 11 causes an error, because i is out of scope
    
10. Line 12 prints:
   ```
   3
   ```
   Length is in the same scope as console.

11. The function will return:
   ```
   [ 50, 100, 150 ]
   ```
   Now we are pushing the discounted prices into our array and the function returns the correct answer.

12. A. student.name
    
    B. student['Grad Year']

    C. student.greeting()

    D. student['Favorite Teacher'].name

    E. student['Favorite Teacher'].name

13. A. 32, string concatenation
    
    B. 1, you cannot do subtraction on strings, so '3' is converted to a number

    C. 3, null does not do do anything in number addition

    D. 3null, null is appened to the string '3'

    E. 4, true is considered as 1 where false is considered as 0

    F. 0, false is 0 and null does nothing

    G. 3undefined, string concatenation

    H. NaN, 3 is converted to a number due to string subtraction

14. A. true, 2 is converted to number

    B. false, the first char of '2' is greater than '12'

    C. true, '2' is converted to a number

    D. false, === does not do type conversion

    E. false, true is equal to 1

    F. true, any number not 0 will be converted to true by Boolean(num)

15. == does automatic type conversion before comparing and === does not

16. see part2-question16.js

17. our first parameter is an array and the second parameter is a reference to a function that returns double of its parameter. In modifyArray(), we create an array and iterate through the entire input array with a for loop. With this for loop, we run the doubling function on every element of our array and push it into the new array, then we return the new array. Therefore, the returned value of this function should be our parameter array with all elements doubled. Hence, our output is [2, 4, 6].
    
18. see part2-question18.js

19. The code prints:
    ```
    1
    4
    3
    2
    ```
    
