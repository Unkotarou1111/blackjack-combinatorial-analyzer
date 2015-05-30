## Blackjack Combinatorial Analyzer ##
**A lightweight blackjack combinatorial analyzer that calculates the expectation value and variance of a blackjack hand**
### by ChemMeister iCountNTrack ###
This is a combinatorial analyzer that is geared towards calculating player's
probabilities of the various possible outcomes of a round of blackjack using perfect play optimal full composition dependent combinatorial analysis. Once the probabilities are computed, the expectation value and the variance of the blackjack hand are easily calculated. To my knowledge this is the first published combinatorial analyzer that computes **the probabilities of each possible outcome and variance for a blackjack round** using full composition dependent combinatorial analysis.
Since splits EV are calculated using optimal post-split strategies, calculations for 2 and especially 3 splits for a full deck will take a long while to finish,
If you have a 64-bit Windows machine, i recommend you use the x64 version.

Current supported rules:

Dealer stands/hits a soft 17, American (peek) game/European No hole card, Resplit up to four hands, Double after split/no double after split. Also included is the option of knowing the dealer's hole card.

Results are outputted to a text file. See sample below for a player 9,9 versus a dealer 6 (S17, 1 split, DAS)

![http://i378.photobucket.com/albums/oo228/iCountNTrack/CDCA.png](http://i378.photobucket.com/albums/oo228/iCountNTrack/CDCA.png)
player's Hand  9,9 versus dealer's upCard  6


player's probabilities for standing

p<sub>-1</sub> = 0.312809031097, p<sub>0</sub> = 0.109186691054, p<sub>+1</sub>= 0.578004277849, p<sub>+1.5</sub> = 0

EV for standing = 0.265195246753 ± 0.905806154785

player's probabilities for doubling

p<sub>-2</sub> = 0.780340663691, p<sub>0</sub> = 0.0260314660969, p<sub>+2</sub>= 0.193627870212

EV for doubling = -1.17342558696 ± 1.5871189393

player's probabilities for hitting

p<sub>-1</sub> = 0.780340663691, p<sub>0</sub> = 0.0260314660969, p<sub>+1</sub> = 0.193627870212

EV for hitting = -0.586712793478 ± 0.793559469651

player's probabilities for splitting

p<sub>-4</sub> = 0.000776701766268, p<sub>-3</sub> = 0.0319114994184, p<sub>-2</sub> = 0.237210834181

p<sub>-1</sub> = 0.0842659697756, p<sub>0</sub> = 0.128753279098, p<sub>+1</sub> = 0.042708933063

p<sub>+2</sub> = 0.397700137121, p<sub>+3</sub> = 0.0740025865067, p<sub>+4</sub> = 0.00267005906972

EV for splitting = 0.413268259647 ± 1.87195167681