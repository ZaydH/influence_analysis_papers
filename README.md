## Training Data Influence Analysis &amp; Estimation Resources

[![paper](https://img.shields.io/badge/Paper-arxiv-b31b1b)](https://arxiv.org/abs/2212.04612)

This repository details resources related to training-set influence analysis.
For a full taxonomy and comparison of training-set influence analysis methods and estimators, please see our [survey paper](https://arxiv.org/abs/2212.04612).

We will regularly update this repository as new research is published.
To have your paper included in this repository, you can send me an email at [zayd.hammoudeh@gmail.com](mailto:zayd.hammoudeh@gmail.com), submit a [pull request](https://github.com/ZaydH/influence_analysis_survey/pulls), or fill out this <a href="https://docs.google.com/forms/d/e/1FAIpQLSdrJ4vM3HLmQzqHaosWgmdBJwRj5M9qFY6m_iJ2CbmdPQpH9Q/viewform" target="_blank">Google form</a>.

## What is Training Data Influence Analysis?

*Influence analysis* studies how to apportion credit (and blame) for specific model behavior to individual or groups of training instances.  Important tasks that influence analysis contribute to include:
* Understanding why a trained model behaves in a specific way
* Identifying limitations/vulnerabilities in the training data
* Determining whether a prediction is well supported by the training set

## Citation


If you found this repo or survey is useful, please cite our paper as follows:

```
@article{Hammoudeh:2022:InfluenceSurvey,
  author = {Zayd Hammoudeh and 
            Daniel Lowd},
  title = {Training Data Influence Analysis and Estimation: A Survey},
  archivePrefix = {arXiv},
  eprint = {2212.04612},
  primaryClass = {cs.LG},
  year = {2022},
}
```

## Survey

- Training Data Influence Analysis and Estimation: A Survey
  [[link]](https://arxiv.org/abs/2212.04612)
  - Zayd Hammoudeh and Daniel Lowd. 2022.


## Retraining-Based Methods

**Click on the arrow** next to the year show/hide the corresponding papers.

<details open>
<summary>2023</summary>

- A Bayesian Perspective On Training Data Attribution
  [[link]](https://arxiv.org/abs/2305.19765)
  - Elisa Nguyen, Minjoon Seo, and Seong Joon Oh. 2023.
<br><br>
- A Note on "Efficient Task-Specific Data Valuation for Nearest Neighbor Algorithms"
  [[link]](https://arxiv.org/abs/2304.04258)
  - Jiachen T. Wang and Ruoxi Jia. 2023.
<br><br>
- A Note on "Towards Efficient Data Valuation Based on the Shapley Value"
  [[link]](https://arxiv.org/abs/2302.11431)
  - Jiachen T. Wang and Ruoxi Jia. 2023.
<br><br>
- Data Banzhaf:  A Robust Data Valuation Framework for Machine Learning
  [[link]](https://arxiv.org/abs/2205.15466)
  - Jiachen T. Wang and Ruoxi Jia. *AISTATS*, 2023.
<br><br>
- ModelPred: A Framework for Predicting Trained Model from Training Data
  [[link]](https://arxiv.org/abs/2111.12545)
  [[video]](https://www.youtube.com/watch?v=RtY0sYaZ0_w)
  - Yingyan Zeng, Jiachen T. Wang, Si Chen, Hoang Anh Just, Ran Jin, and Ruoxi Jia. *SaTML*, 2023.
<br><br>
- FaShapley: Fast and Approximated Shapley Based Model Pruning Towards Certifiably Robust DNNs
  [[link]](https://openreview.net/forum?id=mJF9_Fs52ut)
  [[code]](https://github.com/kangmintong/FaShapley)
  - Mintong Kang, Linyi Li, and Bo Li. *SaTML*, 2023.

</details>
<details open>
<summary>2022</summary>

- Datamodels: Predicting Predictions from Training Data
  [[link]](https://arxiv.org/abs/2202.00622)
  [[blog]](https://gradientscience.org/datamodels-1/)
  [[data]](https://github.com/MadryLab/datamodels-data)
  - Andrew Ilyas, Sung Min Park, Logan Engstrom, Guillaume Leclerc, and Aleksander Madry. *ICML*, 2022.
- Measuring the Effect of Training Data on Deep Learning Predictions via Randomized Experiments
  [[link]](https://arxiv.org/abs/2206.10013)
  - Jinkun Lin, Anqi Zhang, Mathias Lecuyer, Jinyang Li, Aurojit Panda, and Siddhartha Sen. *ICML*, 2022.
<br><br>
- Beta Shapley: A Unified and Noise-Reduced Data Valuation Framework for Machine Learning
  [[link]](https://arxiv.org/abs/2110.14049)
  [[code]](https://github.com/ykwon0407/beta_shapley)
  [[video]](https://slideslive.com/38980844/beta-shapley-a-unified-and-noisereduced-data-valuation-framework-for-machine-learning?ref=speaker-30723)
  - Yongchan Kwon and James Zou. *AISTATS*, 2022.
<br><br>
- Private Data Valuation and Fair Payment in Data Marketplaces
  [[link]](https://arxiv.org/abs/2210.08723)
  - Zhihua Tian, Jian Liu, Jingyu Li, Xinle Cao, Ruoxi Jia, Jun Kong, Mengdi Liu, and Kui Ren. 2022.

</details>
<details open>
<summary>2021</summary>

- Counterfactual Memorization in Neural Language Models
  [[link]](https://arxiv.org/abs/2112.12938)
  - Chiyuan Zhang, Daphne Ippolito, Katherine Lee, Matthew Jagielski, Florian Tramèr, and Nicholas Carlini. 2021.
<br><br>
- Characterizing Structural Regularities of Labeled Data in Overparameterized Models
  [[link]](https://arxiv.org/abs/2002.03206)
  [[code]](https://github.com/pluskid/structural-regularity)
  [[video]](https://slideslive.com/38958656/characterizing-structural-regularities-of-labeled-data-in-overparameterized-models?ref=speaker-19084-latest)
  - Ziheng Jiang, Chiyuan Zhang, Kunal Talwar, and Michael C Mozer. *ICML*, 2021.
<br><br>
- If You Like Shapley Then You’ll Love the Core
  [[link]](https://ojs.aaai.org/index.php/AAAI/article/view/16721)
  [[video]](https://slideslive.com/38949225/if-you-like-shapley-then-youll-love-the-core)
  - Tom Yan and Ariel D. Procaccia. *AAAI*, 2021.
<br><br>
- Scalability vs. Utility: Do We Have to Sacrifice One for the Other in Data Importance Quantification?
  [[link]](https://arxiv.org/abs/1911.07128)
  [[code]](https://github.com/AI-secure/Shapley-Study)
  - Ruoxi Jia, Fan Wu, Xuehui Sun, Jiacen Xu, David Dao, Bhavya Kailkhura, Ce Zhang, Bo Li, and Dawn Song. *CVPR*, 2021.

</details>
<details open>
<summary>2020</summary>

- What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation
  [[link]](https://arxiv.org/abs/2008.03703)
  [[code]](https://github.com/google-research/heldout-influence-estimation)
  [[video]](https://www.youtube.com/watch?v=XTRMSYRVBmU)
  - Vitaly Feldman and Chiyuan Zhang. *NeurIPS*, 2020.
<br><br>
- Data Valuation using Reinforcement Learning
  [[link]](https://arxiv.org/abs/1909.11671)
  [[code]](https://github.com/google-research/google-research/tree/master/dvrl)
  [[video]](https://slideslive.com/38928006)
  - Jinsung Yoon, Sercan Arik, and Tomas Pfister. *ICML*, 2020.
<br><br>
- A Distributional Framework for Data Valuation
  [[link]](https://arxiv.org/abs/2002.12334)
  [[code]](https://github.com/amiratag/DistributionalShapley)
  [[video]](https://slideslive.com/38928367)
  - Amirata Ghorbani, Michael P. Kim, and James Zou. *ICML*, 2020.
<br><br>
- Does Learning Require Memorization? A Short Tale about a Long Tail
  [[link]](https://arxiv.org/abs/1906.05271)
  - Vitaly Feldman. *STOC*, 2020.

</details>
<details open>
<summary>2019</summary>

- Data Shapley: Equitable Valuation of Data for Machine Learning
  [[link]](https://proceedings.mlr.press/v97/ghorbani19c/ghorbani19c.pdf)
  [[code]](https://github.com/amiratag/DataShapley)
  [[video]](https://www.youtube.com/watch?v=TzbFPsJ3o7U)
  - Amirata Ghorbani and James Zou. *ICML*, 2019.
<br><br>
- Towards Efficient Data Valuation Based on the Shapley Value
  [[link]](https://arxiv.org/abs/1902.10275)
  [[technical note]](https://arxiv.org/abs/2302.11431)
  - Ruoxi Jia, David Dao, Boxin Wang, Frances Ann Hubis, Nick Hynes, Nezihe Merve Gurel, Bo Li, Ce Zhang, Dawn Song, and Costas J. Spanos. *AISTATS*, 2019.

</details>
<details open>
<summary>2016</summary>

- "Influence Sketching": Finding Influential Samples in Large-Scale Regressions
  [[link]](https://arxiv.org/abs/1611.05923)
  - Mike Wojnowicz, Ben Cruz, Xuan Zhao, Brian Wallace, Matt Wolff, Jay Luan, Caleb Crable. *BigData*, 2016.

</details>
<details open>
<summary>Older</summary>

- The Shapley Value: Essays in Honor of Lloyd S. Shapley
  [[link]](http://www.library.fa.ru/files/roth2.pdf)
  - Lloyd S. Shapley and Alvin E. Roth. ISBN 052136177X. 1988.
<br><br>
- Residuals and Influence in Regression
  [[link]](https://conservancy.umn.edu/handle/11299/37076)
  - R. Dennis Cook and Sanford Weisberg. ISBN 041224280X. 1982.
<br><br>
- Detection of Influential Observations in Linear Regression
  [[link]](https://www.jstor.org/stable/1268249)
  - R. Dennis Cook. *Technometrics*, 1977.
<br><br>
- On the Uniqueness of the Shapley Value
  [[link]](https://link.springer.com/article/10.1007/BF01780630)
  - Pradeep Dubey. *International Journal of Game Theory*, 1975.
<br><br>
- A Value for n-Person Games
  [[link]](https://www.rand.org/pubs/papers/P295.html)
  - Lloyd S. Shapley. *Contributions to the Theory of Games II*, 1953.

</details>

## Gradient-Based Estimators

**Click on the arrow** next to the year show/hide the corresponding papers.

<details open>
<summary>2023</summary>

- Theoretical and Practical Perspectives on what Influence Functions Do
  [[link]](https://arxiv.org/abs/2305.16971)
  - Andrea Schioppa, Katja Filippova, Ivan Titov, and Polina Zablotskaia. 2023.
<br><br>
- TRAK: Attributing Model Behavior at Scale
  [[link]](https://arxiv.org/abs/2303.14186)
  [[code]](https://github.com/MadryLab/trak)
  - Sung Min Park, Kristian Georgiev, Andrew Ilyas, Guillaume Leclerc, and Aleksander Madry. *ICML*, 2023.

</details>
<details open>
<summary>2022</summary>

- Identifying a Training-Set Attack’s Target Using Renormalized Influence Estimation
  [[link]](https://arxiv.org/abs/2201.10055)
  [[code]](https://github.com/ZaydH/target_identification)
  - Zayd Hammoudeh and Daniel Lowd. *CCS*, 2022.
<br><br>
- Cross-Loss Influence Functions to Explain Deep Network Representations
  [[link]](https://arxiv.org/abs/2012.01685)
  [[code]](https://github.com/core-robotics-lab/cross_loss_influence_functions)
  - Andrew Silva, Rohit Chopra, and Matthew Gombolay. *AISTATS*, 2022.
<br><br>
- If Influence Functions are the Answer, Then What is the Question?
  [[link]](https://arxiv.org/abs/2209.05364)
  - Juhan Bae, Nathan Ng, Alston Lo, Marzyeh Ghassemi, and Roger Grosse. 2022.
<br><br>
- First is Better Than Last for Training Data Influence
  [[link]](https://arxiv.org/abs/2202.11844)
  - Chih-Kuan Yeh, Ankur Taly, Mukund Sundararajan, Frederick Liu, and Pradeep Ravikumar. *NeurIPS*, 2022.
<br><br>
- Influence Functions for Sequence Tagging Models
  [[link]](https://arxiv.org/abs/2210.14177)
  [[code]](https://github.com/successar/Segment_Influence_Functions)
  - Sarthak Jain, Varun Manjunatha, Byron C. Wallace, Ani Nenkova. *Findings of EMNLP*, 2022.
<br><br>
- Scaling Up Influence Functions
  [[link]](https://arxiv.org/abs/2112.03052)
  [[code]](https://github.com/google-research/jax-influence)
  [[video]](https://aaai-2022.virtualchair.net/poster_aaai5853)
  - Andrea Schioppa, Polina Zablotskaia, David Vilar Torres, and Artem Sokolov. *AAAI*, 2022.
<br><br>
- Rethinking Influence Functions of Neural Networks in the Over-Parameterized Regime
  [[link]](https://arxiv.org/abs/2112.08297)
  - Rui Zhang and Shihua Zhang. *AAAI*, 2022.
<br><br>
- TracInAD: Measuring Influence for Anomaly Detection
  [[link]](https://arxiv.org/abs/2205.01362)
  [[code]](https://github.com/TracInAD/TracInAD)
  - Hugo Thimonier, Fabrice Popineau, Arpad Rimmel, Bich-Liˆen Doan, and Fabrice Daniel. *IJCNN*, 2021.

</details>
<details open>
<summary>2021</summary>

- Influence Functions in Deep Learning Are Fragile
  [[link]](https://openreview.net/forum?id=xHKVVHGDOEk)
  [[video]](https://slideslive.com/38953709/influence-functions-in-deep-learning-are-fragile?ref=speaker-25831)
  - Samyadeep Basu, Phil Pope, and Soheil Feizi. *ICLR*, 2021.
<br><br>
- HyDRA: Hypergradient Data Relevance Analysis for Interpreting Deep Neural Networks
  [[link]](https://arxiv.org/abs/2102.02515)
  [[code]](https://github.com/cyyever/aaai_hydra)
  [[video]](https://www.youtube.com/watch?v=uLgHU1icW-o)
  - Yuanyuan Chen, Boyang Li, Han Yu, Pengcheng Wu, and Chunyan Miao. *AAAI*, 2021.
<br><br>
- On Memorization in Probabilistic Deep Generative Models
  [[link]](https://openreview.net/forum?id=PlGSgjFK2oJ)
  [[code]](https://github.com/alan-turing-institute/memorization)
  [[video]](https://slideslive.com/38968257/on-memorization-in-probabilistic-deep-generative-models?ref=recommended)
  - Gerrit J. J. van den Burg and Christopher K. I. Williams. *NeurIPS*, 2021.
<br><br>
- Understanding Instance-based Interpretability of Variational Auto-Encoders
  [[link]](https://openreview.net/forum?id=a5-37ER8qTI)
  [[code]](https://github.com/FengNiMa/VAE-TracIn-pytorch)
  [[video]](https://slideslive.com/38967896/understanding-instancebased-interpretability-of-variational-autoencoders?ref=recommended)
  - Zhifeng Kong and Kamalika Chaudhuri. *NeurIPS*, 2021.
<br><br>
- FastIF: Scalable Influence Functions for Efficient Model Interpretation and Debugging
  [[link]](https://arxiv.org/abs/2012.15781)
  [[code]](https://github.com/salesforce/fast-influence-functions)
  [[video]](https://underline.io/lecture/37878-fastif-scalable-influence-functions-for-efficient-model-interpretation-and-debugging)
  - Han Guo, Nazneen Fatema Rajani, Peter Hase, Mohit Bansal, and Caiming Xiong. *EMNLP*, 2021.
<br><br>
- Influence Estimation for Generative Adversarial Networks
  [[link]](https://arxiv.org/abs/2101.08367)
  [[code]](https://github.com/hitachi-rd-cv/influence-estimation-for-gans)
  [[video]](https://slideslive.com/38954091/influence-estimation-for-generative-adversarial-networks?ref=recommended)
  - Naoyuki Terashita, Hiroki Ohashi, Yuichi Nonaka, and Takashi Kanemaru. *ICLR*, 2021.
<br><br>
- Revisiting Methods for Finding Influential Examples
  [[link]](https://arxiv.org/abs/2111.04683)
  - Karthikeyan K and Anders Søgaard. 2021.
<br><br>
- Finding High-Value Training Data Subset through Differentiable Convex Programming
  [[link]](https://arxiv.org/abs/2104.13794)
  [[code]](https://github.com/SoumiDas/HOST-CP)
  - Soumi Das, Arshdeep Singh, Saptarshi Chatterjee, Suparna Bhattacharya, and Sourangshu Bhattacharya. *ECML-PKDD*, 2021.
<br><br>
- Representer Point Selection via Local Jacobian Expansion for Post-hoc Classifier Explanation of Deep Neural Networks and Ensemble Models
  [[link]](https://openreview.net/forum?id=Wl32WBZnSP4)
  [[code]](https://github.com/echoyi/RPS_LJE)
  [[video]](https://neurips.cc/virtual/2021/poster/27007)
  - Yi Sui, Ga Wu, and Scott Sanner. *NeurIPS*, 2021.
<br><br>
- Simple, Attack-Agnostic Defense Against Targeted Training Set Attacks Using Cosine Similarity
  [[link]](http://www.gatsby.ucl.ac.uk/~balaji/udl2021/accepted-papers/UDL2021-paper-029.pdf)
  [[code]](https://github.com/ZaydH/target_identification)
  - Zayd Hammoudeh and Daniel Lowd. *UDL*, 2021.

</details>
<details open>
<summary>2020</summary>

- Estimating Training Data Influence by Tracing Gradient Descent
  [[link]](https://arxiv.org/abs/2002.08484)
  [[code]](https://github.com/frederick0329/TracIn)
  [[video]](https://videos.neurips.cc/category/34/search/Estimating%20Training%20Data/video/slideslive-38937872?t=0)
  - Garima Pruthi, Frederick Liu, Satyen Kale, and Mukund Sundararajan. *NeurIPS*, 2020.
<br><br>
- RelatIF: Identifying Explanatory Training Samples via Relative Influence
  [[link]](http://proceedings.mlr.press/v108/barshan20a/barshan20a.pdf)
  [[video]](https://slideslive.com/38930122/relatif-identifying-explanatory-training-samples-via-relative-influence?ref=speaker-24253-latest)
  - Elnaz Barshan, Marc-Etienne Brunet, and Gintare Karolina Dziugaite. *AISTATS*, 2020.
<br><br>
- On Second-Order Group Influence Functions for Black-Box Predictions
  [[link]](https://arxiv.org/abs/1911.00418)
  [[video]](https://slideslive.com/38928194/on-secondorder-group-influence-functions-for-blackbox-predictions?ref=speaker-31594-latest&locale=cs)
  - Samyadeep Basu, Xuchen You, and Soheil Feizi. *ICML*, 2020.
<br><br>
- Efficient Estimation of Influence of a Training Instance
  [[link]](https://arxiv.org/abs/2012.04207)
  [[slides]](https://soskek.github.io/publications/sustainlp2020_video_slide.pdf)
  - Sosuke Kobayashi, Sho Yokoi, Jun Suzuki, and Kentaro Inui. *SustaiNLP*, 2020.

</details>
<details open>
<summary>2019</summary>

- On the Accuracy of Influence Functions for Measuring Group Effects
  [[link]](https://arxiv.org/abs/1905.13289)
  [[code]](https://github.com/kohpangwei/group-influence-release)
  - Pang Wei Koh, Kai-Siang Ang, Hubert H. K. Teo, and Percy Liang. *NeurIPS*, 2019.
<br><br>
- Data Cleansing for Models Trained with SGD
  [[link]](https://arxiv.org/abs/1906.08473)
  [[code]](https://github.com/sato9hara/sgd-influence)
  - Satoshi Hara, Atsushi Nitanda, and Takanori Maehara. *NeurIPS*, 2019.

</details>
<details open>
<summary>2018</summary>

- Representer Point Selection for Explaining Deep Neural Networks
  [[link]](https://arxiv.org/abs/1811.09720)
  [[code]](https://github.com/chihkuanyeh/Representer_Point_Selection)
  - Chih-Kuan Yeh, Joon Sik Kim, Ian E.H. Yen, and Pradeep Ravikumar. *NeurIPS*, 2018.

</details>
<details open>
<summary>2017</summary>

- Understanding Black-box Predictions via Influence Functions
  [[link]](https://arxiv.org/abs/1703.04730)
  [[code]](https://github.com/kohpangwei/influence-release)
  [[video]](https://www.youtube.com/watch?v=0w9fLX_T6tY)
  - Pang Wei Koh and Percy Liang. *ICML*, 2017. (**Best paper award winner**)
<br><br>
- A Closer Look at Memorization in Deep Networks
  [[link]](https://arxiv.org/abs/1706.05394)
  - Devansh Arpit, Stanislaw Jastrzebski, Nicolas Ballas, David Krueger, Emmanuel Bengio, Maxinder S. Kanwal, Tegan Maharaj, Asja Fischer, Aaron Courville, Yoshua Bengio, and Simon Lacoste-Julien. *ICML*, 2017.

</details>
<details open>
<summary>Older</summary>

- The Influence Curve and its Role in Robust Estimation
  [[link]](https://www.jstor.org/stable/2285666)
  - Frank R. Hampel. *Journal of the American Statistical Association*, 1974.
<br><br>
- The Infinitesimal Jackknife
  [[link]](https://faculty.washington.edu/fscholz/Reports/InfinitesimalJackknife.pdf)
  - Louis A. Jaeckel. 1972.

</details>


## Non-Parametric Methods

**Click on the arrow** next to the year show/hide the corresponding papers.

<details open>
<summary>2023</summary>


- Adapting and Evaluating Influence-Estimation Methods for Gradient-Boosted Decision Trees
  [[link]](https://arxiv.org/abs/2205.00359)
  [[code]](https://github.com/jjbrophy47/tree_influence)
  - Jonathan Brophy, Zayd Hammoudeh, and Daniel Lowd. *JMLR*, 2023.

</details>
<details open>
<summary>2019</summary>

- Efficient Task-Specific Data Valuation for Nearest Neighbor Algorithms
  [[link]](http://www.vldb.org/pvldb/vol12/p1610-jia.pdf)
  [[code]](https://github.com/AI-secure/KNN-PVLDB)
  [[technical note]](https://arxiv.org/pdf/2304.04258.pdf)
  - Ruoxi Jia, David Dao, Boxin Wang, Frances Ann Hubis, Nezihe Merve Gurel, Bo Li, Ce Zhang, Costas J. Spanos, and Dawn Song. *PVLDB*, 2019.

</details>
<details open>
<summary>2018</summary>

- Finding Influential Training Samples for Gradient Boosted Decision Trees
  [[link]](https://arxiv.org/abs/1802.06640)
  [[code]](https://github.com/bsharchilev/influence_boosting)
  - Boris Sharchilev, Yury Ustinovskiy, Pavel Serdyukov, and Maarten de Rijke. *ICML*, 2018.

</details>

## Applications of Influence Analysis

**Click on the arrow** next to the year show/hide the corresponding papers.

<details open>
<summary>Active Learning</summary>

- Influence Selection for Active Learning
  [[link]](https://arxiv.org/abs/2108.09331)
  [[code]](https://github.com/dragonlzm/ISAL)
  - Zhuoming Liu, Hao Ding, Huaping Zhong, Weijia Li, Jifeng Dai, and Conghui He. *ICCV*, 2021.
<br><br>
- RIM: Reliable Influence-based Active Learning on Graphs
  [[link]](https://openreview.net/forum?id=CEkbBN_-Ja8)
  [[code]](https://github.com/zwt233/RIM)
  - Wentao Zhang, Yexin Wang, Zhenbang You, Meng Cao, Ping Huang, Jiulong Shan, Zhi Yang, and Bin Cui. *NeurIPS*, 2021.

</details>
<details open>
<summary>Adversarial Attacks</summary>

- Membership Inference Attack Using Self Influence Functions
  [[link]](https://arxiv.org/abs/2205.13680)
  [[code]](https://github.com/giladcohen/sif_mi_attack)
  - Gilad Cohen and Raja Giryes. 2022.
<br><br>
- Influence Function based Data Poisoning Attacks to Top-N Recommender Systems
  [[link]](https://arxiv.org/abs/2002.08025)
  - Minghong Fang, Neil Zhenqiang Gong, and Jia Liu. *WWW*, 2020.

</details>
<details open>
<summary>Adversarial Defenses</summary>

- Identifying a Training-Set Attack’s Target Using Renormalized Influence Estimation
  [[link]](https://arxiv.org/abs/2201.10055)
  [[code]](https://github.com/ZaydH/target_identification)
  [[video]](https://dl.acm.org/doi/10.1145/3548606.3559335)
  - Zayd Hammoudeh and Daniel Lowd. *CCS*, 2022.
<br><br>
- Detecting Adversarial Samples Using Influence Functions and Nearest Neighbors
  [[link]](https://arxiv.org/abs/1909.06872)
  [[code]](https://github.com/giladcohen/NNIF_adv_defense)
  - Gilad Cohen, Guillermo Sapiro, and Raja Giryes. *CVPR*, 2020.

</details>
<details open>
<summary>Data Augmentation </summary>

- Influence-guided Data Augmentation for Neural Tensor Completion
  [[link]](https://arxiv.org/pdf/2108.10248.pdf)
  [[code]](https://github.com/srijankr/DAIN)
  - Sejoon Oh, Sungchul Kim, Ryan A. Rossi, and Srijan Kumar. *CIKM*, 2021.
<br><br>
- Learning Augmentation Network via Influence Functions
  [[link]](https://ieeexplore.ieee.org/document/9156698)
  [[video]](https://www.youtube.com/watch?v=tfsyJuTqaKo)
  - Donghoon Lee, Hyunsin Park, Trung Pham, and Chang D. Yoo. *CVPR*, 2020.


</details>
<details open>
<summary>Data Cleaning</summary>

- Resolving Training Biases via Influence-based Data Relabeling
  [[link]](https://openreview.net/forum?id=EskfH0bwNVn)
  [[code]](https://github.com/Viperccc/RDIA)
  [[video]](https://iclr.cc/virtual/2022/oral/6492)
  - Shuming Kong, Yanyan Shen, and Linpeng Huang. *ICLR*, 2022.
<br><br>
- Influence Based Re-Weighing for Labeling Noise in Medical Imaging
  [[link]](https://ieeexplore.ieee.org/document/9761479)
  - Joschka Braun, Micha Kornreich, JinHyeong Park, Jayashri Pawar, James Browning, Richard Herzog, Benjamin Odry, and Li Zhang. *ISBI*, 2022.
<br><br>
- Fortifying Toxic Speech Detectors Against Veiled Toxicity
  [[link]](https://arxiv.org/abs/2010.03154)
  [[code]](https://github.com/xhan77/veiled-toxicity-detection)
  [[video]](https://slideslive.com/38939156/fortifying-toxic-speech-detectors-against-veiled-toxicity)
  - Xiaochuang Han and Yulia Tsvetkov. *EMNLP*, 2020.


</details>
<details open>
<summary>Fairness and Explainability</summary>

- Achieving Fairness at No Utility Cost via Data Reweighing with Influence
  [[link]](https://arxiv.org/abs/2202.00787)
  [[code]](https://github.com/brandeis-machine-learning/influence-fairness)
  - Peizhao Li and Hongfu Liu. *ICML*, 2022.
<br><br>
- An Empirical Comparison of Instance Attribution Methods for NLP
  [[link]](https://arxiv.org/abs/2104.04128)
  [[video]](https://www.youtube.com/watch?v=b9AbcEDmFyg)
  [[code]](https://github.com/successar/instance_attributions_NLP)
  - Pouya Pezeshkpour, Sarthak Jain, Byron C. Wallace, and Sameer Singh. *NAACL*, 2021.
<br><br>
- Leave-One-Out Unfairness
  [[link]](https://arxiv.org/abs/2107.10171)
  [[video]](https://www.youtube.com/watch?v=vbi8bqHFoyo)
  - Emily Black and Matt Fredrikson. *FAccT*, 2021.
<br><br>
- The Many Shapley Values for Model Explanation
  [[link]](https://arxiv.org/abs/1908.08474)
  - Mukund Sundararajan and Amir Najmi. *ICML*, 2020.
<br><br>
- RelatIF: Identifying Explanatory Training Samples via Relative Influence
  [[link]](http://proceedings.mlr.press/v108/barshan20a/barshan20a.pdf)
  [[video]](https://slideslive.com/38930122/relatif-identifying-explanatory-training-samples-via-relative-influence?ref=speaker-24253-latest)
  - Elnaz Barshan, Marc-Etienne Brunet, and Gintare Karolina Dziugaite. *AISTATS*, 2020.

</details>
<details open>
<summary>Subsampling</summary>

- Less Is Better: Unweighted Data Subsampling via Influence Function
  [[link]](https://arxiv.org/abs/1912.01321)
  [[code]](https://github.com/RyanWangZf/Influence_Subsampling)
  - Zifeng Wang, Hong Zhu, Zhenhua Dong, Xiuqiang He, and Shao-Lun Huang. *AAAI*, 2020.
<br><br>
- Optimal Subsampling with Influence Functions
  [[link]](https://arxiv.org/abs/1709.01716)
  - Daniel Ting and Eric Brochu. *NeurIPS*, 2018.


</details>

## Credits

The structure of this repository is inspired by and adapted from the <a href="https://github.com/THUYimingLi/backdoor-learning-resources" target="_blank">backdoor-learning-resources</a> repository.
