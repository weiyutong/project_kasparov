# Project Kasparov
<em> Analyzing chess openings in conjunction with Elo ratings and game performance data using machine learning. </em>


Chess openings are the first few inital moves of a chess game. They heavily decide the progression of the game and the strategies that will be employed. Project Kasparov aims to anazlye chess openings to answer some questions in chess analysis:

* What are the win/loss/draw ratios for different chess openings?
* How does the ratio of utilized chess openings vary among players over a range of Elo ratings?
* Does early-game control of the center correspond to win probability?
* Between games of players of vastly different Elo ratings, does the player with the lower Elo rating utilize different strategies to gain an advantage?
* How do players vary their openings within a match?
* How has the popularity of an opening changed over time?

High-skill chess competitors (those with Elo ratings > 

## Data

`.pgn` (Portable Game Notation) is a text file format which records chess games from which the majority of our data will be acquired. The relevant fields for this project are `Result`, `WhiteElo`, `BlackElo`, `ECO`, `Variation`, `Opening`, and the algebraic chess notation body for the round. I looked at only standard chess games (i.e. no rapid, blitz, lightning, and variant games) between humans.

Data were collected/referenced from these sites: 

* <em>Encyclopedia of Chess Openings</em> 

  A compendium of almost all possible chess openings which are organized by an alphanumeric code in a recursive manner and hierarchical manner. For example all openings that involve first white moving their kingside pawn and then black moving their kingside pawn are located in Volume C. Then all openings that start off with 1. e4 e5 ... a.k.a. the Open Game all have ECO codes in the range C20 - C99. Then all openings which follow with 2. Nc3 (the Vienna Game) are in the range C25 - C29, with the specific opening 1.e4 e5 2.Nc3 Nf6 3.Bc4 Nc6 given the ECO code C29. Openings that have a specific code (as opposed to a range) don't all go into same depth in the game.
  
* <em>theweekinchess.com</em>

* <em>FICS Games Database</em>

* <em>Polyglot Opening Books</em>

Using web scraping techniques, I 

## Analysis

I used `python-chess` package which is used to analyze `.pgn` files and do extensive chess analysis.

https://python-chess.readthedocs.io/en/latest/index.html

https://python-chess.readthedocs.io/en/latest/pgn.html#skimming

## Modeling

https://python-chess.readthedocs.io/en/latest/engine.html#indefinite-or-infinite-analysis

## Conclusions

## Simulations (tentative)

## Game Theory/Business Strategy Applications

Nash Equilibrium

Solution concept

Asymmetric Game Theory
## Appendix

### Definitions

* Elo Ratings System: A method for calculating the relative skill levels of players in chess. 
* Stockfish: A powerful chess AI.
* Algebraic Chess Notation: A notation system that records the moves in a game of chess. 
