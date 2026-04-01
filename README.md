# Comparison of CFD Simulations for Closed vs. Open Systems

This repository contains Tecplot layouts for open and closed versions of `axad-p.plt` and `axad-pa.plt` in addition to PNGs of the graphs those layouts represent. Layouts can be found in the `~/layouts` directory and PNGs in the `~/images` directory. The format for each file name is `outlet-v{outlet #}-axad-{p/pa}-{countour variable}.{ext}`. Outlet-v1 represents a closed system and Outlet-v2 represents an open system. Side-by-side comparisons of each layout's PNGs have been listed below in addition to the files' data statistics.

---

# Simulation Design

The simulation has one inlet in the upper right, and has one outlet that differs in size relative to being considered "open" or "closed." Outlet-v1 represents the "closed" system and outlet-v2 represents the "open" system. The closed system has one small outlet at the lower right of the simulation area, and the open system has an outlet spanning the entire right wall (under the inlet area). The IC contours show where walls are found:

## IC Contours
![IC Contours of Axad-p](images/outlet-v1-axad-p-IC.png)

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
| PA_MIN     | -3971                     | -645                    |
| PA_MAX     | 29415                     | 31062                   |
| PA_RANGE   | 33387                     | 31708                   |
| PA_AVG     | 4751                      | 6549                    |
| UMAG_MIN   | 0                         | 0                       |
| UMAG_MAX   | 124                       | 116                     |
| UMAX_RANGE | 124                       | 116                     |
| UMAG_AVG   | 39                        | 36                      |

## PA Contours

<!-- Table formatting generated with assistance from ChatGPT (OpenAI, 2026) -->
| Closed System | Open System |
|--------------|-------------|
| ![Closed Version of Axad-pa](images/outlet-v1-axad-pa-PA.png) <br><br> Closed version of Axad-pa (outlet-v1/axad-pa.plt) with PA contours | ![Open Version of Axad-pa](images/outlet-v2-axad-pa-PA.png) <br><br> Open version of Axad-pa (outlet-v2/axad-pa.plt) with PA contours |

## UMAG Contours

<!-- Table formatting generated with assistance from ChatGPT (OpenAI, 2026) -->
| Closed System | Open System |
|--------------|-------------|
| ![Closed Version of Axad-pa](images/outlet-v1-axad-pa-UMAG.png) <br><br> Closed version of Axad-pa (outlet-v1/axad-pa.plt) with UMAG contours | ![Open Version of Axad-pa](images/outlet-v2-axad-pa-UMAG.png) <br><br> Open version of Axad-pa (outlet-v2/axad-pa.plt) with UMAG contours |

---

# AXAD-O2

**File Description:** Maximum horizontal velocity (MHV) coordinate position and strength over time

[<video src="https://github.com/sawyerbivens/newrite-research/blob/main/animations/axad-o2-maxhvel-compare.mp4" width="320" height="240" controls></video>](https://github.com/user-attachments/assets/b5b25215-349b-46f1-9ffa-efda650681d3)
