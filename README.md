# The Shape and Size of Ion Clouds in a Cylindrical Penning Trap

## Getting Started

The code was developed in **Python 3** using **Jupyter Notebooks**.

### Running the Notebook

**Option 1: Local Jupyter Environment**
1. Download the notebook file.
2. Open in Jupyter.
3. Run cells in order.

**Option 2: [Google Colab](https://colab.research.google.com/)**
1. Upload notebook file to Google Drive.
2. Right click and open with Colab.
3. Run in browser.

## Limitations and extensions
* This program assumes a five-electrode open-endcap cylindrical Penning trap with a minium inner radius of 0.4 cm. However, modifications are farily simple if the user knows the value of their C<sub>2</sub> quadrupole term expansion coefficient and knows that higher order expansion coefficients are negligable. No actual physical dimensions are then required, but the user must select a spatial grid in which to solve for the potential.

### User Inputs
* N<sub>ions</sub>: The number of ions you want to store in the trap. Must be a positive integer.
* ion<sub>mass</sub>: The mass of a single ion in atomic mass units (amu). Must be a positive number.
* ion<sub>charge</sub>: The charge state of the ion (e.g., 1 for singly charged, 2 for doubly charged). Must be a positive integer.
* rho<sub>0</sub>: The inner radius of the trap in meters. Must be within the range 0.004 to 0.10 meters.
* z<sub>gap</sub>: The size of the gap between adjacent electrodes. Must be between 0 and 5×10⁻⁴ meters.
* U<sub>0</sub>: The applied electric potential in volts. Must be a positive value.
* B<sub>0</sub>: The magnetic field strength in tesla. Must be a positive value.
* T: Resistive cooling temperature. We assume all ions are always in thermal equilibrium with a heat bath with temperature T. Must be between 1 and 10.

Date of last edit: April 1, 2026
