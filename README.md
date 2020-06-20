# Guided Project - Find the Best Markets to Advertise

In this guided project, we make one step further and learn to combine some of these skills to perform practical data analysis. 
Moreover, we'll also make use of what we learned in the first course.

Let's assume that we're working for an an e-learning company that offers courses on programming. 
Most of our courses are on web and mobile development, but we also cover many other domains, like data science, game development, etc. 
We want to promote our product and we'd like to invest some money in advertisement. 
<b>Our goal in this project is to find out the best two markets to advertise our product in.</b>

To reach our goal, we could organize surveys for a couple of different markets to find out which would the best choices for advertising. 
This is very costly, however, and it's a good call to explore cheaper options first.

We can try to search existing data that might be relevant for our purpose. One good candidate is the data from [freeCodeCamp's 2017 New Coder Survey](https://medium.freecodecamp.org/we-asked-20-000-people-who-they-are-and-how-theyre-learning-to-code-fff5d668969). 
[freeCodeCamp](https://www.freecodecamp.org/) is a free e-learning platform that offers courses on web development. Because they run a [popular Medium publication](https://medium.freecodecamp.org/) 
(over 400,000 followers), their survey attracted new coders with varying interests (not only web development), which is ideal for the purpose of our analysis.

The survey data is publicly available in this [GitHub repository](https://github.com/freeCodeCamp/2017-new-coder-survey).

We'll notice that most column names are self-explanatory, but it seems that we don't have a clear documentation explaining each column name. 
However, we can find more information in the [raw-data](https://github.com/freeCodeCamp/2017-new-coder-survey/tree/master/raw-data) folder of the repository we mentioned above — we can find 
the initial survey questions, and from there it should be easy to infer what each column describes.
