## Yun Kim's Projects

### 1. VR Solar System on Google Cardboard (Personal Hobby)
  
  ![Figure 1](https://github.com/melongbob/kabam/blob/master/Screenshot_20191115-230033.png?raw=true)

  [The source code is available at](https://github.com/melongbob)
  
  In September 2019, I attended a VR workshop organized by DesignLab. There, I created my first VR project using Unity and Android Studio. I enjoyed the experience so much that I bought Google Cardboard and built my own solar system in VR.
  
  My solar system is not to scale with the real solar system. The purpose of this project is to demonstrate that I am familiar with basic Unity concepts and interfaces. 
  
  This project is still ongoing. Some ideas for improvements are to make the sun more realistic by adding solar flairs, adding moons to planets, and adding rings to Saturn etc.
  
### 2. Forward Kinematics (School Project - CMPT 466 | Animation)
  
  ![Figure 2](https://github.com/melongbob/kabam/blob/master/running_figure.PNG?raw=true)
  
  The source code is available at [ForwardKinematic.cpp](https://github.com/melongbob/CMPT466-Animation/blob/master/CMPT466-985%20Program%20Assignment%201/build/ForwardKinematic.cpp)
  
  A BVH file containing a running stick figure data and coding template was provided by the instructor. When the user runs the completed code, pressing w will make the stick figure run in a circle.
  
  The main objective of the project was to compute rotations of each joints with respect to the rotation of the root node. My job was to implement the following three functions in ForwardKinematics.cpp:
    computeLocalQuaternion(Joint* joint)
      - converts provided Euler angles to quaternions, and calculates local rotations
    computeGlobalQuaternion(Joint* joint, Vector4 localQuat) 
      - calculate current node's global rotation from the local rotation
    computeGlobalPosition(Joint* joint)
      - calculate current node's global position
      
### 3. Inverse Kinematics (School Project - CMPT 466 | Animation)

  ![Figure 3](https://github.com/melongbob/kabam/blob/master/running_figure.PNG?raw=true)
  
  [The source code is available at](https://github.com/melongbob)
  
  A code template including a stick figure in T-pose was provided by the instructor. When the user runs the completed code, the user can move the figure's right arm by pressing number keys from 1~6.
  
  The objective of this project was to implement inverse kinematics using two different methods (Cyclic Coordinate Descent and Jacobian). My task was to implement two different functions in InverseKinematics.cpp:
    CCDMode()
      - implements inverse kinematics using CCD (iteratively calcuating child node's position with respect to the endpoint).
    JacobianMode()
      - implements inverse kinematics using Jacobian method (using a Jacobian matrix, calculates how rotation change in               parent nodes will affect the position of the endpoint).
  
  Projects 2 and 3 show that I can contribute to an existing code, perform calculations necessary for computer graphics, and imiplement the mathematical operations in object-oriented programming language.
