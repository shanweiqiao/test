 # A Survey of Surveys (LLMs)

<div align='center'>
  <img src=https://img.shields.io/badge/LLMs_survey-blue.svg >
  <img src=https://img.shields.io/badge/release-v1-orange.svg >
  <img src=https://img.shields.io/github/stars/NiuTrans/ABigSurvey >
</div>

--------------------------------------------------------------------------------

- ... to do ...

- We also survey hundreds of survey papers on Natural Language Processing and Machine Learning [[A Survey of Surveys (NLP & ML)](https://github.com/NiuTrans/ABigSurvey?tab=readme-ov-file#large-language-models)] ![GitHub Repo stars](https://img.shields.io/github/stars/NiuTrans/ABigSurvey)

<details><summary>🚀Updates</summary>

| Version | Time | Content |
| ------------------------ | ---------- | ------------------------------------------------------------ |
| V1                       | 2024/03/08 | The initial version.                                         |
</details>


<!-- :new: We add a NEW category of large language models! [<a href="#large-language-models">Large Language Models</a>] -->

## Categorization

We follow the concerning track and hot topic on **Large Language Modeling** research recently. The categorization is as follows:
<!-- + Large Language Modeling
    + <a href="#alignment">Alignment</a>
    + <a href="#data">Data</a>
    + <a href="#evaluation">Evaluation</a>
    + <a href="#societal-implications">Societal Implications</a>
    + <a href="#safety">Safety</a>
    + <a href="#science-of-LMs">Science of LMs</a>
    + <a href="#compute-efficient-lms">Compute Efficient LMs</a>
    + <a href="#engineering-for-large-lms">Engineering for Large LMs</a>
    + <a href="#learning-algorithms">Learning Algorithms</a>
    + <a href="#inference-algorithms">Inference Algorithms</a>
    + <a href="#human-mind-brain-philosophy-laws-and-LMs">Human Mind, Brain, Philosophy, Laws and LMs</a>
    + <a href="#lms-for-everyone">LMs for Everyone</a>
    + <a href="#lms-and-the-world">LMs and The world</a>
    + <a href="#lms-and-embodiment">LMs and Embodiment</a>
    + <a href="#lms-and-interactions">LMs and Interactions</a>
    + <a href="#lms-with-tools-and-code">LMs with Tools and Code</a>
    + <a href="#lms-on-diverse-modalities-and-novel-applications">LMs on Diverse Modalities and Novel Applications</a> -->
+ <a href="#general">General</a>
+ <a href="#alignment">Alignment</a>
+ <a href="#data">Data</a>
+ <a href="#evaluation">Evaluation</a>
+ <a href="#societal-implications">Societal Implications</a>
+ <a href="#safety">Safety</a>
+ <a href="#science-of-LMs">Science of LMs</a>
+ <a href="#compute-efficient-lms">Compute Efficient LMs</a>
+ <a href="#engineering-for-large-lms">Engineering for Large LMs</a>
+ <a href="#learning-algorithms">Learning Algorithms</a>
+ <a href="#inference-algorithms">Inference Algorithms</a>
+ <a href="#human-mind-brain-philosophy-laws-and-LMs">Human Mind, Brain, Philosophy, Laws and LMs</a>
+ <a href="#lms-for-everyone">LMs for Everyone</a>
+ <a href="#lms-and-the-world">LMs and The world</a>
+ <a href="#lms-and-embodiment">LMs and Embodiment</a>
+ <a href="#lms-and-interactions">LMs and Interactions</a>
+ <a href="#lms-with-tools-and-code">LMs with Tools and Code</a>
+ <a href="#lms-on-diverse-modalities-and-novel-applications">LMs on Diverse Modalities and Novel Applications</a>


<!-- To reduce class imbalance, we separate some of the hot sub-topics from the original categorization of ACL and ICML submissions. E.g., Named Entity Recognition is a first-level area in our categorization because it is the focus of several surveys. -->

<!-- ## Statistics

We show the number of paper in each area in Figures 1-2.

<p align="center"><img src="https://s2.loli.net/2023/05/26/DUa43miWf5NFlZx.png" width="70%" height="70%"/></p>

<p align="center">Figure 1: # of papers in each NLP area.</p>

Also, we plot paper number as a function of publication year (see Figure 3).

<p align="center"><img src="https://s2.loli.net/2023/05/26/7tMmcRO1lK9N5hF.png" width="70%" height="70%"/></p>

<p align="center">Figure 3: # of papers vs publication year.</p>

In addition, we generate word clouds to show hot topics in these surveys (see Figures 4-5).

<p align="center"><img src="https://s2.loli.net/2023/05/26/6RqNCKBwsEZtA3H.png" width="60%" height="60%"/></p>

<p align="center">Figure 4: The word cloud for NLP.</p> -->

<!-- <details><summary>Definitions</summary>

- **Training Speed**: the number of training samples processed per second during the training. (bs=4, cutoff_len=1024)
- **Rouge Score**: Rouge-2 score on the development set of the [advertising text generation](https://aclanthology.org/D19-1321.pdf) task. (bs=4, cutoff_len=1024)
- **GPU Memory**: Peak GPU memory usage in 4-bit quantized training. (bs=1, cutoff_len=1024)
- We adopt `pre_seq_len=128` for ChatGLM's P-Tuning and `lora_rank=32` for LLaMA-Factory's LoRA tuning.

| Version                  | Time       | Update Content                                               |
| ------------------------ | ---------- | ------------------------------------------------------------ |
| V1                       | 2023/03/31 | The initial version.                                         |
</details> -->

## 📜 The LLMs Paper List

#### [General](#content)

1. **Instruction Tuning for Large Language Models: A Survey** arXiv (2023)

   *Wayne Xin Zhao, Kun Zhou, Junyi Li, Tianyi Tang, Xiaolei Wang, Yupeng Hou, Yingqian Min, Beichen Zhang, Junjie Zhang, Zican Dong, Yifan Du, Chen Yang, Yushuo Chen, Zhipeng Chen, Jinhao Jiang, Ruiyang Ren, Yifan Li, Xinyu Tang, Zikang Liu, Peiyu Liu, Jian-Yun Nie, Ji-Rong Wen* [[Paper](https://arxiv.org/abs/2303.18223)] [[GitHub](https://github.com/RUCAIBox/LLMSurvey)]

2. **A Survey of GPT-3 Family Large Language Models Including ChatGPT and GPT-4** arXiv (2023)

   *Katikapalli Subramanyam Kalyan* [[Paper](https://arxiv.org/abs/2310.12321)]

3. **Challenges and Applications of Large Language Models** arXiv (2023)

   *Jean Kaddour, Joshua Harris, Maximilian Mozes, Herbie Bradley, Roberta Raileanu, Robert McHardy* [[Paper](https://arxiv.org/abs/2307.10169)]

4. **Harnessing the Power of LLMs in Practice: A Survey on ChatGPT and Beyond** arXiv (2023)

   *Jingfeng Yang, Hongye Jin, Ruixiang Tang, Xiaotian Han, Qizhang Feng, Haoming Jiang, Bing Yin, Xia Hu* [[Paper](https://arxiv.org/abs/2304.13712)] [[GitHub](https://github.com/Mooler0410/LLMsPracticalGuide)]


#### [Alignment](#content)

<!-- 1. **A Comprehensive Survey on Instruction Following**. *Renze Lou et al*. arXiv 2023. [[Paper](https://arxiv.org/abs/2303.10475)] [[GitHub](https://github.com/RenzeLou/awesome-instruction-learning)]

2. **Instruction Tuning for Large Language Models: A Survey**. *Shengyu Zhang et al*. arXiv 2023. [[Paper](https://arxiv.org/abs/2308.10792)] [[GitHub](https://github.com/RenzeLou/awesome-instruction-learning)] -->

1. **Instruction Tuning for Large Language Models: A Survey** arXiv (2023)

   *Renze Lou, Kai Zhang, Wenpeng Yin* [[Paper](https://arxiv.org/abs/2303.10475)] [[GitHub](https://github.com/RenzeLou/awesome-instruction-learning)]

2. **Instruction Tuning for Large Language Models: A Survey** arXiv (2023)

   *Shengyu Zhang, Linfeng Dong, Xiaoya Li, Sen Zhang, Xiaofei Sun, Shuhe Wang, Jiwei Li, Runyi Hu, Tianwei Zhang, Fei Wu, Guoyin Wang* [[Paper](https://arxiv.org/abs/2308.10792)] [[GitHub](https://github.com/RenzeLou/awesome-instruction-learning)]




<!-- >Feel free to let me know the missing papers (issue or pull request). -->


<!-- ## Star History

<a href="https://star-history.com/#NiuTrans/ABigSurvey&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=HqWu-HITCS/Awesome-LLM-Survey&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=HqWu-HITCS/Awesome-LLM-Survey&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=HqWu-HITCS/Awesome-LLM-Survey&type=Date" />
  </picture>
</a> -->
## ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=NiuTrans/ABigSurvey&type=Date)](https://star-history.com/#NiuTrans/ABigSurvey&Date)

## Team Members

The project is maintained by 

*Natural Language Processing Lab., School of Computer Science and Engineering, Northeastern University*

*NiuTrans Research*

Please feel free to contact us if you have any questions (libei_neu [at] outlook.com).

## Acknowledge

We would like to thank the people who have contributed to this project. They are

*Chuanhao Lv, Kaiyan Chang, Ziyang Wang, Shuhan Zhou, Nuo Xu, Bei Li, Yinqiao Li, Quan Du, Xin Zeng, Laohu Wang, Chenglong Wang, Xiaoqian Liu, Xuanjun Zhou, Jingnan Zhang, Yongyu Mu, Zefan Zhou, Yanhong Jiang, Xinyang Zhu, Xingyu Liu, Dong Bi, Ping Xu, Zijian Li, Fengning Tian, Hui Liu, Kai Feng, Yuhao Zhang, Chi Hu, Di Yang, Lei Zheng, Hexuan Chen, Zeyang Wang, Tengbo Liu, Xia Meng, Weiqiao Shan, Tao Zhou, Runzhe Cao, Yingfeng Luo, Binghao Wei, Wandi Xu, Yan Zhang, Yichao Wang, Mengyu Ma, Zihao Liu*
