## Indoor BIM Visualization
By [Fuad Hasan](https://www.linkedin.com/in/fuadhasanm/)

This repository supplements the following paper: [Integration of Augmented Reality and Building Information Positioning System for Automatic On-Site BIM Visualization](https://arxiv.org/abs/2201.145)

## Overview
In this recent era of booming technology, the growth of Augmented Reality (AR) and Building Information Modelling (BIM) in the construction industry has been enormous and is expected to keep rising rapidly for the foreseeable future ahead. This creates a sufficient need to incorporate the two – using AR to enhance the on-site visualization experience of the BIM in the real world for construction facility management.  Although there are a few mobile AR applications like Unity Reflect in the construction market that solves this need , it usually requires the user to manually adjust the BIM  to overlay reality, which creates limitations in the time it takes and consequently the experience of the user . This paper attempted to solve this problem through utilizing Building Information Positioning System (BIPS)  in order to aid AR in accurate and automatic overlaying of the BIM on top of reality . This was achieved by identifying the assets in the image data of the user’s camera using deep learning and comparing assets  in the BIM to extract accurate pose data of the user . This enabled the AR algorithms to precisely overlay the BIM on top of reality,  the accuracy of which was then tested against ground-truth and existing visual odometry methods. Hence, this paper infers how accurate AR overlaying of BIM can be achieved with the aid of BIPS, which, compared to a manual approach, can make the process less time consuming for the user.  


## Methodology
In this project, we used ARCore's built-in source-code to extract the VIO of the smartphone. The project was implemented extensively in Unity. After extracting the VIO we send it to ROS as a ROSmsg and implement another popular image-based localization approach known as Building Information Positioning System (BIPS). BIPS provides global frame odometry of the camera which is then fused with the odometry of ARcore to superpose reality with BIM model for visual inspection of structural assets. 


## Conclusion
If you face any issues, you are more than welcome to contact me in my email mentioned in the intro. 
