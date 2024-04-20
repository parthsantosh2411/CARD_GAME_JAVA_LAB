# Card Deck

This Java program implements a simple card deck management system. It consists of the following classes:

1. **Card**: Represents a playing card with attributes rank and suit.

   - `Card(int rank, String suit)`: Constructor method to initialize a Card object with the provided rank and suit.
   
   - Getter methods for rank and suit attributes.
   
   - `toString()`: Method to return a string representation of the card.
   
   - `compareTo(Card other)`: Method to compare two cards based on their rank and suit.
   
   - `equals(Object obj)`: Method to check if two cards are equal.

2. **Deck**: Represents a deck of playing cards.

   - `Deck()`: Constructor method to initialize a Deck object with an empty deck.
   
   - `createDeck()`: Method to create a standard deck of 52 cards.
   
   - `displayMenu()`: Method to display a menu of options for interacting with the deck.
   
   - Various private helper methods to perform actions like printing the deck, shuffling the deck, drawing a card, etc.

3. **Main**: Contains the main method to run the program and interact with users.

   - `public static void main(String[] args)`: The main method where the program starts execution. It creates a deck, populates it with cards, and displays a menu for users to interact with the deck.

## Usage

To use the program:

1. Run the `Main` class.
2. Choose options from the displayed menu to perform actions like displaying the deck, shuffling the deck, drawing a card, comparing cards, etc.

## Features

- Allows creation of a standard deck of 52 playing cards.
- Provides various options for interacting with the deck, such as shuffling, drawing cards, comparing cards, etc.

## Requirements

- Java Development Kit (JDK) installed on your system.


