# numberphile-math-game
https://www.youtube.com/watch?v=ud_frfkt1t0

Simulation of various strategies to win the following game:
  Player 1 picks two numbers (Limited to $simMin through $simMax) (Hereafter referred to as A and B)
  Player 1 reveals A to Player 2
	Player 2 must guess whether A is bigger or smaller than B
	Player 1 reveals B, and it is revealed whether Player 2 was correct
The following strategies will be tested $simRunTime times:
	A - Player 2 will guess randomly
	B - Player 2 will guess only that A is larger
	C - Player 2 will guess only that B is larger
	D - Player 2 will determine if A is larger than $simHalf ($simRunTime / 2) and guess with that
	E - Player 2 will generate a random number (Limited to $simMin through $simMax) (Hereafter referred to as K)
			Player 2 will determine if A is larger than K and guess with that
The winrate will be determined as a percentage
Winrates will be logged to console
Guesses and answers will be logged to log/sim-$runDate (If you go and remove the commenting lines)
