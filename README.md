<div align="center">

<h1 style="font-family: Georgia, 'Times New Roman', serif;">
LMM-Track4D: A Large Multimodal Model for Multi-View 4D Object Tracking and Trajectory Reasoning
</h1>

<img src="assets/track4d-icon.svg" width="760" alt="LMM-Track4D trajectory banner">

[![Overview](https://img.shields.io/badge/Overview-Framework-2563eb.svg)](#framework-overview)
[![Demo](https://img.shields.io/badge/Demo-Trajectory_Reasoning-0891b2.svg)](#demo)
[![Benchmark](https://img.shields.io/badge/Benchmark-Track4D--Bench-7c3aed.svg)](#track4d-bench)

Paper: coming soon · Checkpoints: coming soon

</div>

## Framework Overview

<p align="center">
  <img src="assets/task.png" width="95%" alt="LMM-Track4D task and method showcase">
</p>

<p align="center">
  <em>
    An overview of our multi-view 4D trajectory reasoning framework.<br>
    <strong>LMM-Track4D</strong> augments a large multimodal model with ray-time geometry, persistent <strong>[TRK]</strong> state tokens,
    and an explicit 3D trajectory decoder. Unlike scene-level 4D LMMs that answer at sparse sampled timestamps,
    our model preserves object identity across dialogue turns and predicts metric trajectories for queried targets.
  </em>
</p>

## Demo

<p align="center">
  <img src="assets/demo.gif" width="95%" alt="LMM-Track4D demo">
</p>

## Track4D-Bench

<p align="center">
  <img src="assets/benchmark.png" width="95%" alt="Track4D-Bench statistics and construction pipeline">
</p>

Track4D-Bench merges **APIDIS**, **KITTI Tracking**, and **WildTrack** into a unified multi-domain benchmark for track-conditioned 4D dialogue.

<div align="center">

<table>
  <thead>
    <tr>
      <th>split</th>
      <th>APIDIS</th>
      <th>KITTI</th>
      <th>WildTrack</th>
      <th>total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>long</strong></td>
      <td align="center">15</td>
      <td align="center">67</td>
      <td align="center">16</td>
      <td align="center">98</td>
    </tr>
    <tr>
      <td><strong>short</strong></td>
      <td align="center">62</td>
      <td align="center">316</td>
      <td align="center">50</td>
      <td align="center">428</td>
    </tr>
    <tr>
      <td><strong>total</strong></td>
      <td align="center"><strong>77</strong></td>
      <td align="center"><strong>383</strong></td>
      <td align="center"><strong>66</strong></td>
      <td align="center"><strong>526</strong></td>
    </tr>
  </tbody>
</table>

</div>
