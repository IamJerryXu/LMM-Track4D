<a id="top"></a>

<div align="center">

<p><img src="assets/readme/hero.svg" width="100%" alt="LMM-Track4D — Multiple views. One continuous track."></p>

<h3>Eliciting 4D Dynamic Reasoning in LMMs<br>via Trajectory-Grounded Dialogue</h3>

Chaoyue Li · [Yongxue Xu](https://jerrysnow.me) · Jie Feng · Jiayu Ding

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
