Port number: 54522
Server file: node server_flashcards.js
Login page: http://server162.site:54522/login.html

Note: On the review page, when you flip the card or press enter in the input box, the input will be checked for correctness and the card will flip. You can manually flip the card back and forth after this, but it won't recheck the input again or make any changes to the card or database until you press next to get the next card.

The logic to get the next card is implemented exactly as is given in the prompt (i.e. score = ( max(1,5-correct) + max(1,5-seen) + 5*( (seen-correct)/seen) ).