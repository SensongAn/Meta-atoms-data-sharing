# Cylinder shaped meta-atoms

The input parameters, simulation environment and results are defined below:

-   **Permittivity:** The meta-atoms are constructed with lossless materials
    with permittivities ranging from 12 to 25. The permittivity for each
    meta-atom is listed in the **1st** column in “parameter” matrix.

-   **Gap:** The minimum gap between two adjacent cylinders, given in µm. The
    gaps range from 0.1 µm to 1.55 µm in this dataset. Listed in the **2nd**
    column in “parameter” matrix.

-   **Thickness:** Thicknesses of the cylinders in the z-direction, given in µm.
    The thicknesses range from 0.5 µm to 1.55 µm in this dataset. Listed in the
    **3rd** column in “parameter” matrix.

-   **Radius:** Radii of the cylinders, given in µm. The radii range from 0.1 µm
    to 1.05 µm in this dataset. Listed in the **4th** column in “parameter”
    matrix.

-   **Lattice size:** Each cylinder shaped meta-atom is placed in a square
    shaped lattice. Side lengths of lattices can be derived with:

$$L = gap + radius*2$$

-   **Substrate:** Each cylinder shaped meta-atom is placed on a 2µm thick
    lossless substrate with a refractive index of 1.4.

-   **Polarization:** Linear-polarized incidence with the polarization direction
    indicated in the figure below.

-   **Frequency:** 30 to 60 THz, with a frequency spacing of 0.1THz. 301
    frequency points in total.

-   **Simulation tool:** All data are derived with the frequency domain solver
    in commercial simulation package CST MICROWAVE STUDIO.

-   **Result:** Real parts and imaginary parts of the transmission spectra of
    each meta-atom are included in the “real” and “imag” matrix, respectively.
    
    ![image](https://github.com/garfieldass/Meta-atoms-data-sharing/blob/master/pics/cylinder.jpg)
