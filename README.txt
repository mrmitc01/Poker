Poker

This code is used to implement a program that plays a simplified poker game, named Texas Hold’em, 
against the computer:
Two cards, known as the hole cards, are dealt face down to the user and the computer respectively, 
and then five community cards (also called “shared cards” or “window cards”) are dealt facing up in 
the center of the table and shared by both players. Each player then combines the hole cards with 
the community cards (2 cards + 5 cards) to seek the best five-card poker hand from any combination 
of the SEVEN cards. The program then compares the highest ranking of the five-card poker hands 
between the user and the computer. The one who has the higher ranking of the five-card poker hand 
wins the game and this is reported. Otherwise, a tie game is reported.

The purposes of each of the following files are stated below:


card.cpp - to provide the implementation of member functions for the Card class          

card.h - to provide the declaration for the Card class             

deck.cpp - to provide the implementation of member functions for the Deck class           

deck.h - to provide the declaration for the Deck class             

pokerhand.cpp - to provide the implementation of member functions for the PokerHand class          

pokerhand.h - to provide the declaration for the PokerHand class       

rank.cpp - to provide the implementation of member functions for the Rank class

rank.h - to provide the declaration for the Rank class

SortedLinkedList.cpp - to provide the implementation of member functions for the Node class and SortedLinkedList class

SortedLinkedList.h - to provide the declaration of the Node class and the SortedLinkedList class

testPokerGame.cpp - to decide the best FIVE-card poker hand out of SEVEN cards according to poker hand ranking; 
                    the testing cases are created for the purpose of testing your definition of PokerHand class

PokerGame.cpp - to play a simplified poker game, named Texas Hold’em, against the computer

makefile - to build the Simplified Poker Game program


Compile the source code for the full Poker Game program by typing the following at the prompt $:
$ make  

Compile the source code for only the Test Poker Game program by typing the following at the prompt $:
$ make testPokerGame

Clean up the mess by typing the following at the prompt $:
$ make clean

Code is available upon request

