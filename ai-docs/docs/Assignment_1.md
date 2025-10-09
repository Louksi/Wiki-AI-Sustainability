# Assignment 1 (evaluated week 3)

## 1. What commercial and experimental systems currently exist?
**Identify existing solutions, both from industry and research.**

There exists research systems (see WUR review) which are using drones with sensors (spectral, thermal) and Machine learning models (mostly for classification tasks).

In the industry, some commercialized models are using LIDAR systems, combined with spectral sensors, or images captured by the drone during its flight and Vegetation index systems (NDVI), to detect the diseases early.
Some others are doing both disease detection and treatment application, with targeted spraying.

---

## 2. How do these systems work?
**Describe their functioning: technologies used (e.g. sensors, AI models, robotics).**

First, there exist several kinds of drones. The most common ones are quadcopters, hexacopters, or fixed-wings.

The drones carry sensors to acquire data. Those sensors are mainly used to get imaging, like High resolution cameras (RGB, Infrared, or both), multispectral, hyperspectral, or thermal sensors, and even LIDAR sensors.
Other sensors can be used for geolocation (of the drone and of the diseased areas/crops), flight safety (regarding altitude, speed, flight zone).

After getting the data, it needs to be preprocessed, to compensate for bad quality, motion-blur, to correct lighting and calibration, and also to georeference (locate where this data comes from in the field: which area / crop).

Then the data can be used for the different tasks: classification, detection, prediction, and mapping. This uses AI algorithms such as CNNs, deep learning, Random forests (so mainly classification tasks).

This step can be done in real time, or after the drone returns or the data is sent to some facility (the farmer’s or a lab) to analyze the results and decide what to do next.

Now, if the drone is equipped with sprayers (or is linked to ground sprayers), there can be real-time data analysis, followed by targeted spraying after detection.

---

## 3. What types of agricultural operations are they designed for?


These drones, sensors and algorithms are used for disease diagnosis or prevention on crops, and also for targeted treatment. Mainly field crops like watermelon, wheat, cotton or tomato, but also orchards with citrus and olive trees, and vineyards with grapes.

For research, those systems are used on small plots, while the industry deploys them on larger fields.

---

## 4. What are the main functional and technological constraints?
**You may consider latency or processing time, number of interventions required per month, field size limitations, weather or terrain constraints, energy or connectivity needs.**


From a physical point of view, first, the drones have to be calibrated to an area-specific parameter like flight area, lighting, speed, etc. Flying the drone is dependent on the weather conditions, which also might induce calibration changes, and also on the obstacles that might be present in the flight zone, like trees for example.
Those drones have limited flight time due to battery limits, and limited coverage. The farmer must plan when to fly the drones and how to calibrate them so that they are more efficient.
Obviously, to cover more area, you need more drones that you have to pay for, with the maintenance and energy.

There is also a need for storing the data collected by the drones, and the algorithms used.
The algorithms need large training sets, and this training must be overseen by experts. In order to have good results, there is a need for labeled data, the more precise the better, and accounting for artifacts in the images like motion blur or different lighting. But this implies computational cost, and training time.
This data must be preprocessed, then processed to give results, and that might take some time.

Then legally, people must pay attention to airspace (the area you are authorized to fly your drone).
 
