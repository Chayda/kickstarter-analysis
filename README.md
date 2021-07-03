# Kickstarting with Excel
## We are using data from Kickstarter to perform analysis and uncover trends
### The purpose of this analysis is to provide Louise with information to help her create a Kickstarter campaign that has a higher chance of success by providing her with relevant data-based analysis of other Kickstarter campaigns that have run for plays. She will be able to view the results of the analysis and see if there is a relationship between successful Kickstarter campaigns for plays and their launch dates. If there appears to be a time of the year that campaigns launched have more success, she will be smart to plan her campaign during the months that have highest success (if there's a trend). This can help inform her if there are optimal times to start future campaigns. She will also have an idea if there is a relationship between campaign goals and their success so she can determine if she needs to set a specific parameter for her campaign goals for plays.
### I encountered a challenge was when I was working with the COUNTIFS function on the 'Outcomes Based on Goals' Worksheet where I was to count the totals of successful, failed, and cancelled fundraising goals based on parameters separating goal amounts by ~$5000 each.  I signed in to the Office Hours and asked the TA if I was putting the function in correctly, because when I googled how, I thought I was doing it properly. He said the format of the arguments looked good so I had to go through and try it against a few different goal parameters. I kept coming up with the same result: “0” and I went back and checked the original dataset to see if that was correct. If it were correct, it would mean that there were many goal amounts that had zero successful campaigns which seemed unlikely, and upon checking I could see that there were indeed successful goals within parameters that my function was returning a value of zero. This meant that I was still doing something incorrectly. I went over the arguments of my function one at a time and noticed that I was using an incorrect column in my function, so when I put the correct column (“Successful Goals,” etc.) I started returning values. I realized that it was easy to check if my value returns were correct by just going back and filtering the data. I learned that I can check my functions if I comb through them and make sure each element is correct. 
### Results
-	Based on the launch dates of the campaigns, it looks like the most successful campaigns were launched from May to July. In contrast, November to January appeared to have the lowest success rates. The trend line for the successful and failed campaigns follow a similar trend, which may indicate that there are other reasons for campaigns to fail that have nothing to do with the launch date.

-	The trend line for the successful campaign goals seems to go down as the goal amounts increase, which has an inverse relationship with the failed campaign goals. The highest success were with campaigns that were under $5,000. Above that amount the success of campaigns mostly goes down, aside from a small number of campaigns in a higher goal bracket, but there were only a few campaigns run that were that high, so the rate is still low as campaign goals increased.

-	Though the dataset is mostly complete, there are variable that are not included in the dataset which could provide more information about why some campaigns are successful in comparison with other campaigns in the same sub-category. We can’t be certain based on the scope of our analysis for the reason(s) why some campaigns failed. 
-	Kickstarter campaigns offer rewards for backers, and knowing what these are as well as demographic information about the backers could provide valuable insight to see if there’s a relationship between the rewards offered and successful campaigns. Other data about the backers, like if they consistently pledge to multiple campaigns would be useful. It would help to know if there are some strategies that incentivize backers to pledge more.
-	Information about the creators would also be extremely useful if it were included in the dataset. Knowing how many successful campaigns creators have run, as well investigating other details such as how large their reach is by viewing their social media following could provide useful insight to factors that affect the success of the campaigns. 
-	Another limitation of the dataset is the Country column. It’s not clear from the abbreviations what each country is, and there would be an assumption that the person analyzing the data should know what each stands for.

-	We could create a pivot chart that filters for location to see if there are some locations where plays are more successful than others. Some locations might have populations that go to plays more frequently or in higher numbers. This could help Louise decide if there are better locations to run her campaigns, if possible.

