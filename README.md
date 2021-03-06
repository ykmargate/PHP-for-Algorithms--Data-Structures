# PHP for Algorithms and Interview#

##Find the Missing Element
Consider an array of non-negative integers. A second array is formed by shuffling the elements of the first array and deleting a random element. Given these two arrays, find which element is missing in the second array.
Here is an example input, the first array is shuffled and the number 7 is removed to construct the second array.

Input:  
findMissing( \[5, 5, 7, 7\], \[7, 5, 5\])

Output:  
7

##Anagram
Given two strings, check to see if they are anagrams. An anagram is when the two strings can be written using the exact same letters (so you can just rearrange the letters to get a different phrase or word).

For example:

"Debit card" is an anagram of "Bad credit"  
"Payment received" is an anagram of "Every cent paid me"

##Array Pair Sum
Given an integer array, output all the unique pairs that sum up to a specific value k.

So the input:  
pair_sum([[2, 3, 1, 4, 6, 5], 5)

would return 2 pairs:  
(2,3)  
(1,4)

## Find me
Find the position of the first occurrence of a substring in a string

Input:  
findMe("Hello world. I'm looking for a needle in a long string.", "for")

Output:  
25

## String parsing

Given a strings with a separators. Extract all words and print them in a reverse order.

Input:  
"one,two, three/four/ five"

Output:  
"five four three two one"

## The Fibonacci sequence
Store the Fibonacci sequence into an array using recursion

Input:  
10

Output:  
Array  
(  
    [0] => 0  
    [1] => 1  
    [2] => 1  
    [3] => 2  
    [4] => 3  
    [5] => 5  
    [6] => 8  
    [7] => 13  
    [8] => 21  
    [9] => 34  
    [10] => 55  
)

## Split name
Write a function named splitName which takes a user-provided string  
and returns an array with keys 'firstname' and 'lastname'.  
Middle name(s) should be included with the first name if present.  
Examples:

splitName('Josh Moore') // returns array('firstname' => 'Josh',     'lastname' => 'Moore')  
splitName('Helen R. Ables') // returns array('firstname' => 'Helen R.', 'lastname' => 'Ables')  
splitName('Shakira') // returns array('firstname' => 'Shakira',  'lastname' => '')

## Pi calculator
Given that Pi can be estimated using the function 4 * (1 – 1/3 + 1/5 – 1/7 + …)  
with more terms giving greater accuracy, write a function that calculates Pi  
to an accuracy of a specified number of decimal places.  
Examples:
 
4 * (1 - 1/3) = 2.666666666667  
4 * (1 - 1/3 + 1/5) = 3.46666666666667  
4 * (1 - 1/3 + 1/5 - 1/7) = 2.895238095238  
4 * (1 - 1/3 + 1/5 - 1/7 + 1/9) = 3.339682539682539682









