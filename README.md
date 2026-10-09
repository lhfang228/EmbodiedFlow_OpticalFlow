<h1 align="center">EmbodiedFlow: Semantic-Contextualized Matching for Robust Optical Flow in Embodied Scenarios</h1>

<p align="center">
  <a href="https://scholar.google.com/citations?hl=en&user=pFazUOQAAAAJ">Lihuang Fang</a><sup>1</sup>,
  <a href="https://scholar.google.com/citations?user=Ra7B_EoAAAAJ&hl=en">Xiao Hu</a><sup>2</sup>,
  <a href="https://scholar.google.com/citations?user=m9AfyE8AAAAJ&hl=en">Yuchen Zou</a><sup>3</sup>,
  Jinghui Qin<sup>4</sup>,
  <a href="https://www.sustech.edu.cn/zh/faculties/zhanghong.html">Hong Zhang (life Fellow IEEE)</a><sup>1</sup>
</p>

<p align="center">
  <sup>1</sup> Southern University of Science and Technology (SUSTech)<br>
  <sup>2</sup> International Digital Economy Academy (IDEA)<br>
  <sup>3</sup> Xi'an Jiaotong University (XJTU)<br>
  <sup>4</sup> Guangdong University of Technology (GDUT)
</p>

## Abstract

Optical flow represents the per-pixel two-dimensional displacement between video frames, supporting visual odometry and the tracking of hands, tools, and manipulated objects. However, videos captured by robot-mounted or egocentric cameras often contain simultaneous camera, hand, robot-arm, and object motion, introducing appearance ambiguity, large displacement, occlusion, and motion blur that make local appearance cues unreliable. We therefore introduce EmbodiedFlow, which contextualizes semantic features through intra-frame and bidirectional cross-frame attention and fuses them with appearance features for optical-flow matching. We evaluate this design on **EmbodiedFlow-Bench**, which comprises 1,560 image pairs spanning Navigation, Dexterous Hand, and Bimanual Interaction and reports overall performance as the average across the three categories. Among the evaluated methods, EmbodiedFlow achieves the lowest errors both overall and on the Large split, with reductions of 5.5% and 6.7%, respectively, relative to the matched appearance-only baseline. It also reduces EPE by 5.3–13.2% on standard optical-flow benchmarks. Finally, replacing the optical-flow estimator in an RGB-D visual-odometry pipeline with EmbodiedFlow improves trajectory estimation in a dynamic-scene case study, demonstrating its utility for downstream robot perception.
