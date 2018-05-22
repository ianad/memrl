I would like a measure of "optimal choice" such that on every trial, we know if the participant picked the cue that had given the most positive feedback in past trials. To determine this, you'll need:

- a running tally of the % positive outcomes that were awarded when a cue was selected 

	- eg: Cue A has been selected 4 times and gave 2 positive outcomes = 50%, Cue B has been selected 1 time and gave 1 positive outcome = 100%

- Based on these running tallies from all previous trials, determine if the cue chosen from a pair was the optimal choice.

- Code as 1 if optimal, 0 of non-optimal, and 99 if neither 

	- 99 codes will be applied when the cues in a given pair have identical % of positive outcomes (eg: both 50%, both 0% -- as on the first trial). 
