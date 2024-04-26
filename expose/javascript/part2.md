# Part 2

## Variable Scope
1. The code will print 3 because i is initialized with the var keyword which means it is accessible within the entire function, not just the code block it's in. This is because it has no block-scope, it is function-scoped or global-scoped.
2. This will print 150 because discountedPrice is initialized using "var" which means it has function-scope here. That means it basically stores the final value of discounted price which is 300 * 0.5 = 150.
3. Line 14 will print 150 because final price is updated in the for loop to be the final value of the rounded discounted price. That way, it will be 150.
4. This function will return an array of the discounted prices by 50%, [50, 100, 150] because each element in the array is reduced by 50% and added to the discounted array which is made up of the final prices.
5. Now an error occurs because when using the let keyword, the variable declared has block-scope. i will not be defined outside of the for loop block so an error occurs.
6. An error occurs because when using the let keyword, the variable declared has block-scope. Because discountedPrice is initialized within the for loop, it will not be defined outside of the for loop block so an error occurs.
7. The code prints out 150 because finalPrice is defined in the function outside of the for loop with the let keyword. That means that this variable has function scope and it's value will be printed out.
8. The function will return an array of discounted prices, [50, 100, 150] because the discounted array has function scope since it is defined by the let keyword and is inside of the function block.
9. An error will occur because i will not be defined on line 11. It was initialized with the let keyword so it is only defined within the code block of the for loop.
10. Line 12 will print out 3 because length is defined with const and has function scope. The number of elements in prices is 3.
11. The function will return the array [ 50, 100, 150 ]. Even though discounted is a const variable, the variable only gets added to but doesn't get redefined so there is no error here.

## Datatypes
12. Notations for 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]

## Basic Operators & Type Conversion
13. Arithmetic
    A. '32' because + can be used for string concatenation and since '3' is a string, it maps 2 to it's string representation.
    B. 1 because - is a mathematical operator and since 2 is a number, the string '3' is mapped to a number.
    C. 3 becuase null maps to 0 in this case.
    D. '3null" because null maps to a string in this case.
    E. 4 because true maps to 1 and is added to 3.
    F. 0 because both false and null map to 0 in the numerical representation and perform 0 + 0.
    G. '3undefined' because undefined maps to a string since '3' is a string.
    H. NaN because undefined maps to NaN and a mathematical operation attempts to be performed here.

14. Comparison
    A. true because since 1 is a number, JS converts 2 into its integer representation.
    B. false because since both values are strings, they are compared lexigraphically.
    C. true because '2' is converted to it's number representation and compared to 2.
    D. false because both value and datatype are compared using the === operator compared to the last case.
    E. false because true is converted into the number 1 and then compared
    F. true because the Boolean of any number greater than 0 is true and since Boolean(2) is a Boolean type, there is no issue with comparing the types and value with the === operator.

15. The == operator allows for a conversion for a given value on the right or left side to a different type while === compares datatype and value with no changes made. 

## Loops
16. Please look at part2-question16.js file

## Functions
17. In this function, array is [1,2,3] and the callback is doSomething. When modifyArray is called, these arguments are passed on and newArr, an empty array, is initialized. For each item in the array, the doSomething callback function is called on each element and pushed to the newArr. This means that every element in the array is multiplied by 2 in the new array. As a result, the function should return the newArr and in this case will return [2, 4, 6].
18. See part2-question18.js
19. 1
    4
    3
    2


