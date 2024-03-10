
# Casino War

The game is played with a standard 52 card deck. The cards are ranked in the same way that cards in poker games are ranked, with aces being the highest cards.

One card each is dealt to an AI and to a player. If the player's card is higher, they win the wager they bet. However, if the AI's card is higher, the player loses their bet.

A tie occurs when the ai and the player each have cards of the same rank. In a tie situation, the player has two options:

The player can surrender, in which case the player loses half the bet.  
The player can go to war, in which case the player must double their stake.

If the player continues play in view of a tie, the computer burns (discards) three cards before dealing each of them an additional card. If the player's card is ranked higher than the AI's, then the player wins the amount of their original wager only. If the Ai's card is ranked higher than the player's, the player loses their (doubled) wager.





## Authors

- [Tibor Blascsok](https://github.com/Btibor02)
- [Kate Arvay](https://github.com/Preia-Starle)
- [Antoine Geiger](https://github.com/tableba)



## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Demo

Insert link to demo


## Installation

Use git clone to clone the repository

```bash
git clone https://github.com/Preia-Starle/casino-war-game
```


It is best to make a virtual environement (venv) first before installing dependencies.

Making virtual environement (venv)
```bash
    make venv
```
And follow the instructions.

Installing necessary dependencies
```bash
    make install
```

Run the game
```bash
    make
```
    

## Running Tests

To run tests, run the following command

```bash
  make coverage
```

## Linting

To run linting

```bash
    make flake8
```

or 

```bash
    make pylint
```

## Documentation

Documentation is available and can be run with

```bash
    make docs
```


## Clearing Files
To clear generated files while playing the game or generating documentation, run 

```bash
    make clean
```

Or to clean the generated documentation
```bash
    make clean-docs
```


## Deployment

To deploy this project run

```bash
  npm run deploy
```



## License

[MIT](https://choosealicense.com/licenses/mit/)

