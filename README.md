# URDFModelica Reference Results
Reference results for standalone simple Modelica URDF robots [urdfmodelica](https://github.com/DLR-RM/urdfmodelica).

## Abstract
The DLR URDFModelica Library is a free open-source library for simulation of robots described as URDF. Given a robot URDF description, a python script translates it to Modelica syntax and automatically builds a package structure to simulate this robot in Modelica. Alternatively a generic robot simulation can be parameterized based on a single Modelica record.

## Reference Results
This repository contains the reference results for the library examples.

Each example, i.e. model with `experiment` annotation, in the library (the main version, not the tutorial version) has a `comparisonSignals.txt` file in the library resources that defines a few variables that are representative for a successful simulation, i.e. position and orientation of the end effector of a manipulator.

The results of these simulations are saved in this repository. Following the same structure than the library, there is one folder for each example in this repository that contains three files that define the reference results.
- `creation.txt` gives some information about how the results were generated, e.g. Modelica version, library version, integration algorithm, start and stop time, ...
- `simulate_passed.log` is a the log file (commonly `dslog.txt`) returned by `dymosim`.
- `ExampleName.csv` contains the values of the variables listed in the corresponding `comparisonSignals.txt` for the example as comma separated values.

The first set of reference resuts was created in September 2025 on a Windows 11 machine with Dymola 2024x.

## Contact
Antoine Pignède [@afxp](https://github.com/afxp)<br>
Carsten Oldemeyer [@CarstenOldemeyer](https://github.com/CarstenOldemeyer)<br>
Deutsches Zentrum f&uuml;r Luft und Raumfahrt e.V. (DLR)<br>
Robotik- und Mechatronikzentrum (RMC)<br>
M&uuml;nchener Stra&szlig;e 20<br>
D-82234 Wessling, Germany<br>
