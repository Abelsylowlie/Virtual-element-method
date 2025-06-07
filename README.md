![PNS](logo-pns.png)
## MAM5/M2-INUM
# Projet de fin d'étude
# 2024-25

# Virtual-element-method

## Overview
The Virtual Elements Method (VEM) is an innovative numerical approach used to solve engineering and physics problems in fields such as fluid mechanics, solid mechanics, and electromagnetic problems. Developed to overcome the limitations of classical finite element methods, VEM enables the treatment of complex geometries and unstructured meshes without requiring a precise mesh.

### Key Features:
* Geometric Flexibility: VEM is particularly effective for domains with irregular shapes and singularities, making it ideal for industrial applications.

* Use of Virtual Elements: Unlike traditional methods, VEM relies on virtual elements that do not require numerical integration in the real domain but rather in a reference domain, thus simplifying calculations.

* Stability and Precision: The method offers better numerical stability and increased accuracy, especially for large deformation and discontinuity problems.

* Adaptability: VEM easily adapts to different types of problems, including those with complex boundary conditions.
### Significance
This method represents a significant advancement in the field of numerical analysis, providing engineers and researchers with a powerful tool to efficiently model physical systems.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [License](#license)

## Requirements

- Python 3.12.7
- NumPy
- Matplotlib
- Scipy

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/RaphaelGrger/Virtual-element-method.git
```
```bash
cd Virtual-element-method
```

## Usage

To print meshes, execute the following command:

```bash 
python main.py
```

## Functions:
- **`read_meshes.py :`** returns meshes in the good format.
- **`functions.py :`** different functions like boundary, geometry proprieties.
- **`vem.py :`** the vem function, plots and errors.
- **`main.py :`** select a mesh .npz and it returns a solution.
- **`main_convergence.py :`** convergence test of the method.

## Meshes:
Different meshes are given, and we create different meshes.
## License

This project is licensed under the MIT License - see the LICENSE file for details.
