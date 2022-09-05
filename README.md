# Was-Steph-Curry-Robbed-in-2015
An Investigation into Steph Curry's (lack of a) 2015 Finals MVP. 
This investigation seeks to answer the question: WOULD Steph Curry have won Finals MVP based off of the way the FINALS MVP has generally been awarded? The question of SHOULD is a matter of debate that can get murky and highly subjective.
I scraped data from the web for all of the NBA Finals going back to 1969 (when Finals MVP was introduced) 
I looked at the biggest point differentials between Finals MVP and Leading Scorer on a team. 2015 was one of the biggest. Points is also a great indicator for who will win Finals MVP.
I built a model to predict who wins Finals MVP. The initial model used 5 features. Attempts with more features were made but the 5 basic features worked best as they are "traditional" stats which is what voters of the Finals MVP (and casual fans) typically pay attention to (remember, who WOULD win).

UPDATE
One huge feature that was left out of the original model was "Winning Team"; only one player from a losing team has ever won Finals MVP. The addition of "Winning Team" as a binary boosted the accuracy of the model by close to a percent and the precision went up 10 percentage points.
