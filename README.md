# Unscrambler-Game

![scrabble](https://user-images.githubusercontent.com/38334354/117216764-3c366c80-adce-11eb-9349-62ee896a4ca6.jpg)


Two words are anagrams of each other if they have the same letters in the same quantity, in a different sequence. For instance, cat and act are anagrams. Also pots, stop, and tops are all anagrams of one another (each can be formed by permuting the letters of the others).
This is a program that, given a word, will find all anagrams of the word that are in the provided dictionary (words.txt). The program should repeatedly ask the user to enter a word and it should display the anagrams of the word entered by the user. The program should also give the user the option to exit.

Sample run:

Enter a word (press enter to exit)> cat

Anagrams of cat: act cat

Enter a word (press enter to exit)> meat

Anagrams of meat: mate meat meta tame team

Enter a word (press enter to exit)> pot

Anagrams of pot: opt pot top

Enter a word (press enter to exit):

Good bye 



At the beginning of the program, load the dictionary into a map where the key is a word in its alphabetized form and the value is the set of all words that map to that key. A word is converted to its alphabetized form by sorting all the letters in the word alphabetically. The map will look like:

KEY | VALUE

act | act, cat

aeonrsst | senators, treasons

deirw | weird, wider, wired, wrieds

When looking for the anagrams of a word, lookup the alphabetized form of that word in the map and then simply retrieve the set of words associated to that key.
