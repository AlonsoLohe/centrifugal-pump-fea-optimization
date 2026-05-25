# \# Centrifugal Pump Optimization via FEA \& CFD

# 

# Hydraulic performance optimization of a centrifugal oil pump using SolidWorks Flow Simulation 2025. By modifying the impeller geometry, a \*\*12.5% increase in volumetric flow rate\*\* was achieved (exceeding the 10% target) while maintaining the original operating conditions and structural integrity.

# 

# \---

# 

# \## Results Summary

# 

# | Parameter | Original | Modified | Change |

# |---|---|---|---|

# | Impeller blades | 7 | 8 | +1 blade |

# | Volumetric flow rate | 0.0104 m³/s | 0.0117 m³/s | \*\*+12.5%\*\* |

# | Inlet velocity | \~6.28 m/s | \~7.22 m/s | +15% |

# | Max blade velocity | \~11.32 m/s | \~11.35 m/s | stable |

# | Outlet velocity | \~8.80 m/s | 8.25–9.29 m/s | increased |

# | Internal pressure | \~2103 kPa | \~130,251 Pa | significantly reduced |

# | Cavitation indicators | Present | Reduced | improved |

# 

# \---

# 

# \## Simulation Setup

# 

# \*\*Software:\*\* SolidWorks Flow Simulation 2025  

# \*\*Study type:\*\* Steady-state internal laminar flow (incompressible, isothermal)  

# \*\*Fluid:\*\* Olive oil — density 917.53 kg/m³, dynamic viscosity 0.081 Pa·s  

# \*\*Operating temperature:\*\* 293.2 K (20 °C)  

# \*\*Impeller speed:\*\* 1200 rpm (clockwise rotating region)

# 

# \### Boundary Conditions

# 

# | Boundary | Value |

# |---|---|

# | Inlet static pressure | 200,000 Pa |

# | Outlet (ambient) pressure | 101,325 Pa |

# | Pressure differential | 98,675 Pa |

# 

# \### Mesh

# 

# 3D Cartesian mesh with automatic refinement near impeller blades and outlet.

# 

# | | Original | Modified |

# |---|---|---|

# | Fluid cells | 149,015 | 149,091 |

# | Partial cells | 60,332 | 61,017 |

# | Base grid | 26×38×30 divisions | 26×38×30 divisions |

# 

# \---

# 

# \## Geometry Modification

# 

# The original impeller had \*\*7 blades\*\* arranged in a circular pattern. Analysis of the baseline flow revealed recirculation losses and cavitation indicators at the blade tips, suggesting that increasing blade count could improve flow stability and reduce mixing losses at the inlet.

# 

# The modification increased the blade count from \*\*7 to 8\*\* using the Circular Pattern feature in SolidWorks, maintaining equal angular spacing between blades. All other geometry, boundary conditions, and operating parameters remained identical to the baseline.

# 

# \*\*Why this works:\*\* Additional blades provide the fluid with more guided surface area, reducing recirculation, improving energy transfer per unit volume, and lowering the internal pressure peaks that cause cavitation.

# 

# \---

# 

# \## Flow Simulation Images

# 

# | Original model | Modified model |

# |---|---|

# | !\[](images/flow-simulation-1.jpg) | !\[](images/flow-simulation-2.jpg) |

# 

# !\[](images/flow-simulation-3.jpg)

# 

# \---

# 

# \## Files

# 

# ```

# centrifugal-pump-fea-optimization/

# ├── pump-fea-simulation.zip     # SolidWorks part + Flow Simulation study

# ├── docs/

# │   └── PUMP\_OPTIMIZATION\_FEA.pdf   # Full analysis report

# ├── images/

# │   ├── flow-simulation-1.jpg

# │   ├── flow-simulation-2.jpg

# │   └── flow-simulation-3.jpg

# └── README.md

# ```

# 

# \### Requirements to open the simulation

# 

# \- SolidWorks 2025 with Flow Simulation add-in

# \- Unzip `pump-fea-simulation.zip` — keep the folder structure intact before opening

# 

# \---

# 

# \## Key Findings

# 

# \- Adding a single blade to the impeller exceeded the 10% flow rate target, achieving \*\*12.5% improvement\*\*

# \- The modified design showed \*\*significantly reduced internal pressure peaks\*\*, indicating less cavitation — an important secondary benefit not initially targeted

# \- The symmetric, well-converged flow trajectories in the modified model confirm that the additional blade does not disrupt the flow pattern

# 

# \---

# 

# \## Author

# 

# \*\*Alonso Lopez Hernandez\*\* — Mechatronics Engineer  

# \[LinkedIn](https://www.linkedin.com/in/alonso-lópez-hernández-10335716a) · \[GitHub](https://github.com/AlonsoLohe)

