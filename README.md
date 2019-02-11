# Tech Screener Exercises

The solutions to the exercises were written in JavaScript, HTML & CSS. The code, my thought process and the results of the two programs on a few testcases are provided on the HTML page as well. Simply hit the `Run Code` button and view the results on the screen!

## Exercise One

Leet: L37'5 h4v3 50m3 fun.

Replace letters in a string with the mapping below: 

`[a,A] -> 4, [e,E] -> 3, [i,I] -> 1, [o,O] -> 0, [s,S] -> 5, [t,T] -> 7, [b,D] -> 5`

## Objective

To convert a String into Leet.

## Thought process

The idea is to initially create a map object of the given mapping. Then loop over each character in the input string and if the map contains the character, replace it with the mapping in the map object and add it to the string array. If not, simply add the character as is to the string array.

## Exercise Two

String: Manipulate strings with repeating characters, for example - `aaabbbbccccc > a3b4c5`

## Objective

Take each repeated letter in a string, and re-arrange the string so each letter in the string is shown once along with the number of times it is repeated. Do this serialized for each instance of any letter, and not for the total number of times that letter is shown in the string.

## Thought process

The idea here is to loop through the characters of the input string and continuously compare it with the previous character. Add the first character to the result string, and in the loop if the character is repeated, increment the count until a different character is seen. When the different character is seen, simply add the count and the next character to the result string until done.