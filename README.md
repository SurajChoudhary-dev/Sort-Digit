# Sort-Digit
Sorting the given array in descending order that contains digits from 1 to 9.
This algorithm is effective to sort a given undorted array of size 'n' to a sorted array with minimum time and space complexity.
Steps implemented: >Take the length of the array in a variable, 'n'.>Initialise an array, arr[n] of size n that contains all the elements.> Initialise another array of size 9(count [9]) to store the repetition of each digit to its respective index value in the count array.> Example:- Repetition of 1 will be stored in index 1 of count array, repetition of 2 in index 2 of count array and so on.> Declare a variable that stores the the repetition of digits present in the array.>Use modulo function to extract the highest digit from the number and store till its repetition.
Finally print the array in descending order.
