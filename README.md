# Palindrome-Checker-Console-version

Question 1.

In JavaScript, build a function that checks if a word is a palindrome (reads the same backwards as forwards, e.g. kayak, rotator, radar etc).
if the word is a palindrome, function should return true, else, false.
  
Assumptions:

1.	Word is a palindrome (reads the same backwards as forwards, e.g. kayak, rotator, radar etc.)
2.	We are checking the words, not numeric palindromes. Therefore I didn’t not add regular expressions to exclude numbers in the string (“9Bob9” or “9009” will 		return “This is a palindrome.”), but in this case it is irrelevant. Input should be a word. I tested for the characters which make words only, not numbers/digits.
3.	We do not check for word¬s (or sentences) in the function, but for a word. We may argue that “Anna!” is a word, but actually it is a one-word sentence. To be 		consistent I excluded all the sentences, also one-word sentences.
4.	Presence of a space in a string indicates we have a sentence which will not meet an assumption.
5.	All solutions claiming some sentences are palindromes (for example: “Bob bob”) are logically wrong and should be rejected. The question clearly asks for a word.
6.	There are many methods to search for a palindrome. Just to mention: forEach, for loop, for of, map, reduce, recursion (compare the first and the last character 	of a string), split-reverse-joint. There is no requirement to select the fastest one or describe time/space complexity, therefore there is no particular reason 	 I chose this one over another.

Result of testing after running the code:

![Palindrome Console jsfiddle net](https://user-images.githubusercontent.com/88635610/153877617-0ac1ec21-e96f-437f-9a12-c4da97834c89.png)

