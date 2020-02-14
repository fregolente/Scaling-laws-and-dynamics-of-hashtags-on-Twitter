Abstract

In this paper we quantify the statistical properties and dynamics of the frequency of hashtag use on Twitter. Hashtags are special words used in social media to attract attention and to organize content. Looking at the collection of all hashtags used in a period of time, we identify the scaling laws underpinning both the hashtag frequency distribution (Zipf's law) and the number of unique hashtags as a function of sample size (Heaps' law). While these scaling laws appear to be universal, in the sense that similar exponents are observed irrespective of when the sample is gathered, the volume and nature of the hashtags depends strongly on time, with the appearance of bursts at the minute scale to drifts at the scale of months. We quantify this dynamics by computing the Jensen-Shannon divergence between hashtag distributions at different times and find that the speed of change decays as a function of time~$\tau$ roughly as 1/\tau. Our findings are based on the analysis of 3.5 billion hashtags used between 2015 and 2016.

Methods

Twitter data to measure hashtag popularity was obtained from a sample of public tweets provided by the Twitter streaming application programming interface. Rare hashtags have a lower chance of being represented in this sample, however, such a bias should not affect the resuts. We extracted every hashtage from each tweet and computed their frequency considering three time scales, namely, days, hours and minuts. 

 

Usage Notes

Each folder contains *csv files with the hashtags and their frequency.
