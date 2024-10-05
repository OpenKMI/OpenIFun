<p align="center">
  <img src="https://github.com/user-attachments/assets/19fc637c-b1d7-4f6d-9061-d1525944abc1" width="500" >
</p>
  
## Overview of Blood Input Function
Tracer kinetic modeling is a fundamental technique in dynamic positron emission tomography (PET) that uses mathematical models to extract physiologically significant parameters from the measured data. A blood input function is commonly required to serve as the input to the kinetic model and then used to fit the time activity curve (TAC) of a tissue region of interest or image voxel. However, obtaining a reliable input function is challenging in several contexts and has attracted much effort in the technical field.

## OpenIFun: an OpenKMI data project

**OpenIFun** is an open-data project, launched as a part of the Open Kinetic Modeling Initiative (OpenKMI), aiming to build a database of blood input functions for tracer kinetic modeling in dynamic PET data. It uses total-body PET scanners to collect image-derived input functions (IDIF) from dynamic PET scans of human subjects. The database includes
- **OpenIFun4FDG**: The first phase of this open data project plans to collect the IDIFs of 200 human subject scans performed with a long axial field-of-view PET scanner (e.g. UIH uEXPLORER and Siemens Quadra) at multiple institutions.

## Applications of the OpenIFun Database

The OpenIFun database may have several important technical applications for kinetic modeling and parametric imaging with both short- and long-axial field-of-view PET scanners. Examples include, but are not limited to:

- Develop population-based input function models, for instance, for whole-body Patlak parametric imaging of shortened dynamic scans that do not include an early dynamic scan for deriving the complete blood input function.
- Develop optimization-derived blood input functions for dynamic brain PET imaging with conventional PET scanners.
- Develop deep-learning models and algorithms by providing training pairs of high-quality and low-quality IDIFs and associated other types of data.
