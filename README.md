# wordlists for the mari wordle

- wordlists are a courtesy of Jeremy Bradley, src: https://www.univie.ac.at/maridict/site-2014/book.php?int=0
- play at: https://mari-wordle.anvil.app/
- mutle.py: contains the source code of the anvil web app. To create a wordle for your own language, all it takes is to paste your own wordlist into function readall() and readtgt() and define the characters of your keyboard in the variable keybrd.

#Todo

- return a 5\*5 grid of coloured buttons with letters in them instead of strings and heart-emojis
- colour keyboard green, yellow and gray after each guess
- Store infos about date - IP address - guesses in a pastebin and allow only one access per day
- only one word per day, reset at midnight Mari El time zone
- improve design
- add share button