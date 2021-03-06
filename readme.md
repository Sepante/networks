# Epyc
This project aims to simulate various kinds of compartmental epidemic models, consisting of but not limited to SIR, SIR-SIR, SIS-SIR and the newly introduced SIS-SID, on various types of static and dynamic networks.
The main simulating engine is written in C++, and the visualizing scripts are written in Python.

<h1 align="center">
	<br>
	<img width="200" src="Model Illustration/SID-SID.png" alt="Bucket">
  <img width="220" src="Model Illustration/SIS-SIR.png" alt="Bucket" style = "margin:10000px" >
  <img width="200" style = "margin:10000px" src="Model Illustration/SIS-SID.png" alt="Bucket">

<br>
<br>

<br>
Three types of coinfective spreading models.
</h1>

### Prerequisites

#### The simulating engine:
```
A C++ compiler
Boost C++ library
```
#### Analysis component:
```
Python3
numpy
scipy
sklearn
matplotlib
pandas
networkx
```
### Installing


```
Enter the Src directory and call the makefile by simply typing "make" in the command line.
```
