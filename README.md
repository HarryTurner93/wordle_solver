# Wordle Solver
A pure python implementation of a solver for the popular game wordle.

## Disclaimer
This implementation is deliberately simple. It's not efficient, at all. I use only Python lists and strings, there are lots of ways this could be improved, by representing words as numpy arrays and using broadcasting operations for example. This is also not the only way to solve Wordle, just an approach that made sense to me. Finally, I can't guarantee it's free of bugs. Feel free to modify and submit a PR if you can improve it. With all of that fluff out of the way, I hope you enjoy it and find it useful.

# Requirements.
 - Python 3. (This was written and tested in Python 3.9).

# Setup
 - Clone this repository and `cd` into it.
 - Run the solver with `python main.py` and follow the prompts.
 - There are no dependencies to install as it's a pure Python implementation.
 
 # Usage
The solver will prompt you for a guess and the associated feedback. You should enter into the solver the same word that you entered into Wordle and then enter into the solver the feedback that Wordle gave you. This feedback should a five letter string containing either `g` for green, `y` for yellow, or `_` (underscore) for blank/black.
Note that there is always an optimal first word to start with. According to this solver, that word is `raise`.
