# AV_Team_18_miniProject_
## Description:
<align>Hello, This repo is all about the project on "<strong> Object detection and Tracking </strong> " in the domain of "<strong>Autonomous Vehicles</strong>".</align>

### Introduction:
<p>We are living in the era of advanced machines where they are capable of taking decisions on their own and predict the outcomes or the results. Machines may be static or dynamic. One of the major improvements can be seen in the field of <strong>Autonomous Vehicles</strong>, whose demand has been growing day by day. Therefore, for the better performance of the Autonomous Vehicles the safety of the driver and the passenger is very important. Even though self-driving cars are already in the market, many efforts are being put by the researchers in order to assure the maximum safety of the passengers. Machine learning being an important key aspect of the autonomous vehicles supports with different models or algorithms that helps the system to determine the environment in its surroundings so that the system can take proper action with respect to the situation. Vehicle or the object detection and tracking is very helpful in various aspects such as security purposes, traffic controlling and many more.</p>

### Constraints:
<ol>
<li>Input is captured video.</li>
<li>On clear day light weather conditions.</li>
<li>On structured road.</li>
<li>On fore vehicles.</li>
</ol>

### Methodology:
<p>Here, as said earlier that the object of concern here in this context is the vehicles. Therefore inorder to detect the object the model that is being used in this project is YOLOv7. As it is a pre-trained model there is no need of training the model once again. For the tracking of the object, center point method is being used. Since for each detected object the bounding box appears and then by making use of the coordinates of the centre point of the bounding boxes for each detected object the coordinates of the centre points are stored in an array. After certain number of frames the difference between the present and the previous n^th centre point is calculated. Then if the difference comes out to be positive then the vehicle takes right turn else it takes left turn.</p>

