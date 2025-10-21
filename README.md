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

<div style="text-align: center;">
<table style="margin: auto;" width="95%">
<thead>
<tr>
  <th width="10%"></th>
  <th width="15%">Dataset</th>
  <th width="20%">Instrument</th>
  <th width="10%">Platform</th>
  <th width="15%">Approx. density / resolution</th>
  <th width="15%">Area of Interest</th>
  <th width="15%">Type of data</th>
  <th width="10%">Ground Truth (GT)</th>
</tr>
</thead>

<tbody>

<!-- ======================= Dataset A ======================= -->
<tr>
  <td rowspan="3" valign="top"><strong>3<br>D<br>3</strong></td>
  <td colspan="1" align="center">A</td>
  <td rowspan="3" align="center">Riegl VQ780ii<br>Mono-wavelength LiDAR (1064 nm)</td>
  <td rowspan="3" align="center">Aircraft</td>
  <td rowspan="3" align="center">15 pts/m²</td>
  <td rowspan="3" align="center">1000 × 12000 m</td>
  <td rowspan="3" align="center">LiDAR: X, Y, Z, I<br>Urban, Mediterranean biome</td>
  <td rowspan="3" align="center">ITS, species<br>(32,350 trees in 203 classes)</td>
</tr>
<tr><td align="center"><img src="./pictures/3D3/A.png" height="100" width="130"></td></tr>
<tr><td align="center"><img src="./pictures/3D3/A_network.png" height="100" width="130"></td></tr>

<!-- ======================= Dataset B ======================= -->
<tr>
  <td colspan="1" align="center">B</td>
  <td rowspan="3" align="center">Teledyne Optech GALAXY T1000 LiDAR (1064 nm);<br>SPECIM AISAFENIX Hyperspectral (381–2502 nm);<br>PhaseOne iXU-RS 1000 RGB</td>
  <td rowspan="3" align="center">Aircraft</td>
  <td rowspan="3" align="center">LiDAR: 75 pts/m²<br>HSI: 60 cm<br>RGB: 10 cm</td>
  <td rowspan="3" align="center">1680 × 1550 m</td>
  <td rowspan="3" align="center">LiDAR: X,Y,Z,I<br>Hyperspectral: 364 bands<br>RGB: R,G,B<br>Dense, Continental biome</td>
  <td rowspan="3" align="center">Species (237 trees, 5 classes)</td>
</tr>
<tr><td align="center"><img src="./pictures/3D3/B.png" height="100" width="130"></td></tr>
<tr><td align="center"><img src="./pictures/3D3/B_network.png" height="100" width="130"></td></tr>

<!-- ======================= Dataset C ======================= -->
<tr>
  <td colspan="1" align="center">C</td>
  <td rowspan="3" align="center">Riegl VUX-120 LiDAR (1550 nm);<br>PhaseOne iXM100 RGB</td>
  <td rowspan="3" align="center">Helicopter</td>
  <td rowspan="3" align="center">375 pts/m²</td>
  <td rowspan="3" align="center">2000 × 2000 m</td>
  <td rowspan="3" align="center">LiDAR: X, Y, Z, I<br>Dense, Mediterranean biome</td>
  <td rowspan="3" align="center">ITS</td>
</tr>
<tr><td align="center"><img src="./pictures/3D3/C.png" height="100" width="130"></td></tr>
<tr><td align="center"><img src="./pictures/3D3/C_network.png" height="100" width="130"></td></tr>

<!-- ======================= Dataset D ======================= -->
<tr>
  <td colspan="1" align="center">D</td>
  <td rowspan="3" align="center">HeliALS multispectral LiDAR:<br>VQ-840-G (532 nm), miniVUX-1DL (905 nm), VUX-1HA (1550 nm)</td>
  <td rowspan="3" align="center">Helicopter</td>
  <td rowspan="3" align="center">1200 pts/m²</td>
  <td rowspan="3" align="center">2000 × 500 m</td>
  <td rowspan="3" align="center">LiDAR: X, Y, Z, SWIR, NIR, Green<br>Boreal biome</td>
  <td rowspan="3" align="center">FSS (six classes)</td>
</tr>
<tr><td align="center"><img src="./pictures/3D3/D.png" height="100" width="130"></td></tr>
<tr><td align="center"><img src="./pictures/3D3/D_network.png" height="100" width="130"></td></tr>

<!-- ======================= Dataset E ======================= -->
<tr>
  <td colspan="1" align="center">E</td>
  <td rowspan="3" align="center">DJI-L1 Mono-wavelength LiDAR (905 nm)</td>
  <td rowspan="3" align="center">UAV, MLS, TLS</td>
  <td rowspan="3" align="center">2000 pts/m²</td>
  <td rowspan="3" align="center">275 × 150 m</td>
  <td rowspan="3" align="center">LiDAR: X, Y, Z, I<br>Dense, Continental biome</td>
  <td rowspan="3" align="center">ITS, trunk sizes, tree species</td>
</tr>
<tr><td align="center"><img src="./pictures/3D3/E.png" height="100" width="130"></td></tr>
<tr><td align="center"><img src="./pictures/3D3/E_network.png" height="100" width="130"></td></tr>

<!-- ======================= Dataset F ======================= -->
<tr>
  <td colspan="1" align="center">F</td>
  <td rowspan="3" align="center">Semi-Synthetic</td>
  <td rowspan="3" align="center">Aircraft</td>
  <td rowspan="3" align="center">0–75 pts/m²</td>
  <td rowspan="3" align="center">Flexible</td>
  <td rowspan="3" align="center">LiDAR: X, Y, Z, I<br>Variable biome</td>
  <td rowspan="3" align="center">ITS, FSS, species</td>
</tr>
<tr><td align="center"><img src="./pictures/3D3/F.png" height="100" width="130"></td></tr>
<tr><td align="center"><img src="./pictures/3D3/F_network.png" height="100" width="130"></td></tr>

</tbody>
</table>
</div>

