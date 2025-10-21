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
  <table style="margin: auto;" width="90%">
    <thead>
      <tr>
        <th width="8%"></th>
        <th width="20%">Dataset</th>
        <th width="22%">Instrument</th>
        <th width="15%">Platform</th>
        <th width="12%">Density / Resolution</th>
        <th width="18%">Area & Biome</th>
        <th width="15%">Ground Truth</th>
      </tr>
    </thead>
    <tbody>

      <!-- ======== DATASET A ======== -->
      <tr>
        <td rowspan="3" valign="top"><strong>A</strong></td>
        <td colspan="1" align="center">Dataset A</td>
        <td rowspan="3" align="center">Riegl VQ780ii<br>Mono-wavelength LiDAR (1064 nm)</td>
        <td rowspan="3" align="center">Aircraft</td>
        <td rowspan="3" align="center">15 pts/m²</td>
        <td rowspan="3" align="center">1000 × 12000 m<br>Urban, Mediterranean</td>
        <td rowspan="3" align="center">ITS, species<br>(32,350 trees, 203 classes)</td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/A.png" height="110" width="130"></td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/A_network.png" height="110" width="130"></td>
      </tr>

      <!-- ======== DATASET B ======== -->
      <tr>
        <td rowspan="3" valign="top"><strong>B</strong></td>
        <td colspan="1" align="center">Dataset B</td>
        <td rowspan="3" align="center">Teledyne Optech GALAXY T1000 (1064 nm)<br>SPECIM AISAFENIX (381–2502 nm)<br>PhaseOne iXU-RS 1000 RGB</td>
        <td rowspan="3" align="center">Aircraft</td>
        <td rowspan="3" align="center">LiDAR: 75 pts/m²<br>Hyperspectral: 60 cm<br>RGB: 10 cm</td>
        <td rowspan="3" align="center">1680 × 1550 m<br>Dense, Continental</td>
        <td rowspan="3" align="center">Species (237 trees, 5 classes)</td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/B.png" height="110" width="130"></td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/B_network.png" height="110" width="130"></td>
      </tr>

      <!-- ======== DATASET C ======== -->
      <tr>
        <td rowspan="3" valign="top"><strong>C</strong></td>
        <td colspan="1" align="center">Dataset C</td>
        <td rowspan="3" align="center">Riegl VUX-120 (1550 nm)<br>PhaseOne iXM100 RSM35 RGB</td>
        <td rowspan="3" align="center">Helicopter</td>
        <td rowspan="3" align="center">375 pts/m²</td>
        <td rowspan="3" align="center">2000 × 2000 m<br>Dense, Mediterranean</td>
        <td rowspan="3" align="center">ITS</td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/C.png" height="110" width="130"></td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/C_network.png" height="110" width="130"></td>
      </tr>

      <!-- ======== DATASET D ======== -->
      <tr>
        <td rowspan="3" valign="top"><strong>D</strong></td>
        <td colspan="1" align="center">Dataset D</td>
        <td rowspan="3" align="center">HeliALS multispectral LiDAR:<br>VQ-840-G (532 nm), miniVUX-1DL (905 nm), VUX-1HA (1550 nm)</td>
        <td rowspan="3" align="center">Helicopter</td>
        <td rowspan="3" align="center">1200 pts/m²</td>
        <td rowspan="3" align="center">2000 × 500 m<br>Touching trees, Boreal</td>
        <td rowspan="3" align="center">FSS (6 classes)</td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/D.png" height="110" width="130"></td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/D_network.png" height="110" width="130"></td>
      </tr>

      <!-- ======== DATASET E ======== -->
      <tr>
        <td rowspan="3" valign="top"><strong>E</strong></td>
        <td colspan="1" align="center">Dataset E</td>
        <td rowspan="3" align="center">DJI-L1<br>Mono-wavelength LiDAR (905 nm)</td>
        <td rowspan="3" align="center">UAV, MLS, TLS</td>
        <td rowspan="3" align="center">2000 pts/m²</td>
        <td rowspan="3" align="center">275 × 150 m<br>Dense, Continental</td>
        <td rowspan="3" align="center">ITS, trunk sizes, species</td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/E.png" height="110" width="130"></td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/E_network.png" height="110" width="130"></td>
      </tr>

      <!-- ======== DATASET F ======== -->
      <tr>
        <td rowspan="3" valign="top"><strong>F</strong></td>
        <td colspan="1" align="center">Dataset F</td>
        <td rowspan="3" align="center">Semi-Synthetic</td>
        <td rowspan="3" align="center">Aircraft</td>
        <td rowspan="3" align="center">0–75 pts/m²</td>
        <td rowspan="3" align="center">Flexible<br>Variable biomes</td>
        <td rowspan="3" align="center">ITS, FSS, species</td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/F.png" height="110" width="130"></td>
      </tr>
      <tr>
        <td align="center"><img src="./pictures/3D3/F_network.png" height="110" width="130"></td>
      </tr>

    </tbody>
  </table>
</div>
