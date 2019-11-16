## Yun Kim's Projects

### 1. VR Solar System on Google Cardboard (Personal Hobby)
  
  ![Figure 1](https://github.com/melongbob/kabam/blob/master/Screenshot_20191115-230033.png?raw=true)

  The github repository for my [Solar System](https://github.com/melongbob/SolarSystemVR)
  
  In September 2019, I attended a VR workshop organized by DesignLab. There, I created my first VR project using Unity and Android Studio. I enjoyed the experience so much that I bought Google Cardboard and built my own solar system in VR.
  
  My solar system is not to scale with the real solar system. The purpose of this project is to demonstrate that I am familiar with basic Unity concepts and interfaces. 
  
  This project is still ongoing. Some ideas for improvements are to make the sun more realistic by adding solar flairs, adding moons to planets, and adding rings to Saturn etc.
  
### 2. Forward Kinematics (School Project - CMPT 466 | Animation)
  
  ![Figure 2](https://github.com/melongbob/kabam/blob/master/running_figure.PNG?raw=true)
  
  The actual code for [ForwardKinematic.cpp](https://github.com/melongbob/CMPT466-Animation/blob/master/CMPT466-985%20Program%20Assignment%201/build/ForwardKinematic.cpp)
  
  A BVH file containing a running stick figure data and coding template was provided by the instructor. When the user runs the completed code, pressing w will make the stick figure run in a circle.
  
  The main objective of the project was to compute rotations of each joints with respect to the rotation of the root node. My job was to implement the following three functions in ForwardKinematics.cpp:

<ul>
    <li>computeLocalQuaternion(Joint* joint)</li>
      <li>&nbsp;&nbsp;&nbsp;&nbsp; converts provided Euler angles to quaternions, and calculates local rotations</li>
    <li>computeGlobalQuaternion(Joint* joint, Vector4 localQuat)</li>
      <li>&nbsp;&nbsp;&nbsp;&nbsp; calculate current node's global rotation from the local rotation</li>
    <li>computeGlobalPosition(Joint* joint)</li>
      <li>&nbsp;&nbsp;&nbsp;&nbsp; calculate current node's global position</li>
</ul>   

### 3. Inverse Kinematics (School Project - CMPT 466 | Animation)

  ![Figure 3](https://github.com/melongbob/kabam/blob/master/right_arm_move.PNG?raw=true)
  
  (This assignment is still being marked. Source code was not posted here to prevent potential plagirism. Code can be provided upon request)
  
  A code template including a stick figure in T-pose was provided by the instructor. When the user runs the completed code, the user can move the figure's right arm by pressing number keys from 1~6.
  
  The objective of this project was to implement inverse kinematics using two different methods (Cyclic Coordinate Descent and Jacobian). My task was to implement two different functions in InverseKinematics.cpp:

<ul>
  <li>CCDMode()</li>
  <li>&nbsp;&nbsp;&nbsp;&nbsp; implements inverse kinematics using CCD (iteratively calcuating child node's position with respect to the endpoint)</li>
  <li>JacobianMode()</li>
  <li>&nbsp;&nbsp;&nbsp;&nbsp; implements inverse kinematics using Jacobian method (using a Jacobian matrix, calculates how rotation change in parent nodes will affect the position of the endpoint)</li>
</ul>

<br/>
  Projects 2 and 3 show that I can contribute to an existing code, perform calculations necessary for computer graphics, and imiplement the mathematical operations in object-oriented programming language.
