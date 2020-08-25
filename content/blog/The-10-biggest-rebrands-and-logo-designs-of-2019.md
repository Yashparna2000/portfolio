---
author: Yashparna D
date: "2020-08-23T13:40:00+06:00"
feature_image: images/blog/cc.jpg
image: images/blog/cc_new.jpg
title: 'The correlation-Causation fallacy' 
---
### If correlation does not imply causation, what does? 

**How do we apply this to our learning? What do we consider while analyzing data or for machine learning? **                           
**In this blog post, let us try to understand and answer such questions.**


It is surprising how news can frame a mindset through properly framing the content and making use of the fact that correlation means causation. As I was going through the news of the rise in covid cases, I came across the article which stated which city is safest to stay at the moment and we were happy we weren’t staying in Mumbai which was called the least safe.
But when we take a step back and think, we are correlating a place with the number of cases and its safety, not taking in other factors such as the medical facility, the number of recoveries etc.

![news clipping](C:\Users\Owner\Documents\portfolio\static\images\blog\cc1.jpg)


 This made me think, how many times do we come across such examples where we assume correlation means causation?
 
We have also come across articles such as people who drink tea frequently are less prone to lung cancer or, studying at so and so places has shown increase in employment by such percentages. 
How do we know what to believe? How can we conclude the correlations do or don’t imply causation? 


To get the answer to some of the questions asked , let us first know what exactly is correlation and what is causation?
Understanding both the statistical terms is important to make correct conclusions.

**Correlation is a statistical technique which tells us how strongly the pair of variables are linearly related and change together. It does not tell us why and how behind the relationship but it just says the relationship exists.**

**Causation takes a step further than correlation. It says any change in the value of one variable will cause a change in the value of another variable, which means one variable makes other to happen. It is also referred as cause and effect.**

Now that we know the basic difference and definition of both, let us now check out the fallacy. Are they both related or not?

**Correlation does not necessarily imply causation:**

![graph](C:\Users\Owner\Documents\portfolio\static\images\blog\cc2.png)


As we can see from the above example, correlation does not always imply causation. We can find many such examples and hence proving this fact (click [here](https://www.tylervigen.com/spurious-correlations) to go through this site for more examples just for fun)

But then can we say that it’s always true? Then how do we do analysis and train machines with data for automation?

**Then what does imply causation?**

 *-Randomized trials*
 
Although the fallacy is right, we still take random data variables while making a model, let it be machine learning or analyzing data, and search for the highest correlation and train our data. Then how can we assume our model is even right forget about giving optimal solution?

This is exactly the first confusion that I had in mind, although the answer to it is rather direct and simple.

We get an optimized solution because:
1)  We consider randomized data for training our model
2)  We only consider the variables that can lead to the output causation

To explain the first point, consider that we are conducting a survey where I’m trying to prove that only student who drink sprite are the toppers, And I conduct the survey by just giving sprite to the student who are already on the toppers list and tabulate the data. 

Although I’ll get a high correlation here the data is not reliable. This problem can be solved had I chosen students randomly.


Now comes the second point. So even though in the above example we have a random selection of data, we might still get a correlation by chance, hence proving the fallacy. 

This can only be taken care by choosing the variables using our common sense.

We know that there is no component in sprite that can lead us to any conclusion about student’s IQ. Hence we don’t take it as a variable.
Sometimes, even though we can’t see a direct correlation, we can find an extra variable that can lead to causation explanation.


There are few ways in which leads to causation in data science that can be considered to avoid such problems.
(Click [here](https://insights.principa.co.za/5-correlation-types-in-data-science-and-how-to-not-fool-yourself)  to know more)   


![chart](C:\Users\Owner\Documents\portfolio\static\images\blog\cc3.png)


Hence, although we work with correlation between variables in ML and data analysis, keeping the above points in mind we can conclude that, **Correlation might and might not imply causation. It’s up to you.**

