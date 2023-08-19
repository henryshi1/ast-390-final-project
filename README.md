# AST 390 Spring 2020 - Final Project
* Stony Brook University
* Final project for course AST 390: Special Topics in Astrophysics
* Spring 2020 topic: Exoplanets
* Numerical Python simulation in Jupyter Notebook
* Using REBOUND Python package by user **hannorein**: https://github.com/hannorein/rebound
* N-body simulation of 100 Kuiper Belt objects

# Purpose
To simulate the effects of a hypothetical "Planet 9" in the Kuiper Belt on Kuiper Belt objects over 10 million years

# Programming Languages
Python, LaTeX

# File Descriptions
All Jupyter Notebooks can be found in the **code** folder. Different conditions were simulated, and their results are discussed in the final report.
| Title of Notebook | Outer Planets<sup>1</sup> | Kuiper Belt<sup>2</sup> | Scattered Disc<sup>3</sup> | Planet 9<sup>4</sup> |
|        ---        |      ---      |     ---     |      ---       |   ---    |
| `outer-planets-only-control.ipynb` | X |   |   | Absent (control) |
| `outer-planets-only-exp.ipynb` | X |   |   | Present (experimental) |
| `Kuiper-Belt-only-control.ipynb` |   | X |   | Absent (control) |
| `Kuiper-Belt-only-exp.ipynb` |   | X |   | Present (experimental) |
| `Scattered Disc-only-control.ipynb` |   |   | X | Absent (control) |
| `Scattered Disc-only-exp.ipynb` |   |   | X | Present (experimental) |
| `everything-control.ipynb` | X | X | X | Absent (control) |
| `everything-exp.ipynb` | X | X | X | Present (experimental) |

<sup>1</sup> Jupiter, Saturn, Uranus, Neptune

<sup>2</sup> Includes Eris and Sedna

<sup>3</sup> 

<sup>4</sup> Properties determined from Batygin et. al.

Final report is **ast-390-final-report.pdf**.

# Bibliography
REBOUND Python package produced by user **hannorein** <https://github.com/hannorein/rebound>

EVIDENCE FOR A DISTANT GIANT PLANET IN THE SOLAR SYSTEM, Konstantin Batygin & Michael E. Brown <https://arxiv.org/pdf/1601.05438.pdf>

The Planet Nine Hypothesis, Batygin et. al. <https://arxiv.org/pdf/1902.10103.pdf>

Sedna (dwarf planet) <https://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/9/90377_Sedna.htm>

Eris (dwarf planet) <https://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/e/Eris_%2528dwarf_planet%2529.htm>

Kuiper Belt <https://solarsystem.nasa.gov/solar-system/kuiper-belt/in-depth/>

Kuiper Belt Dynamics <http://www.scholarpedia.org/article/Kuiper_belt_dynamics>

The Solar System <https://imagine.gsfc.nasa.gov/features/cosmic/solar_system_info.html>
