#Project1

Description
For this project you will read words from a given file into your program. Each word consists strictly of the letters A-Z and a-z. Any whitespace, punctuation, digit, etc. will separate words. An example would be this!is A&Word. This text would represent the 4 words this, is, A, and Word. Each word should be convertedtolowercasesothatonlylowercase letters remain.
Once you have read all of the words, you should output the total number of words read. Your next task is to determine how many distinct words appear in the file and output that value. Finally, you will prompt the user to enter a word and report how many occurrences of the given word are in the file. You will continue to prompt the user until they enter the EOF character.
When the user enters a word to search for, a ‘?’ character may be present as some of the letters for the search. This special character represents the ability to match any character, including the empty character. For example, colo?r matches both "color" and "colour". This query should report every word that matches.
Keep in mind that the ? character in the source input file is not a wildcard match. In the original source, it is just another non-letter character.
