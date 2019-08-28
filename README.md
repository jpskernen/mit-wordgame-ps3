# mit-wordgame-ps3
MIT OCW 6.0001 Problem Set 3 Word Game similar to scrabble.
This game looks a lot like Scrabble or Words with Friends. 
#Rules
Dealing
A player is dealt a hand of HAND-SIZE letters of the alphabet. These letters are chosen at random. This means you may get multiple instances of the same letter. ie. aaa
The player arranges the hand into as many words as they want out of the letters, but using each letter at most once. 
Som letters may remain unused, though the size of the hand when a word is played does affect its scored. 

#Scoring
The score of the hand is the sum of the score for each word formed. 
The score for a word is the prodcut of two coponents: 
1. Sum of points for letters
2. Either [7*word_length - 3 * (n-word_length] or 1 whichever value is greater, where: 
a. word_length is the number of letters used in the word
b. n is the number of letteers available in the current hand. 

Letters are scored as in Scrabble; A is worth 1, B is worth 3... 
###
I do not know the value of letters, but luckily they have defined a dictionary SCRABBLE_LETTER_VALUES
###
