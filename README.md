# iOS Prework Swift Assessment
A short assessment to test basic comprehension of the Swift Prework.

## Instructions
Follow these instructions in order and explain out loud your logic as you code.

### 1. Make your declarations
In your AppDelegate.swift file's `application:didFinishLaunchingWithOptions:` method, declare the following three variables and set them to empty objects of the appropriate type:

* An empty array called of type `Int` called  `numbersArray`
* An empty array of type `String` called `lettersArray`
* An empty dictionary called `alphabetDictionary`

Next, declare the three following methods and set them to return `nil` until you have written their implementations:

* `generateArrayOfNumbers`, which returns an array of type `Int`
* `generateArrayOfLetters`, which returns an array of type `String`
* `generateNumbersAndLettersDictionary`, which takes as arguments `numbersArray` and `lettersArray` and returns a dictionary of type `[Int:String]` 

### 2. Reassign values to your variables
On a new line, reassign `numbersArray` to the return of `generateArrayOfNumbers` and `lettersArray` to the return of `generateArrayOfLetters`. Next, reassign `alphabetDictionary` to the return of `generateNumbersAndLettersDictionary`, which should take in as arguments the two arrays you previously declared.

### 3. Implement `generateArrayOfNumbers`
This method should return an array which contains 26 elements, the whole numbers 1 through 26. Do not hard-code these values into the array.

### 4. Implement `generateArrayOfLetters`
This method should return an array which contains the 26 letters of the English alphabet, lowercase and in ascending order.


### 5. Implement `generateNumbersAndLettersDictionary`
This method should return a dictionary that contains key-value pairs of numbers as keys and their corresponding letters as values by using the two provided arguments.

### 6. Log the contents of `alphabetDictionary`
Write a `print` statement in the `application:didFinishLaunchingWithOptions:` method after you've called your three other methods to print the entire contents of your final dictionary to the console.

### 7. Reassign your arrays
Reassign `numbersArray` to the keys from `alphabetDictionary`. Create a new array , `newLettersArray`, remove all objects from this array, and assign to it all the values retrieved by iterating over `alphabetDictionary`. With a single `print` statement, print both `numbersArray` and `newLettersArray` to the console, separated by a new line.