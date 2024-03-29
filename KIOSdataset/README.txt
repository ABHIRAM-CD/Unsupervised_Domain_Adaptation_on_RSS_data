KIOS dataset: The KIOS dataset is a collection of WiFi RSS samples collected with several WiFi-enabled commercial mobile devices. It is ideal for research activities 
in the field of WiFi RSS fingerprint-based positioning.

Author:
Christos Laoudias
Email: laoudias@ucy.ac.cy
http://www2.ucy.ac.cy/~laoudias/index.html

Copyright (c) 2012, KIOS Research Center, University of Cyprus. All rights reserved.

DISCLAIMER
You can use the KIOS dataset in your research group without further permissions. If someone else requests the dataset, you should refer them to us and do not 
distribute the dataset, as we would like to know who is using it. If you have any publications resulting while using this dataset, please cite the following paper: 

C. Laoudias, R. Piche, C. Panayiotou, "Device Self-Calibration in Location Systems using Signal Strength Histograms", Journal of Location Based Services, 7(3), 
pp. 165-181, 2013. (DOI: 10.1080/17489725.2013.816792)

DESCRIPTION
The KIOS dataset contains WiFi RSS data collected during an extensive measurement campaign at KIOS Research Center, Cyprus (http://www.kios.ucy.ac.cy/). This is a 
560m^2 typical office environment that consists of several open cubicle-style and private offices, labs, a conference room and corridors.
There are 9 WiFi APs installed locally that provide full coverage throughout the floor. Moreover, there is a varying number of neighboring WiFi APs that can be sensed 
in different parts of the floor and in some locations more than 60 APs (access points) could be detected.
Five different mobile devices were used for collecting RSS data, namely a HP iPAQ hw6915 PDA with Windows Mobile, an Asus eeePC T101MT laptop running Windows 9, 
an HTC Flyer Android tablet and two other Android smartphones (HTC Desire, Samsung Nexus S).
The data collection for the Android devices was conducted with our Airplace logging and positioning platform available at:

http://www2.ucy.ac.cy/~laoudias/pages/platform.html

CONTENTS
The 'Training data' folder contains the recorded RSS measurements from all available APs, at 105 distinct reference locations by carrying all 5 devices at the same 
time. A total of 2100 training fingerprints, corresponding to 20 fingerprints per reference location, were collected with each device. NaN value indicates that an AP 
is not detected at a particular location. These data can be used to build device-specific radiomaps by calculating the mean value RSS fingerprint that corresponds to 
each reference location.

The 'Test data' folder contains the recorded RSS measurements from all available APs, at 96 distinct test locations by carrying all 5 devices at the same time. A 
total of 960 test fingerprints, corresponding to 10 fingerprints per test location, were collected with each device. NaN value indicates that an AP is not detected 
at a particular location. These data can be used to evaluate WiFi RSS fingerprint-based positioning algorithms and/or device calibration techniques in conjunction 
with the training data.