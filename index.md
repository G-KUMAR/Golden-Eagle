## Welcome to Project Golden-Eagle

The Aim of this project is to develop a Drone system from scratch with the
capability of fully autonomous exploration in indoor scenarios and autonomous
object localization with retrieval . The constraint is to develop an economical
robust system with minimum sensor suite but complete autonomy . The gripping
capability of the Drone should not be limited to a particular shape and material
of the object while the design should also avoid a significant change in dynamics
of the system while operating.
 
### The System

![](https://ibb.co/jsarXz)

### The Hardware Pipeline

![](https://github.com/G-KUMAR/Golden-Eagle.io/blob/master/system.png)

### Videos
# [Manual Pick&Place](https://www.youtube.com/watch?v=YuA12b6oyLw).
# [Autonomous Pick&Place(Tag based object tracking)](https://www.youtube.com/watch?v=WOCUoD3dMKc).
# [Realtime Onboard Reconstruction and Trajectory Planning](https://www.youtube.com/watch?v=w2a-wZNqYQI).
# [Complete Onboard Exploration in Indoor Environment](https://www.youtube.com/watch?v=pKTTRCladBQ).


### Methodology
Camera and IMU(Inertial Measurement Unit) readings are fused for an accurate state estimation which is the most crucial aspect while navigating in unknown cluttered
environment. To have an efficient understanding of the environment, a monocular camera based dense reconstruction is used which is light weight in terms of the required
processing power and is suitable to be used on-board. A simultaneous object detection algorithm makes the search possible while exploring the environment. A downward facing
camera along with a height sensor makes accurate landing of the drone over the target object smoother. Combining the state-of-the-art techniques of State Estimation, Dense
Mapping, Object Detection, Trajectory Planning and Object Grasping resulted in a system which has been successfully tested in real world conditions.

### Summary
This is a system integration design of an aerial robot which is low cost, light weighpower efficient, fully on-board, autonomous and has a versatile gripping capability. Ousystem is capable of running end to end pipeline from state estimation to dense indoor mapping, planning, object detection, picking and navigation in a cluttered indoor environment on a single on-board CPU efficiently. We also propose a simple but efficientechnique to predict the position of visible objects in global frame. A gripper feedback based failure recovery method makes the entire system robust towards unsuccessful gripping and mid air payload drop. Our system is capable of searching, accurately localizing and picking up objects of varying shape with unknown location.



Note: As The Project is still in progress further details cannot be disclosed publicly.


### People
The Project is still in progress and is being done by [Gourav Kumar](https://gourav.kumar@research.iiit.ac.in), [Pravin Mali](https://pravin.mali@research.iiit.ac.in), [Animesh Sahu](https://pravin.mali@research.iiit.ac.in) under [Prof. K. Madhava Krishna](https://faculty.iiit.ac.in/~mkrishna/) at [Robotics Research Center](http://robotics.iiit.ac.in/), [IIIT Hyderabad, India](https://www.iiit.ac.in/). The Invaluable contribution of [Ashwin K.](https://ashwinvk94@gmail.com ) and [Gajendra Nagar](https://gajena@iitk.ac.in) is thankfully acknowledged.
