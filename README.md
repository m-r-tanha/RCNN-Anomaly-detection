# RCNN (Recurrent Convolutional Neural Network)
# Anomaly-Detection

![Anomaly detection](https://github.com/m-r-tanha/RCNN-Anomaly-detection/blob/master/GettyImages-960881164.jpg)

[IEEE SAMI 2020 Conference paper link](https://github.com/m-r-tanha/RCNN-Anomaly-detection/blob/master/ICC4.pdf)
<h3>
In this project, we propose a novel algorithm to detect anomaly in terms of Key Parameter Indicators (KPI)s over live cellular networks based on the combination of Recurrent Neural Networks (RNN), and Convolutional Neural Networks (CNN), as Recurrent Convolutional Neural Networks (R-CNN). CNN models the spatial correlations and information, whereas, RNN models the temporal correlations and information. Hence, adopting R-CNN provides us with spatial-temporal analysis. In this paper, the studied cellular network consists of 2G, 3G, 4G, and 4.5G technologies, and the KPIs include Voice and data traffic of the cells. The data and voice traffics are extremely important for the owner of wireless networks, because it is directly related to the revenue, and quality of service that users experience. These traffic changes happen due to a couple of reasons: the subscriber behavior changes due to especial events, making neighbor sites on-air or down, or by shifting the traffic to the other technologies, e.g. shifting the traffic from 3G to 4G. Traditionally, in order to keep the network stable, the traffic should be observed layer by layer during each interval to detect major changes in KPIs, in large scale telecommunication networks it will be too time-consuming with the low accuracy of anomaly detection. However, the proposed algorithm is capable of detecting the abnormal KPIs for each element of the network in a time-efficient and accurate manner. It observes the traffic layer trends, and classifies them into 8 traffic categories: Normal, Suddenly Increasing, Gradually Increasing, Suddenly Decreasing, Gradually Decreasing, Faulty Site, New Site, and Down Site. This classification task enables the vendors and operators to detect anomalies in their live networks in order to keep the KPIs in normal trend. The algorithm is trained and tested on the real dataset over a cellular network with more than 25000 thousand.
