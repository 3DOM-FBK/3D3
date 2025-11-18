<p align="center">
  <img src="[pending-image-link]" width="80%">
</p>

<h1 align="center">3D3 Benchmark Dataset</h1>

<p align="center">
  <strong>A multi-sensor multi-resolution dataset to support forest inventory methods</strong>  
  <br>
  <a href="[pending-paper-link]">📄 Paper (Pending)</a> | <a href="[pending-dataset-link]">🌲 Dataset (Pending)</a>
</p>

---

## 🌍 Overview

**3D3** is a large-scale benchmark designed to evaluate high-resolution 3D forestry methods, under a wide range of acquisition conditions and sensing modalities.

It integrates **airborne, helicopter, UAV, mobile, and terrestrial LiDAR** with **hyperspectral** and **RGB** data across diverse European forest types — from **urban** and **Mediterranean** to **boreal** environments.  

Each site provides **ground truth for at least one core task of high-resolution 3D forestry** — *individual tree segmentation (ITS)*, *forest semantic segmentation (FSS)*, or *tree species classification* — ensuring consistent reference data across modalities and acquisition densities.  

---

## 🌲 3D3 Dataset Table 

<div align="center">
  
| **Dataset [(X GB)](http://)** | **A [(X GB)](#dataset-a)** | **B [(X GB)](#dataset-b)** | **C [(X GB)](#dataset-c)** | **D [(X GB)](#dataset-d)** | **E [(X GB)](#dataset-e)** | **F [(X GB)](#dataset-f)** |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| **Instrument** | Riegl VQ780ii<br>Mono-wavelength<br>LiDAR (1064 nm) | Teledyne Optech<br>GALAXY T1000 -<br>Mono-wavelength<br>LiDAR (1064 nm);<br>SPECIM AISAFENIX<br>- Hyperspectral<br>camera (381.35 nm to<br>2502.38 nm);<br>PhaseOne iXU-RS<br>1000 RGB camera | Riegl VUX-120<br>Monowavelength<br>LiDAR (1550<br>nm);<br>PhaseOne<br>iXM100<br>RSM35 RGB<br>camera | HeliALS<br>multispectral<br>LiDAR:<br>VQ-840-G (532<br>nm),<br>miniVUX-1DL<br>(905 nm),<br>VUX-1HA<br>(1550 nm) | DJI-L1 Monowavelength<br>LiDAR (905<br>nm) | Semi-Synthetic |
| **Platform** | Aircraft | Aircraft | Helicopter | Helicopter | UAV, MLS and<br>TLS | Miscellaneous |
| **Approximated<br>density/resolution** | LiDAR: 10 pts/m² | LiDAR: 75 pts/m²<br>Hyperspectral: 60 cm<br>RGB ortho: 10 cm | LiDAR: 375 pts/m² | LiDAR: 1200 pts/m² | LiDAR: 2000 pts/m² | LiDAR: From 0 to 2000<br>pts/m² |
| **Area of Interest** | 1000 m x 12000 m | 1680 m x 1550 m | 2000 m x 2000<br>m | 2000 m x 500 m | 275 m x 150 m | Flexible |
| **Type of data** | LiDAR [(X GB)](http://): X, Y, Z, I | LiDAR [(X GB)](http://): X, Y, Z, I<br>Hyperspectral [(X GB)](http://): 364<br>bands<br>OrthoRGB [(X GB)](http://): R, G, B | LiDAR [(X GB)](http://): X, Y,<br>Z, I | LiDAR [(X GB)](http://): X, Y,<br>Z, SWIR, NIR,<br>Green | LiDAR [(X GB)](http://): X, Y,<br>Z, I, RGB | LiDAR [(X GB)](http://): X, Y,<br>Z, I |
| **Biome** | Urban,<br>Continental | Dense, Continental | Dense, Mediterranean | Dense, Boreal | Dense, Alpine | Variable |
| **Ground Truth** | ITS [(X GB)](http://), species [(X GB)](http://) (203<br>classes) | Species [(X GB)](http://) (5 classes) | ITS [(X GB)](http://) | FSS [(X GB)](http://) (6 classes) | ITS [(X GB)](http://), trunk sizes [(X GB)](http://),<br>tree species [(X GB)](http://) | ITS [(X GB)](http://), FSS [(X GB)](http://),<br>species [(X GB)](http://) |

</div>

---

## Dataset A

<div align="center">

| **LiDAR [(X GB)](#dataset-a-lidar)** | **ITS [(X GB)](#dataset-a-its)** | **Species [(X GB)](#dataset-a-species)** |
|:---:|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset B

<div align="center">

| **LiDAR [(X GB)](#dataset-b-lidar)** | **Hyperspectral [(X GB)](#dataset-b-hyperspectral)** | **OrthoRGB [(X GB)](#dataset-b-orthorgb)** | **Species [(X GB)](#dataset-b-species)** |
|:---:|:---:|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset C

<div align="center">

| **LiDAR [(X GB)](#dataset-c-lidar)** | **ITS [(X GB)](#dataset-c-its)** |
|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset D

<div align="center">

| **LiDAR [(X GB)](#dataset-d-lidar)** | **FSS [(X GB)](#dataset-d-fss)** |
|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset E

<div align="center">

| **LiDAR [(X GB)](#dataset-e-lidar)** | **ITS [(X GB)](#dataset-e-its)** | **Trunk sizes [(X GB)](#dataset-e-trunk)** | **Tree species [(X GB)](#dataset-e-species)** |
|:---:|:---:|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset F

<div align="center">

| **LiDAR [(X GB)](#dataset-f-lidar)** | **ITS [(X GB)](#dataset-f-its)** | **FSS [(X GB)](#dataset-f-fss)** | **Species [(X GB)](#dataset-f-species)** |
|:---:|:---:|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## License

The data provided here is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

<p align="center">
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">
    <img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" alt="CC BY-NC-SA 4.0">
  </a>
</p>
