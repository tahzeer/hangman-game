# Hangman Game

Terminal based game of hangman programmed in python for a mini-project.

A random word is chosen from an editable external txt file containing words separated by newline character, and the player has to guess the word, either letter by letter or the entire word at once, without making more than 6 mistakes as it would complete the hangman diagram.

## Requirements
- `python 3.x`
- `random` module
```
  pip install random
```

Add all the files in a common directory and while still in the directory, run this command inside your terminal:
```
  python hangman.py
```

## Snippets

- Staring the game.

  ```
  Let's play Hangman!

                    --------       
                    |      |       
                    |
                    |
                    |
                    |
                    -

  ______


  Length of the word:  6


  Please guess a letter or the word: 
  ```

- Loosing the game.

  ```
  I is not in the word.

                    --------
                    |      |
                    |      0
                    |     \|/
                    |      |
                    |     / \
                    -

  ______


  Length of the word:  6


  Sorry, you ran out of tries. The word was VERSED. Maybe next time!
  Play Again? (Y/N):
  ```
  
- Winning the game.

  ```
  
                    --------
                    |      |
                    |      0
                    |     \|/
                    |      |
                    |
                    -

  SEEMLY


  Length of the word:  6


  Congrats, you guessed the word! You win!
  Play Again? (Y/N):
  ```
  
### **Author**

[Tahzeer Ashraf](https://github.com/tahzeer)
