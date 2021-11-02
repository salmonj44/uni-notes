#SDAV 
# SDAV

need to think about the input, prrocess and output


## How do we construct features from our data

- by taking our data and putting it over a useful time interval
(MPH)

- using classification
Number of emails sent to or from a specific addressnumber of unique words in each email

- Then add this to some sort of temporal or spacial feature
GPS coordinates
pixel locations in an image

- temporal/spacial features
pixel lovation in a video stream
gps coordinates of a moving vehicles position

## Finding and cleaning data
ilterinoug out noise
collectiong timestamps

will be explored furthesr in future pracs


## Types of anomalies
- 3 types of outlier
	- point
	- contextual
	- subsequence
- WE will be thinking about time series anoalies

### Point alomaly
- A singe point in a Time SEries is anomalous compared to the rest of the data

### Contextual Anomaly
- A data instance ina  time series which is considered anomalous because of the context. In order to detect such anomalies we need to have information on the ontext itself

### Subsequence anomaly
-  This is where collective anomalies which are anomalous with regards to the rest of the data *even though* dataoints from within the subsequence might not be considered anomalous
-  ![[Pasted image 20211102101358.png]]

## Descriptive Statistics
- Distribution
	- a set of data
- MEan
	- average value of the distribution
- Medial
	- middle value of the distribution
- Mode
	- most common value
- Standard deviation
	- Spread of the data

## Comparing data
![[Pasted image 20211102102257.png]]

Ststistically they are all equal!
![[Pasted image 20211102102337.png]]

This is known as anscombe's quartet


Make both calculations and graphs, as they can give very different data visualisations

Correlation does not mean causation




