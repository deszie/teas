# Exploratory data analysis : French Second Round election 2017
#### Project #1: Survey
#### Project #2: Unemployment data and FN vote 

----------------------
### Project #1: Survey 
#### Introduction : 

This is a proof-of-concept for how new methods of collecting and generating data can be used to help think about political events and shape investment decisions. For a nominal sum of money in Facebook ads I got >1000 survey respondents targetted at exactly the demographics I needed, and was able to confirm that although Marine Le Pen was indeed popular among the youth, followed by Melenchon neck and neck with Macron, the likely scenario overall would still be a Macron victory. 

About 400 of them also gave me answers to long-response questions. In the [second notebook](nbs/Part II - French election survey .ipynb) I use IBM's Watson ToneAnalyzer to find that comments about Le Pen trigger a higher amount of 'fear' rating than that of Macron. These responses are rich with opinion and can be exploited further with more advanced NLP methods in the future. 

The first notebook focuses on exploring the quantitative survey data. The [second](nbs/Part II - French election survey .ipynb) looks at the textual data generated by the open-ended questions.

**Conclusion: ** This is a very cheap method for gathering proprietary data and can be easily scaled up.

#### Description of work: 

Here in New York, I watched as Donald Trump was elected President in November 2016. With the opportunity to subtly interview people from all walks of life here, I found it relatively easy to get a good sense of how voters thought and felt. 

In April 2017, I wondered if there was a chance of a similar event happening in France, where Marine le Pen had pitted herself as a Trump-wannabe in the upcoming presidential elections. 

Since I was unwilling to fly to Paris, I made do with extensive research on my own: careful study of the news and examination of candidates, interviews with French diaspora in NYC, speaking with fellow researchers and investors on the issue. After the first round, I built a [very simple model](https://annjie.com/presidentielle-2017-election-model/) that showed Le Pen needed a substantial portion of the remaining voters to switch to her side if she wanted to carry the day. 

One of the key issues in the past election centered around French youth. This was a new block of voters who had come of age in an economy with high unemployment and a relatively pessimistic view of the future. Moreover, they didn't view the Front National with the baggage that older generations carried -- they never knew Jean Marie Le Pen the same way young people in America today never felt Bill Clinton's impeachment in 1997.    

The rise of Melenchon towards the end of the first round seemed to indicate that young voters wanted an alternative in Melenchon, not Marine le Pen. Further, my interviews with young French diaspora here in NYC told me there was a strong aversion to Marine le Pen. Yet I wondered if this was because of selection bias: those who were here in New York were more likely to support progressive values. 

In the week before the second round of the election I receieved 1014 responses from an ad I put up on Facebook linking to a French-language survey. This survey targeted 18-35 year olds in France across the country. I explored topics surrounding turnout and support for either candidate in the 2nd round. I kept it simple because I wanted more people to respond.

#### Future possible work: 
- Predictive power - understanding survey respondent background and mapping it onto demographics of voters. Ask for income and occupation. 
- Upgrade SurveyMonkey so I can receive more than 1000 responses. (Overwhelming demand!)
- Exploring IP addresses, plotting voting intentions on map. 

#### Limitations:
- People who wanted to win money responded to this, possibly low quality of the people who responded? How can we implement a quality check? 
- Facebook reports the demographics of my respondents, but I could also add in an additional layer of questions in the survey.  
- This method of gathering data requires the honesty of respondents: this is self-reported, as opposed to based on recorded past behavior. 


----------------------
#### Project #2: Unemployment data and FN vote 
#### Introduction : 
Here, to examine the relationship between economic conditions and FN support, I use unemployment data from the French interior ministry website as well as the vote results from the first round of the legislative elections in France in 2015, when the FN first broke ground in its history by finishing first in the elections. (however, it still sorely lost in the second) 

#### Summary: 

I find a positive correlation between unemployment data and share of the FN vote in 2015. I further extend this to the past presidential election results in 2017 to show that Macron's support is strongest where unemployment is lower. 


