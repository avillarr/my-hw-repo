### ***Design Write-up Feedback***

***Nico Van de Bovenkamp***

***

***Regarding Site Info***  
It seems to me that you have the site_id in the dataset for the users. This means you could indicate what site they came from and just throw that into the model as part of your modeling task (an indicator of if they went to that site or not). Maybe I am misunderstanding what the actual data means, but if this is the case then throw it in the model because I would believe that your hunch is correct.

***Regarding costs of an inaccurate model***  
I'm not sure there are *no* costs. It depends, I suppose, on what actions you would take after having said model and the purpose of the model. If you are just trying to find out what are great indicators of conversion, then maybe not! But if you are using it to, say, target or push campaigns to different people, then you may want to weigh the cost of sending/targeting someone that will not actually convert. We covered this briefly, but when performing modeling tasks that result in some classification, you can usually turn that probability into real terms by making it some form of expectation. Given the probability of converting, what is the expected return of targeting this person?

**Questions:**

* Can you get support data? That would be interesting. That may be a slightly different analysis, and begs a slightly different set of questions too, but maybe this would be good information to put into the model!

* What kind of model (models) do you want to try using? What model/models make the most sense? 
