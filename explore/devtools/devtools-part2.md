# DevTools - Debugging

1. The bug was that num1 and num2 are input values so they are received and interpreted as strings. That way, when finding the sum of num1 and num2, the numbers are really just strings being concatenated.
2. To fix the bug, we need to parse the string value and turn it into a numerical value so that the values are properly added together.