<p align="center">
  <img height="150" alt="image" src="https://github.com/user-attachments/assets/8a4902a5-59de-4ca1-9dbb-b417512ba8f1" />
  <img height="150" alt="image" src="https://github.com/user-attachments/assets/aba6146a-c625-4d6b-b66d-83f34ac4d832" />
  <img height="150" alt="image" src="https://github.com/user-attachments/assets/a10c26a6-5ea6-48c3-9ce5-ce2a4947e130" />
</p>

<h1 align="center">3D3 Benchmark Dataset</h1>

<p align="center">
  <br>
  <a>Bocaux, L., Takhtkeshha, N., Ma, Z., Remondino, F., 2025: <br><strong><a href="https://isprs-archives.copernicus.org/articles/XLVIII-1-W6-2025/33/2025/">A multi-sensor multi-resolution dataset to support forest inventory methods.</a></strong><br>Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., in press – Geobench 2025 workshop, in press </a><br> 
  | 🌲 <a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EomUL1NvtNdDivGfWtDj_zkB6Kpz5BYwqs8GRpmBLJj5OQ?e=jVhuRo">All data available here</a> 🌲 | <br>contact: 3dom@fbk.eu
</p>

---

## 🌍 Overview

**3D3** is a large-scale benchmark designed to evaluate high-resolution 3D forestry methods, under a wide range of acquisition conditions and sensing modalities.

It integrates **airborne, helicopter, UAV, mobile, and terrestrial LiDAR** with **hyperspectral** and **RGB** data across diverse European forest types — from **urban** and **Mediterranean** to **boreal** environments.  

Each site provides **ground truth for at least one core task of high-resolution 3D forestry** — *individual tree segmentation (ITS)*, *forest semantic segmentation (FSS)*, or *tree species classification* — ensuring consistent reference data across modalities and acquisition densities.  

---

## 🌲 3D3 Dataset Table 

<div align="center">
  
| **<a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EomUL1NvtNdDivGfWtDj_zkB6Kpz5BYwqs8GRpmBLJj5OQ?e=jVhuRo">Dataset</a>** | **[A](#dataset-a)** | **[B](#dataset-b)** | **[C](#dataset-c)** | **[D](#dataset-d)** | **[E](#dataset-e)** | **[F](#dataset-f)** |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| **Instrument** | Riegl VQ780ii<br>Mono-wavelength<br>LiDAR (1064 nm) | Teledyne Optech<br>GALAXY T1000 -<br>Mono-wavelength<br>LiDAR (1064 nm);<br>SPECIM AISAFENIX<br>- Hyperspectral<br>camera (381.35 nm to<br>2502.38 nm);<br>PhaseOne iXU-RS<br>1000 RGB camera | Riegl VUX-120<br>Monowavelength<br>LiDAR (1550<br>nm);<br>PhaseOne<br>iXM100<br>RSM35 RGB<br>camera | HeliALS<br>multispectral<br>LiDAR:<br>VQ-840-G (532<br>nm),<br>miniVUX-1DL<br>(905 nm),<br>VUX-1HA<br>(1550 nm) | DJI-L1 Monowavelength<br>LiDAR (905<br>nm) | Semi-Synthetic |
| **Platform** | Aircraft | Aircraft | Helicopter | Helicopter | UAV, MLS and<br>TLS | Miscellaneous |
| **Approximated<br>density/resolution** | LiDAR: 10 pts/m² | LiDAR: 75 pts/m²<br>Hyperspectral: 60 cm<br>RGB ortho: 10 cm | LiDAR: 375 pts/m² | LiDAR: 1200 pts/m² | LiDAR: 2000 pts/m² | LiDAR: From 0 to 2000<br>pts/m² |
| **Area of Interest** | 11 km x 16 km | 1680 m x 1550 m | 1 km x 1 km | 8000 m² | 275 m x 150 m | Flexible |
| **Type of data** | [LiDAR](#dataset-a-lidar): X, Y, Z, I | [LiDAR](#dataset-b-lidar): X, Y, Z, I<br>[Hyperspectral](#dataset-b-hyperspectral): 364<br>bands<br>[OrthoRGB](#dataset-b-orthorgb): R, G, B | [LiDAR](#dataset-c-lidar): X, Y,<br>Z, I | [LiDAR](#dataset-d-lidar): X, Y,<br>Z, SWIR, NIR,<br>Green | [LiDAR](#dataset-e-lidar): X, Y,<br>Z, I, RGB | [LiDAR](#dataset-f-lidar): X, Y,<br>Z, I |
| **Biome** | Urban,<br>Continental | Dense, Continental | Dense, Mediterranean | Dense, Boreal | Dense, Alpine | Variable |
| **Ground Truth** | [ITS](#dataset-a-its), [species](#dataset-a-species) (203<br>classes) | [ITS](#dataset-b-its), [Species](#dataset-b-species) (5 classes) | [ITS](#dataset-c-its) | [FSS](#dataset-d-fss) (6 classes) | [ITS](#dataset-e-its), [trunk size](#dataset-e-parameters),<br>[tree type](#dataset-e-parameters), [tree height](#dataset-e-parameters) | [ITS](#dataset-f-trees), [species](#dataset-f-trees) |

</div>

---

## 🌳 3D3 Datasets

### <a id="dataset-a"></a><a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Em7VTRYMfaRLuHtnrd8EG2wBVIVr3l_ehgXhTNXMekyE9A?e=a3OCJe">Dataset A</a>

<div align="center">

| <span id="dataset-a-lidar">**LiDAR [(11.0 GB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Etu4l9TGL_xJoi7asBmsZh8B8YPJ9nKw4W9ilCMtoLoUPg?e=2cJjze)**</span> | <span id="dataset-a-its">**ITS [(228 KB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EutNTlw-fKtNuRob8ONlObEBb0vdIKomshdrRUebR1a1Vg?e=mp5LZi)**</span> | <span id="dataset-a-species">**Species [(229 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EokRcM1iZt1AoP-jaE68jA0BZdb_5mTGSHjdwwgTcJZu4Q?e=SlxPUK)**</span> |
|:---:|:---:|:---:|
| <img alt="a_lidar_1" src="https://github.com/user-attachments/assets/a3dcfda8-181d-4ae5-b1f5-1b039bfff3b6" width="350"> <br> <img alt="a_lidar_2" src="https://github.com/user-attachments/assets/1a869ef6-50f2-46f7-b2c2-479e33cfd63b" width="350"> | <img alt="a_its_1" src="https://github.com/user-attachments/assets/61bf6493-8eaa-407d-9e83-620232e4f2f1" width="350"> <br> <img width="350" alt="a_its_2" src="https://github.com/user-attachments/assets/0f0550a5-aba0-4eb1-924f-3324e44395c6" /> | <img width="340"  alt="image" src="https://github.com/user-attachments/assets/4daee5ba-e3d1-4491-b742-204282abed35" /> |

</div>

---

### <a id="dataset-b"></a><a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EvuDKHTQvdRIig29C7oTi-cBkUamLT7BvIdcIwPcggo0hg?e=zeEJd7">Dataset B</a>

<div align="center">

| <span id="dataset-b-lidar">**LiDAR [(662 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/ErPsJ7UbAONBge8r_XsGfQEBuxqC0D0Gf0LJaDLAej0fTQ?e=1dqKtO)**</span> | <span id="dataset-b-hyperspectral">**Hyperspectral [(4.90 GB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Eklh8dRXNTxMs6F6K5j0UM8BSiBKZ-MqIPX3l4iG3ZmPqg?e=HmGjR9)**</span> | <span id="dataset-b-orthorgb">**OrthoRGB [(738 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EjlE6bFt7dVNmPsvL-q2QNQBk91JDq7HCJrSs2zt5Y_18A?e=erXc1a)**</span> | <span id="dataset-b-its">**ITS [(4.38 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EhLxiFqrYV1Pjfs6uOJmEVwBfoPl345BGl1Jn1aDdYjQDg?e=bh99DH)**</span> | <span id="dataset-b-species">**Species [(57.3 KB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Ev6wZx68d1VPlr-zla3zaXcBTmuPlbLdtS_9cxuPthQE8Q?e=aTqAaJ)**</span> |
|:---:|:---:|:---:|:---:|:---:|
| <img width="200" alt="image" src="https://github.com/user-attachments/assets/e08b960d-249e-49cf-876f-d98ab59808cd" /> | <img width="200" alt="image" src="https://github.com/user-attachments/assets/6f64ee06-cf88-4bea-93e2-fb0fb84b7e5d" /> | <img width="200"  alt="image" src="https://github.com/user-attachments/assets/2e1cb246-ce0e-45fe-86bd-318ac030e798" /> | <img width="200" alt="image" src="https://github.com/user-attachments/assets/b1fbf700-74c1-4bac-bc65-eac5e21d86b7" /> | <img width="200" alt="image" src="https://github.com/user-attachments/assets/a3641635-f2eb-4009-bf79-04521aa5fd8b" /> |

</div>

---

### <a id="dataset-c"></a><a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Ek2QIVQ2Pl9HqT39hEOd4WkBNA-zvfO8WyGC9T7Tc8z5hw?e=dh6Qgi">Dataset C</a>

<div align="center">

| <span id="dataset-c-lidar">**LiDAR [(4.29 GB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EnX_f9VycutAkrTaGiY8m3kBnOQ7ethtR2nBQ0fYxMedBA?e=6fzAmN)**</span> | <span id="dataset-c-its">**ITS [(8.74 KB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Eosrtlr7Qq1AvTdDje31wTQBhRNapK3MrrkDUglJO8F55Q?e=1Wwwfy)**</span> |
|:---:|:---:|
| <img width="400" alt="image" src="https://github.com/user-attachments/assets/a22a5023-a27a-4f59-8261-02d82537cb17" /> <br>  <img width="400" alt="image" src="https://github.com/user-attachments/assets/5105d97d-4689-40d4-9d79-0af93c986ce7" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/b41d23da-1d27-4a22-a4d2-da894218ff0d" /> <br> <img width="400" alt="image" src="https://github.com/user-attachments/assets/fb983eea-90f3-47b1-8a3c-d62576d8f432" /> |

</div>

---

### <a id="dataset-d"></a><a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EvW_VU5Ed7NKjJDtVWmTdCUB_ZoLf1GH8tyukgAEDpIaCA?e=AGg1xg">Dataset D</a>

<div align="center">

| <span id="dataset-d-lidar">**LiDAR [(111 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Eg2R-dDEBwlMs5OiINz9nUkBjwPbgbaZYgR7dcnkaD1rLg?e=aol0f3)**</span> | <span id="dataset-d-fss">**FSS [(111 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Erw6-L6SHq5HsjLybdTP03EBXGmhtA6JyMvjBqJIPjohkg?e=DSKLh5)**</span> |
|:---:|:---:|
| <img width="220" alt="image" src="https://github.com/user-attachments/assets/aaaddd84-2341-442a-93d2-f72f352c71fb" /> <img width="220" alt="image" src="https://github.com/user-attachments/assets/eacd25d8-fa95-4f2a-a45f-3294124b96ea" /> <img width="220" alt="image" src="https://github.com/user-attachments/assets/a8f911c4-5e32-48d9-b56d-6a8fd2fdc73e" /> | <img alt="image" width="220" src="https://github.com/user-attachments/assets/697a19ba-32ab-4d05-8103-d494db4d7d24" /> |

</div>

---

### <a id="dataset-e"></a><a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EqEvPSJ3hbFOpBUDYsJ11QMBtxZVct-7uitOFUwdBwFJ4g?e=obf5fb">Dataset E</a>

<div align="center">

| <span id="dataset-e-lidar">**LiDAR [(296 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Eq-5iMbGd2pDqjvJKaDEgk8Bz6FC1EVSxYEv1m787TwH4g?e=YhRcaa)**</span> | <span id="dataset-e-its">**ITS [(5.08 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/ErcNhlDMLSxHi6a_WZy0MmMBlCle0sO2rqCpCXEH9v4jZg?e=MzZslX)**</span> | <span id="dataset-e-parameters">**Tree Parameters [(47.8 KB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/EmfSN6k3jHhJjH7s2n-rfoYBkmEeCKWLnWWqVjETU-Mqjg?e=p9bigf)**</span> |
|:---:|:---:|:---:|
| <img width="320" alt="image" src="https://github.com/user-attachments/assets/9279b1cd-f8e9-48d9-bf00-5ee77f606eda" /> | <img width="320" alt="image" src="https://github.com/user-attachments/assets/2a1705cc-6bfa-4d27-85fd-d8cb77da365b" /> | <img width="320" alt="image" src="https://github.com/user-attachments/assets/56784f17-e227-4c1a-9717-12c91f415d5e" /> |
</div>

---

### <a id="dataset-f"></a><a href="https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Ekss54R__w5JrPMlYxUpqKcBKZ29P_2JQava4wdQXjQuxw?e=wzXQz1">Dataset F</a>

<div align="center">

| <span id="dataset-f-trees">**Trees [(30.1 MB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Ehwg1fHK_hhHmzRSFN_wnZMBvZOjAdxSaNN1LxRNppq2MA?e=8pp3tl)**</span> | <span>**SSGT generator [(189 KB)](https://fbk.sharepoint.com/:f:/s/BENCHMARKS/Ehu_-huJ0MhHlIkeaL-nBM8Baq6KdYYJnVxlE2u1x5HzQQ?e=0agR1F)**</span> |
|:---:|:---:|
| <img height="250" alt="image" src="https://github.com/user-attachments/assets/1c29df55-9066-40d6-97c4-4eab9b0bddce" /> | <img height="250" alt="Screenshot 2025-11-18 194646" src="https://github.com/user-attachments/assets/5576c47c-9bca-40d0-8b33-633ef61e5272" /> |

---

## License

The data provided here is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

<p align="center">
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">
    <img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" alt="CC BY-NC-SA 4.0">
  </a>
</p>
