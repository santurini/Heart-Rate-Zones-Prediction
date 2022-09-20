# Heart Rate Zones Prediction
![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

This project allowed us to win the [Hackaton](https://www.kaggle.com/competitions/statistical-learning-sapienza-spring-2022) 2021/2022 reserved for students of the  Statistical Learning course of the MSc in Data Science at the University of Rome, La Sapienza.

## 🏃 Run Baby Run 🏃🏻‍♀️

Heart rate zones, or HR zones, are a way to monitor how hard you’re training.
There are typically 5+1 heart rate zones (Zone-0, Zone-1,…,Zone-5) based on the intensity of training with regard to the individual maximum heart rate.

Heart rate zones are closely linked to your aerobic and anaerobic thresholds. Understanding this can really help when considering heart rate zones exercise, especially your heart rate zones for running or heart rate zone training for other fitness goals.

The following HR zones chart shows the level of intensity as a percentage of Maximum Heart Rate used in each one.

<br />
<p align="center">
  <img src="https://user-images.githubusercontent.com/91251307/185799289-c86661c8-2b67-4a59-a5f4-7f4f3c70f299.png" style="width:800px">
</p>
<br />

## Data Collection
Modern sports watches contain many sensors to monitor _heart rate, cadence, altitude, etc._ The readings are typically saved every once per second.

The data are coming from [FIT files](https://developer.garmin.com/fit/protocol/) collected on many runs during 2021 and 2022. The runs were made in various environments, i.e. hilly and flat. Also, various efforts, e.g. long and slow runs and interval training, are included. The data collection was made using an Apple Watch accompanied by a [Polar OH1](https://www.polar.com/en/products/accessories/polar-verity-sense) sensor.

## Task

The data are relative to 1 minute long running efforts, the task is to predict the associated heart-rate zone being careful to obtain a performing model both on the public and on the private test set.

## Team members
- [Giulio D'Erasmo](https://github.com/giulio-derasmo)
- [Arturo Ghinassi](https://github.com/santurini)
- [Andrea Potì](https://github.com/obster991)
- [Amedeo Ranaldi](https://github.com/Requiem98)
- Camilla Savarese


 <br />
 <br />
 <br />
 <br />
 <br />
 
<p align="center">
    <img src="https://user-images.githubusercontent.com/50860347/147412786-183da6b0-990f-4016-9f2e-0719d8066f5b.png" style="width: 100%"/>
<p>
  

