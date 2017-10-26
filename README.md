# 3_years_of_Maan_Ki_Baat_A_WordCloud_Analysis

'Mann Ki Baat' is a monthly radio program hosted by Prime Minister Narendra Modi in which he addresses the people of the nation on various issues, often social. The first broadcast took place on the 3rd of October, 2014 and a total of 36 episodes have been completed thus far i.e. 3 years. It has enjoyed high listenership and is widely heard across India, dealing mostly with social issues.The purpose of this analysis is to see if ‘Maan Ki Baat’ is influenced by political considerations other than social issues.

## Background 
Narendra Modi was elected with a majority to the Lok Sabha n May 2014. This was the first time in 30 years when apolitical party in India, BJP in this case, achieved majority on its own. This win was attributed to the charisma and towering personality of Modi. All newly elected political leaders enjoy a ‘honeymoon period’ lasting a few months from the election. For Narendra Modi, this period can be said to last upto the Bihar Assembly polls period i.e. November 2015 when the BJP suffered a big defeat despite Modi campaigning extensively. Till that point, BJP did not put up CM candidates upfront before polls and tied to cash on the Modi’s popularity. Subsequently, however BJP began announcing CM candidates for state polls. So, Bihar election was definitely an inflection point which we can use as an indicative point to check for changes in nature of speeches. If any change is seen in ‘Maan Ki Baat’ speech content post Bihar election result, we can conclude that politics or its impact affects the nature of ‘Maan Ki Baat’.

## Methodology
The speeches were sourced from the the English transcript version from the [PM_India website](http://www.pmindia.gov.in/en/tag/mann-ki-baat/).  There were 13 speeches before November 2015, which is when the Bihar election results were declared. So, transcripts from the first broadcast delivered on October 2014 to October 2015 delivered before Bihar polls were copied into a single file. Similarly, broadcasts from November 2015(delivered post Bihar results) to October 2016 were copied into a single file and lastly November 2016 to September 2017 ie the latest broadcast were copied into a single file. Thus, these three files represent the total Maan Ki Baat for each year and the Bihar election provides a neat division between the 1st and 2nd year.

The texts were cleaned us R text mining packages wordcloud, SnowballC, tm. First, the respective text files are transformed to lowercase followed by removing punctuation, stop-words and extra space among words. Then, it was converted to root words by stemming so that all versions of the different words are represented as their root words. So, now the word cloud is generated for each year using the transformed text transcripts.

![WordCloud Comparision across 3 years](https://github.com/homagnibhatt/3-years-of-Maan-Ki-Baat-A-WordCloud-Analysis/blob/master/Picture1.jpg)

## Comparing the top 10 words accross the three years.
Now, let us compare the top 10 word frequencies accross the three years so that we can have an easy way to check if the word pattern has changed.

![Barchart Comparision showing word frequencies across 3 years](https://github.com/homagnibhatt/3-years-of-Maan-Ki-Baat-A-WordCloud-Analysis/blob/master/Capture_barchart.JPG)


## Conclusion
From, both the WordCloud analysis and Word count plots we can see that Bihar election results have not had any effect on the
nature of speeches made in 'Maan ki Baat'.  
Indeed, throughout the 3 year period, election results have not had any impact.
Thus, we can say that the 'Maan Ki Baat' programme is independent of politics and will continue to highlight social issues 
and engage citizen participation with the aim of inducing positive changes in citizen behaviour. 
