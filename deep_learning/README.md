## Deep Learning

### Semantic Segmentation

| Paper| Notes | Author | Summary |
|:-----:|:-----:|:-----:|:----------:|
| [Gated-SCNN: Gated Shape CNNs for Semantic Segmentation](http://openaccess.thecvf.com/content_ICCV_2019/html/Takikawa_Gated-SCNN_Gated_Shape_CNNs_for_Semantic_Segmentation_ICCV_2019_paper.html) (ICCV '19) | [HackMD](https://hackmd.io/tXDEyCEcTmqgaR75Gno0Mw) | [Akshay](https://akshayk07.weebly.com/) | This paper presents a 2-stream CNN i.e. one stream is normal CNN (classical stream) while the other is a shape stream, which explicitly processes shape information in a separate stream. |
| [ENet: A Deep Neural Network Architecture for Real-Time Semantic Segmentation](https://arxiv.org/abs/1606.02147) | [HackMD](https://hackmd.io/5jM_pajoSnS6LoZkdech8A) | [Akshay](https://akshayk07.weebly.com/) | This paper presents a network architecture which is faster and more compact, for low real-time inference times. |
| [W-Net: A Deep Model for Fully Unsupervised Image Segmentation](https://arxiv.org/abs/1711.08506) | [HackMD](https://hackmd.io/mNcCcyMFRuGLQg97qfTJaQ) | [Akshay](https://akshayk07.weebly.com/) | This paper presents fully unsupervised semantic segmentation using deep networks and a soft version of Normalized Cut. |
| [Understanding Deep Learning Techniques for Image Segmentation](https://arxiv.org/abs/1907.06119) | [HackMD](https://hackmd.io/RcL7gzVTTLCfJa1LGJGmZg) | [Akshay](https://akshayk07.weebly.com/) | This paper aims to provide an intuitive understanding of significant DL-based approaches to segmentation. |
| [Recent progress in semantic image segmentation](https://arxiv.org/ftp/arxiv/papers/1809/1809.10198.pdf) | [HackMD](https://hackmd.io/UpB9AC5CT0yTUmxGIsIArw) | [Akshay](https://akshayk07.weebly.com/) | This paper presents a review on semantic segmentation approaches - traditional as well as DL-based. |

### Domain Adaptation


| Paper| Notes | Author | Summary |
|:-----:|:-----:|:-----:|:----------:|
| [DACS: Domain Adaptation via Cross-domain Mixed Sampling](https://arxiv.org/abs/2007.08702) | [HackMD](https://hackmd.io/@akshayk07/ByhfvJ7XP) | [Akshay](https://akshayk07.weebly.com/) | This paper proposes Domain Adaptation via Cross-domain Mixed Sampling which mixes images from two domains along with their corresponding labels. These mixed samples are trained on, along with the labelled data itself. |
| [Learning Texture Invariant Representation for Domain Adaptation of Semantic Segmentation](https://openaccess.thecvf.com/content_CVPR_2020/html/Kim_Learning_Texture_Invariant_Representation_for_Domain_Adaptation_of_Semantic_Segmentation_CVPR_2020_paper.html) (CVPR '20) | [HackMD](https://hackmd.io/@akshayk07/B167fmyGD) | [Akshay](https://akshayk07.weebly.com/) | This paper uses style transfer to enforce texture invariance in the model, followed by self training to adapt to the target domain texture for the semantic segmentation task. |
| [Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision](https://arxiv.org/abs/2004.07703) (CVPR '20 Oral) | [HackMD](https://hackmd.io/@akshayk07/SkwXI-jkP) | [Akshay](https://akshayk07.weebly.com/) | This paper proposes a two-step self-supervised DA approach to minimize the inter-domain and intra-domain gap together. |
| [Unsupervised Domain Adaptation with Residual Transfer Networks](https://papers.nips.cc/paper/6110-unsupervised-domain-adaptation-with-residual-transfer-networks.pdf) (NIPS '16) | [HackMD](https://hackmd.io/@akshayk07/S1O9iopRU) | [Akshay](https://akshayk07.weebly.com/) | A domain adaptation approach that can jointly learn adaptive classifiers and transferable features from labeled data in the source domain and unlabeled data in the target domain. |
| [Phase Consistent Ecological Domain Adaptation](https://openaccess.thecvf.com/content_CVPR_2020/html/Yang_Phase_Consistent_Ecological_Domain_Adaptation_CVPR_2020_paper.html) (CVPR '20) | [HackMD](https://hackmd.io/@akshayk07/HkRSZC00I) | [Akshay](https://akshayk07.weebly.com/) | This paper introduces 2 criteria to regularize the optimization involved in UDA: (1) the map between 2 image domains should be phase-preserving and (2) to leverage regularities in the scene, regardless of the illuminant or imaging sensor. |
| [FDA: Fourier Domain Adaptation for Semantic Segmentation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_FDA_Fourier_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2020_paper.pdf) (CVPR '20) | [HackMD](https://hackmd.io/@akshayk07/SkktSZC0L) | [Akshay](https://akshayk07.weebly.com/) | A simple method for UDA where the discrepancy between the source and target distributions is reduced by swapping the low-frequency spectrum of one with the other. |
| [Domain Adaptation for Structured Output via Discriminative Patch Representations](https://arxiv.org/abs/1901.05427) (ICCV '19) | [HackMD](https://hackmd.io/Nh2sTmn1RpSeytghA6E2JQ) | [Akshay](https://akshayk07.weebly.com/) | This paper proposes a UDA approach that explicitly discovers many modes in the structured output space of semantic segmentation to learn a better discriminator between the 2 domains, ultimately leading to a better domain alignment. |

### Knowledge Distillation


| Paper| Notes | Author | Summary |
|:-----:|:-----:|:-----:|:----------:|
| [Distilling the Knowledge in a Neural Network](https://arxiv.org/pdf/1503.02531.pdf) (NIPS '14W) | [HackMD](https://hackmd.io/AntG2tWLQw-dflF5Y1fXig) | [Raj](https://github.com/RajGhugare19) | This paper is the first DL approach to transfer knowledge from a teacher network to a student network, and uses softened outputs of the teacher network for training the student network. |
| [A Gift from Knowledge Distillation: Fast Optimization, Network Minimization and Transfer Learning](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yim_A_Gift_From_CVPR_2017_paper.pdf) (CVPR '17) | [HackMD](https://hackmd.io/@akshayk07/rkj6RFc28) | [Akshay](https://akshayk07.weebly.com/) | This paper formulates the knowledge to be transferred in terms of flow between layers, calculates it as the inner product between feature maps from 2 layers, and uses this for Knowledge Distillation. |
| [Paying More Attention to Attention: Improving the Performance of Convolutional Neural Networks via Attention Transfer](https://arxiv.org/abs/1612.03928) (ICLR '17) | [HackMD](https://hackmd.io/@akshayk07/BkzGciz38) | [Akshay](https://akshayk07.weebly.com/) | This paper defines attention for CNNs, and uses it to improve the performance of a student CNN network by forcing it to mimic the attention maps of a powerful teacher network. |
| [Active Mixup for Data-Efficient Knowledge Distillation from a Blackbox Model](https://arxiv.org/abs/2003.13960) (CVPR '20) | [HackMD](https://hackmd.io/nwM8AKmtStGStXbRWVQnrg) | [Akshay](https://akshayk07.weebly.com/) | This paper proposes to blend active learning ([Gissin and Shalev-Shwartz, 2019](https://arxiv.org/abs/1907.06347)) and image mixup ([Zhang et. al. 2017](https://arxiv.org/abs/1710.09412)) to tackle data-efficient knowledge distillation from a blackbox teacher model. |
| [Data-Free Learning of Student Networks](https://arxiv.org/abs/1904.01186) (ICCV '19) | [HackMD](https://hackmd.io/LMTITxOtSlmrLi877J3Ntg) | [Akshay](https://akshayk07.weebly.com/) | The pre-trained teacher network is considered as a fixed discriminator and a generator generates training samples which can obtain maximum response from the discriminator. Simultaneously, a smaller network is trained using the generated data and the teacher network. |

### Active Learning

| Paper| Notes | Author | Summary |
|:-----:|:-----:|:-----:|:----------:|
| [Variational Adversarial Active Learning](https://arxiv.org/abs/1904.00370) (ICCV '19) | [HackMD](https://hackmd.io/CxZNGh6dS3m2axmP50iN8g) | [Akshay](https://akshayk07.weebly.com/) | This paper introduces a pool-based active learning strategy which learns a low dimensional latent space from labeled and unlabeled data using a VAE. |

### Feature Detection and Description
| Paper| Notes | Author | Summary |
|:-----:|:-----:|:-----:|:----------:|
| [D2 Net - A Trainable CNN for Joint Description and Detection of Local Features](https://arxiv.org/abs/1905.03561) (CVPR '19) | [HackMD](https://hackmd.io/@AniketGujarathi/SywvV8iQD) | [Aniket Gujarathi](https://www.linkedin.com/in/aniket-gujarathi/?originalSubdomain=in) | This paper introduces a Deep Learning based approach to solve the problem of local features detection and description using the detect-and-describe approach instead of the traditionally used detect-then-describe approach. |
