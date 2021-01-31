# Credit-Scoring-using-Fuzzy-Logic

## Fuzzy Inference System
Fuzzy Inference System is the key unit of a fuzzy logic system having decision making as its primary work. It uses the “IF…THEN” rules along with connectors “OR” or “AND” for drawing essential decision rules.

## SciKit-Fuzzy
Scikit-Fuzzy is a collection of fuzzy logic algorithms intended for use in the SciPy Stack, written in the Python computing language.

## Usecase 
Credit scoring is a statistical analysis carried out by lenders and financial institutions to access a person's creditworthiness. Credit rating is used by lenders to help decide whether to grant or deny credit.
Artificial intelligence, being a very strong tool based on statistics, plays here a major role : **supporting decision-making** . We can predict to which category this client belongs, either by providing the algorithm with a large database so that it can find the relationships between the different attributes and the target or based on rules that we define ourselves, as in our case.

## Methodolgy 
In order to determine the class to which the client belongs, I followed the following logic:
1. Calculate the net annual income of the client:
From data influencing the net income of the client.. 
Example: married or not / number and ages of children ..etc
2. Classify the environment:
Taking into account other factors such as the accomadation situation (renting or owner), the existence of other credits .. etc.
3. Classify the client: having as input the previous two points and adding the annual slice of the requested credit: this slice represents a benchmark for us. Indeed, after
doing some research, I found that this slice typically accounts for 33% of the income and can reach 45% if the income is very large and therefore the client will always have a
remains to be lived which allows him to satisfy all his needs.

