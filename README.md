# IoT-Sensors-Data-Imputer-and-Classifier

This solution is a deep learning-based trainable algorithm which can classify data from multiple sensors and impute missing values.

## Product overview

This solution utilizes an Autoencoder model to learn and understand the data distribution which can fill in missing values once trained. Its objective is to classify the events based on the patterns and observations collected for data from multiple sensors. In production, the solution can handle missing information in sensor data and can still generate the correct classification for a given data point.

## Product Highlight 

* When dealing with multiple sensors as data sources, there might be interruptions to the data stream if one or more of them stop working at any point in time. A denoising autoencoder is modelled to learn the distribution of the data by training to recreate it identically so that it can account for these changes, ensuring the model can work sustainably despite any such issues with the devices. After training using data without missing values and with added synthetic masking noise, the developed model is robust to any such disappearances in the data.   

* The trained model can be made use of for classification tasks with the incoming data which could be from a variety of sources. Even if the data is of different types arising from many different sensors, devices, machines or meters, this solution is designed to take this into consideration and give out accurate classification results. This finds its applications in various industries like IT infrastructure, production and manufacturing where key business decisions are based on the information collected from such sensors.

* InfraGraf is a patented Cognitive infrastructure automation platform that optimizes enterprise technology infrastructure investments. It diagnoses and predicts infrastructure failures. Need customized Machine Learning and Deep Learning solutions? Get in touch!!

## Amazon Marketplace Link
The product can be found [here](https://aws.amazon.com/marketplace/pp/prodview-uia2s7d6vuapc)
