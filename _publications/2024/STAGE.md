---
title:          "STAGE：基于多时空任务GAN的轨迹生成"
date:           2024-05-12 00:01:01 +0800
selected:       false
pub:            "International Journal of Geographical Information Science (IJGIS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  人的移动行为具有一些显著模式和特征。例如，城市中个体通常具有一定的日常活动规律（例如，晚上居家、白天工作），形成特定的时序模式；轨迹可使用不同粒度的空间单元表达，而不同尺度下生成的轨迹应当具有空间一致性（例如，1公里网格应当是相应2公里网格的一部分）。上述模式和特征可以从轨迹中直接获取，并将其视为轨迹固有的显式时空知识，通过多任务学习来指导轨迹生成过程。
基于上述分析，本团队创新性提出一种时空知识增强的多任务生成对抗网络——STAGE (Spatiotemporal-knowledge enhanced multi-TAsk GEnerative adversarial network)用于生成大规模个体时空轨迹。STAGE主要采用GAN架构，由生成器和判别器两部分组成。生成器包含三个分阶段的时空生成任务，依次是①个体活动序列生成、②街道层面（粗粒度）的个体轨迹生成和③社区层面（细粒度）的个体轨迹生成。其中，社区层面（细粒度）的轨迹生成为主任务，其余两个为辅任务。判别器主要用于鉴别所生成轨迹的真实度。此外，本文在对抗训练阶段设计了空间一致性损失函数，以约束不同尺度下生成的轨迹在空间上保持一致。STAGE所生成的轨迹数据与真实数据更加接近，不但在下游任务中具有较好可用性，且通过了隐私泄露测试。
cover:          /assets/images/covers/STAGE.jpg
authors:
  - Zhongcai Cao
  - Kang Liu*
  - Li Ning
  - Ling Yin
  - Feng Lu
links:
  Paper: https://www.tandfonline.com/doi/full/10.1080/13658816.2024.2381146
---
