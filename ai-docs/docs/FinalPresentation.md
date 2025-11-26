# Synthesis :

## Summarize your projet, present the objectives of the solution and the pros/cons - and, if appropriate, give a final opinion on the application in the environmental context.

-intro/summary
Our project is about UAVs (Unmanned Aerial Vehicle) used for disease diagnosis, prevention and target treatment of crops.<br>

Our first impression was mixed, we had a lot of preconceptions that we then tried to verify or refute on several topics. Such initial ideas were related to several topics, such as the energy used to power the drone, how such a technology could help a farmer, or the use of AI in this domain.<br>

We reserached existing solutions, who made them, with which technologies, and for what purpose.<br>
Then we discussed the use of AI in drones like that. How the data is processed and where it comes from.<br>
We looked up information on the energy consumption of existing drones, and studied two different reports on LCA (Life Cycle Assessment) of UAVs used in farming.<br>
And finally we tried to gather information on the impact of manufacturing such technologies, and what is said by stakeholders on the use of UAVs in this context.<br>

-discussion of the pros and cons: what we found out across the assignments

-short discussions about each assignment (sum up each assignment)

1.

Current drone systems, developed for both research and industry, operate using optical, thermal, or LiDAR sensors, sometimes combined with AI models, to detect diseases and, in some cases, perform targeted spraying. They work by capturing geolocated images or measurements, then preprocessing them to correct acquisition errors before having them analyzed by AI algorithms (CNNs, deep learning, random forests) to produce maps or diagnoses, potentially in real time.

These technologies are used for disease monitoring and crop treatment, with experiments on small plots and industrial applications on large areas.

However, these drones are subject to certain constraints/limitations such as weather conditions, short battery life, the need for frequent calibration, equipment costs, storage constraints, the need for labeled and expensive training data, processing time, and strict adherence to airspace regulations.

2.

Drone-based disease detection systems primarily rely on supervised learning, using classical models (random forests, SVMs) or deep neural networks, such as CNNs, or other architectures like ResNet, EfficientNet, or U-Net. Some approaches combine multiple networks (e.g., LaNet5 + SegNet for vine segmentation) or employ feature selection and optimization techniques (mRMR, ant colony algorithms). When labeled data is lacking, unsupervised methods or reinforcement learning can be used instead.

The resulting data to be analyzed consists of large, geolocated images accompanied by metadata, sometimes amounting to tens of gigabytes per flight. This data is generally private and protected, then stored locally or in the cloud. Before training, the data is preprocessed, labeled, and augmented to produce robust datasets, as in YOLO-Fi, which combines multispectral bands, vegetation indices, and manual annotations to create structured training and validation datasets.

The necessary infrastructure relies on drones equipped with various optical sensors (RGB, multispectral, hyperspectral, thermal, LiDAR) and GPS systems. Data can be processed in real time via onboard modules or analyzed post-flight on local or cloud servers using image and data processing tools such as OpenCV, GDAL, or QGIS, and frameworks like PyTorch or TensorFlow. Some systems, such as those using YOLO-Fi, rely on specific multispectral drones and RTK stations for highly accurate geolocation, as well as powerful computing hardware (e.g., RTX 4090 GPUs) for training.

3.

After combining various resources, we found that the annual consumption of a drone was approximately 0.8 and 0.9 MWh annually, almost all of which is due to physical materials and propulsion and not to the onboard AI system (less than 1%).

...

4.
We had a hard time finding reports from companies. Unfortunately, the one we did find did not have any information on GHG emissions, water usage, or energy consumption during the manufacture, or use of those technologies. The report from DJI Agriculture [5] focuses on the impact of their products on farming. However, they do not discuss the impact of AI, nor the cost of drones over traditional methods.<br>
While we didn’t find any specific figures on the environmental impact of drones in agriculture given by companies, there are some reports that study LCA of such drones.<br>
They rarely give precise numbers, but we understand through a comparison between ground-based techniques and UAVs [8], that drones generally are less power hungry, they are more efficient and help reduce labor.<br>
The stakeholders agree the UAVs are a technology that helps farmers efficiently, reducing labor, waste (of products and water), and mitigating the environmental impact of farming practices, which leads to cost savings.<br>
However, those specialized drones first come with a price, they need specific infrastructure, maintaining, and good connectivity. This is restricting access to those technologies to organisations that can afford it in the first place.<br>
In addition, stakeholders worry about the use of data collected. Images or videos are taken so they are asking for regulations on data privacy and ownership.

-final opinion (optionnal)

---
