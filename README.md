# Project Milestone 2


Milestone P2 by the PinaColADA Team : Eloi Garandel, Kilian d'Eternod, Antoine Daeniker & Rafael Mozo. This project aims to perform a deep analysis on the Youniverse dataset.


### Abstract 
### The (predictable ?) rise and fall of YouTube stars
Created in 2005, Youtube has gained very large popularity and has expanded to the whole world. 

On the Internet, popularity and virality of content are still often misunderstood. Many creators produce very similar content but only some of them make it to the top. How can we explain such a conjecture ?


Is the process totally random or can the rise of popularity of YouTube channels be predicted in advance to some extent by looking at the numbers ? Does it always start with a buzz video for example ? On the other hand are there warning signs in the data about the virtual “death” of some channels or could any of the idols of today be the relics of tomorrow ? We could focus on channels that have exploded in popularity or inversely disappeared from the public eye during the time period of the dataset and see if we see some interesting indicators of that change. What can it say about the way that we consume content as a society ?

To vizualize our results, we will adopt the viewpoint of a fictional Youtube channel, from its creation to its end, its ups and downs. We will present the conclusions we draw from the dataset in the story of our fictitious Youtube channel to create a scenario throughout our study. Fictional events will happen and influcence our channel's metrics behavior.

### Research Questions 

Throughout our study, we will try to answer different research questions : 

- Can we identify indicators of the rise and fall of Youtube channels ? Are there recurring patterns that we can extract from the data ?
- Are top channels rising and dying at a similar rate, i.e. being replaced over time ?

- Trends are also an important part of Youtube : Are there categories that work better than others ?
- 

### Methods

- Exploratory analysis via timeseries plotting : It will show preliminary results and help us to get a better understanding of the overall datasets. For instance, by plotting some key metrics, we can already get a first idea of the correctness of our assumptions.
- Polynomial/(multiple) linear regression : by using such ML methods, we can approximate trends for individual channels or videos.
- Clustering by metrics : group channels or videos to determine models of evolution through time. We can imagine that some channels gain popularity suddenly (thanks to a viral video for example) or grow slowly, therefore following different models of evolution.
- Correlation tests between different metrics : for instance, comparing if likes/dislikes and comments are related or not as they are both engagement metrics.
- T-tests for different period of time : performing t-tests allow us to see significant changes in some metrics between different periods of time, for example, in the video duration among others.

### Proposed timeline

We will divide the overall project into 3 main parts : 

- Dataset exploratory analysis : this unavoidable step would be the start of our analysis.
- Separation by channel behavior : here, the goal is to classify into several clusters channels to have similar behaviors according to their metrics. Channels to grow or shrink in a similar manner (channels that have a similar number of likes over time for examples). This first aggregation of the data will be useful in order to better see what metric can be seen as a potential indicator.
- Prediction and indicator selection : after completion of the two previous parts, the final one will be to determine what indicator are significant for predicting a channel evolution. Here, we want to see if by taking a proportion of channels, we can predict the evolution of the other ones according to their metrics.
- Story telling setup: once we have our result, we will have to write the scenario of our fictionnal Youtube channel. This also include plotting our final vizualizations as well as the development of our project webpage.

### Organization within the team



### Questions for TAs

- Missing/weird data : while exploring the timeseries dataset, we saw that there was a huge missing chunk of data before November 2016 (affecting multiple metrics : views, subscribers, etc...). This can be seen in one of the graph we have in the jupyter notebook. Therefore, we planned to only take into account data after this date. We were thinking about replacing this missing data by the mean for example but for a part of as big as this one it would be too much extrapolation.




