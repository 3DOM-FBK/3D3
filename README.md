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

<div align="center">

<table style="border-collapse:collapse; width:100%; font-family:Arial, sans-serif; font-size:14px;" border="1" cellpadding="6">
  <thead>
    <tr style="background-color:#f2f2f2; text-align:center;">
      <th style="width:16%;">Property</th>
      <th style="width:14%;">A</th>
      <th style="width:14%;">B</th>
      <th style="width:14%;">C</th>
      <th style="width:14%;">D</th>
      <th style="width:14%;">E</th>
      <th style="width:14%;">F</th>
    </tr>
  </thead>
  <tbody>

    <tr>
      <th align="left" style="background:#fafafa;">Instrument</th>
      <td align="left">Riegl VQ780ii<br>Mono-wavelength LiDAR (1064 nm)</td>
      <td align="left">
        Teledyne Optech GALAXY T1000 LiDAR (1064 nm);<br>
        SPECIM AISAFENIX Hyperspectral (381–2502 nm);<br>
        PhaseOne iXU-RS 1000 RGB camera
      </td>
      <td align="left">
        Riegl VUX-120 LiDAR (1550 nm);<br>
        PhaseOne iXM100 RSM35 RGB camera
      </td>
      <td align="left">
        HeliALS multispectral LiDAR:<br>
        VQ-840-G (532 nm), miniVUX-1DL (905 nm), VUX-1HA (1550 nm)
      </td>
      <td align="left">DJI-L1 Mono-wavelength LiDAR (905 nm)</td>
      <td align="left">Semi-synthetic</td>
    </tr>

    <tr>
      <th align="left" style="background:#fafafa;">Platform</th>
      <td align="center">Aircraft</td>
      <td align="center">Aircraft</td>
      <td align="center">Helicopter</td>
      <td align="center">Helicopter</td>
      <td align="center">UAV, MLS, TLS</td>
      <td align="center">Aircraft</td>
    </tr>

    <tr>
      <th align="left" style="background:#fafafa;">Approx. density / resolution</th>
      <td align="center">15 pts/m²</td>
      <td align="center">
        LiDAR: 75 pts/m²<br>
        Hyperspectral: 60 cm<br>
        RGB: 10 cm
      </td>
      <td align="center">375 pts/m²</td>
      <td align="center">1200 pts/m²</td>
      <td align="center">2000 pts/m²</td>
      <td align="center">0–75 pts/m²</td>
    </tr>

    <tr>
      <th align="left" style="background:#fafafa;">Area of Interest</th>
      <td align="center">1000 × 12000 m</td>
      <td align="center">1680 × 1550 m</td>
      <td align="center">2000 × 2000 m</td>
      <td align="center">2000 × 500 m</td>
      <td align="center">275 × 150 m</td>
      <td align="center">Flexible</td>
    </tr>

    <tr>
      <th align="left" style="background:#fafafa;">Type of data</th>
      <td align="left">LiDAR: X, Y, Z, I</td>
      <td align="left">
        LiDAR: X, Y, Z, I;<br>
        Hyperspectral: 364 bands;<br>
        OrthoRGB: R, G, B
      </td>
      <td align="left">LiDAR: X, Y, Z, I</td>
      <td align="left">LiDAR: X, Y, Z, SWIR, NIR, Green</td>
      <td align="left">LiDAR: X, Y, Z, I</td>
      <td align="left">LiDAR: X, Y, Z, I</td>
    </tr>

    <tr>
      <th align="left" style="background:#fafafa;">Biome</th>
      <td align="center">Urban, Mediterranean</td>
      <td align="center">Dense, Continental</td>
      <td align="center">Dense, Mediterranean</td>
      <td align="center">Touching trees, Boreal</td>
      <td align="center">Dense, Continental</td>
      <td align="center">Variable</td>
    </tr>

    <tr>
      <th align="left" style="background:#fafafa;">Ground Truth</th>
      <td align="left">
        ITS, species<br>
        <small>(32,350 trees in 203 classes)</small>
      </td>
      <td align="left">
        Species<br>
        <small>(237 trees in 5 classes)</small>
      </td>
      <td align="center">ITS</td>
      <td align="center">FSS (six classes)</td>
      <td align="left">ITS, trunk sizes, species</td>
      <td align="center">ITS, FSS, species</td>
    </tr>

  </tbody>
</table>

</div>


