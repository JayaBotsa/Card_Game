# Card_Game

# Introduction
This Python script implements a simple card game where two players draw cards from their respective draw piles and compare them. The player with the higher card value wins the round and collects both cards into their discard pile. If the drawn cards have the same value, additional cards are drawn until a winner is determined.

# How to Use
To use this script, simply run it using a Python interpreter. The game will automatically simulate the gameplay and print the result once a player wins.
 `python card_game.py`
 
# Implementation Details
- CardGame Class: This class represents the card game and includes methods for initializing the game, drawing cards, comparing cards, playing turns, and determining the game outcome.
- create_shuffled_deck: Method to create and shuffle a standard deck of cards.
- compare_cards: Method to compare two card values.
- shuffle_deck: Method to shuffle the deck of cards.
- draw_card: Method to draw a card from a player's draw pile, with automatic reshuffling if the draw pile is empty.
- play_turn: Method to simulate a single turn of the game, where each player draws a card and the outcome is determined.
- play_game: Method to play the entire game until one player runs out of cards.

# Test
The script includes a test scenario where the game is instantiated and played. The result of the game (which player wins) is printed at the end of execution.
