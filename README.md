# Thin-films-Color-simulation

Thin-films-Color-simulation is a Python-based project developed to simulate the **color of multilayer thin films** by considering optical properties such as reflectance, transmittance, attenuation, and interference effects.

## Features
- Calculates the reflectance spectrum in the visible range based on complex refractive indices
- Converts the reflectance data to CIE XYZ color space using color matching functions
- Further converts CIE XYZ to sRGB color space through a transformation matrix and gamma compression
- Supports various multilayer structures, exemplified by SiO₂/Si, SnO₂/SiO₂/Si, and ZnO/SiO₂/Si

## Folder Structure
```
/DATA
  ├── CIE_cc_1931_2deg_cvrl.csv       (Color matching functions)
  ├── D65_step_1.csv                  (White reference)
  ├── Si n k.csv                      (n and k values of Si)
  ├── SiO2 n.csv                      (Refractive index of SiO₂)
  ├── SnO2 n.csv                      (Refractive index of SnO₂)
  ├── SnO2 k.csv                      (Extinction coefficient of SnO₂)
  ├── ZnO n Aguilar.csv               (Refractive index of ZnO)
  ├── ZnO k Aguilar.csv               (Extinction coefficient of ZnO)
```

## Usage
You can run the simulation using the provided Jupyter notebooks (`Thin-films-Color-simulation.ipynb`) or Python scripts.
Examples include structures such as SiO₂/Si, SnO₂/SiO₂/Si, and ZnO/SiO₂/Si.
See the citation section following. 

## Citation

If you find this code useful, please cite:

> Dongik Lee and Seunghun Lee, **Color simulation of Multilayered Thin Films Using Python**, *Advances Sciences* (accepted, the link to be updated) (2025).  
> Preprint on ArXiv: [https://doi.org/10.48550/arXiv.2412.12828](https://doi.org/10.48550/arXiv.2412.12828)

The references in the citation following ample background on its underlying physics and coding—from basic electrodynamics, including the Fresnel equations, to the conversion of reflectance spectrum to RGB values based on a color matching function. 

