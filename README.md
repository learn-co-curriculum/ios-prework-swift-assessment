# iOS Prework Swift Assessment
A short assessment to test basic comprehension of the Swift Prework.

## Instructions
Follow these instructions in order and explain out loud your logic as you code.

### 1. Make your declarations
In your AppDelegate.swift file's `application:didFinishLaunchingWithOptions:` method, declare the following three variables and set them to empty objects of the appropriate type:

* An empty array of type `Int` called  `numbersArray`
* An empty array of type `String` called `lettersArray`
* An empty dictionary called `alphabetDictionary` of type `[Int : String]`

Write the following functions (we'll define the body in a bit):

* `generateArrayOfNumbers`, which returns an array of type `Int`
* `generateArrayOfLetters`, which returns an array of type `String`
* `generateNumbersAndLettersDictionary`, which takes as arguments and array of `Ints` and an array of `String` and returns a dictionary of type `[Int:String]` 

### 2. Reassign values to your variables
Go back to `application:didFinishLaunchingWithOptions:` and on a new line, reassign `numbersArray` to the return of `generateArrayOfNumbers` and `lettersArray` to the return of `generateArrayOfLetters`. Next, reassign `alphabetDictionary` to the return of `generateNumbersAndLettersDictionary`, which should take in as arguments the two arrays you previously declared.

### 3. Implement `generateArrayOfNumbers`
This method should return an array which contains 26 elements, the whole numbers 1 through 26. Do not hard-code these values into the array.

### 4. Implement `generateArrayOfLetters`
This method should return an array which contains the 26 letters of the English alphabet, lowercase and in ascending order.

**hint** Here's the alphabet typed out if you need it: "a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y", "z".

### 5. Implement `generateNumbersAndLettersDictionary`
This method should return a dictionary that contains key-value pairs of numbers as keys and their corresponding letters as values by using the two provided arguments.

### 6. Print the contents of `alphabetDictionary`
Write a `print` statement in the `application:didFinishLaunchingWithOptions:` method after you've called your three other methods to print the entire contents of your final dictionary to the console.

### 7. Reassign your arrays
Under the `print` statement, reassign `numbersArray` to the keys from `alphabetDictionary`. Create a new array of strings, named `newLettersArray`, remove all objects from this array, and assign to it all the values retrieved by iterating over `alphabetDictionary`. With a single `print` statement, print both `numbersArray` and `newLettersArray` to the console, separated by a new line.
