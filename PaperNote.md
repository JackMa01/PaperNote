# Paper Note (Simplified)

---

### Rui Li, Qianfen Jiao, Wenming Cao, Hau-San Wong, Si Wu. Model Adaptation: Unsupervised Domain Adaptation without Source Data. In CVPR. 2020.

[[Abstract](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html)] [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.pdf)] [[Note](https://github.com/JackMa01/PaperNote/blob/main/PaperNote.md#rui-li-qianfen-jiao-wenming-cao-hau-san-wong-si-wu-model-adaptation-unsupervised-domain-adaptation-without-source-data-in-cvpr-2020)]

\<Transfer Learning\> \<Domain Adaptation\> \<Model Adaptation\>

\<Generation Based\> \<Unsupervised\> \<Unlabeled Target Data\> \<Source Data Free\> \<Source Model Available\> \<GAN\> \<Regularization\> \<Weight Regularization\> \<Clustering-based Regularization\> \<Pre-trained Source Model\> \<Collaborative Class Conditional GAN\> \<3C-GAN\> 

![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222135346.jpg)

$$
\min_{\theta_C}\lambda_g\ell_{gen}+\lambda_w\ell_{wReg}+\lambda_{clu}\ell_{cluReg}
$$


---

### Sk Miraj Ahmed, Dripta S. Raychaudhuri, Sujoy Paul, Samet Oymak, Amit K. Roy-Chowdhury. Unsupervised Multi-source Domain Adaptation Without Access to Source Data. In CVPR 2021.

[[Abstract](https://openaccess.thecvf.com/content/CVPR2021/html/Ahmed_Unsupervised_Multi-Source_Domain_Adaptation_Without_Access_to_Source_Data_CVPR_2021_paper.html)] [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Ahmed_Unsupervised_Multi-Source_Domain_Adaptation_Without_Access_to_Source_Data_CVPR_2021_paper.pdf)] [[Note](https://github.com/JackMa01/PaperNote/blob/main/PaperNote.md#sk-miraj-ahmed-dripta-s-raychaudhuri-sujoy-paul-samet-oymak-amit-k-roy-chowdhury-unsupervised-multi-source-domain-adaptation-without-access-to-source-data-in-cvpr-2021)]

\<Transfer Learning\> \<Domain Adaptation\> \<Model Adaptation\>

\<Self-training Based\> \<Multi-source\> \<Source Data Free\> \<Source Model Available\> \<Unsupervised\> \<Classifier Fixed\> \<Adapt Feature Maps\> \<Pseudo-labeling\> \<UDA\>

![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222141210.jpg)

![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222141656.jpg)

$$
\mathcal L_{tot}=\mathcal L_{ent}-\mathcal L_{div}+\lambda\mathcal L_{pl}
\\
\begin{aligned}
\mathop{minimize}_{\{\phi_S^j\}^n_{j=1},\{\alpha_j\}^n_{j=1}}\ \ \  & \mathcal L_{tot} \\
subject\ to \ \ \ & \alpha_j\ge0,\forall j\in\{1,2,...,n\},\\
& \sum_{j=1}^n\alpha_j=1
\end{aligned}
$$


---

### Junho Yim, Donggyu Joo, Jihoon Bae, Junmo Kim. A Gift from Knowledge Distillation: Fast Optimization, Network Minimization and Transfer Learning. In CVPR. 2017.

[[Abstract](https://openaccess.thecvf.com/content_cvpr_2017/html/Yim_A_Gift_From_CVPR_2017_paper.html)] [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Yim_A_Gift_From_CVPR_2017_paper.pdf)] [[Note](https://github.com/JackMa01/PaperNote/blob/main/PaperNote.md#junho-yim-donggyu-joo-jihoon-bae-junmo-kim-a-gift-from-knowledge-distillation-fast-optimization-network-minimization-and-transfer-learning-in-cvpr-2017)]

\<Model Compression\> \<Knowledge Distillation\> \<Knowledge Distillation\>

\<Knowledge Transfer\> \<FSP\> \<FSP Matrix\> \<Flow for Solving a Problem\> \<Flow Between Layers\> \<Two Stages of Training\> 

We define the distilled knowledge to be transferred in terms of flow between layers. We defined high-level distilled knowledge as **the flow for solving a problem**, the flow of solving a problem can be defined as **the relationship between features from two layers**.

![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222142316.png)

FSP Matrix:

$$
G_{i,j}(x;W)=\sum_{s=1}^h\sum_{t=1}^w\frac{F^1_{s,t,i}(x;W)\times F^2_{s,t,j}(x;W)}{h\times w}
$$

![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222142547.png)

$$
L_{FSP}(W_t,W_s)=\frac{1}{N}\sum_x\sum_{i=1}^n\lambda_i\times ||G^T_i(x;W_t)-G^S_i(x;W_s)||_2^2
$$


![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222142555.png)


---

### Shiran Zada, Itay Benou, Michal Irani. Pure Noise to the Rescue of Insufficient Data: Improving Imbalanced Classification by Training on Random Noise Images. In arXiv. 2021.

[[Abstract](https://arxiv.org/abs/2112.08810)] [[Paper](https://arxiv.org/pdf/2112.08810.pdf)] [[Note](https://github.com/JackMa01/PaperNote/blob/main/PaperNote.md#shiran-zada-itay-benou-michal-irani-pure-noise-to-the-rescue-of-insufficient-data-improving-imbalanced-classification-by-training-on-random-noise-images-in-arxiv-2021)]

\<Unclassified\> \<Unclassified\> \<Unclassified\>

\<Pure Noise Images\> \<Long-tail\> \<Long-tail Distribution\> \<Re-balanced Dataset\> \<Oversampling with Pure Noise Images\> \<OPeN\> \<Distribution-Aware Routing Batch Norm\> \<DAR-BN\> 

we propose **generating pure random noise images and using them as additional training data** (especially for minority classes). 

![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222143216.jpg)

![pic](https://mj-note.oss-cn-shanghai.aliyuncs.com/Windows/pic_20200428100628/paper_20211222143341.jpg)

---

