# Machine Condition Monitoring with Clustering 🔊



## The Mission

Acme Corporation is a worldwide supplier of technological equipment. The factory is facing significant problems with their manufacturing line, the machines are constantly facing failures due to a lack of maintenance and the production is stopped every time an unexpected failure is presented. As a result, Acme is losing millions of U.S. Dollars and important clients like Wile E. Coyote are experiencing delays in deliveries.

The company has collected audio samples of equipment working on normal and anomalous conditions. Their objective is to develop a machine learning model able to monitor the operations and identify anomalies in the sound pattern.

The implementation of this model can allow Acme to operate the manufacturing equipment at full capacity and detect signs of failure before the damage is so critical that the production line has to be stopped.

Mission is to build a machine learning model for Acme, so they can continue their manufacturing activities and help the Coyote to catch the roadrunner.
For the model in this part I used unsupervised ML model which is clustering. In this term I tried to make a classification to normal, abnormal and transition sounds.

![giphy](https://user-images.githubusercontent.com/46165841/144567559-31b66a05-e5b5-40a7-a438-6096c2ef6802.gif)



 
#### Which dataset?

Orijinal dataset can be downloaded on the following link:

- [Machine Condition Monitoring](https://zenodo.org/record/3384388#.YFIrNXnvJEY)

But for the limited time datasets are downloaded directly from repository of [Ujjwal Kandel](https://github.com/UjjwalKandel2000/Machine-conditions-monitoring.git)
Thanks for his sharing the datas.

## Installation

- Pull requests are welcome.
- or ```https://github.com/yusufakcakaya/Machine-condition-monitoring-with-clustering.git```
- 

## Repo Architecture 

```
Machine-condition-monitoring-with-clustering
│
│   
│__   
│   Datasets                   : include .csv files
│
│__ __ valve.csv
|
|__ __ fan.csv
|
|__ __ pump.csv
|
│__ __ slider.csv
│
│ 
│__ README.md                  : explains the project
│
|
│__ fan_clustering.ipynb       : k-mean clustering for machine of fan
│  
│__ pump_clustering.ipynb      : k-mean clustering for machine of pump
│
│__ slider_clustering.ipynb    : k-mean clustering for machine of slider
│                
│__ valve_clustering.ipynb     : k-mean clustering for machine of valve
│

```


## Visuals

Value relations with eachother

![image](https://user-images.githubusercontent.com/46165841/145583504-ed18add2-6231-4470-88da-db7a9994f365.png)

Value relations in heatmap

![image](https://user-images.githubusercontent.com/46165841/145590060-98edd303-fd0a-4936-961d-8f897585d9df.png)

After clustering data( ZCR and Spectral Centroid)

![image](https://user-images.githubusercontent.com/46165841/145590300-b178f5fa-c212-4d4a-8205-0a275353f5de.png)

All data clustering

![image](https://user-images.githubusercontent.com/46165841/145590355-2e9afb3f-d821-455d-9073-bde85a6c0d47.png)

Silhouette analysis 

![image](https://user-images.githubusercontent.com/46165841/145590438-5c3e9e85-832b-4d15-8bc2-076c9081c1dc.png)

## Timeline

- Type of challenge: Learning
- Duration: `3 days`
- Deadline : `Thu 10/12/21 H: 4:00 PM`
- Team challenge: Solo

## Good Luck!
