# AST 390 Spring 2020 - Final Project
* Stony Brook University
* Final project for course AST 390: Special Topics in Astrophysics
* Spring 2020 topic: Exoplanets
* Numerical Python simulation in Jupyter Notebook
* Using REBOUND Python package by user **hannorein**: https://github.com/hannorein/rebound
* N-body simulation of 100 Kuiper Belt objects

# Purpose
To simulate the effects of a hypothetical "Planet 9" in the Kuiper Belt on Kuiper Belt objects over 10 million years

# Methodology

Planet 9 is simulated with the properties given by Batygin & Brown et. al.
|      Property     |        Value         |
|        ---        |          ---         |
|  Semi-major axis  |     $a = 700$ AU     |
|    Eccentricity   |       $e = 0.6$      |
|       Mass        |    $10\ M_\oplus$    |
|    Inclination    |    $i = 30^\circ$    |
| Perihelion moment | $\omega = 150^\circ$ |

# Background

In 2014, astronomers hypothesized the existence of a possible "Planet 9" in the outer solar system, beyond the orbit of Neptune. This hypothesis was based on their observation of the clustering of the periheria of Kuiper Belt objects with semimajor axes 150 AU - 250 AU. Namely, the perihelia of Kuiper Belt objects tend to cluster around $\omega = 318^\circ$.

In this project I added Planet 9 to REBOUND Jupyter Notebook simulations of the Solar System with and without the outer planets, Kuiper Belt, and Scattered Disc. I investigated whether the presence of Planet 9 has a significant effect on the clustering of Kuiper Belt object perihelia.

# Programming Languages
Python, LaTeX

# Code Results
All Jupyter Notebooks can be found in the **code** folder. Different conditions were simulated, and their results are discussed in the final report.

I used both control simulations (no Planet 9) and experimental simulations (Planet 9) to determine whether Planet 9 had a significant effect on the Solar System.

All programs simulate for 10 million years.
| Title of Notebook | Outer Planets<sup>1</sup> | Kuiper Belt<sup>2</sup> | Scattered Disc<sup>3</sup> | Planet 9<sup>4</sup> | Results |
|        ---        |      ---      |     ---     |      ---       |   ---    | --- |
| `outer-planets-only-control.ipynb` | X |   |   | Absent (control) |     |
| `outer-planets-only-exp.ipynb` | X |   |   | Present (experimental) |     |
| `Kuiper-Belt-only-control.ipynb` |   | X |   | Absent (control) |     |
| `Kuiper-Belt-only-exp.ipynb` |   | X |   | Present (experimental) |     |
| `Scattered Disc-only-control.ipynb` |   |   | X | Absent (control) |     |
| `Scattered Disc-only-exp.ipynb` |   |   | X | Present (experimental) |     |
| `everything-control.ipynb` | X | X | X | Absent (control) |     |
| `everything-exp.ipynb` | X | X | X | Present (experimental) |     |

<sup>1</sup> Jupiter, Saturn, Uranus, Neptune

<sup>2</sup> Includes Eris and Sedna

<sup>3</sup> 

<sup>4</sup> Properties determined from Batygin et. al.

# Final Report
Final report is **ast-390-final-report.pdf**.

# Methodology

For each N-body numerical simulation, I setup the Solar System with the Sun in the center, orbited by the 4 gas giant planets: Jupiter, Saturn, Uranus, Neptune. I added the 3 well-known Kuiper Belt objects 

# Bibliography
REBOUND Python package produced by user **hannorein** <https://github.com/hannorein/rebound>

EVIDENCE FOR A DISTANT GIANT PLANET IN THE SOLAR SYSTEM, Konstantin Batygin & Michael E. Brown <https://arxiv.org/pdf/1601.05438.pdf>

The Planet Nine Hypothesis, Batygin et. al. <https://arxiv.org/pdf/1902.10103.pdf>

Sedna (dwarf planet) <https://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/9/90377_Sedna.htm>

Eris (dwarf planet) <https://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/e/Eris_%2528dwarf_planet%2529.htm>

Kuiper Belt <https://solarsystem.nasa.gov/solar-system/kuiper-belt/in-depth/>

Kuiper Belt Dynamics <http://www.scholarpedia.org/article/Kuiper_belt_dynamics>

The Solar System <https://imagine.gsfc.nasa.gov/features/cosmic/solar_system_info.html>
