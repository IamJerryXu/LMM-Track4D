<a id="top"></a>

<div align="center">

<p><img src="assets/readme/hero.svg" width="100%" alt="InkMind.AI · LMM-Track4D — multi-view trajectories through space and time"></p>

<p><img src="assets/readme/subtitle.svg" width="90%" alt="Eliciting 4D Dynamic Reasoning in LMMs via Trajectory-Grounded Dialogue"></p>

<p>
<a href="https://arxiv.org/abs/2605.19390"><img src="assets/readme/nav-paper.svg" height="43" alt="Paper on arXiv"></a>
&nbsp;
<a href="#framework-overview"><img src="assets/readme/nav-overview.svg" height="43" alt="Overview"></a>
&nbsp;
<a href="#demo"><img src="assets/readme/nav-demo.svg" height="43" alt="Demo"></a>
&nbsp;
<a href="#track4d-bench"><img src="assets/readme/nav-benchmark.svg" height="43" alt="Benchmark"></a>
&nbsp;
<a href="#citation"><img src="assets/readme/nav-citation.svg" height="43" alt="Citation"></a>
</p>

</div>

<a id="framework-overview"></a>

<p><img src="assets/readme/heading-overview.svg" width="100%" alt="The task"></p>

**Answer the question. Keep track of the object.** Trajectory-grounded multi-turn dialogue pairs spatiotemporal answers with structured 3D target trajectories, over a short clip or a queried segment of a longer video.

<p align="center">
  <img src="assets/task.png" width="100%" alt="LMM-Track4D task and method showcase">
</p>

**LMM-Track4D** combines **RTGE** for ray-time geometry encoding, a persistent **[TRK]** token for cross-turn state propagation, and **OSK-RA** for structured, query-conditioned 3D trajectory decoding. Together, these components maintain dynamic object states across time, viewpoints, and dialogue turns.

<a id="demo"></a>

<p><img src="assets/readme/heading-demo.svg" width="100%" alt="See it in motion"></p>

<p align="center"><img src="assets/demo.png" width="100%" alt="Examples of trajectory-grounded dialogue and 3D trajectory predictions"></p>

<p align="center">
  <a href="assets/demo.mp4"><img src="assets/demo.gif" width="100%" alt="Animated LMM-Track4D demo — open the full video"></a>
</p>

<p align="center"><a href="assets/demo.mp4"><strong>Watch the full demo ↗</strong></a></p>

<a id="track4d-bench"></a>

<p><img src="assets/readme/heading-benchmark.svg" width="100%" alt="Track4D-Bench"></p>

<p align="center">
  <img src="assets/benchmark.png" width="100%" alt="Track4D-Bench statistics and construction pipeline">
</p>

Track4D-Bench merges **APIDIS**, **KITTI Tracking**, and **WildTrack** into a unified multi-domain benchmark for track-conditioned 4D dialogue.

<p align="center"><img src="assets/readme/benchmark-table.svg" width="100%" alt="Clip counts by split (APIDIS / KITTI / WildTrack / Total): Long 15 / 67 / 16 / 98; Short 62 / 316 / 50 / 428; Total 77 / 383 / 66 / 526."></p>

<a id="citation"></a>

<p><img src="assets/readme/heading-citation.svg" width="100%" alt="Cite this work"></p>

If this work is useful to your research, please consider citing:

```bibtex
@misc{li2026lmmtrack4deliciting4ddynamic,
  title={LMM-Track4D: Eliciting 4D Dynamic Reasoning in LMMs via Trajectory-Grounded Dialogue},
  author={Chaoyue Li and Yongxue Xu and Jie Feng and Jiayu Ding},
  year={2026},
  eprint={2605.19390},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2605.19390}
}
```

<div align="center">

<p><img src="assets/readme/closing.svg" width="100%" alt="Keep the object in the story."></p>

Code will be released upon paper acceptance.

[Read the paper ↗](https://arxiv.org/abs/2605.19390) · [Coauthor's repository ↗](https://github.com/mikubaka88/LMM-Track4D) · [Back to top ↑](#top)

</div>
