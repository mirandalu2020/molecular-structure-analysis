# Calculating Energy Levels for a Complex Organic Molecule using RDKit
This repository provides a Python implementation for calculating energy levels of a complex organic molecule using RDKit. The goal is to utilize the RDKit library to perform molecular modeling and generate insights into the electronic structure and energy levels of the molecule.

## Table of Contents
- Introduction
- Requirements
- Usage

## Introduction
RDKit is an open-source cheminformatics library that provides a wide range of tools and algorithms for molecular modeling and analysis. It allows for the construction, manipulation, and visualization of chemical structures, as well as the calculation of various molecular properties.

Psi4 is an open-source quantum chemistry software package that offers various methods for performing quantum chemical calculations, including Hartree-Fock, density functional theory (DFT), and post-HF methods. It provides accurate calculations of molecular properties, including energy levels.

By combining the functionalities of RDKit and Psi4, it is possible to load a complex organic molecule, perform quantum chemical calculations, and estimate energy levels using the desired method.

Calculating energy levels of a complex organic molecule is essential for understanding its electronic structure, stability, and reactivity. With RDKit, it is possible to perform quantum chemical calculations and estimate energy levels using methods such as molecular mechanics or quantum mechanical calculations based on semi-empirical, density functional theory (DFT), or other methods. 

This repository provides a Python script that utilizes RDKit to load a complex organic molecule, perform energy level calculations, and retrieve relevant energy properties. It serves as a starting point for further exploration and analysis of the molecule's electronic structure. NGView was used as a visualization tool. The example moledule used in this project was Benzocaine. 

Requirements
To use the energy level calculation script, you need to have the following installed:

Python 3.x
Psi4
RDKit
NGLView

## Usage
Clone this repository to your local machine or download the ZIP file.

Open a terminal or command prompt and navigate to the repository directory.

Prepare your complex organic molecule in a suitable format, such as a SMILES string or a structure file (e.g., SDF, PDB). Ensure that you have the necessary information to perform the desired energy level calculations.

Modify the main.py file to specify the file path or molecular information of your complex organic molecule.

Import and utilize the appropriate RDKit functions to load the molecule and prepare it for the Psi4 calculation. Use the Psi4 library to set up the desired quantum chemical calculation method and retrieve the energy levels or properties of interest. Refer to the RDKit and Psi4 documentation, as well as relevant literature, for guidance on the specific calculations you wish to perform.

## Credits

This project was done as a class project at UCDavis CHE155, with help from Lee-ping Wang, PhD.
