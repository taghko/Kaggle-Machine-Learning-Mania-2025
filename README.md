Description
The scope of the project is to predict the outcomes of this year's college basketball tournaments. 
The winners and losers will be picked using a combination of rich historical data and computing power, while the ground truth unfolds on television.

Provided data is historical NCAA games to forecast the outcomes of the Division 1 Men's and Women's basketball tournaments. 
This competition is the official 2025 edition, with points, medals, prizes, and basketball glory at stake.

Evaluation
Models are evaluated on the Brier score between the predicted probabilities and the actual game outcomes (this is equivalent to mean squared error in this context).

The Brier score is a strictly proper scoring rule that measures the accuracy of probabilistic predictions. For unidimensional predictions, it is strictly equivalent to the mean squared error as applied to predicted probabilities.

The Brier score is applicable to tasks in which predictions must assign probabilities to a set of mutually exclusive discrete outcomes or classes. 
The set of possible outcomes can be either binary or categorical in nature, and the probabilities assigned to this set of outcomes must sum to one (where each individual probability is in the range of 0 to 1). 
It was proposed by Glenn W. Brier in 1950.[1]

The Brier score can be thought of as a cost function. More precisely, across all items 
i ∈ 1...N
{\displaystyle i\in {1...N}} in a set of N predictions, the Brier score measures the mean squared difference between:

The predicted probability assigned to the possible outcomes for item i
The actual outcome 
o
i
{\displaystyle o_{i}}
Therefore, the lower the Brier score is for a set of predictions, the better the predictions are calibrated. 
Note that the Brier score, in its most common formulation, takes on a value between zero and one, since this is the square of the largest possible difference between a predicted probability (which must be between zero and one) and the actual outcome (which can take on values of only 0 or 1). In the original (1950) formulation of the Brier score, the range is double, from zero to two.

The Brier score is appropriate for binary and categorical outcomes that can be structured as true or false, but it is inappropriate for ordinal variables which can take on three or more values.
