# <p align=center>A Survey on Interpretable Cross-modal Reasoning

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![arXiv](https://img.shields.io/badge/arXiv-2309.01955-b31b1b.svg)](https://arxiv.org/abs/2309.01955)
![Status](https://img.shields.io/badge/Status-building-brightgreen)
![GitHub stars](https://img.shields.io/github/stars/ZuyiZhou/Awesome-Interpretable-Cross-modal-Reasoning?color=yellow&label=Stars)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FZuyiZhou%2FAwesome-Interpretable-Cross-modal-Reasoning&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)


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

**Reasoning on the relation: Enhancing visual representation for visual question answering and cross-modal retrieval** [TMM 2022]<br>
Jing Yu, Weifeng Zhang, Yuhang Lu, Zengchang Qin, Yue Hu, Jianlong Tan, and Qi Wu.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/8988148) [[Code]](http://github.com/rosinality/relation-networks-pytorch)

**Grounding answers for visual questions asked by visually impaired people** [CVPR 2022]<br>
Chongyan Chen, Samreen Anjum, and Danna Gurari.  <br>
[[Paper]](https://arxiv.org/pdf/2202.01993.pdf) [[Code]](https://vizwiz.org/tasks-and-datasets/answergrounding-for-vqa)

**Film: Visual reasoning with a general conditioning layer** [AAAI 2018]<br>
Ethan Perez, Florian Strub, Harm De Vries, Vincent Dumoulin, and Aaron Courville.  <br>
[[Paper]](https://arxiv.org/pdf/1709.07871.pdf) [[Code]](https://github.com/ethanjperez/film)

**Zero-Shot Everything Sketch-Based Image Retrieval, and in Explainable Style** [CVPR 2023]<br>
Fengyin Lin, Mingkang Li, Da Li, Timothy Hospedales, Yi-Zhe Song, and Yonggang Qi.  <br>
[[Paper]](https://arxiv.org/pdf/2303.14348.pdf) [[Code]](https://github.com/buptLinfy/ZSE-SBIR)

**Multi-modal sarcasm detection with interactive in-modal and cross-modal graphs** [ACM MM 2021]<br>
Bin Liang, Chenwei Lou, Xiang Li, Lin Gui, Min Yang, and Ruifeng Xu.  <br>
[[Paper]](https://dl.acm.org/doi/10.1145/3474085.3475190)

**UnICLAM: Contrastive Representation Learning with Adversarial Masking for Unified and Interpretable Medical Vision Question Answering** [arXiv 2022]<br>
Chenlu Zhan, Peng Peng, Hongsen Wang, Tao Chen, and Hongwei Wang.  <br>
[[Paper]](https://arxiv.org/pdf/2212.10729.pdf)

**DIME: Fine-grained Interpretations of Multimodal Models via Disentangled Local Explanations** [AIES 2022]<br>
Yiwei Lyu, Paul Pu Liang, Zihao Deng, Ruslan Salakhutdinov, and Louis-Philippe Morency.  <br>
[[Paper]](https://arxiv.org/pdf/2203.02013.pdf) [[Code]](https://github.com/lvyiwei1/DIME)

**MultiViz: Towards Visualizing and Understanding Multimodal Models** [ICLR 2023]<br>
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

**Learning Relation Alignment for Calibrated Cross-modal Retrieval** [ACL-IJCNLP 2021]<br>
Shuhuai Ren, Junyang Lin, Guangxiang Zhao, Rui Men, An Yang, Jingren Zhou, Xu Sun, and Hongxia Yang.  <br>
[[Paper]](https://arxiv.org/pdf/2105.13868.pdf) [[Code]](https://github.com/lancopku/IAIS)

**SLAN: Self-Locator Aided Network for Cross-Modal Understanding** [arXiv 2022]<br>
Jiang-Tian Zhai, Qi Zhang, Tong Wu, Xing-Yu Chen, Jiang-Jiang Liu, Bo Ren, and Ming-Ming Cheng.  <br>
[[Paper]](https://arxiv.org/pdf/2211.16208.pdf)

**Robust and Interpretable Grounding of Spatial References with Relation Networks** [EMNLP 2020]<br>
Tsung-Yen Yang, Andrew Lan, and Karthik Narasimhan.  <br>
[[Paper]](https://arxiv.org/pdf/2005.00696.pdf) [[Code]](https://sites.google.com/view/robust-relation-net/home)

**Cross-modal Relational Reasoning Network for Visual Question Answering** [ICCV 2021]<br>
Hongyu Chen, Ruifang Liu, and Bo Peng.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/9607451)

**MMT: Image-guided Story Ending Generation with Multimodal Memory Transformer** [ACM MM 2023]<br>
Dizhan Xue, Shengsheng Qian, Quan Fang, and Changsheng Xu.  <br>
[[Paper]](https://dl.acm.org/doi/10.1145/3503161.3548022) [[Code]](https://github.com/LivXue/MMT)



### <span id="head-2"> *2.2 Methods of Textual Explanation* </span>

**More than an answer: Neural pivot network for visual qestion answering** [ACM MM 2017]<br>
Yiyi Zhou, Rongrong Ji, Jinsong Su, YongjianWu, and YunshengWu.  <br>
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3123266.3123335)

**Tell-and-Answer: Towards Explainable Visual Question Answering using Attributes and Captions** [EMNLP 2018]<br>
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

**Fvqa: Fact-based visual question answering** [T-PAMI 2017]<br>
PengWang, QiWu, Chunhua Shen, Anthony Dick, and Anton Van Den Hengel.  <br>
[[Paper]](https://arxiv.org/pdf/1606.05433.pdf)

**Straight to the facts: Learning knowledge base retrieval for factual visual question answering.** [ECCV 2018]<br>
Medhini Narasimhan and Alexander G Schwing.  <br>
[[Paper]](https://arxiv.org/pdf/1809.01124.pdf)

**Multi-level knowledge injecting for visual commonsense reasoning** [TCSVT 2020]<br>
Zhang Wen and Yuxin Peng. 2020.  <br>
[[Paper]](https://ieeexplore.ieee.org/abstract/document/9083951)

**Explicit cross-modal representation learning for visual commonsense reasoning** [TMM 2012]<br>
Xi Zhang, Feifei Zhang, and Changsheng Xu.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/9465732)

**TiNatural Language Rationales with Full-Stack Visual Reasoning: From Pixels to Semantic Frames to Commonsense Graphstle** [EMNLP 2020]<br>
Ana Marasović, Chandra Bhagavatula, Jae sung Park, Ronan Le Bras, Noah A Smith, and Yejin Choi.  <br>
[[Paper]](https://arxiv.org/pdf/2010.07526.pdf) [[Code]](https://github.com/allenai/visual-reasoning-rationalization)

**Beyond vqa: Generating multi-word answers and rationales to visual questions** [CVPR 2021]<br>
Radhika Dua, Sai Srinivas Kancheti, and Vineeth N Balasubramanian. <br>
[[Paper]](https://arxiv.org/pdf/2010.12852.pdf)

**Learn to explain: Multimodal reasoning via thought chains for science question answering** [Pan Lu, Swaroop Mishra, Tanglin Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, and Ashwin Kalyan 2022]<br>
Pan Lu, Swaroop Mishra, Tanglin Xia, Liang Qiu, Kai-Wei Chang, Song-Chun Zhu, Oyvind Tafjord, Peter Clark, and Ashwin Kalyan.  <br>
[[Paper]](https://arxiv.org/pdf/2209.09513.pdf) [[Code]](https://scienceqa.github.io/)

**Multimodal chain-of-thought reasoning in language models.** [arXiv 2023]<br>
Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, and Alex Smola.  <br>
[[Paper]](https://arxiv.org/pdf/2302.00923.pdf) [[Code]](https://github.com/amazon-science/mm-cot)

**T-SciQ: Teaching Multimodal Chain-of-Thought Reasoning via Large Language Model Signals for Science Question Answering** [arXiv 2023]<br>
Lei Wang, Yi Hu, Jiabang He, Xing Xu, Ning Liu, Hui Liu, and Heng Tao Shen.  <br>
[[Paper]](https://arxiv.org/pdf/2305.03453.pdf)

**The Art of SOCRATIC QUESTIONING: Zero-shot Multimodal Reasoning with Recursive Thinking and Self-Questioning** [arXiv 2023]<br>
Jingyuan Qi, Zhiyang Xu, Ying Shen, Minqian Liu, Di Jin, Qifan Wang, and Lifu Huang.  <br>
[[Paper]](https://arxiv.org/pdf/2305.14999.pdf)

### <span id="head-3"> *2.3 Methods of Graph Explanation* </span>

**Learning conditioned graph structures for interpretable visual question answering** [NeurIPS 2018]<br>
Will Norcliffe-Brown, Stathis Vafeias, and Sarah Parisot.  <br>
[[Paper]](https://arxiv.org/pdf/1806.07243.pdf) [[Code]](https://github.com/aimbrain/vqa-project)

**Relation-aware graph attention network for visual question answering** [ICCV 2019]<br>
Linjie Li, Zhe Gan, Yu Cheng, and Jingjing Liu. <br>
[[Paper]](https://arxiv.org/pdf/1903.12314.pdf) [[Code]](https://github.com/linjieli222/VQA_ReGAT)

**Visual semantic reasoning for image-text matching** [ICCV 2019]<br>
Kunpeng Li, Yulun Zhang, Kai Li, Yuanyuan Li, and Yun Fu.  <br>
[[Paper]](https://arxiv.org/pdf/1909.02701.pdf) [[Code]](https://github.com/KunpengLi1994/VSRN)

**Coarse-to-fine reasoning for visual question answering** [CVPR 2023]<br>
Binh X Nguyen, Tuong Do, Huy Tran, Erman Tjiputra, Quang D Tran, and Anh Nguyen..  <br>
[[Paper]](https://arxiv.org/pdf/2110.02526.pdf) [[Code]](https://github.com/aioz-ai/CFR_VQA)

**Explainable high-order visual question reasoning: A new benchmark and knowledgerouted network** [arXiv 2019]<br>
Qingxing Cao, Bailin Li, Xiaodan Liang, and Liang Lin.  <br>
[[Paper]](https://arxiv.org/pdf/1909.10128.pdf)

**Query and attention augmentation for knowledge-based explainable reasoning** [CVPR 2022]<br>
Yifeng Zhang, Ming Jiang, and Qi Zhao.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/9879458) [[Code]](https://github.com/SuperJohnZhang/QAA)

**Vqa with no questions-answers training** [CVPR 2020]<br>
Ben-Zion Vatashsky and Shimon Ullman.  <br>
[[Paper]](https://arxiv.org/abs/1811.08481.pdf) [[Code]](https://github.com/benyv/uncord)

**Linguistically driven graph capsule network for visual question reasoning** [arXiv 2020]<br>
Qingxing Cao, Xiaodan Liang, Keze Wang, and Liang Lin.  <br>
[[Paper]](https://arxiv.org/pdf/2003.10065.pdf) [[Code]]

**Learning cross-modal context graph for visual grounding** [AAAI 202o]<br>
Yongfei Liu, Bo Wan, Xiaodan Zhu, and Xuming He.  <br>
[[Paper]](https://arxiv.org/pdf/1911.09042.pdf)  [[Code]](https://github.com/youngfly11/LCMCG-PyTorch)

**Hierarchical Cross-Modal Graph Consistency Learning for Video-Text Retrieval** [SIGIR 2021]<br>
Weike Jin, Zhou Zhao, Pengcheng Zhang, Jieming Zhu, Xiuqiang He, and Yueting Zhuang.  <br>
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3404835.3462974)

**Cross-modal graph matching network for image-text retrieval** [TOMM 2022]<br>
Yuhao Cheng, Xiaoguang Zhu, Jiuchao Qian, Fei Wen, and Peilin Liu.  <br>
[[Paper]](https://dl.acm.org/doi/10.1145/3499027) [[Code]](https://github.com/cyh-sj/CGMN)

**KBGN: Knowledge-bridge graph network for adaptive vision-text reasoning in visual dialogue** [ACM MM 2020]<br>
Xiaoze Jiang, Siyi Du, Zengchang Qin, Yajing Sun, and Jing Yu.  <br>
[[Paper]](https://arxiv.org/pdf/2008.04858.pdf)

**Mucko: multi-layer cross-modal knowledge reasoning for fact-based visual question answering** [IJCAI 2021]<br>
Zihao Zhu, Jing Yu, Yujing Wang, Yajing Sun, Yue Hu, and Qi Wu.  <br>
[[Paper]](https://arxiv.org/pdf/2006.09073.pdf)

**Cross-modal representation learning and relation reasoning for bidirectional adaptive manipulation** [IJCAI 2022]<br>
Lei Li, Kai Fan, and Chun Yuan.  <br>
[[Paper]](https://arxiv.org/pdf/2006.09073.pdf)

**Mukea: Multimodal knowledge extraction and accumulation for knowledgebased visual question answering** [CVPR 2022]<br>
Yang Ding, Jing Yu, Bang Liu, Yue Hu, Mingxin Cui, and Qi Wu.  <br>
[[Paper]]https://arxiv.org/pdf/2203.09138.pdf) [[Code]](https://github.com/AndersonStra/MuKEA) 

### <span id="head-4"> *2.4 Methods of Symbol Explanation* </span>

**Explicit reasoning over end-to-end neural architectures for visual question answering** [AAAI 2018]<br>
Somak Aditya, Yezhou Yang, and Chitta Baral.  <br>
[[Paper]](https://arxiv.org/pdf/1803.08896.pdf)

**Multimodal Logical Inference System for Visual-Textual Entailment** [ACL SRW 2019]<br>
NamRiko Suzuki, Hitomi Yanaka, Masashi Yoshikawa, Koji Mineshima, and Daisuke Bekki.  <br>
[[Paper]](https://arxiv.org/pdf/1906.03952.pdf)

**Exploring Logical Reasoning for Referring Expression Comprehension** [ACM MM 2021]<br>
Ying Cheng, Ruize Wang, Jiashuo Yu, Rui-Wei Zhao, Yuejie Zhang, and Rui Feng.  <br>
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3475677)

**SPACES: Explainable multimodal ai for active surveillance, diagnosis, and management of adverse childhood experiences** [Big Dat 2021]<br>
Nariman Ammar, Parya Zareie, Marion E Hare, Lisa Rogers, Sandra Madubuonwu, Jason Yaun, and Arash Shaban-Nejad.  <br>
[[Paper]](https://ieeexplore.ieee.org/document/9671303)

**Interpretable Multimodal Misinformation Detection with Logic Reasoning** [arXiv 2023]<br>
Hui Liu, Wenya Wang, and Haoliang Li.  <br>
[[Paper]](https://arxiv.org/pdf/2305.05964.pdf) [[Code]](https://github.com/less-and-less-bugs/LogicMD)

**Integrating non-monotonic logical reasoning and inductive learning with deep learning for explainable visual question answering.** [FRAI 6 2019]<br>
Heather Riley and Mohan Sridharan.  <br>
[[Paper]](https://www.frontiersin.org/articles/10.3389/frobt.2019.00125/full) [[Code]](https://github.com/hril230/masters_code) 

**VQA-LOL: Visual Question Answering Under the Lens of Logic** [ECCV 2022]<br>
Tejas Gokhale, Pratyay Banerjee, Chitta Baral, and Yezhou Yang.  <br>
[[Paper]](https://arxiv.org/pdf/2002.08325.pdf)

**Neural Module Networks** [CVPR 2016]<br>
Jacob Andreas, Marcus Rohrbach, Trevor Darrell, and Dan Klein.  <br>
[[Paper]](https://arxiv.org/pdf/1511.02799.pdf)

**Learning to reason: End-to-end module networks for visual question answering** [ICCV 2017]<br>
Ronghang Hu, Jacob Andreas, Marcus Rohrbach, Trevor Darrell, and Kate Saenko.  <br>
[[Paper]](https://arxiv.org/pdf/1704.05526.pdf)

**Neural-symbolic vqa: Disentangling reasoning from vision and language understanding** [NeurIPS 2018]<br>
Kexin Yi, Jiajun Wu, Chuang Gan, Antonio Torralba, Pushmeet Kohli, and Josh Tenenbaum.  <br>
[[Paper]]https://arxiv.org/pdf/1810.02338.pdf) [[Code]](http://nsvqa.csail.mit.edu) 

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


### <span id="head-5"> *2.5 Methods of Multimodal Explanation* </span>

## <span id="headtax"> *3. Datasets* </span> [       «🎯Back To Top»       ](#)