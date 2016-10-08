# my_VINS

This project tries to implement paper:

[Monocular Visual Inertial Odometry on a Mobile Device](https://vision.in.tum.de/_media/spezial/bib/shelley14msc.pdf "Monocular Visual Inertial Odometry on a Mobile Device")


[Consistency of EKF-based Visual-Inertial Odometry](http://www.ee.ucr.edu/~mli/ICRA2012REPORT.pdf "Consistency of EKF-based Visual-Inertial Odometry")

**-2015-4-11-**

I finished whole framework, which is a simplified version of *shelley14msc*. Now I am going to write several ROS package to process image and do simulation.

Gonna folk dvorak0's sensor_processor and data_generator

**-2015-4-15-**

add ROS packages

   1.  msckf_vins. core package, move all MyTriangulation code here, and wrap ROS interface to receive sensor data
   2.  sensor_processor. Read IMU and process image 
   3.  data_generator. a simulated environment that can generate IMU and image 

**-2016-10-08-**

Please use exp branch amber_vins. Last year I initiaited this project in April, then in July Amber joined the project and contribute the amber_vins. This version revised original version.


