# Project Kasparov
<em> Analyzing chess openings in conjunction with Elo ratings and game performance data using machine learning. </em>


Chess openings are the first few inital moves of a chess game. They heavily decide the progression of the game and the strategies that will be employed. Project Kasparov aims to anazlye chess openings to answer some questions in chess analysis:

* What are the win/loss/draw ratios for different chess openings?
* How does the ratio of utilized chess openings vary among players over a range of Elo ratings?
* Does early-game control of the center correspond to win probability?
* Between games of players of vastly different Elo ratings, does the player with the lower Elo rating utilize different strategies to gain an advantage?
* How do players vary their openings within a match?
* How has the popularity of an opening changed over time?

## Data

`.pgn` (Portable Game Notation) is a text file format which records chess games from which the majority of our data will be acquired. The relevant fields for this project are `Result`, `WhiteElo`, `BlackElo`, `ECO`, `Variation`, `Opening`, and the algebraic chess notation body for the round.

Data were collected/referenced from these sites: 

* <em>Encyclopedia of Chess Openings</em> 
  A compendium of almost all possible chess openings which are organized by an alphanumeric code. For example 
* <em>theweekinchess.com</em>
* <em>FICS Games Database</em>
*e
## Simulations (tentative)

## Game Theory Applications

## Appendix

### Definitions

* Elo Ratings System: A method for calculating the relative skill levels of players in chess. 
* Stockfish: A powerful chess AI.
* Algebraic Chess Notation: A notation system that records the moves in a game of chess. 
