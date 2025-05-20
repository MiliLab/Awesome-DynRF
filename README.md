# Awesome-DynRF
Complete bibliographic list for Paper: "Advances in Radiance Field for Dynamic Scene: From Neural Field to Gaussian Field".

# Abstract
Dynamic scene representation and reconstruction have undergone transformative advances in recent years, catalyzed by breakthroughs in neural radiance fields and 3D Gaussian splatting techniques. While initially developed for static environments, these methodologies have rapidly evolved to address the complexities inherent in 4D dynamic scenes through an expansive body of research. Coupled with innovations in differentiable volumetric rendering, these approaches have significantly enhanced the quality of motion representation and dynamic scene reconstruction, thereby garnering substantial attention from the computer vision and graphics communities. This survey presents a systematic analysis of over 200 papers focused on dynamic scene representation using radiance field, spanning the spectrum from implicit neural representations to explicit Gaussian primitives. We categorize and evaluate these works through multiple critical lenses: motion representation paradigms, reconstruction techniques for varied scene dynamics, auxiliary information integration strategies, and regularization approaches that ensure temporal consistency and physical plausibility. We organize diverse methodological approaches under a unified representational framework, concluding with a critical examination of persistent challenges and promising research directions. By providing this comprehensive overview, we aim to establish a definitive reference for researchers entering this rapidly evolving field while offering experienced practitioners a systematic understanding of both conceptual principles and practical frontiers in dynamic scene reconstruction.

# Framework
[Survey](#survey)

[Reconstruction with Rigid Motion](#reconstruction-with-rigid-motion)

[Reconstruction with Articulated Motion](#reconstruction-with-articulated-motion)

[Reconstruction with Nor-rigid Motion](#reconstruction-with-nor-rigid-motion)

[Reconstruction with Hybrid Motion](#reconstructing-with-hybrid-motion)

# Survey
### perprint
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|
|[Differentiable rendering: A survey](https://arxiv.org/abs/2006.12057)                                                                             | arXiv2020 | | Survey |
|[Neural volume rendering: Nerf and beyond](https://arxiv.org/abs/2101.05204)                                                                       | arXiv2020 | | Survey |
|[Nerf: Neural radiance field in 3d vision, a comprehensive review](https://arxiv.org/abs/2210.00379)                                               | arXiv2022 | | Survey |
|[BeyondPixels: A comprehensive review of the evolution of neural radiance fields](https://ui.adsabs.harvard.edu/abs/2023arXiv230603000S/abstract)  | arXiv2023 | | Survey |
|[Neural radiance fields: Past, present, and future](https://arxiv.org/abs/2304.10050)                                                              | arXiv2023 | | Survey |
|[A survey on 3d gaussian splatting](https://arxiv.org/abs/2401.03890)                                                                              | arXiv2024 | | Survey |
|[3d gaussian as a new vision era: A survey](https://ui.adsabs.harvard.edu/abs/2024arXiv240207181F/abstract)                                        | arXiv2024 | | Survey |
|[Semantically-aware neural radiance fields for visual scene understanding: A comprehensive review](https://arxiv.org/abs/2402.11141)               | arXiv2024 | | Survey |
|[Neural Radiance Field in Urban: A Survey](https://arxiv.org/abs/2404.13816)                                                          | arXiv2024 | | Survey |
|[How nerfs and 3d gaussian splatting are reshaping slam: A survey](https://fabiotosi92.github.io/files/survey-slam.pdf)                            | arXiv2024 | | Survey |
|[NeRF in robotics: A survey](https://arxiv.org/abs/2405.01333)                                                                                     | arXiv2024 | | Survey |
|[Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220)                                                                            | arXiv2024 | | Survey |

### Paper
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|
|[Neural fields in visual computing and beyond](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14505)                      |Computer Graphics Forum 2022   | | Survey |
|[3d gaussian splatting as new era: A survey](https://ieeexplore.ieee.org/abstract/document/10521791/?casa_token=0QyGxTRXcuoAAAAA:lcs7VXV5u9xntc4wQtFBjAejlh5aAHHDboeQDN1aQu-SPdVgZRMB1341gfWlt7iKSB7N2Eg2moE)                        | IEEE TVCG 2024                | | Survey |
|[Recent advances in 3d gaussian splatting](https://link.springer.com/article/10.1007/s41095-024-0436-y)                        |Computational Visual Media 2024| | Survey |
|[3d gaussian splatting: Survey, technologies, challenges, and opportunities](https://ieeexplore.ieee.org/abstract/document/10870258/?casa_token=sf77HC5Y85sAAAAA:2ukklYMHulxMaKfBV-AH9I0ZpOrnj8tcGv3cAZGp_5d5H7dWAw7yjjIy4RT1Ln5vG5Q0gr7e168)                        | IEEE TCSVT 2025               | | Survey |
|[Gaussian splatting: 3d reconstruction and novel view synthesis, a review](https://ieeexplore.ieee.org/abstract/document/10545567/)| IEEE Access 2024          | | Survey |
|[Human 3d avatar modeling with implicit neural representation: A brief survey](https://ieeexplore.ieee.org/abstract/document/10218567/?casa_token=eqD5GGUIgHcAAAAA:kqCuDuxbKgYy5Ndn6Qu2ORYScL62HXkLSNAhcLNyOXZCNwQykukvkhk1mhgoaCos4H_gTrZGG0aJGA)                         | ICSPS 2022                | | Survey |
|[Benchmarking neural radiance fields for autonomous robots: An overview](https://www.sciencedirect.com/science/article/pii/S0952197624018438?casa_token=lUGEAcODULoAAAAA:RoeYzcwQpI4VUAsp6zAnrwWX7ipHVRyi3V1JsCl9JaKDAHQZdAiATK8sxLBzmtPLlVhyC57awT4)                            | EAAI 2025                 | | Survey |
|[Recent Trends in 3D Reconstruction of General Non-Rigid Scenes](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.15062)        | CGF 2024                  | | Survey |
|[State of the Art in Dense Monocular Non-Rigid 3D Reconstruction](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14774)       | CGF 2023                  | | Survey |
|[Neural radiance fields in the industrial and robotics domain: Applications, research opportunities and use cases](https://www.sciencedirect.com/science/article/pii/S0736584524000978?casa_token=IbEL6IFsBrcAAAAA:N1ijHI5IXgjmtYh0WVADDM4OBXoHsdAMhef9VZohHdghCTMo-8QBBfCvPgbASBFib8yr_ywZRg)           | RCIM 2024                 | | Survey |
|[A Brief Review on Differentiable Rendering: Recent Advances and Challenges](https://www.mdpi.com/2079-9292/13/17/3546)            | Electronics 2024          | | Survey |

# Reconstruction with Rigid Motion
### perprint
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|
|[Prosgnerf: Progressive dynamic neural scene graph with frequency modulated auto-encoder in urban scenes](https://arxiv.org/abs/2312.09076)     |Arxiv 2023| |Urban       |

### Paper
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|
|[Street gaussians: Modeling dynamic urban scenes with gaussian splatting](https://arxiv.org/abs/2401.01339)                                                  |ECCV 2024   |[Code](https://github.com/zju3dv/street_gaussians)                                                                                                            |Urban       |
|[Neural scene graphs for dynamic scenes ](http://openaccess.thecvf.com/content/CVPR2021/html/Ost_Neural_Scene_Graphs_for_Dynamic_Scenes_CVPR_2021_paper.html)                                                                                                                                                         |CVPR 2021   |[Code](https://github.com/princeton-computational-imaging/neural-scene-graphs)                                                                                |Urban       |
|[Multi-level neural scene graphs for dynamic urban environments](http://openaccess.thecvf.com/content/CVPR2024/html/Fischer_Multi-Level_Neural_Scene_Graphs_for_Dynamic_Urban_Environments_CVPR_2024_paper.html)                                                                  |CVPR 2024   |[Code](https://github.com/tobiasfshr/map4d)                                                                                                                   |Urban       |
|[3d geometry-aware deformable gaussian splatting for dynamic view synthesis](http://openaccess.thecvf.com/content/CVPR2024/html/Lu_3D_Geometry-Aware_Deformable_Gaussian_Splatting_for_Dynamic_View_Synthesis_CVPR_2024_paper.html)                                                           |CVPR 2024   |[Code](https://github.com/zhichengLuxx/GaGS)                                                                                                                  |Urban       |
|[Star: Selfsupervised tracking and reconstruction of rigid objects in motion with neural rendering](http://openaccess.thecvf.com/content/CVPR2021/html/Yuan_STaR_Self-Supervised_Tracking_and_Reconstruction_of_Rigid_Objects_in_Motion_CVPR_2021_paper.html)                                                   |CVPR 2021||Indoor|
|[Panoptic neural fields: A semantic object-aware neural scene representation](http://openaccess.thecvf.com/content/CVPR2022/html/Kundu_Panoptic_Neural_Fields_A_Semantic_Object-Aware_Neural_Scene_Representation_CVPR_2022_paper.html)                                                    |CVPR 2022||Urban|
|[Hugs: Holistic urban 3d scene understanding via gaussian splatting](http://openaccess.thecvf.com/content/CVPR2024/html/Zhou_HUGS_Holistic_Urban_3D_Scene_Understanding_via_Gaussian_Splatting_CVPR_2024_paper.html)                     |CVPR 2024|[Code](https://github.com/hyzhou404/HUGS)|Urban|
|[S-nerf: Neural radiance fields for street views](https://openreview.net/forum?id=gx2yJS-ENqI)                |ICLR 2023|[Code](https://github.com/fudan-zvg/S-NeRF)|Urban|
|[Drivinggaussian: Composite gaussian splatting for surrounding dynamic autonomous driving scenes](http://openaccess.thecvf.com/content/CVPR2024/html/Zhou_DrivingGaussian_Composite_Gaussian_Splatting_for_Surrounding_Dynamic_Autonomous_Driving_Scenes_CVPR_2024_paper.html)                                        |CVPR 2024|[Code](https://github.com/VDIGPKU/DrivingGaussian)                                                                                                             |Urban      |
|[Unisim: A neural closedloop sensor simulator](http://openaccess.thecvf.com/content/CVPR2023/html/Yang_UniSim_A_Neural_Closed-Loop_Sensor_Simulator_CVPR_2023_paper.html)|CVPR 2023| [Project Site](https://waabi.ai/unisim/)|Urban|
|[Neurad: Neural rendering for autonomous driving](http://openaccess.thecvf.com/content/CVPR2024/html/Tonderski_NeuRAD_Neural_Rendering_for_Autonomous_Driving_CVPR_2024_paper.html)                          |CVPR 2024|[Code](https://github.com/georghess/neurad-studio)|Urban|

# Reconstruction with Articulated Motion
## Human Body
### perprint 
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|


### Paper
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|



## Hand
### perprint
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|


### Paper
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|




## Animal
### perprint
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|


### Paper
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|



## Other Objects
### perprint
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|


### Paper
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|



# Reconstruction with Nor-rigid Motion
## 4D Spacetime
### perprint
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|


### Paper
| **Paper**                                                                                                             | **Conference/Journal** |**Code**    |**Type**    |
|-----------------------------------------------------------------------------------------------------------------------|------------------------|------------|------------|

## Canonical Space with Deformation Field
## Frame-to-Frame Flow Field
## Point Tracking
## Factorization

# Reconstructing with Hybrid Motion
