### ***Project 4 Feedback***

***Nico Van de Bovenkamp***

***

**Overall**  
Great work on this assignment! You walked through the key layout of the problem, your data, your analysis, results, and future things to explore. When you are walking through your analysis, it's nice, at times, to present some issues that you ran into when working on this problem (why is this problem... a problem?!). Another recommendation is for a few more plots that are associated with your model. For example, a decision tree diagram, predicted probabilities, model performance, roc curves, etc.! Also, be mindful of how you construct your models.


***Fitting your model***  
Great work on the set up of your model, and it's interpretation! Remember, though, to One Hot Encode your categorical variables (ie. drop prestige_4.0 and only keep three) this way you avoid multi-colinearity issues! As you can see, your coefficients are a bit all over, and your summary statistics have NaNs! Try and drop that column first, then build your model.
