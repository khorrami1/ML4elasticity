# ML4elasticity

For dataset generation: generate_dataset.ipynb
  * using Voronoi tesselation to randomly create microstructures with different grain microstructures in DAMASK.
  * running DAMASK to analyse mechanical quantities, here stress components
  * saving data for the machine learning surrogate modeling

For downloading dataset in numpy (Python) format:

* 1- dataset for Young's modulus E (units: GPa): https://sync.academiccloud.de/remote.php/webdav/ML_elasticity/E.npy
* 2- dataset for Poisson's ratio v (unitless): https://sync.academiccloud.de/remote.php/webdav/ML_elasticity/v.npy
* 3- dataset for stress component P22 (units: Pa): https://sync.academiccloud.de/remote.php/webdav/ML_elasticity/P22.npy
* 4- dataset for stress component P23 (units: Pa): https://sync.academiccloud.de/remote.php/webdav/ML_elasticity/P23.npy
* 5- dataset for stress component P32 (units: Pa): https://sync.academiccloud.de/remote.php/webdav/ML_elasticity/P32.npy
* 6- dataset for stress component P33 (units: Pa): https://sync.academiccloud.de/remote.php/webdav/ML_elasticity/P33.npy

For loading dataset, making Fourier Neural Operator (FNO), training, and testing the trained network: main_training.ipynb

