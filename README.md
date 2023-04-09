Card Deck Java Program

This Java program is a basic implementation of a card deck. It consists of three classes: Main, Card, and Deck.

Main

Main is the main class that interacts with the user through the console. It has a Deck object and a Scanner object to take user input. It presents the user with a menu of options to choose from. These options include printing the entire deck, printing a single card, printing all cards of a given suit, printing all cards of a given rank, finding a card by suit and rank, dealing five random cards from the deck, shuffling the deck, and exiting the program.

Card

Card is a class that represents a single card in a deck. It has two private variables suit and rank that are set when the object is created. It also has getter methods for both variables and an override of the toString() method to display the card's rank and suit.

Deck

Deck is a class that represents a deck of cards. It has an ArrayList of Card objects that represent the cards in the deck. It has methods to print the entire deck, print a single card, print all cards of a given suit, print all cards of a given rank, find a card by suit and rank, deal five random cards from the deck, and shuffle the deck.
