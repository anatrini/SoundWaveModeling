# SoundWaveModeling
 3D Acoustic Room Modes Analysis: A Jupyter notebook implementing a Finite Element Method (FEM) solver in Mathematica for calculating and visualizing the acoustic modes of a room based on a 3D model. It provides detailed insights into the acoustic properties of the room such as mode frequencies, energies, decay times, and maximum amplitudes.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Mathematica (version 12.0 or later)
- Jupyter notebook

### Installation

1. Clone the repository to your local machine using `git clone`.
2. Navigate to the directory containing the Jupyter notebook.

### Usage

1. Open the Jupyter notebook.
2. Ensure that the path to the STL file of the room model is correctly specified or specify a custom one using your own STL model. 
3. Run the cells in the notebook sequentially.

The notebook will import the room model, generate a FEM mesh, and solve the eigenvalue problem to calculate the room modes. It will also calculate various properties of the modes such as their frequencies, energies, decay times, and maximum amplitudes for a specified range and distance.