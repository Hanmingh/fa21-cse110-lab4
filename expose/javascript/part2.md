1. line 12 prints the value of i, which is '3'. The reason why it is 3 is the loop terminates until i = 3. The reason why i can be called outside the loop is var has no block scope, which means it is visible through blocks.
2. line 13 prints the value of discountedPrice, which is '150'. The reason why it is 150 is in the last round of loop discountedPrice is assigned to the value 150. The reason why discountedPrice can be called outside the loop is var has no block scope, which means it is visible through blocks.
3. line 14 prints the value of finalPrice, which is '150'. The reason why it is 150 is in the last round of loop the result of mathematics calculation in line 8 is 150, which is assigned to finalPrice. The reason why finalPrice can be called outside the loop is var has no block scope, which means it is visible through blocks.
4. Since in each round of the for loop, the ith element in array [100, 200, 300] will be multiplied with 0.5, do a round operation, and then be pushed into an array called discounted. And because in the end array 'discounted' is returned, the returned array is [50, 100, 150].
5. The code returns an error, because unlike 'var', 'let' operation has block scope. Therefore, 'i' is undefined when it is called in line 12.
6. The code returns an error, because unlike 'var', 'let' operation has block scope. Therefore, 'discountedPrice' is undefined when it is called in line 12.
7. Line 14 prints the value of 'finalPrice', which is '150'. The reason why it is 150 is in the last round of the for loop, it is assined with the value 150. The reason why it can be called is it is declared in the function but the outside the for loop, so it can still be called in the function no matter if it's in or outside the loop.
8. It returns an array '[50, 100, 150]'. The reason is similar to question 4: in each round of the for loop, the ith element in array [100, 200, 300] will be multiplied with 0.5, do a round operation, and then be pushed into an array called discounted. The reason why it still works is declaring varialbes with 'let' does not effect the result, since the var keyword is almost the same as let.
9. The code returns an error, because unlike 'var', 'let' operation has block scope. Therefore, 'i' is undefined when it is called in line 11.
10. Line 12 prints the value of 'length', which is 3. The reason why it's value is 3 is it is assigned as a constant with value 3. The reason why it can be called is it is declared and called in the same block.
11. It returns an array '[50, 100, 150]'. The reason is similar to question 4 and 9:in each round of the for loop, the ith element in array [100, 200, 300] will be multiplied with 0.5, do a round operation, and then be pushed into an array called discounted. The reason why it still works is delcaring varialbes using keyword 'const' does not affect the output as long as it is not reassigned.
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. the output is '32', since integers map to their exact string representation.
    B. the output is 1, since string converts into number in a mathematical function.
    C. the output is 3, since string mull maps to 0.
    D. the output is '3null', since it is string concatenation.
    E. the output is 5, since true maps to 1.
    F. the output is 0, since both false and null map to 0.
    G. the output is '3undefined', since it is string concatenation.
    H. the output is Nan, since string undefined cannot be converted into a valid number.
14. A. the output is true, since string '2' becomes number 2.
    B. the output is false, since letter '2' is larger than letter '1'.
    C. the output is true, since string '2' becomes number 2.
    D. the output is false, because strict equality operator checks equality without type conversion.
    E. the output is false, since true maps to 1.
    F. the output is true, because boolean value of 2 is true.
15. == operator checks equality with type conversion while === does not.
16. see the file  part2-question16.js.
17. the result is [ 2, 4, 6 ]. After calling 'modifyArray([1,2,3], doSomething)', a constant array called newArr will be created. For each element i in [1,2,3], the function doSomething will double i then push it into the array newArr.
18. see the file part2-question18.js.
19. The output is:
    1
    4
    3
    2