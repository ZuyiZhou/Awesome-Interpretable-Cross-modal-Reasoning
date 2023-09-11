# <p align=center>A Survey on Interpretable Cross-modal Reasoning


> [**A Survey on Interpretable Cross-modal Reasoning**](https://arxiv.org/abs/2309.01955)<br>
[Dizhan Xue](https://orcid.org/0000-0002-0173-1556)[Shengsheng Qian](https://orcid.org/0000-0001-9488-2208) [Zuyi Zhou](https://orcid.org/0009-0008-0306-8461) [Changsheng Xu]
> **<p align="justify"> Abstract:** *In recent years, cross-modal reasoning (CMR), the process of understanding and reasoning across different modalities, has emerged as a  pivotal area with applications spanning from multimedia analysis to healthcare diagnostics. As the deployment of AI systems becomes  more ubiquitous, the demand for transparency and comprehensibility in these systems’ decision-making processes has intensified. This survey delves into the realm of interpretable cross-modal reasoning (I-CMR), where the objective is not only to achieve high  predictive performance but also to provide human-understandable explanations for the results. This survey presents a comprehensive  overview of the typical methods with a three-level taxonomy for I-CMR. Furthermore, this survey reviews the existing CMR datasets  with annotations for explanations. Finally, this survey summarizes the challenges for I-CMR and discusses potential future directions. In conclusion, this survey aims to catalyze the progress of this emerging research area by providing researchers with a panoramic and  comprehensive perspective, illuminating the state of the art and discerning the opportunities.* </p>

##  Citation

If you find this paper and repo helpful for your research, please cite it as below:

```bibtex
@misc{xue2023survey,
      title={A Survey on Interpretable Cross-modal Reasoning}, 
      author={Dizhan Xue and Shengsheng Qian and Zuyi Zhou and Changsheng Xu},
      year={2023},
      eprint={2309.01955},
      archivePrefix={arXiv},
      primaryClass={cs.AI}
}

```
## <span id="head-content"> *Content* </span>
* - [x] [1. Introduction](#headIntro)

* - [ ] [2. Methods for interpretable cross-modal reasoning](#headtax)
  * - [x] [2.1 Methods of Visual Explanation](#head-1)
  * - [x] [2.2 Methods of Textual Explanation](#head-2)  
  * - [x] [2.3 Methods of Graph Explanation](#head-3)
  * - [x] [2.4 Methods of Symbol Explanation](#head-4)
  * - [x] [2.5 Methods of Multimodal Explanation](#head-5)
  
  
* - [ ] [3. Datasets](#headda)  
  * - [x] [Oxford-102 Flower](#head-flower)
  * - [x] [Caltech-UCSD Bird (CUB)](#head-cub)
  * - [x] [MS-COCO](#head-coco)


* [*Contact Us*](#head7)
## <span id="headIntro"> *1. Description* </span>

* ...

* Papers, codes, and datasets for the text-to-image task are available here.


## <span id="headtax"> *2. Methods for interpretable cross-modal reasoning* </span> [       «🎯Back To Top»       ](#)

### <span id="head-1"> *2.1 Methods of Visual Explanation* </span>

**Murel: Multimodal relational reasoning for visual question answering** [CVPR 2019] <br>
Remi Cadene, Hedi Ben-Younes, Matthieu Cord, and Nicolas Thome.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/8953864)[[Code]](https://github.com/Cadene/murel.bootstrap.pytorch)

**Reasoning on the relation: Enhancing visual representation for visual question answering and cross-modal retrieval** [IEEE Transactions on Multimedia 2022]<br>
Jing Yu, Weifeng Zhang, Yuhang Lu, Zengchang Qin, Yue Hu, Jianlong Tan, and Qi Wu.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/8988148) [[Code]](http://github.com/rosinality/relation-networks-pytorch)

**Grounding answers for visual questions asked by visually impaired people** [CVPR 2022]<br>
Chongyan Chen, Samreen Anjum, and Danna Gurari.  <br>
[[Paper]](https://arxiv.org/pdf/2202.01993.pdf) [[Code]](https://vizwiz.org/tasks-and-datasets/answergrounding-for-vqa)

**Film: Visual reasoning with a general conditioning layer** [AAAI Conference on Artificial Intelligence 2018]<br>
Ethan Perez, Florian Strub, Harm De Vries, Vincent Dumoulin, and Aaron Courville.  <br>
[[Paper]](https://arxiv.org/pdf/1709.07871.pdf) [[Code]](https://github.com/ethanjperez/film)

**Zero-Shot Everything Sketch-Based Image Retrieval, and in Explainable Style** [CVPR 2023]<br>
Fengyin Lin, Mingkang Li, Da Li, Timothy Hospedales, Yi-Zhe Song, and Yonggang Qi.  <br>
[[Paper]](https://arxiv.org/pdf/2303.14348.pdf) [[Code]](https://github.com/buptLinfy/ZSE-SBIR)

**Multi-modal sarcasm detection with interactive in-modal and cross-modal graphs** [ACM international conference on multimedia 2021]<br>
Bin Liang, Chenwei Lou, Xiang Li, Lin Gui, Min Yang, and Ruifeng Xu.  <br>
[[Paper]](https://dl.acm.org/doi/10.1145/3474085.3475190)

**UnICLAM: Contrastive Representation Learning with Adversarial Masking for Unified and Interpretable Medical Vision Question Answering** [arXiv 2022]<br>
Chenlu Zhan, Peng Peng, Hongsen Wang, Tao Chen, and Hongwei Wang.  <br>
[[Paper]](https://arxiv.org/pdf/2212.10729.pdf)

**DIME: Fine-grained Interpretations of Multimodal Models via Disentangled Local Explanations** [AAAI/ACM Conference on AI, Ethics, and Society. 2022]<br>
Yiwei Lyu, Paul Pu Liang, Zihao Deng, Ruslan Salakhutdinov, and Louis-Philippe Morency.  <br>
[[Paper]](https://arxiv.org/pdf/2203.02013.pdf) [[Code]](https://github.com/lvyiwei1/DIME)

**MultiViz: Towards Visualizing and Understanding Multimodal Models** [International Conference on Learning Representations 2023]<br>
Paul Pu Liang, Yiwei Lyu, Gunjan Chhablani, Nihal Jain, Zihao Deng, Xingbo Wang, Louis-Philippe Morency, and Ruslan Salakhutdinov.  <br>
[[Paper]](https://arxiv.org/pdf/2207.00056.pdf) [[Code]](https://github.com/pliang279/MultiViz)

**X-pool: Cross-modal language-video attention for text-video retrieval** [CVPR 2022]<br>
Satya Krishna Gorti, Noël Vouitsis, Junwei Ma, Keyvan Golestan, Maksims Volkovs, Animesh Garg, and Guangwei Yu.  <br>
[[Paper]](https://arxiv.org/pdf/2203.15086.pdf) [[Code]](https://layer6ai-labs.github.io/xpool/)

**Video-text as game players: Hierarchical banzhaf interaction for cross-modal representation learning** [CVPR 2023]<br>
Peng Jin, Jinfa Huang, Pengfei Xiong, Shangxuan Tian, Chang Liu, Xiangyang Ji, Li Yuan, and Jie Chen.  <br>
[[Paper]](https://arxiv.org/pdf/2303.14369.pdf) [[Code]](https://jpthu17.github.io/HBI/)

**Step-Wise Hierarchical Alignment Network for Image-Text Matching** [IJCAI 2021]<br>
Zhong Ji, Kexin Chen, and Haoran Wang.  <br>
[[Paper]](https://arxiv.org/pdf/2106.06509v1.pdf)

**Learning Relation Alignment for Calibrated Cross-modal Retrieval** [the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing 2021]<br>
Shuhuai Ren, Junyang Lin, Guangxiang Zhao, Rui Men, An Yang, Jingren Zhou, Xu Sun, and Hongxia Yang.  <br>
[[Paper]](https://arxiv.org/pdf/2105.13868.pdf) [[Code]](https://github.com/lancopku/IAIS)

**SLAN: Self-Locator Aided Network for Cross-Modal Understanding** [arXiv 2022]<br>
Jiang-Tian Zhai, Qi Zhang, Tong Wu, Xing-Yu Chen, Jiang-Jiang Liu, Bo Ren, and Ming-Ming Cheng.  <br>
[[Paper]](https://arxiv.org/pdf/2211.16208.pdf)

**Robust and Interpretable Grounding of Spatial References with Relation Networks** [Association for Computational Linguistics: EMNLP 2020]<br>
Tsung-Yen Yang, Andrew Lan, and Karthik Narasimhan.  <br>
[[Paper]](https://arxiv.org/pdf/2005.00696.pdf) [[Code]](https://sites.google.com/view/robust-relation-net/home)

**Cross-modal Relational Reasoning Network for Visual Question Answering** [IEEE/CVF International Conference on Computer Vision 2021]<br>
Hongyu Chen, Ruifang Liu, and Bo Peng.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/9607451)

**MMT: Image-guided Story Ending Generation with Multimodal Memory Transformer** [the 30th ACM International Conference on Multimedia]<br>
Dizhan Xue, Shengsheng Qian, Quan Fang, and Changsheng Xu.  <br>
[[Paper]](https://dl.acm.org/doi/10.1145/3503161.3548022) [[Code]](https://github.com/LivXue/MMT)



### <span id="head-2"> *2.2 Methods of Textual Explanation* </span>

**More than an answer: Neural pivot network for visual qestion answering** [the 25th ACM international conference on Multimedia 2017]<br>
Yiyi Zhou, Rongrong Ji, Jinsong Su, YongjianWu, and YunshengWu.  <br>
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3123266.3123335)

**Tell-and-Answer: Towards Explainable Visual Question Answering using Attributes and Captions** [the 2018 Conference on Empirical Methods in Natural Language Processing 2018]<br>
Qing Li, Jianlong Fu, Dongfei Yu, Tao Mei, and Jiebo Luo.  <br>
[[Paper]](https://arxiv.org/pdf/1801.09041.pdf)

**Vqa-e: Explaining, elaborating, and enhancing your answers for visual questions** [ECCV 18]<br>
Qing Li, Qingyi Tao, Shafiq Joty, Jianfei Cai, and Jiebo Luo.  <br>
[[Paper]](https://arxiv.org/pdf/1803.07464.pdf)

**Visual question answering as reading comprehension** [CVPR 2019]<br>
Hui Li, Peng Wang, Chunhua Shen, and Anton van den Hengel.  <br>
[[Paper]](https://arxiv.org/pdf/1811.11903.pdf)

**Relation-Aware Image Captioning for Explainable Visual Question Answering** [TAAI 2022]<br>
Ching-Shan Tseng, Ying-Jia Lin, and Hung-Yu Kao.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/10056492)

**From Images to Textual Prompts: Zero-shot Visual Question Answering with Frozen Large Language Models** [CVPR 2023]<br>
Jiaxian Guo, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Boyang Li, Dacheng Tao, and Steven Hoi.  <br>
[[Paper]](https://arxiv.org/pdf/2212.10846.pdf) [[Code]](https://github.com/salesforce/LAVIS/tree/main/projects/img2llm-vqa)

**Fvqa: Fact-based visual question answering** [IEEE transactions on pattern analysis and machine intelligence 40 2017]<br>
PengWang, QiWu, Chunhua Shen, Anthony Dick, and Anton Van Den Hengel.  <br>
[[Paper]](https://arxiv.org/pdf/1606.05433.pdf)

**Straight to the facts: Learning knowledge base retrieval for factual visual question answering.** [ECCV 2018]<br>
Medhini Narasimhan and Alexander G Schwing.  <br>
[[Paper]](https://arxiv.org/pdf/1809.01124.pdf)

**Multi-level knowledge injecting for visual commonsense reasoning** [IEEE Transactions on Circuits and Systems for Video Technology 2020]<br>
Zhang Wen and Yuxin Peng. 2020.  <br>
[[Paper]](https://ieeexplore.ieee.org/abstract/document/9083951)

**Explicit cross-modal representation learning for visual commonsense reasoning** [IEEE Transactions on Multimedia 2012]<br>
Xi Zhang, Feifei Zhang, and Changsheng Xu.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/9465732)

**Title** [Association for Computational Linguistics: EMNLP 2020]<br>
Ana Marasović, Chandra Bhagavatula, Jae sung Park, Ronan Le Bras, Noah A Smith, and Yejin Choi.  <br>
[[Paper]](https://arxiv.org/pdf/2010.07526.pdf) [[Code]](https://github.com/allenai/visual-reasoning-rationalization)

**Beyond vqa: Generating multi-word answers and rationales to visual questions** [CVPR 2021]<br>
Radhika Dua, Sai Srinivas Kancheti, and Vineeth N Balasubramanian. <br>
[[Paper]](https://arxiv.org/pdf/2010.12852.pdf)

**Title** [Pan Lu, Swaroop Mishra, Tanglin Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, and Ashwin Kalyan 2022]<br>
Pan Lu, Swaroop Mishra, Tanglin Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, and Ashwin Kalyan.  <br>
[[Paper]](https://arxiv.org/abs/2209.09513)

**Title** [Conf 2022]<br>
Name.  <br>
[[Paper]](https://)

**Title** [Conf 2022]<br>
Name.  <br>
[[Paper]](https://)

**Title** [Conf 2022]<br>
Name.  <br>
[[Paper]](https://)

**Title** [Conf 2022]<br>
Name.  <br>
[[Paper]](https://)

**Title** [Conf 2022]<br>
Name.  <br>
[[Paper]](https://)

### <span id="head-3"> *2.3 Methods of Graph Explanation* </span>


### <span id="head-4"> *2.4 Methods of Symbol Explanation* </span>


### <span id="head-5"> *2.5 Methods of Multimodal Explanation* </span>

## <span id="headtax"> *3. Datasets* </span> [       «🎯Back To Top»       ](#)