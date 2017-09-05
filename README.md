# List of Projects

This repository provides a list of projects to do with DOME and/or using Modelica (preferably both); primarily to leave as end-of-course project/exam.

Several types of projects are listed:
- Introductory projects are suitable for BSc students,
- Intermediate projects are suitable for BSc students with good computing skills and graduate students
- Advanced projects are suitable for Graduate students and may also be suitable for full MSc projects.

This list is coordinated between Federico Milano at UCD Dublin and Luigi Vanfretti at RPI (USA).

# Project Topics

## Introductory
### Modeling and Simulation of the "Electromagnet" Example
From: Luigi Vanfretti

To implement the Electromagnet model using the Modelica language, and utilizing the different time-scale representations as shown in Chapter 1 of Federico's book.

## Intermediate Projects
### Model Calibration for the MOSTAR power plant
The MOSTAR power plant is located in Bosnia/Herzegovia.


## Advanced Projects

### State Matrix Conditioning to improve the Robustness of Power System Small-signal Stability Analysis
From: Federico Milano

Small-signal stability analysis is a fundamental tool for power system operators. It consists in computing the eigenvalues of the state matrix of a power system at a given operating point. The values of such eigenvalues determine whether the system is stable or unstable in a neighbourhood of the operating point.
The reliability of small-signal stability analysis results highly depends on the ability to  accurately define power system models and on the robustness of numerical methods to compute the eigenvalues. Several practical and numerical issues, in fact, may lead to inconsistent results. These issues can be caused by system parameter uncertainty, measurement errors, topological changes, ill-conditioned Jacobian matrices, etc.  
The project consists in exploring and implementing numerical strategies based on matrix conditioning to increase the robustness of the small-signal stability analysis.
The student will develop skills in power system modelling and numerical methods for small-signal stability analysis.

ME additional task consists in proposing solutions to improve the numerical robustness of existing approaches.

### Modelling and Control of Marine Current Turbine Systems
From: Federico Milano

In recent years, various turbine technologies have been developed to capture kinetic energy from marine and tidal currents. It is not surprising that some similar principles in wind generation systems can be applied in marine current turbine (MCT) systems due to the fact that both of them aim to capture energy from one kind of flowing mass. This similarity helps the marine current generation system to develop faster and become more mature than other marine renewable energy systems. However, the turbine blade design, the system dimensions, and power profiles have their special characteristics for MCT. The main advantage of marine current energy is its high predictability: marine currents are mostly driven by the tide and the astronomic nature of tides makes marine tidal current highly predictable with 98% accuracy for decades. Marine tidal current speed can be disturbed by swell phenomenon and the induced variations in current flow speed will cause large power fluctuations in MCT extracted power.

The project aims at defining the state of art of MCTs, implementing suitable models of MCTs as well as of the swell phenomenon.

The student will develop skills in power system modelling, control and stability analysis.

ME additional task consists in studying the impact of the penetration of MCT on the dynamic response of electric power systems.

### Identification of Synchronous Machine Parameters
From: Federico Milano

This project consists in defining numerical techniques to identify the parameters of the dynamic model of a synchronous machine based on measures taken at the point of connection with the grid.

The project consists in three phases, as follows.
•	Learn the dynamic model at generator bus using measurements (generated synthetically through simulations) and regression techniques (e.g. grey-box approach). The model has to be adequate for transient stability analysis and should retain relevant non-linear features of the real-world machine.
•	Propose and learn reduced generator (and, possibly, exciter) models that can be reused for grid analysis.
•	ME additional task consists in designing an “active learning” test able to reconstruct proper reduced dynamic model with minimal input perturbation.

The student will develop skills in power system modelling, regression techniques and model identification.

### Dynamic Modelling of Distance Protections
From: Federico Milano

This project consists in defining and testing a hybrid dynamic model of distance protections for high-voltage transmission systems. The model will take into account  CTs and VTs, relays and breakers and properly define different relays logics. Then the dynamic response of the proposed dynamic model will be compared using a simple test system with standard simplified and static models.

The student will develop skills in power system protections, modelling and transient stability analysis.

ME additional task consists in including noise and uncertainty in the simulated measured quantities, evaluate their effect on the dynamic response of the power system and propose remedial actions to reduce such impact.

### Design of a frequency controlled load on a microcomputer
From: Federico Milano

In recent years, demand response and, in particular, load frequency control have become a very active area of research. There are both economic and technical challenges to be solved. In this project, the focus is on modelling and control aspects.
The project consists in designing a simple thermal load dynamic model with a frequency controller on a microcomputer (e.g., Arduino, Raspberry PI or Teensy) and connecting it to a software tool that simulates the dynamics of the  remainder of the power system. Such a tool can be based on Matlab/Simulink or any other software package chosen by the student. The main goals of the project are to understand the concepts of hybrid systems, co-simulation and real-time simulation.
The student will develop skills in power system control, numerical methods for time domain integration, co-simulation and microcomputer programming.
