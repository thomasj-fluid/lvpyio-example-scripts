### Introduction
This collection of Jupyter Notebooks presents example cases on how one can use the Python package [lvpyio](https://pypi.org/project/lvpyio/) from [LaVision](https://www.lavision.de/en/) to work with **DaVis** data formats. The goal is to have a growing collection of various examples covering most commonly used data analysis tasks as well as more advanced data processings.

### Used Python modules/packages
- [lvpyio](https://pypi.org/project/lvpyio/)
- [numpy](https://pypi.org/project/numpy/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [csaps](https://pypi.org/project/csaps/)
- and their dependecies...

### Included examples
- **lvpyio_Example_Read_Plot_Uncertainty**:
	- Showcasing the use of the read functionality of the vector interface
	- Showcasing how to access attached scalar values of a vector field
	- Showcasing how to plot the extracted Velocity Uncertainty field
- **lvpyio_Example_Calculate_Velocity_Curvature**:
	- Showcasing the use of the read and write functionality of the particle interface
	- Showcasing how to derive velocity and curvature values from the raw particle positions
	- Showcasing how to attach an additional scalar value to the particles
- **lvpyio_Example_Filter_every_2nd_track**:
	- Showcasing the use of the read and write functionailty of the particle interface
	- Showcasing how to reduce the number of tracks in a set by only considering every 2nd track
- **lvpyio_Example_Write_CSV_from_Particle_Set:**
	- Showcasing the use of the read and write functionailty of the particle interface
	- Showcasing how to derive velocity values from the raw particle positions
	- Showcasing how to export the particle data in a CSV formatted file

### Included data
- PIV Vector Field with additional scalar information
- Particle tracks of simulated cylinder wake flow from Khojasteh et al. (2022)  [10.1016/j.dib.2021.107725](https://doi.org/10.1016/j.dib.2021.107725); [10.15454/GLNRHK](https://doi.org/10.15454/GLNRHK)

### Feedback
Any feedback on the showcased notebooks is appreciated. Just raise an issue containing your suggestions/improvements/recommendations/... . If you want to contribute with additional notebooks, feel free to get in contact.
