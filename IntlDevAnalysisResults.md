# Who cares?  Drivers of engagement in International Development

With over a quarter of the world's population on Facebook, the platform is an effective tool for enhancing communication and outreach strategies.  For international development organizations, increased engagement helps raise awareness and mobilizes financial and in-kind support for key issues that contribute to social and economic development.  How do international development organizations differ in approaches to Facebook engagement in relation to frequency of posts, topic of posts, and associated media?  What are effective strategies for enhancing engagement as measured by likes, comments, and shares of posts?  Do the timing of posts and frequency of posts matter?  Does using videos or photos provide attention getting value?  What topics generates greater comments? Are users sensitive to content subjectivity or degree of positive content contained in messages?

## Data

This project uses Facebook page data of international development organizations and their feeds over time available from Facebook's public graph API.  Preliminary insights are provided on the production of social media by these organizations and strategies that could be effective in enhancing follower engagement.

## Social media production:  posting frequency and content 

The international organizations reviewed are making efforts to use social media and keep followers engaged by posting on average more than one post per day.  UNDP has the highest average number of posts with 2.3.  Pictures and videos are used frequently by the UN and World Bank with half of all posts containing photos and UNHR using photos nearly 3/4 of the time.  Videos are used less frequently with the UN using this type of media the most frequently out of the reviewed organizations at 18 percent.  Messages generally tend to be framed more positively than negatively as observed by the positive value on polarity.  Most posted messages are more objectively framed with statistical facts and figures as the average subjectivity of posts are closer to 0 than 1.  World Bank and ADB focus the most on poverty and inequality in their posts at 30 percent and 18 percent respectively.  UNHR and the UN have a greater focus on corruption and governance accounting for 15-19 percent of all of their posts.

While UN, UNHR and World Bank have a high number of fans/followers of the pages at over 2 million the conversion of fans into actual engagement is low with the UN and UNHR receiving only about 400-500 likes per average while the World Bank receives 1500 likes per post.  However, the ADB has the highest likes per number of followers given that it only has around 250K follower, but nearly 1100 likes per post.  If comments and shares is a better measure of true engagement then both the UN is doing the best of the organizations reaching an average of 50 comments compared to only 3 comments on ADB pages and 15 comments on World Bank pages.  The UN organizations the UNHR also has nearly 4 times as many shares as the World Bank at 170 shares on average per post.  Nevertheless some of these basic statistics should be viewed with caution as a closer examination of World Bank and ADB page likes over time indicates that these likes may not be organic.  In contrast, comments and shares appear to suffer less from distortions.   

**Table 1**

|Page|# of Posts|Days on FB|# of Posts per Day|Photo share|Video share|Message Polarity|Message Subjectivity|Mean likes|Mean comments|Mean shares|
|---|---|---|---|---|---|---|---|---|---|---|
|AsianDevBank|3033.0|2639.0|1.149|0.337|0.121|0.126|0.348|1169.574|3.245|21.411|
|IADB.org|5123.0|3101.0|1.652|0.213|0.041|0.107|0.292|11.806|0.453|4.745|
|UNDP|7084.0|3053.0|2.32|0.428|0.121|0.155|0.36|329.997|13.155|68.768|
|USAID|5534.0|2969.0|1.864|0.248|0.096|0.119|0.281|121.344|5.595|16.887|
|United Nations (UN)|7322.0|4123.0|1.776|0.585|0.182|0.132|0.323|406.665|54.919|112.732|
|UN Human Rights|4591.0|3343.0|1.373|0.76|0.062|0.07|0.289|506.255|43.793|177.365|
|World Bank|6006.0|3824.0|1.571|0.518|0.163|0.131|0.351|1495.177|15.735|44.151|

**Table 2**

|Page|Poverty, Ineq., Growth|Aid Effectiveness|Climate Change|Corruption and Governance|Education|Gender|Data and Technology|Finance and Investment|Global Health|Infrastructure|Migration|International Trade|Other|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|AsianDevBank|0.167|0.106|0.153|0.081|0.046|0.048|0.025|0.056|0.034|0.089|0.029|0.028|0.136|
|IADB.org|0.102|0.1|0.112|0.115|0.075|0.046|0.032|0.072|0.051|0.048|0.013|0.033|0.2|
|UNDP|0.13|0.114|0.106|0.13|0.037|0.108|0.018|0.03|0.066|0.04|0.043|0.009|0.17|
|USAID|0.082|0.143|0.045|0.133|0.095|0.076|0.027|0.021|0.115|0.037|0.045|0.01|0.171|
|United Nations (UN)|0.071|0.082|0.121|0.156|0.048|0.094|0.024|0.018|0.124|0.016|0.053|0.017|0.176|
|UN human rights|0.067|0.095|0.087|0.19|0.036|0.166|0.008|0.017|0.084|0.022|0.034|0.016|0.177|
|World Bank|0.309|0.046|0.101|0.101|0.062|0.052|0.021|0.032|0.058|0.041|0.05|0.01|0.117|

![alt text](https://github.com/natc79/IntlDevEngagement/blob/master/post_engagement.png "Average Engagement with Posts")

## Trends over time


![alt text](https://github.com/natc79/IntlDevEngagement/blob/master/engagement_per_month.png "Engagement Per Month")

## Real Engagement?

A key concern is that engagement may be superficial if organizations undertake actions to boost their engagement numbers.  The publicly available Facebook data, however, is somewhat limited in its scope to identify organizations undertaking actions that boost artifically count numbers as it is not possible to break down likes by countries, languages or view details on most people who like the page beyond the ID/name.  This presents difficulties in the analysis in that it introduces an additional error into any model that attempts to understand factors driving engagement as it is unrelated to actual content and quality of the post.  For example boosting the number of likes of your posts by 1000 can cost as little as $5 per month.

Considering that comments are a better measure of real engagement compared to likes as it involves an extra time cost and far fewer services are for post commenting, we examine how the organizations compare in terms of the ratio of likes to comments.  All observations where comments are 0 are dropped from consideration.  The graph below shows that ADB stands out with nearly 455 times the number of likes compared to comments.  Nevertheless, World Bank has a comparatively high number of likes to comments at around 65 in comparison to some of the other organizations that have ratios of 30 or less.  Are these real likes driven by differences in core constituent populations that focus more on likes or are they artificially boosted numbers?  At the very least it indicates the need to better understand some of the drivers of likes to comments as artificially boosting the number of likes may have very little return in developing true engagement. 

![alt text](https://github.com/natc79/IntlDevEngagement/blob/master/likes_to_comments.png "Likes to Comments")

## Factors influencing engagement on Facebook

Regression estimation allows us to focus on different factors that influence engagement on Facebook.  While these factors are not considered causal within this framework they do provide a way to narrow down the set of strategies that could matter in increasing user engagement.  These linear regressions use robust standard errors that correct for serial correlation in errors over time that are related to trends in engagement.  

Broad findings:
1. Posts with photos typically are more effective in obtaining likes, comments, and shares compared to posts that do not.  They also are generally more effective than video potentially due to the hurdle (even if it is small one) of needing to watch the video.
2. Posting time does tend to matter in generating more likes, comments, and shares.  Posts that occur on Sunday/Monday generally tend to do better than those that occur on Friday or Saturday.
3. Posts with longer messages on average do increase likes and comments.  Whether this is related to quality of content or other factors is still unknown.
4. There are indications that the core followers of the organizations differ substantially in terms of their response rates to different content.  For the World Bank there is no difference in likes among the different topic postings, but topics of migration, corruption and governance, and infrastructure getting more shares.  The UN gets more likes on topics of corruption and governance, gender, and education.  ADB only receives positive responses to topics of climate change.


![alt text](https://github.com/natc79/IntlDevEngagement/blob/master/significance_AsianDevBank.png "Asian Development Bank")

![alt text](https://github.com/natc79/IntlDevEngagement/blob/master/significance_worldbank.png "World Bank")

![alt text](https://github.com/natc79/IntlDevEngagement/blob/master/significance_unitednations.png "United Nations")


# Conclusions

The organizations considered have many differences in the frequency of posts, timing of posts, and the topic matter of the posts.  They also differ in strategies on using video and photo messaging.  We used a simple linear framework to analyze contributors to higher number of likes, comments, and shares. It was found that how people interact with the pages and what they respond to are different among the organizations suggesting differences in demographics and preferences of the consumers of the content of posts put out by these organizations.  However, when organizations potentially rely heavily on buying likes the content may matter very little in increasing real user engagement.  

## Improving identification

This is a first pass at trying to understand what drives user engagement in international organizations.  However, by gathering outside data on relevant and newsworthy topics it is possible to better understand the value added from strategic posting.  Being able to obtain more detailed data on who is liking, sharing and commenting on the pages can help to better design posting content that is targeted and different demographic groups and identify key influencers that can be leveraged to generate greater engagement.  Finally, being able to separate out artificial likes from real likes may be important step in trying to improving accountability and the content produced by these organizations that is responsive and more informative for the issues that followers are concerned about.  



