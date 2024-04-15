# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Name: Srimathi K
### Roll no: 212221040161
### Dept : CSE

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
DART studio screen shots for linear interpolation and DART studio screen shots for joint interpolation 

![image](https://github.com/madhi43/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/103943383/92d1fc3b-db61-4d05-82c7-6290667bc470)














### Robot movements :




![image](https://github.com/madhi43/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/103943383/6e513472-e306-43b3-bfd6-a9da7f749989)


![image](https://github.com/madhi43/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/103943383/6e513472-e306-43b3-bfd6-a9da7f749989)











### Results:  
    The program for linear and joint interpolation of industrial manipulator is developed  successfully
