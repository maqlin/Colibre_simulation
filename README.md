# Colibre_simulation
# Figure Annotations and Definitions

To ensure clarity regarding the various definitions used in this analysis, the following annotations describe the criteria and content for each figure and panel.

---

## 1. Core Definitions

### **Young Stars**
Defined as stars with a formation age of no more than **100 Myr**.

### **In-situ Stars**
There are two distinct definitions used in this study:
* **Type I**: Stars whose progenitor gas particles were **bound** to the system at the time of formation.
* **Type II**: Stars whose progenitor gas particles were bound to the system **and** located at a distance $r < 2R_{50}$.

### **Morphological Classification**
Morphological analysis is conducted exclusively for **Type II** stars. The classification is based on the circularity parameter $j_z/j_c$:
* **Bulge**: Particles with $j_z/j_c < 0$ are assigned to the bulge. To maintain a symmetric spheroidal component, an equivalent number of particles with $j_z/j_c > 0$ are randomly assigned to the bulge as well.
* **Thin Disk**: Defined by particles with $j_z/j_c > 0.7$.
* **Thick Disk**: Includes the remaining stars after the bulge and thin disk components are removed.
* **Extended Stars**: Defined as stars that meet the **Type I** criteria but are **not** classified as **Type II**.

---

## 2. Image Panels (Uppercase Labels)

The uppercase subscripts denote spatial distribution images. The numeric suffixes indicate the viewing angle:
* **1**: Face-on view
* **2**: Edge-on view

| Panel | Description |
| :--- | :--- |
| **A** | Bound stars |
| **B** | Type I stars |
| **C** | Bulge stars |
| **D** | Thick disk stars |
| **E** | Thin disk stars |

---

## 3. Evolution & Analysis Panels (Lowercase Labels)

* **Panel a**: Evolution history of **virial halo mass**, **gas mass** (within $R_{vir}$), **stellar mass** (within 50 kpc), and **black hole mass** (within $R_{vir}$).
* **Panel b**: 
    * **Cold-gas content**: ($T < 2 \times 10^4$ K) within $R_{90,*}$, normalized by the total mass within the virial radius.
    * **Cold-gas spin**: Defined as $\lambda_{gas} = j_{gas}(<R_{90,*}) / (\sqrt{2} R_{vir} V_{vir})$.
* **Panel c**: The **angular momentum-energy phase space** of Type I young bound stars.
* **Panel d**: The **Star Formation Rate (SFR)** for the total system, bulge, thick disk, thin disk, and extended stars.
* **Panel e**: Mass fractions of the **bulge, thick disk, and thin disk** (excluding extended stars).
* **Panel f**: Size evolution of the **halo** ($R_{vir}$), **galaxy**, and **bulge** ($R_{50}$).
* **Panel g**: The **radial distribution** of young stars (bulge, thick disk, thin disk, and extended), normalized by the virial radius ($R_{vir}$).
* **Panel h**: Distributions of the **current** $j_z/j_c$ and the $j_z/j_c$ **at the time of formation** for Type II stars. This panel distinguishes whether stars at a specific redshift were "**born hot/cold**" or if they kinematically evolved over time.
