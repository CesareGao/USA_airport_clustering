# USA Airport Clustering

Data source: U.S. Federal Aviation Administration and Research and Special Programs Administration, ‘Airport Activity Statistics’ (1990). I ﬁnd it on [jse](http://jse.amstat.org/datasets/airport.dat.txt). 

This data set consists of all 135 large and medium sized air hubs in the United States as deﬁned by the Federal Aviation Administration. 

A brief description from the data contributor is in [link]( http://jse.amstat.org/datasets/airport.txt ).

## Question Analyzed

Use R to explore if the data set could be clustered as two parts, large size and medium sized air hub, as the dataset claimed, or more reasonable clustering method could work.

## Method

I use hierarchical clustering. Although k-means clustering runs quite faster than hierarchical clustering, it is quite random and could produces diﬀerent result, which is vague to test appropriate parameters like the number of clusters. The hierarchical clustering is more clear to show the priority of diﬀerent number clusters and which one is more reasonable.

## Result

The airports are clustered to 3 different groups. And one of them gives me the top five as:
- HARTSFIELD INTL ATLANTA
- O'HARE INTL CHICAGO
- DALLAS/FT WORTH INTL DALLAS/FT WORTH
- LOS ANGELES INTL LOS ANGELES
- SAN FRANCISCO INTL SAN FRANCISCO/OAKLAND
, which quite corresponds to what I found online.
