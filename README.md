<p align="center">
  <img src="[pending-image-link]" width="80%">
</p>

<h1 align="center">3D3 Benchmark Dataset</h1>

<p align="center">
  <strong>A multi-sensor and multi-resolution dataset to support forest inventory methods</strong>  
  <br>
  <a href="[pending-paper-link]">📄 Paper (Pending)</a> | <a href="[pending-dataset-link]">🌲 Dataset (Pending)</a>
</p>

---

## 🌍 Overview

**3D3** is a large-scale benchmark designed to evaluate high-resolution 3D forestry methods, under a wide range of acquisition conditions and sensing modalities.

It integrates **airborne, helicopter, UAV, mobile, and terrestrial LiDAR** with **hyperspectral** and **RGB** data across diverse European forest types — from **urban** and **Mediterranean** to **boreal** environments.  

Each site provides **ground truth for at least one core task of high-resolution 3D forestry** — *individual tree segmentation (ITS)*, *forest semantic segmentation (FSS)*, or *tree species classification* — ensuring consistent reference data across modalities and acquisition densities.  

---

## 🌲 3D3 dataset table 

<table border="1" cellpadding="6" cellspacing="0" style="border-collapse:collapse; width:100%; font-family:Arial, sans-serif;">
  <thead>
    <tr style="background:#f2f2f2; text-align:left;">
      <th style="width:14%;">Dataset</th>
      <th style="width:14%;">A</th>
      <th style="width:14%;">B</th>
      <th style="width:14%;">C</th>
      <th style="width:14%;">D</th>
      <th style="width:14%;">E</th>
      <th style="width:16%;">F</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th style="text-align:left; background:#fafafa;">Instrument</th>
      <td>
        Riegl VQ780ii<br>
        Mono-wavelength LiDAR (1064 nm)
      </td>
      <td>
        Teledyne Optech GALAXY T1000 - Mono-wavelength LiDAR (1064 nm);<br>
        SPECIM AISAFENIX - Hyperspectral camera (381.35 nm to 2502.38 nm);<br>
        PhaseOne iXU-RS 1000 RGB camera
      </td>
      <td>
        Riegl VUX-120 Mono-wavelength LiDAR (1550 nm);<br>
        PhaseOne iXM100 RSM35 RGB camera
      </td>
      <td>
        HeliALS multispectral LiDAR:<br>
        VQ-840-G (532 nm),<br>
        miniVUX-1DL (905 nm),<br>
        VUX-1HA (1550 nm)
      </td>
      <td>
        DJI-L1 Mono-wavelength LiDAR (905 nm)
      </td>
      <td>
        Semi-Synthetic
      </td>
    </tr>

    <tr>
      <th style="text-align:left; background:#fafafa;">Platform</th>
      <td>Aircraft</td>
      <td>Aircraft</td>
      <td>Helicopter</td>
      <td>Helicopter</td>
      <td>UAV, MLS and TLS</td>
      <td>Aircraft</td>
    </tr>

    <tr>
      <th style="text-align:left; background:#fafafa;">Approximated density / resolution</th>
      <td>15 pts/m²</td>
      <td>
        LiDAR: 75 pts/m²<br>
        Hyperspectral: 60 cm<br>
        RGB ortho: 10 cm
      </td>
      <td>375 pts/m²</td>
      <td>1200 pts/m²</td>
      <td>2000 pts/m²</td>
      <td>From 0 to 75 pts/m²</td>
    </tr>

    <tr>
      <th style="text-align:left; background:#fafafa;">Area of Interest</th>
      <td>1000 m × 12000 m</td>
      <td>1680 m × 1550 m</td>
      <td>2000 m × 2000 m</td>
      <td>2000 m × 500 m</td>
      <td>275 m × 150 m</td>
      <td>Flexible</td>
    </tr>

    <tr>
      <th style="text-align:left; background:#fafafa;">Type of data</th>
      <td>
        LiDAR: X, Y, Z, I
      </td>
      <td>
        LiDAR: X, Y, Z, I;<br>
        Hyperspectral: 364 bands;<br>
        OrthoRGB: R, G, B
      </td>
      <td>
        LiDAR: X, Y, Z, I
      </td>
      <td>
        LiDAR: X, Y, Z, SWIR, NIR, Green
      </td>
      <td>
        LiDAR: X, Y, Z, I
      </td>
      <td>
        LiDAR: X, Y, Z, I
      </td>
    </tr>

    <tr>
      <th style="text-align:left; background:#fafafa;">Biome</th>
      <td>Urban, Mediterranean</td>
      <td>Dense, Continental</td>
      <td>Dense, Mediterranean</td>
      <td>Touching trees, Boreal</td>
      <td>Dense, Continental</td>
      <td>Variable</td>
    </tr>

    <tr>
      <th style="text-align:left; background:#fafafa;">Ground Truth</th>
      <td>
        ITS, species<br>
        <small>(32,350 trees in 203 classes)</small>
      </td>
      <td>
        Species<br>
        <small>(237 trees in 5 classes)</small>
      </td>
      <td>ITS</td>
      <td>FSS (six classes)</td>
      <td>ITS, trunk sizes, tree species</td>
      <td>ITS, FSS, species</td>
    </tr>
  </tbody>
</table>
