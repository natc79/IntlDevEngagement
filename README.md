# International Development Engagement (README file)

Facebook data is used to compare post timing and content of international organizations and factors determining engagement.

## Main Report

**IntlDevAnalysisResults.md **
Contains the write-up for the main results of the analysis.

## Python Files

**AnalyzeFacebookData.ipynb**
Provides the primary code use for analysis that processes and formats the Facebook data that was retrieved from Facebook's Graph API.

**WikipediaTopics.ipynb**
Downloads Wikipedia pages related to key international development topics.  It then extracts the the 30 most common nouns and the 10 most common bigrams from these pages using Python's NTLK library and outputs them into separate files.  These most common words are then drawn upon in AnalyzeFacebookData to categorize different posts in terms of their topic based on the content found in the message of the posts.


