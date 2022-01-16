# wordlists for the mari wordle

## Contents:

- wordlists are a courtesy of Jeremy Bradley, src: https://www.univie.ac.at/maridict/site-2014/book.php?int=0
- play at: https://mari-wordle.anvil.app/
- mutle.py: contains the backend code of the anvil web app.

## Todo:

- return a 5\*5 grid of coloured buttons with letters in them instead of strings and heart-emojis
- colour keyboard green, yellow and grey after each guess
- Store infos about date - IP address - guesses in a pastebin and allow only one access per day
- only one word per day, reset at midnight Mari El time zone
- improve design
- add share button
- find out how to unittest anvil apps

## Notes:

To use this script go to anvil.works https://anvil.works/, start a new project and paste the content of mutle.py into the "Code" section. The "Design" section consist only of one TextArea called text_area_1. To create a wordle for your own language, all it takes is to paste your own wordlists into function readall() and readtgt() and define the characters of your keyboard in the variable keybrd.