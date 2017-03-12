Summary:
I have previously conducted exploratory data analysis on the Titanic dataset and found that gender and passenger class was correlated with survival. 
My objective is to visualise this correlation and tell the story in a way that is easy to understand.  

Design:
I decided that a pie matrix would be a good choice to visualise the survival rate based on two categorical variables. My feedback was very positive but with some room for optimization e.g. I changed the pie color to be more intuitive, perfected fontsize and customized the tooltips. At the same time, the precise survival rate wasn't displayed unless you hoovered over one of the pies which made it harder to easily crasp the story.
I decided to change my chart to a bar chart displaying survival rate for both males and females, and by passenger class. The survival rate in percentage is shown on the y axis as den dependent variable and the two independent variables on the x axis. I colored the male bars blue and the female bars red since these colors a the ones stereotypically associcate with each gender. 
I thoose the skyblue and salmon because they are more easy on the eye. 
I did consider a scatterplot or line chart, but considering the categorical nature of the variables gender and passenger class (even though passenger class is ordered), I decided on the bar chart. 

Feedback:
-1st review: 
Two reviewers present. 
One of the reviewers quickly understood the story but found the colors counterintuitive and suggested that I switched them around (the red and blue). She accoiated death or danger with red and survival or no danger with blue.
Also, the legend text was too small.  
The other reviewer was somewhat passive and there is a possibility that he struckeled to comprehend the story. 
-2nd review:
One reviewer present. 
He found the tooltips a little confusing with variables like "PassengerId" and "Pclass" in the tooltip that wasn't explained anywhere. And "Survived: Survived" and "Survived: Died" required additional explanation. I decided to customize and simplify the tooltips.
-3rd review:
By Udacity. Friends don't let friends use pie charts...or pie matrices...
And an introductory explanation was needed. 
-4th review:
One reviewer present.

Resources:
-dimplejs documentation
-stackoverflow
-https://www.kaggle.com/c/titanic