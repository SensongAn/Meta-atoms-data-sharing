# Cylinder shaped meta-atoms

The input parameters, simulation environment and results are defined below:  
Please cite to our paper (https://pubs.acs.org/doi/abs/10.1021/acsphotonics.9b00966) if you are using this dataset.

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
    <p align="center">L = gap + radius*2</p>                              

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
    
    ![image](https://github.com/SensongAn/Meta-atoms-data-sharing/blob/master/pics/cylinder.jpg)
    
    
    
&nbsp;
# “H” shaped meta-atoms

The input parameters, simulation environment and results are defined below:  
Please cite to our paper (https://pubs.acs.org/doi/abs/10.1021/acsphotonics.9b00966) if you are using this dataset.

-   **Lattice size:** Each H shaped meta-atom is placed in a square shaped
    lattice. Side lengths of lattices are fixed to be 3 µm.

-   **Thickness:** Thicknesses of the meta-atoms in the z-direction, given in
    µm. The thicknesses range from 0.5 µm to 1 µm in this dataset. Listed in the
    **2nd** column in “parameter” matrix.

-   **Refractive index:** The meta-atoms are constructed with lossless materials
    with refractive indices ranging from 3.5 to 5. The index for each meta-atom
    is listed in the **3rd** column in “parameter” matrix.

-   **Meta-atom dimensions**: Four parameters, Lx, Lx1, Ly, and Ly1 are used to
    sketch an H-shaped meta-atom. These parameters (in current order) are listed
    in the **4th – 7th** columns in “parameter” matrix, respectively.

-   **Substrate:** Each H shaped meta-atom is placed on a 2µm thick lossless
    substrate with a refractive index of 1.4.

-   **Polarization:** Linear-polarized incidence with the polarization direction
    indicated in the figure below.

-   **Frequency:** 30 to 60 THz, with a frequency spacing of 0.1THz. 301
    frequency points in total.

-   **Simulation tool:** All data are derived with the frequency domain solver
    in commercial simulation package CST MICROWAVE STUDIO.

-   **Result:** Real parts and imaginary parts of the transmission spectra of
    each meta-atom are included in the “real” and “imag” matrix, respectively.
    
![image](https://github.com/SensongAn/Meta-atoms-data-sharing/blob/master/pics/H.jpg)



&nbsp;
# Free-form meta-atoms

The input parameters, simulation environment and results are defined below:  
Please cite to our paper (https://arxiv.org/abs/2001.00121) if you are using this dataset.

-   **Lattice size:** Each free-form meta-atom is placed in a square shaped
    lattice. Side length of each lattice ranges from 2.5 µm to 3 µm. Listed in
    the **1st** column in “parameter” matrix.

-   **Thickness:** Thicknesses of the meta-atoms in the z-direction, given in
    µm. The thicknesses range from 0.5 µm to 1 µm in this dataset. Listed in the
    **2nd** column in “parameter” matrix.

-   **Refractive index:** The meta-atoms are constructed with lossless materials
    with refractive indices ranging from 3.5 to 5. The index for each meta-atom
    is listed in the **3rd** column in “parameter” matrix.

-   **Meta-atom patterns**: The 2D cross section of each freeform meta-atom is
    subdivided into a 64 by 64 binary matrix, with “1”s representing dielectric
    and “0”s representing vacuum. All patterns can be found in the “pattern”
    matrix.

-   **Substrate:** Each H shaped meta-atom is placed on a 2µm thick lossless
    substrate with a refractive index of 1.4.

-   **Polarization:** Linear-polarized incidence with the polarization direction
    indicated in the figure below.

-   **Frequency:** 30 to 60 THz, with a frequency spacing of 0.1THz. 301
    frequency points in total.

-   **Simulation tool:** All data are derived with the frequency domain solver
    in commercial simulation package CST MICROWAVE STUDIO.

-   **Result:** Real parts and imaginary parts of the transmission spectra of
    each meta-atom are included in the “real” and “imag” matrix, respectively.

![image](https://github.com/SensongAn/Meta-atoms-data-sharing/blob/master/pics/freeform.jpg)
