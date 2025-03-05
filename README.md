Doomed_Dice

Project Structure

#Doomed-Dice-Challenge

README.md: Project Documentation
doomed_dice.py: Main Python Script


#Usage

Calculate dice probabilities.
Transform the dice under Loki’s conditions while preserving sum probabilities.

#Example Output

Total Outcomes: 36
Sum = 2: Count = 1, P(Sum = 2) = 0.0278
Sum = 7: Count = 6, P(Sum = 7) = 0.1667

New Die A (<=4 spots): [1, 2, 3, 4, 1, 1]
New Die B: [6, 7, 8, 5, 4, 3]

#Functions Explained

dice_combinations(die_a, die_b)
Generates all possible dice roll combinations.

distribution_and_probability(die_a, die_b)
Computes the frequency and probability of each sum.

undoom_dice(die_a, die_b)
Transforms the dice under Loki’s conditions while preserving probabilities.
