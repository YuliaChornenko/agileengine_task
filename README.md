# agileengine_task

python

main.py - file with functions, running which you can see information about all "Everything OK" buttons
input.py - run it, paste the link to the page here and you will see the info about the button "Everything OK" on it

A bit about my algorithm:

First we find the right container with buttons. For the words that are most often found in button variations, I picked up synonyms. If one of them is found in the button text, this suits us. But I also provided that the button may simultaneously contain words that do not suit us (for example 'Break everyone's OK' - we have the word ok, but the word 'break' does not suit us here), for these words we also select synonyms, and if there are no these words in the button text, then we finally display all the information about it.

Our main function is make_ok, for its launch a link to the page with the desired button is enough.
