# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:





### SIMULATION 
 
 ![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/7811751a-8ab8-4dee-a3d5-d521493aa7d7)

 
 
 
 
 
 ### PLOT 
 LINKS:
 ![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/882d9f93-98ab-438c-823f-ac1b326d8561)

![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/d2e20116-749c-4829-80f4-08ee05973217)

![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/6d8a3501-166b-4251-beb4-c87829537248)

JOINTS:

![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/06cdc35b-c94a-4bd7-b4a9-4a986e5baafd)

![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/b5440487-2745-40d2-b1be-5a47668f39a3)

![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/efd43f54-4196-467e-88c6-41b7e1c45161)

![image](https://github.com/Dhanush12022004/Forward-kinematics-using-robot-analyzer/assets/128135558/cea80cf2-9cc3-458c-b79f-7a4b8f1b9cd1)

 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
