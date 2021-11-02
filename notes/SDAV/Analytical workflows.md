#SDAV 
# Analytical workflows

- Collect
	-  what form of data are we planning to collect?
	- what is the problem that we plan to colect
	- where do we collect from
		- organisational data
		- online
		- sensors (IOT)
		- Image/video sensors
		- human reporting
- Store
	- How do we store data
		- File formats (CSV, JSON)
		- Databases
			- MYSQL
			- MongoDB
	- Combine
		- How do we combine data sources?
		- how do we transform data sources to tell our story
			- aggregation
			- feature etraction
			- data pre-processing
				- take mean value (eg: mean packets observed every minute)
	- aNALYSE
		- How do we abalyse data?
			- Classification of data
				- labeled samples to train on
			- prediction or forecasting from data
				- are we likely to be trageted again?
			- clusterig of similar data attributes
				- types of malware?
				- no labels
			- Outlier/anomaly detection
				- Key part
				- given observation, how ca i identify when something is different, and how is it anomalous
	- Visualise
			- 2 dimential charts and plots
				- sometimes simplest is best for smaller amounts of data
			- 3d data representations
			- Focus and context
			- interaction
				- the user can interact with the data, eg zoom in and out to points


### There is no single right way to do data visualisation

## Data Science workflow
![[Pasted image 20211019134422.png]]

![[Pasted image 20211019134439.png]]

- This is often descrbed as having a human in the loop
- more common nowadays
- dashboards and stuff make it easier
