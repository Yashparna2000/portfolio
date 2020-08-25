---
author: Yashparna De
date: "2020-08-25T13:32:54+06:00"
feature_image: images/blog/FD.jpg
image: images/blog/fdd.jpg
title: False Dichotomy in data science
---
### -Philosophy or data science?

*In one of my previous blogs, I’ve already discussed a logical data fallacy called correlation causation fallacy (To read that blog post, go back to portfolio section).*


*Here I’m going to discuss another fallacy that I recently discovered could be considered a data fallacy after some thinking. In this blog post, I’m going to tell about how and why I think its logical data fallacy that should be considered for data analysis.*

![image](/images/blog/fd1.jpg)


To start off, what exactly is dichotomy?

I came across this term while going through a course in philosophy in a part that was explaining about arguments. It is considered one of the logical fallacies.

**Fallacies are common errors in reasoning that will undermine the logic of your argument. Fallacies can be either illegitimate arguments or irrelevant points, and are often identified because they lack evidence that supports their claim.**

**Dichotomy** is basically a division or contrast between two things that are or are represented as being opposed or entirely different, like right or wrong.
A false dichotomy is when, an argument falsely assumes that there are only two possibilities, when in fact, there are more than two possibilities.

Example, when our friends say that we’ll have to go to some place with them otherwise we will get bored. Here the argument is assuming that there are only two options, two possibilities. Whereas that’s not true.

For a more data driven definition, we can say that false dichotomy assumes binary states, when that is not the case.
It says that it can be either X or Y.


![image](/images/blog/fd2.jpg)

 
 When we keep only binary inputs, we sometimes fail to see and consider the other conditions and variable that could affect out outcome.
Example, consider that I’m trying to sell a two dresses online. I keep an offer of buy 2 get Rs. 100 off and give the link to few selective people. No one ends up buying the dresses. I assume that my offer wasn’t something worth and hence blame it on the price and offer I set. I fail to realize that the reason might also be that the audience to whom I have given the link aren’t the right customers. Or that the link was broken and hence no one could contact me thereafter. 

The same case, if I apply to data science, we can see that we analyze our results with respect to some variables that affect the output (Correlation –causation) and we also ignore some variables that are coming less significant when trying to fit in some particular model.  Sometimes even our accuracy increases when we remove the insignificant variables. But sometimes its better to keep in the variables.

>It all depends on what kind of final output we want.


**When to remove and when to keep the insignificant variables?**

Its important to understand what to do with the insignificant variables in order to get the optimal output that we need.

**When to keep :**

1) Very few variables present. 

   For the data to be dependent on some variable, its better to take all variables into account for increasing accuracy. It might decrease the flexibility ( Decision trees) but its still a good model.
   

2) You want to show what all are controlling your output.

   We need to consider that even though less significant, it still has some effect on the output considered.
   

3)  Predictors you have specific hypotheses about.

Another example is if the point of a model is to specifically test a predictor–you have a hypothesis about a predictor and it’s meaningful to show that it’s not significant. In that case, I would leave it in, even if not significant.


4)  Items involved in higher-order terms

When you take out a term that is involved in something higher, like a two-way interaction that is part of a three-way interaction, you actually change the meaning of the higher order term.  The sums of squares for each higher-order term is based on comparisons to specific means and represents variation around that mean.
If you take out the lower order term, that variation has to be covered somewhere, and it’s usually not where you expect it.  For example, a two-way interaction represents the variation in cell means around the main effect means.  But if the variation between the main effect means isn’t measured with a main effect term, it ends up in the interaction, and that interaction doesn’t reflect the variation it did if the main effect were in the model.




**When to not:**

I’ll only state a few reason from the top of my head and not go into details because this one we already know pretty well.


1) We have limit to the number of variables we can use.

Sometimes when we have large dataset with many variables, the data will become too rigid for our test cases and the model making will also take up huge amount of time.


2) Strongly related variables.

When there is a strong correlation between two variables, we can safely assume that the change in output with respect to one will be almost same as the change in output to the other. Hence we don’t need to include unnecessary extras.

    
There are few other reasons too why we need to consider or not consider the variables.


To conclude, as we already know  that analytical thinking and basic common sense is the basis of solving data science problem. Solving this false dichotomy also boils down to **do what you need to  get the output that you need. But make sure to play by the rules.**

