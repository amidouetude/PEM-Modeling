		PEM Fuel Cell Modeling & Performance Analysis Tools 

This repository contains two Python-based tools developed for the modeling, simulation, and performance analysis of Proton Exchange Membrane Fuel Cells (PEMFCs).
The codes are intended for academic, research, and educational purposes, with a strong focus on electrochemical modeling and parametric studies.

Code 1: Dynamic PEMFC Model with Tkinter Interface

	Description
This notebook implements a dynamic and interactive PEM fuel cell model coupled with a Tkinter graphical user interface (GUI).
It allows users to analyze the influence of electrochemical and operating parameters on the polarization curve and power output in real time.

	Features
* Interactive GUI using Tkinter
* Real-time visualization of:
  o Cell voltage vs current density
  o Power density vs current density

* Adjustable parameters:
  o Operating temperature
  o Relative humidity
  o Exchange current density (i?)
  o Limiting current density (i?)
  o Ohmic resistance / membrane properties

* Electrochemical modeling based on:
  o Butler Volmer kinetics
  o Activation, ohmic, and concentration losses

	Technologies Used
* Python
* NumPy
* Matplotlib
* Tkinter

	Use Cases
* Teaching PEMFC fundamentals
* Sensitivity analysis of operating parameters
* Preliminary fuel cell performance optimization


Code 2: PEMFC Curve Tool   Comparison Curves

	Description
This tool focuses on comparative analysis of PEM fuel cell performance curves under different operating conditions and material configurations.
It is designed to compare multiple scenarios on the same plots, making it ideal for parametric and sensitivity studies.

	Features
* Generation of:
  o Polarization curves
  o Power density curves
* Comparison of multiple cases such as:
  o Different temperatures
  o Different pressures
  o Different Nafion membranes (e.g., 112, 117, 211)
  o Variations in kinetic parameters (?, i?)
* Clean and publication-ready plots

	Technologies Used
* Python
* NumPy
* Matplotlib

	Use Cases
* Academic reports and theses
* Performance benchmarking
* Fuel cell system optimization studies

	Scientific Background
Both tools are based on classical PEM fuel cell modeling approaches including:
* Nernst equation for reversible voltage
* Butler Volmer equation for activation losses
* Ohmic loss modeling via membrane conductivity
* Concentration losses via limiting current density
These models align with standard fuel cell literature and are suitable for steady-state performance evaluation.



	How to Run
1. Install required dependencies:
  pip install numpy matplotlib
2. Open the notebooks using:
  jupyter notebook
3. Run all cells sequentially.
  For the Tkinter-based model, ensure your Python environment supports GUI rendering.

	Author
Amidou MAIGA
MSc Student   Energy and Renewable Energy
Department of Energy Systems Engineering
Erciyes University, Kayseri, T rkiye

	Contact & Full Documentation
If you are interested in:
* The full academic report
* Model extensions
* Collaboration or research discussions

	Please contact me via: 
* www.linkedin.com/in/amidou-maiga-etude or amidou.maiga@2ie-edu.org.

License
This project is shared for educational and research purposes.
Feel free to use and adapt the code with proper citation.

