# Comparison of CFD Simulations for Closed vs. Open Systems

This repository contains Tecplot layouts for open and closed versions of `axad-p.plt` and `axad-pa.plt` in addition to PNGs of the graphs those layouts represent. Layouts can be found in the `~/layouts` directory and PNGs in the `~/images` directory. The format for each file name is `outlet-v{outlet #}-axad-{p/pa}-{countour variable}.{ext}`. Outlet-v1 represents a closed system and Outlet-v2 represents an open system. Side-by-side comparisons of each layout's PNGs have been listed below in addition to the files' data statistics.

---

# AXAD-P

**File Description:** Final time U,V,P,VT,UMAG,IC

## Data Statistics Table

<!-- Table formatting generated with assistance from ChatGPT (OpenAI, 2026) -->
| Metric      | Closed System (outlet-v1) | Open System (outlet-v2) |
|------------|:-------------------------:|:-----------------------:|
| P_MIN      | -6066                     | -1652                   |
| P_MAX      | 28266                     | 32945                   |
| P_RANGE    | 29918                     | 28531                   |
| P_AVG      | 4375                      | 8063                     |
| UMAG_MIN   | 0                         | 0                       |
| UMAG_MAX   | 204                       | 166                     |
| UMAG_RANGE | 204                       | 166                     |
| UMAG_AVG   | 42.36                     | 39.83                   |



## Pressure Contours

<!-- Table formatting generated with assistance from ChatGPT (OpenAI, 2026) -->
| Closed System | Open System |
|--------------|-------------|
| ![Closed Version of Axad-p](images/outlet-v1-axad-p-P.png) <br><br> Closed version of Axad-p (outlet-v1/axad-p.plt) with pressure contours | ![Open Version of Axad-p](images/outlet-v2-axad-p-P.png) <br><br> Open version of Axad-p (outlet-v2/axad-p.plt) with pressure contours |

## UMAG Contours

<!-- Table formatting generated with assistance from ChatGPT (OpenAI, 2026) -->
| Closed System | Open System |
|--------------|-------------|
| ![Closed Version of Axad-p](images/outlet-v1-axad-p-UMAG.png) <br><br> Closed version of Axad-p (outlet-v1/axad-p.plt) with UMAG contours | ![Open Version of Axad-p](images/outlet-v2-axad-p-UMAG.png) <br><br> Open version of Axad-p (outlet-v2/axad-p.plt) with pressure UMAG |

---

# AXAD-PA

**File Description:** UA,VA,PA,UMAG Averaged values from 20s to 50s?

## Data Statistics Table

<!-- Table formatting generated with assistance from ChatGPT (OpenAI, 2026) -->
| Metric      | Closed System (outlet-v1) | Open System (outlet-v2) |
|------------|:-------------------------:|:-----------------------:|
| UMAG_MIN   | 0                         | 0                       |
| UMAG_MAX   | 124                       | 116                     |
| UMAX_RANGE | 124                       | 116                     |
| UMAG_AVG   | 39                        | 36                      |

## UMAG Contours


<!-- Table formatting generated with assistance from ChatGPT (OpenAI, 2026) -->
| Closed System | Open System |
|--------------|-------------|
| ![Closed Version of Axad-p](images/outlet-v1-axad-pa-UMAG.png) <br><br> Closed version of Axad-pa (outlet-v1/axad-pa.plt) with UMAG contours | ![Open Version of Axad-p](images/outlet-v2-axad-pa-UMAG.png) <br><br> Open version of Axad-pa (outlet-v2/axad-pa.plt) with UMAG contours |

# To-Do
- [ ] *requires Tecplot access:* Layouts and images for `axad-p.plt` should be completed using `IC` (Indicator Cell) as countours (by Sawyer).
- [x] *requires Tecplot access:* Layouts and images for `axad-p.plt` should be completed using `P` (Pressure) as contours (by Sawyer).
- [x] *requires Tecplot access:* Layouts and images for `axad-p.plt` should be completed using `UMAG` (Velocity Magnitude) as contours (by Sawyer).
- [ ] *requires Tecplot access:* Layouts and images for `axad-pa.plt` should be completed using `PA` (Pressure Averaged) as contours (by Sawyer).
- [x] *requires Tecplot access:* Layouts and images for `axad-pa.plt` should be completed using `UMAG` (Velocity Magnitude) as contours (by Sawyer).
- [x] *requires Tecplot access:* Data for the minimum, maximum, range, and mean `P` should be included in the Data Statistics Table for `axad-p.plt` (by Sawyer).
- [x] *requires Tecplot access:* Data for the minimum, maximum, range, and mean `UMAG` should be included in the Data Statistics Table for `axad-p.plt` (by Sawyer).
- [ ] *requires Tecplot access:* Data for the minimum, maximum, range, and mean `PA` should be included in the Data Statistics Table for `axad-pa.plt` (by Sawyer).
- [x] *requires Tecplot access:* Data for the minimum, maximum, range, and mean `UMAG` should be included in the Data Statistics Table for `axad-pa.plt` (by Sawyer).
- [ ] *requires Tecplot access:* Layouts and images for `axad-o.plt` and `axad-o2.plt` should be completed (by Daniel).
- [x] Create "P Contours" section with images under AXAD-P section.
- [x] Create "UMAG Contours" section with images under AXAD-P section.
- [ ] Create "PA Contours" section with images under AXAD-PA section.
- [x] Create "UMAG Contours" section with images under AXAD-PA section.
- [ ] Get feedback from Dr. Selvam, and make iterations to layouts and visualizations if neccessary.
- [ ] Begin work on comparisons and drawing conclusions.
