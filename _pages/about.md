---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<section class="profile-hero" markdown="1">
<p class="profile-eyebrow">Postdoctoral Researcher at City University of Hong Kong</p>

# Zhiwei Zhong

Zhiwei Zhong received his Ph.D. from the Faculty of Computing, Harbin Institute of Technology (HIT), supervised by Professor [Xianming Liu](https://homepage.hit.edu.cn/xmliu?lang=en) and Professor [Debin Zhao](https://homepage.hit.edu.cn/zhaodebin). He is currently a postdoctoral researcher at City University of Hong Kong (CityU) under the supervision of Professor [Shiqi Wang](https://www.cs.cityu.edu.hk/~shiqwang/). His research focuses on computer vision and image processing, especially image restoration, guided image super-resolution, depth map super-resolution, and deep learning.

<div class="profile-links">
  <a href="#publications">Selected Publications</a>
  <a href="#competitions">Competitions</a>
  <a href="#honors">Honors</a>
</div>
</section>

<span class='anchor' id='news'></span>

# News
<ul class="news-list">
  <li><span>2026.06</span> One paper, "Event-driven Motion Deblurring via Trajectory-based Kernel Reconstruction", has been accepted by ECCV 2026.</li>
  <li><span>2026.06</span> We achieved 2nd place in Track 2 at the IEEE/CVF PBVS 2026 Thermal Image Super-Resolution Challenge.</li>
  <li><span>2026.05</span> One paper, "Dual Graph Regularized Deep Unfolding Network for Guided Depth Map Super-Resolution", has been accepted by IEEE CVPR 2026.</li>
  <li><span>2025.06</span> One paper, "Dual-Level Cross-Modality Neural Architecture Search for Guided Image Super-Resolution", has been accepted by IEEE TPAMI.</li>
  <li><span>2025.06</span> We achieved 1st place in Track 2-x8 PSNR at the IEEE CVPR 2025 PBVS <a href="https://openaccess.thecvf.com/content/CVPR2025W/PBVS/papers/Rivadeneira_Thermal_Image_Super-Resolution_Challenge_Results_-_PBVS_2025_CVPRW_2025_paper.pdf">Thermal Image Super-Resolution Challenge</a>.</li>
  <li><span>2024.06</span> We achieved 1st place in Track 1 and Track 2 at the IEEE CVPR 2024 PBVS Thermal Image Super-Resolution Challenge.</li>
  <li><span>2023.06</span> We achieved 1st place in Track 1 and Track 2 at the IEEE CVPR 2023 PBVS Thermal Image Super-Resolution Challenge.</li>
</ul>

<span class='anchor' id='publications'></span>

# Selected Publications
<p class="section-note">First-author and primary research works are listed below.</p>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><a href="files/event-driven-motion-deblurring-eccv2026.pdf"><img src='images/eccv2026-deblurring.png' alt="Event-driven motion deblurring overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Event-driven Motion Deblurring via Trajectory-based Kernel Reconstruction](files/event-driven-motion-deblurring-eccv2026.pdf)

<p class="pub-meta"><strong>Zhiwei Zhong</strong>, Peilin Chen, Wei Dong, Bo Li, Anmin Liu, Shiqi Wang</p>

<p class="paper-links"><a href="files/event-driven-motion-deblurring-eccv2026.pdf">PDF</a></p>
<p class="paper-summary">A physically grounded event-driven framework that reconstructs trajectory-based blur kernels for non-uniform motion deblurring.</p>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE CVPR 2026</div><a href="files/dual-graph-regularized-deep-unfolding-network.pdf"><img src='images/lapnet.png' alt="Dual graph regularized unfolding network overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Dual Graph Regularized Deep Unfolding Network for Guided Depth Map Super-Resolution](files/dual-graph-regularized-deep-unfolding-network.pdf)

<p class="pub-meta"><strong>Zhiwei Zhong</strong>, Peilin Chen, Qiangqiang Shen, Bo Li, Shiqi Wang</p>

<p class="paper-links"><a href="files/dual-graph-regularized-deep-unfolding-network.pdf">PDF</a> <a href="https://github.com/zhwzhong/LAPNet">GitHub</a></p>
<p class="paper-summary">Efficiently unfolds graph optimization into a deep neural network for guided depth map super-resolution.</p>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TPAMI 2025</div><a href="files/dual-level-cross-modality-nas-guided-image-sr.pdf"><img src='images/dcnas.png' alt="Dual-level cross-modality NAS overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Dual-Level Cross-Modality Neural Architecture Search for Guided Image Super-Resolution](files/dual-level-cross-modality-nas-guided-image-sr.pdf)

<p class="pub-meta"><strong>Zhiwei Zhong</strong>, Xianming Liu, Junjun Jiang, Debin Zhao, Shiqi Wang</p>

<p class="paper-links"><a href="files/dual-level-cross-modality-nas-guided-image-sr.pdf">PDF</a> <a href="https://github.com/zhwzhong/DCNAS">GitHub</a> <a href="https://ieeexplore.ieee.org/document/11029618">Publisher</a></p>
<p class="paper-summary">The first neural architecture search method for guided depth map super-resolution.</p>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM CSUR 2023</div><a href="files/guided-depth-map-super-resolution-survey.pdf"><img src='images/survey.png' alt="Guided depth map super-resolution survey overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Guided Depth Map Super-Resolution: A Survey](files/guided-depth-map-super-resolution-survey.pdf)

<p class="pub-meta"><strong>Zhiwei Zhong</strong>, Xianming Liu, Junjun Jiang, Debin Zhao, Xiangyang Ji</p>

<p class="paper-links"><a href="files/guided-depth-map-super-resolution-survey.pdf">PDF</a> <a href="https://github.com/zhwzhong/Guided-Depth-Map-Super-resolution-A-Survey">GitHub</a> <a href="https://dl.acm.org/doi/10.1145/3584860">Publisher</a></p>
<p class="paper-summary">A comprehensive survey and benchmark for guided depth map super-resolution.</p>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNNLS 2023</div><a href="files/deep-attentional-guided-image-filtering.pdf"><img src='images/tnnls.png' alt="Deep attentional guided image filtering overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Deep Attentional Guided Image Filtering](files/deep-attentional-guided-image-filtering.pdf)

<p class="pub-meta"><strong>Zhiwei Zhong</strong>, Xianming Liu, Junjun Jiang, Debin Zhao, Xiangyang Ji</p>

<p class="paper-links"><a href="files/deep-attentional-guided-image-filtering.pdf">PDF</a> <a href="https://github.com/zhwzhong/DAGF">GitHub</a> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10089494">Publisher</a></p>
<p class="paper-summary">A learning-based multi-scale image filtering framework for guided image filtering.</p>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIP 2022</div><a href="files/high-resolution-depth-maps-imaging-ahmf.pdf"><img src='images/tip.png' alt="Attention-based hierarchical multi-modal fusion overview" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[High-Resolution Depth Maps Imaging via Attention-Based Hierarchical Multi-Modal Fusion](files/high-resolution-depth-maps-imaging-ahmf.pdf)

<p class="pub-meta"><strong>Zhiwei Zhong</strong>, Xianming Liu, Junjun Jiang, Debin Zhao, Zhiwen Chen, Xiangyang Ji</p>

<p class="paper-links"><a href="files/high-resolution-depth-maps-imaging-ahmf.pdf">PDF</a> <a href="https://github.com/zhwzhong/AHMF">GitHub</a> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9642435">Publisher</a></p>
<p class="paper-summary">An attention-based hierarchical multi-modal fusion network for guided depth map super-resolution.</p>
</div>
</div>

<span class='anchor' id='competitions'></span>

# Selected Competitions

<div class='paper-box competition-box'><div class='paper-box-image'><div><div class="badge badge-award">CVPR PBVS 2026</div><a href="files/pbvs2026-track2-second-place-certificate.pdf"><img src='images/pbvs2026-track2-certificate.png' alt="PBVS 2026 Track 2 second place certificate" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[IEEE CVPR 2026 PBVS Thermal Image Super-Resolution Challenge - Track 2 Certificate](files/pbvs2026-track2-second-place-certificate.pdf)

<p class="pub-meta"><strong>2nd Place</strong>, Track 2, 7th Thermal Image Super-Resolution Challenge, IEEE/CVF PBVS Workshop</p>

<p class="paper-links"><a href="files/pbvs2026-track2-second-place-certificate.pdf">Certificate</a></p>
<p class="paper-summary">Certificate preview copied locally and linked directly to the PDF.</p>
</div>
</div>

<div class='paper-box competition-box'><div class='paper-box-image'><div><div class="badge badge-award">CVPR PBVS 2025</div><a href="files/pbvs2025-track2-x8-winner-certificate.pdf"><img src='images/pbvs2025-track2-x8-certificate.png' alt="PBVS 2025 Track 2 x8 winner certificate" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[IEEE CVPR 2025 PBVS Thermal Image Super-Resolution Challenge - Track 2 Certificate](files/pbvs2025-track2-x8-winner-certificate.pdf)

<p class="pub-meta"><strong>1st Place</strong>, Track 2-x8 PSNR, 6th Thermal Image Super-Resolution Challenge, IEEE CVPR 2025 PBVS Workshop</p>

<p class="paper-links"><a href="files/pbvs2025-track2-x8-winner-certificate.pdf">Certificate</a> <a href="https://openaccess.thecvf.com/content/CVPR2025W/PBVS/papers/Rivadeneira_Thermal_Image_Super-Resolution_Challenge_Results_-_PBVS_2025_CVPRW_2025_paper.pdf">Results</a></p>
<p class="paper-summary">Certificate preview copied locally and linked directly to the PDF.</p>
</div>
</div>

<div class='paper-box competition-box'><div class='paper-box-image'><div><div class="badge badge-award">CVPR PBVS 2024</div><a href="files/pbvs2024-track1-winner-certificate.pdf"><img src='images/pbvs2024-track1-certificate.png' alt="PBVS 2024 Track 1 winner certificate" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[IEEE CVPR 2024 PBVS Thermal Image Super-Resolution Challenge - Track 1 Certificate](files/pbvs2024-track1-winner-certificate.pdf)

<p class="pub-meta"><strong>1st Place</strong>, Track 1-PSNR/SSIM, 5th Thermal Image Super-Resolution Challenge, IEEE CVPR 2024 PBVS Workshop</p>

<p class="paper-links"><a href="files/pbvs2024-track1-winner-certificate.pdf">Certificate</a> <a href="https://codalab.lisn.upsaclay.fr/competitions/17013">Results</a></p>
<p class="paper-summary">Certificate preview copied locally and linked directly to the PDF.</p>
</div>
</div>

<div class='paper-box competition-box'><div class='paper-box-image'><div><div class="badge badge-award">CVPR PBVS 2024</div><a href="files/pbvs2024-track2-winner-certificate.pdf"><img src='images/pbvs2024-track2-certificate.png' alt="PBVS 2024 Track 2 winner certificate" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[IEEE CVPR 2024 PBVS Thermal Image Super-Resolution Challenge - Track 2 Certificate](files/pbvs2024-track2-winner-certificate.pdf)

<p class="pub-meta"><strong>1st Place</strong>, Track 2-PSNR/SSIM, 5th Thermal Image Super-Resolution Challenge, IEEE CVPR 2024 PBVS Workshop</p>

<p class="paper-links"><a href="files/pbvs2024-track2-winner-certificate.pdf">Certificate</a> <a href="https://codalab.lisn.upsaclay.fr/competitions/9666#results">Results</a></p>
<p class="paper-summary">Certificate preview copied locally and linked directly to the PDF.</p>
</div>
</div>

<div class='paper-box competition-box'><div class='paper-box-image'><div><div class="badge badge-award">CVPR PBVS 2023</div><a href="files/pbvs2023-track1-winner-certificate.pdf"><img src='images/pbvs2023-track1-certificate.png' alt="PBVS 2023 Track 1 winner certificate" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[IEEE CVPR 2023 PBVS Thermal Image Super-Resolution Challenge - Track 1 Certificate](files/pbvs2023-track1-winner-certificate.pdf)

<p class="pub-meta"><strong>1st Place</strong>, Track 1-Evaluation1-SSIM, 4th Thermal Image Super-Resolution Challenge, IEEE CVPR 2023 PBVS Workshop</p>

<p class="paper-links"><a href="files/pbvs2023-track1-winner-certificate.pdf">Certificate</a> <a href="https://codalab.lisn.upsaclay.fr/competitions/9666#results">Results</a></p>
<p class="paper-summary">Certificate preview copied locally and linked directly to the PDF.</p>
</div>
</div>

<div class='paper-box competition-box'><div class='paper-box-image'><div><div class="badge badge-award">CVPR PBVS 2023</div><a href="files/pbvs2023-track2-winner-certificate.pdf"><img src='images/pbvs2023-track2-certificate.png' alt="PBVS 2023 Track 2 winner certificate" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[IEEE CVPR 2023 PBVS Thermal Image Super-Resolution Challenge - Track 2 Certificate](files/pbvs2023-track2-winner-certificate.pdf)

<p class="pub-meta"><strong>1st Place</strong>, Track 2-Evaluation-PSNR/SSIM, 4th Thermal Image Super-Resolution Challenge, IEEE CVPR 2023 PBVS Workshop</p>

<p class="paper-links"><a href="files/pbvs2023-track2-winner-certificate.pdf">Certificate</a> <a href="https://codalab.lisn.upsaclay.fr/competitions/9666#results">Results</a></p>
<p class="paper-summary">Certificate preview copied locally and linked directly to the PDF.</p>
</div>
</div>

<div class='paper-box competition-box'><div class='paper-box-image'><div><div class="badge badge-award">ACM ICMR 2021</div><a href="files/acm-icmr2021-real-dsr-certificate.pdf"><img src='images/icmr2021-real-dsr-certificate.png' alt="ACM ICMR 2021 Real DSR Challenge winner certificate" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[ACM ICMR 2021 Real DSR Challenge - Winner Certificate](files/acm-icmr2021-real-dsr-certificate.pdf)

<p class="pub-meta"><strong>Winner</strong>, Stage 1 and Stage 2, ACM ICMR 2021 Real DSR Challenge</p>

<p class="paper-links"><a href="files/acm-icmr2021-real-dsr-certificate.pdf">Certificate</a> <a href="https://icmr21-realdsr-challenge.github.io/">Challenge Page</a></p>
<p class="paper-summary">Certificate copied locally from Chair.pdf; the PDF contains both Stage 1 and Stage 2 award pages.</p>
</div>
</div>

<span class='anchor' id='honors'></span>

# Honors and Awards
<ul class="award-list">
  <li><span>2026.06</span> <strong>2nd Place</strong>, IEEE/CVF PBVS Thermal Image Super-Resolution Challenge, Track 2.</li>
  <li><span>2025.06</span> <strong>Winner</strong>, IEEE CVPR 2025 PBVS Thermal Image Super-Resolution Challenge, <a href="https://openaccess.thecvf.com/content/CVPR2025W/PBVS/papers/Rivadeneira_Thermal_Image_Super-Resolution_Challenge_Results_-_PBVS_2025_CVPRW_2025_paper.pdf">Track 2-x8 PSNR</a>.</li>
  <li><span>2024.06</span> <strong>Winner</strong>, IEEE CVPR 2024 PBVS Thermal Image Super-Resolution Challenge, <a href="https://codalab.lisn.upsaclay.fr/competitions/17013">Track 1</a> and <a href="https://codalab.lisn.upsaclay.fr/competitions/9666#results">Track 2</a>.</li>
  <li><span>2023.06</span> <strong>Winner</strong>, IEEE CVPR 2023 PBVS Thermal Image Super-Resolution Challenge, <a href="https://codalab.lisn.upsaclay.fr/competitions/9666#results">Track 1 and Track 2</a>.</li>
  <li><span>2021.12</span> <strong>Winner</strong>, ACM ICMR 2021 Guided Depth Map Super-Resolution <a href="https://icmr21-realdsr-challenge.github.io/">Challenge</a>.</li>
  <li><span>Selected</span> National Scholarship, Heilongjiang Provincial Outstanding Student, Heilongjiang Provincial Outstanding Ph.D. Graduate, HIT Outstanding Ph.D. Graduate, Tencent Scholarship, HIT Outstanding Ph.D. Thesis Nomination ($10\%$).</li>
</ul>

<span class='anchor' id='experience'></span>

# Work Experience
- *2023.12 - (now)*, Postdoc Research, Department of Computer Science, City University of Hong Kong (CityU), HK, China.

<span class='anchor' id='education'></span>

# Education
- *2017.09 - 2023.09*, Ph.D., School of Computer Science and Technology, Harbin Institute of Technology (HIT), Harbin, China.
- *2013.09 - 2017.06*, Bachelor, School of Computer Science and Technology, Heilongjiang University, Harbin, China.

<span class='anchor' id='talks'></span>

# Invited Talks
- *2024.10*, Guided Image Super-resolution: From Traditional Methods to Deep Learning (Northeastern University, Shenyang, China).

<span class='anchor' id='internships'></span>

# Internships
- *2018.09 - 2023.12*, [Peng Cheng Laboratory](https://www.pcl.ac.cn/index.html), Shenzhen, China.
