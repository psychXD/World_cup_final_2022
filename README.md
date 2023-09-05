# World_cup_final_2022
This script demonstrates how to use historical match data to predict the outcome of a hypothetical football match between Argentina and France. It incorporates the following steps:

1. Calculates a K factor based on historical performance for both Argentina and France.
2. Adjusts the initial team ratings using the K factor.
3. Trains machine learning models to predict match outcomes.
4. Predicts the outcome of a hypothetical match between Argentina and France.

The code is designed to be adaptable to other team matchups by providing the necessary dataset files.

## Features

- Calculation of a K factor to account for historical performance.
- Adjustment of team ratings using the K factor.
- Machine learning models to predict match outcomes.
- Flexibility to replace dataset files for different teams and matchups.

## k factor calculation as:

K = (Total Points Won / Total Matches Played) + 1
where Total Points Won is the sum of all points earned (3 points for a win, 1 point for a draw, 0 points for a loss), and Total Matches Played is the total number of matches played.


## Contributins
Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.
