<div align="center">
    <h1>SynHMR: Synergistic Joint-Mesh Modeling for LiDAR-based Human Mesh Reconstruction (ECCV 2026)</h1>
    <div>
        <a href="https://github.com/ShiRui1208/" target="_blank">Rui Shi</a><sup>1</sup>&emsp;
        <a href="https://github.com/AnxQ/" target="_blank">Xiaoqi An</a><sup>1</sup>&emsp;
        <a href="https://sharling-lz.github.io/" target="_blank">Lin Zhao</a><sup>1</sup>&emsp;
        <a href="https://scholar.google.com/citations?user=N1Y-n5EAAAAJ&hl=en" target="_blank">Di Wang</a><sup>2</sup>&emsp;
        <a href="https://gcatnjust.github.io/ChenGong/index.html" target="_blank">Chen Gong</a><sup>3</sup>&emsp;
        <a href="https://scholar.google.com.sg/citations?user=61LOyWUAAAAJ&hl=en" target="_blank">Le Zhang</a><sup>4</sup>
    </div>
    <div>
        <sup>1</sup>School of Computer Science and Engineering, Nanjing University of Science and Technology
    </div>
    <div>
        <sup>2</sup>School of Computer Science and Technology, Xidian University
    </div>
    <div>
        <sup>3</sup>School of Automation and Intelligent Sensing, Shanghai Jiao Tong University
    </div>
    <div>
        <sup>4</sup>School of Information and Communication Engineering, University of Electronic Science and Technology of China
    </div>
</div>

<br>

<p align="justify">
We propose SynHMR, a single-frame LiDAR-based human mesh reconstruction framework for robust human understanding from sparse point clouds. Existing methods usually follow a decoupled pipeline that first estimates skeletal joints and then reconstructs the mesh, which may propagate pose errors under sparse and incomplete LiDAR observations. To address this issue, SynHMR performs synergistic joint-mesh modeling by representing both skeletal joints and sampled mesh vertices as queries. A Geometry-Aware Transformer enables bidirectional interaction between joint and vertex queries, where skeletal guidance helps mesh reconstruction and surface constraints help correct joint estimation. We further introduce a Noise-Augmented Learning strategy to improve robustness during training. Extensive experiments on LiDARHuman26M, SLOPER4D, and Human-M3 demonstrate that SynHMR achieves state-of-the-art performance among LiDAR-based human mesh reconstruction methods.
</p>



## SynHMR Framework

![Paper](/framework.png)

## 📣 News

- [2026/06] SynHMR has been accepted to ECCV 2026! 🎉🎉Code, additional qualitative results, and videos will be released soon!
