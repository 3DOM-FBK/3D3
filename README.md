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
  
| **Dataset (X GB)** | **[A](#dataset-a)** | **[B](#dataset-b)** | **[C](#dataset-c)** | **[D](#dataset-d)** | **[E](#dataset-e)** | **[F](#dataset-f)** |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| **Instrument** | Riegl VQ780ii<br>Mono-wavelength<br>LiDAR (1064 nm) | Teledyne Optech<br>GALAXY T1000 -<br>Mono-wavelength<br>LiDAR (1064 nm);<br>SPECIM AISAFENIX<br>- Hyperspectral<br>camera (381.35 nm to<br>2502.38 nm);<br>PhaseOne iXU-RS<br>1000 RGB camera | Riegl VUX-120<br>Monowavelength<br>LiDAR (1550<br>nm);<br>PhaseOne<br>iXM100<br>RSM35 RGB<br>camera | HeliALS<br>multispectral<br>LiDAR:<br>VQ-840-G (532<br>nm),<br>miniVUX-1DL<br>(905 nm),<br>VUX-1HA<br>(1550 nm) | DJI-L1 Monowavelength<br>LiDAR (905<br>nm) | Semi-Synthetic |
| **Platform** | Aircraft | Aircraft | Helicopter | Helicopter | UAV, MLS and<br>TLS | Miscellaneous |
| **Approximated<br>density/resolution** | LiDAR: 10 pts/m² | LiDAR: 75 pts/m²<br>Hyperspectral: 60 cm<br>RGB ortho: 10 cm | LiDAR: 375 pts/m² | LiDAR: 1200 pts/m² | LiDAR: 2000 pts/m² | LiDAR: From 0 to 2000<br>pts/m² |
| **Area of Interest** | 1000 m x 12000 m | 1680 m x 1550 m | 2000 m x 2000<br>m | 2000 m x 500 m | 275 m x 150 m | Flexible |
| **Type of data** | [LiDAR](#dataset-a-lidar): X, Y, Z, I | [LiDAR](#dataset-b-lidar): X, Y, Z, I<br>[Hyperspectral](#dataset-b-hyperspectral): 364<br>bands<br>[OrthoRGB](#dataset-b-orthorgb): R, G, B | [LiDAR](#dataset-c-lidar): X, Y,<br>Z, I | [LiDAR](#dataset-d-lidar): X, Y,<br>Z, SWIR, NIR,<br>Green | [LiDAR](#dataset-e-lidar): X, Y,<br>Z, I, RGB | [LiDAR](#dataset-f-lidar): X, Y,<br>Z, I |
| **Biome** | Urban,<br>Continental | Dense, Continental | Dense, Mediterranean | Dense, Boreal | Dense, Alpine | Variable |
| **Ground Truth** | [ITS](#dataset-a-its), [species](#dataset-a-species) (203<br>classes) | [Species](#dataset-b-species) (5 classes) | [ITS](#dataset-c-its) | [FSS](#dataset-d-fss) (6 classes) | [ITS](#dataset-e-its), [trunk sizes](#dataset-e-trunk),<br>[tree species](#dataset-e-species) | [ITS](#dataset-f-its), [FSS](#dataset-f-fss),<br>[species](#dataset-f-species) |

</div>

---

## Dataset A {#dataset-a}

<div align="center">

| <span id="dataset-a-lidar">**LiDAR (X GB)**</span> | <span id="dataset-a-its">**ITS (X GB)**</span> | <span id="dataset-a-species">**Species (X GB)**</span> |
|:---:|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset B {#dataset-b}

<div align="center">

| <span id="dataset-b-lidar">**LiDAR (X GB)**</span> | <span id="dataset-b-hyperspectral">**Hyperspectral (X GB)**</span> | <span id="dataset-b-orthorgb">**OrthoRGB (X GB)**</span> | <span id="dataset-b-species">**Species (X GB)**</span> |
|:---:|:---:|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset C {#dataset-c}

<div align="center">

| <span id="dataset-c-lidar">**LiDAR (X GB)**</span> | <span id="dataset-c-its">**ITS (X GB)**</span> |
|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset D {#dataset-d}

<div align="center">

| <span id="dataset-d-lidar">**LiDAR (X GB)**</span> | <span id="dataset-d-fss">**FSS (X GB)**</span> |
|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset E {#dataset-e}

<div align="center">

| <span id="dataset-e-lidar">**LiDAR (X GB)**</span> | <span id="dataset-e-its">**ITS (X GB)**</span> | <span id="dataset-e-trunk">**Trunk sizes (X GB)**</span> | <span id="dataset-e-species">**Tree species (X GB)**</span> |
|:---:|:---:|:---:|:---:|
| <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> | <img src="[pending-image]" width="200"> |

</div>

---

## Dataset F {#dataset-f}

<div align="center">

| <span id="dataset-f-lidar">**LiDAR (X GB)**</span> | <span id="dataset-f-its">**ITS (X GB)**</span> | <span id="dataset-f-fss">**FSS (X GB)**</span> | <span id="dataset-f-species">**Species (X GB)**</span> |
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
