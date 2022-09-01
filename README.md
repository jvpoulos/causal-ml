# Must-read recent papers and resources on {Causal}∩{ML}

Contributions are welcome. Inspired by [GNNpapers](https://github.com/thunlp/GNNPapers).

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Surveys</a></td></tr> 
<tr>
<tr><td colspan="2"><a href="#individual-treatment-effects">2. Individual treatment effects</a></td></tr>
    <td>&emsp;<a href="#heterogeneous-treatment-effects">2.1. Heterogeneous treatment effects</a></td>
    <td>&emsp;<a href="#static-data">2.2. Static data</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#temporal-data">2.3. Temporal data</a></td>
</tr> 
<tr><td colspan="2"><a href="#representation-learning">3. Representation learning</a></td></tr>
<tr><td colspan="2"><a href="#semiparametric-inference">4. Semiparametric / double robust inference</a></td></tr>
<tr><td colspan="2"><a href="#policy-learning">5. Policy learning / causal discovery</a></td></tr>
<tr><td colspan="2"><a href="#causal-recommendation">6. Causal recommendation</a></td></tr>
<tr><td colspan="2"><a href="#causal-reinforcement-learning">7. Causal reinforcement learning</a></td></tr>
<tr><td colspan="2"><a href="#causal-reinforcement-learning">8. Feature selection in causal inference</a></td></tr>
<tr><td colspan="2"><a href="#applications">9. Applications</a></td>
    <td>&emsp;<a href="#social-sciences">9.1. Social Sciences</a></td>
    <td>&ensp;<a href="#text">9.2. Text</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#text">9.3. Health</a></td>
</tr> 
<tr><td colspan="2"><a href="#resources">10. Resources</a></td></tr> 
    <td>&emsp;<a href="#workshops">10.1. Workshops</a></td>
    <td>&emsp;<a href="#proceedings">10.2. Proceedings</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#code-libraries">10.3. Code libraries</a></td>
    <td>&emsp;<a href="#benchmark-datasets">10.4. Benchmark datasets</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#courses">10.5. Courses</a></td>
    <td>&emsp;<a href="#industry">10.6. Industry</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#groups">10.7. Groups</a></td>
    <td>&emsp;<a href="#lists">10.8. Lists</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#books">10.9. Books</a></td>
</tr> 
</table>

## [Survey papers](#content)

1. **Causal Machine Learning: A Survey and Open Problems**, 2022. [paper](https://arxiv.org/abs/2206.15475)

    Jean Kaddour, Aengus Lynch, Qi Liu, Matt J. Kusner, Ricardo Silva.

1. **Toward Causal Representation Learning**, *IEEE*, 2021. [paper](https://ieeexplore.ieee.org/abstract/document/9363924)
    
    Bernhard Schölkopf, Francesco Locatello, Stefan Bauer, Nan Rosemary Ke, Nal Kalchbrenner, Anirudh Goyal, Yoshua Bengio.

1. **A Survey of Learning Causality with Data: Problems and Methods**, *ACM*, 2020. [paper](https://arxiv.org/abs/1809.09337)
    
    Ruocheng Guo, Lu Cheng, Jundong Li, P. Richard Hahn, Huan Liu.

1. **Machine learning and causal inference for policy evaluation**, *KDD*, 2015. [paper](https://dl.acm.org/citation.cfm?id=2785466)
    
    Susan Athey.

## [Individual treatment effects](#content) 

### [Heterogeneous treatment effects](#content)  

1. **Can Transformers be Strong Treatment Effect Estimators?**, *arxiv*, 2022. [paper](https://arxiv.org/abs/2202.01336) [code](https://github.com/hlzhang109/TransTEE)

    Yi-Fan Zhang, Hanlin Zhang, Zachary C. Lipton, Li Erran Li, Eric P. Xing.

1. **Causal Effect Inference for Structured Treatments**, *NeurIPS*, 2021. [paper](https://arxiv.org/abs/2106.01939) [code](https://github.com/JeanKaddour/SIN)
    
    Jean Kaddour, Yuchen Zhu, Qi Liu, Matt J. Kusner, Ricardo Silva.

1. **Quasi-Oracle Estimation of Heterogeneous Treatment Effects**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1712.04912)

    Xinkun Nie, Stefan Wager.

1. **Generalized Random Forests**, *Annals of Statistics*, 2019. [paper](https://arxiv.org/abs/1610.01271)

    Susan Athey, Julie Tibshirani, Stefan Wager.

1. **Machine Learning Estimation of Heterogeneous Treatment Effects with Instruments**, *NeurIPS*, 2019. [paper](https://arxiv.org/abs/1905.10176)
    
    Vasilis Syrgkanis, Victor Lei, Miruna Oprescu, Maggie Hei, Keith Battocchi, Greg Lewis.

1. **Orthogonal Random Forest for Causal Inference**, *PMLR*, 2019. [paper](http://proceedings.mlr.press/v97/oprescu19a.html)

    Miruna Oprescu, Vasilis Syrgkanis, Zhiwei Steven Wu.

1. **Meta-learners for Estimating Heterogeneous Treatment Effects using Machine Learning**, *PNAS*, 2019. [paper](https://arxiv.org/abs/1706.03461)

    Miruna Oprescu, Vasilis Syrgkanis, Zhiwei Steven Wu.

1. **Machine Learning Analysis of Heterogeneity in the Effect of Student Mindset Interventions**, *Observational Studies*, 2019. [paper](https://arxiv.org/abs/1811.05975)
    
    Fredrik D. Johansson.

1. **Estimation and Inference of Heterogeneous Treatment Effects using Random Forests**, *JASA*, 2018. [paper](https://amstat.tandfonline.com/doi/full/10.1080/01621459.2017.1319839#.XaPLBeZKhhE)
    
    Stefan Wager, Susan Athey.

1. **Limits of Estimating Heterogeneous Treatment Effects: Guidelines for Practical Algorithm Design**, *PMLR*, 2018. [paper](http://proceedings.mlr.press/v80/alaa18a.html)
    
    Ahmed Alaa, Mihaela Schaar.

1. **Transfer Learning for Estimating Causal Effects using Neural Networks**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1808.07804)

    Sören R. Künzel, Bradly C. Stadie, Nikita Vemuri, Varsha Ramakrishnan, Jasjeet S. Sekhon, Pieter Abbeel.

1. **Recursive partitioning for heterogeneous causal effects**, *PNAS*, 2016. [paper](https://www.pnas.org/content/113/27/7353)
    
    Susan Athey, Guido Imbens.

1. **Machine Learning Methods for Estimating Heterogeneous Causal Effects**, *ArXiv*, 2015. [paper](https://arxiv.org/abs/1504.01132v1)

    Susan Athey, Guido W. Imbens.


### [Static data](#content) 

1. **VCNet and Functional Targeted Regularization For Learning Causal Effects of Continuous Treatments**, *ICLR*, 2021. [paper](https://arxiv.org/abs/2103.07861)  [code](https://github.com/lushleaf/varying-coefficient-net-with-functional-tr)

    Lizhen Nie, Mao Ye, Qiang Liu, Dan Nicolae.

1. **Learning Counterfactual Representations for Estimating Individual Dose-Response Curves**, *AAAI*, 2020. [paper](https://arxiv.org/abs/1902.00981) [code](https://github.com/d909b/drnet)

    Patrick Schwab, Lorenz Linhardt, Stefan Bauer, Joachim M. Buhmann, Walter Karlen.

1. **Estimating the Effects of Continuous-valued Interventions using Generative Adversarial Networks**, *NeurIPS*, 2020. [paper](https://arxiv.org/abs/2002.12326) [code](https://github.com/ioanabica/SCIGAN)

    Ioana Bica, James Jordon, Mihaela van der Schaar.

1. **Learning Individual Causal Effects from Networked Observational Data**, *WSDM*, 2020. [paper](https://arxiv.org/abs/1906.03485) [code](https://github.com/rguo12/network-deconfounder-wsdm20)

    Ruocheng Guo, Jundong Li, Huan Liu.

1. **Learning Overlapping Representations for the Estimation of Individualized Treatment Effects**, *AISTATS*, 2020. [paper](https://arxiv.org/abs/2001.04754)

    Yao Zhang, Alexis Bellot, Mihaela van der Schaar.

1. **Adapting Neural Networks for the Estimation of Treatment Effects**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1906.02120) [code](http://github.com/claudiashi57/dragonnet)
    
    Claudia Shi, David M. Blei, Victor Veitch.

1. **Program Evaluation and Causal Inference with High-Dimensional Data**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1311.2645)
    
    Alexandre Belloni, Victor Chernozhukov, Ivan Fernández-Val, Christian Hansen.    

1. **GANITE: Estimation of Individualized Treatment Effects using Generative Adversarial Nets**, *ICLR*, 2018. [paper](https://openreview.net/pdf?id=ByKWUeWA-) [code](https://github.com/jsyoon0823/GANITE)
    
    Jinsung Yoon, James Jordon, Mihaela van der Schaar.

1. **Estimation of Individual Treatment Effect in Latent Confounder Models via Adversarial Learning**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1811.08943)
    
    Changhee Lee, Nicholas Mastronarde, Mihaela van der Schaar.

1. **Deep IV: A Flexible Approach for Counterfactual Prediction**, *PMLR*, 2017. [paper](http://proceedings.mlr.press/v70/hartford17a.html)
    
    Uri Shalit, Fredrik D. Johansson, David Sontag.

1. **Causal Effect Inference with Deep Latent-Variable Models**, *arXiv*, 2017. [paper](https://arxiv.org/abs/1705.08821) [code](https://github.com/AMLab-Amsterdam/CEVAE)
    
    Christos Louizos, Uri Shalit, Joris Mooij, David Sontag, Richard Zemel, Max Welling.

1. **Estimating individual treatment effect: generalization bounds and algorithms**, *PMLR*, 2017. [paper](http://proceedings.mlr.press/v70/shalit17a.html) [code](https://github.com/clinicalml/cfrnet)
    
    Uri Shalit, Fredrik D. Johansson, David Sontag.

### [Temporal data](#content) 

1. **Time Series Deconfounder: Estimating Treatment Effects over Time in the Presence of Hidden Confounders**, *ICML*, 2020. [paper](https://arxiv.org/abs/1902.00450) [code](https://github.com/ioanabica/Time-Series-Deconfounder)

    Ioana Bica, Ahmed M. Alaa, Mihaela van der Schaar.

1. **Estimating Counterfactual Treatment Outcomes over Time through Adversarially Balanced Representations**, *ICLR*, 2020. [paper](https://openreview.net/pdf?id=BJg866NFvB) [code](https://github.com/ioanabica/Counterfactual-Recurrent-Network)

    Ioana Bica, Ahmed M. Alaa, James Jordon, Mihaela van der Schaar.

1. **Generative Learning of Counterfactual for Synthetic Control Applications in Econometrics**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1910.07178)
    
    Chirag Modi, Uros Seljak.

1. **Robust Synthetic Control**, *JMLR*, 2019. [paper](http://www.jmlr.org/papers/volume19/17-777.pdf)
    
    Muhammad Amjad, Devavrat Shah, Dennis Shen.

1. **ArCo: An artificial counterfactual approach for high-dimensional panel time-series data**, *Journal of Econometrics*, 2018. [paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2823687)
    
    Carlos Carvalho, Ricardo Masini, Marcelo C. Medeiros.

1. **Forecasting Treatment Responses Over Time Using Recurrent Marginal Structural Networks**, *NIPS*, 2018. [paper](https://papers.nips.cc/paper/7977-forecasting-treatment-responses-over-time-using-recurrent-marginal-structural-networks) [code](https://github.com/sjblim/rmsn_nips_2018)
    
    Sonali Parbhoo, Stefan Bauer, Patrick Schwab.

## [Representation learning](#content)   

1. **Deep Structural Causal Models for Tractable Counterfactual Inference**, *NeurIPS*, 2020. [paper](https://arxiv.org/abs/2006.06485) [code](https://github.com/biomedia-mira/deepscm)

    Nick Pawlowski, Daniel C. Castro, Ben Glocker.

1. **NCoRE: Neural Counterfactual Representation Learning for Combinations of Treatments**, *arXiv*, 2021. [paper](https://arxiv.org/abs/2103.11175)
    
    Sonali Parbhoo, Stefan Bauer, Patrick Schwab.

1. **Perfect Match: A Simple Method for Learning Representations For Counterfactual Inference With Neural Networks**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1810.00656) [code](https://github.com/d909b/perfect_match)
    
    Patrick Schwab, Lorenz Linhardt, Walter Karlen.

1. **Representation Learning for Treatment Effect Estimation from Observational Data**, *NeurIPS*, 2019. [paper](https://papers.nips.cc/paper/7529-representation-learning-for-treatment-effect-estimation-from-observational-data.pdf) 
    
    Liuyi Yao et al.

1. **Invariant Models for Causal Transfer Learning**, *JMLR*, 2018. [paper](http://jmlr.org/papers/v19/16-432.html) 
    
    Mateo Rojas-Carulla, Bernhard Schölkopf, Richard Turner, Jonas Peters.

1. **Learning Representations for Counterfactual Inference**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1605.03661) [code](https://github.com/clinicalml/cfrnet)
    
    Fredrik D. Johansson, Uri Shalit, David Sontag.

## [Semiparametric / double robust inference](#content)  

1. **Sparsity Double Robust Inference of Average Treatment Effects**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1905.00744)
    
    Jelena Bradic, Stefan Wager, Yinchu Zhu.

1. **Deep Neural Networks for Estimation and Inference**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1809.09953)
    
    Max H. Farrell, Tengyuan Liang, Sanjog Misra.

1. **Approximate Residual Balancing: De-Biased Inference of Average Treatment Effects in High Dimensions**, *JRSS-B*, 2018. [paper](https://arxiv.org/abs/1604.07125)
    
    Susan Athey, Guido W. Imbens, Stefan Wager.

1. **Deep Counterfactual Networks with Propensity-Dropout**, *arXiv*, 2017. [paper](https://arxiv.org/abs/1706.05966)
    
    Ahmed M. Alaa, Michael Weisz, Mihaela van der Schaar.

1. **Double/Debiased Machine Learning for Treatment and Causal Parameters**, *arXiv*, 2017. [paper](https://arxiv.org/abs/1608.00060)
    
    Victor Chernozhukov, Denis Chetverikov, Mert Demirer, Esther Duflo, Christian Hansen, Whitney Newey, James Robins.

1. **Doubly Robust Policy Evaluation and Optimization**, *Statistical Science*, 2014. [paper](https://arxiv.org/abs/1503.02834)
    
    Miroslav Dudík, Dumitru Erhan, John Langford, Lihong Li.

## [Policy learning / causal discovery](#content)  

1. **Differentiable Causal Discovery Under Unmeasured Confounding**, *arXiv*, 2021. [paper](https://arxiv.org/abs/2010.06978)
    
    Rohit Bhattacharya, Tushar Nagarajan, Daniel Malinsky, Ilya Shpitser.

1. **Causal Discovery with Attention-Based Convolutional Neural Networks**, *Machine Learning and Knowledge Extraction*, 2019. [paper](https://www.mdpi.com/2504-4990/1/1/19) [code](https://github.com/M-Nauta/TCDF)
    
    Meike Nauta, Doina Bucur, Christin Seifert.

1. **A Meta-Transfer Objective for Learning to Disentangle Causal Mechanisms**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1901.10912)
    
    Yoshua Bengio, Tristan Deleu, Nasim Rahaman, Rosemary Ke, Sébastien Lachapelle, Olexa Bilaniuk, Anirudh Goyal, Christopher Pal.

1. **Causal Discovery with Reinforcement Learning**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1906.04477)
    
    Shengyu Zhu, Zhitang Chen.

1. **CausalGAN: Learning Causal Implicit Generative Models with Adversarial Training**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1709.02023)
    
    Murat Kocaoglu, Christopher Snyder, Alexandros G. Dimakis, Sriram Vishwanath.

1. **Learning When-to-Treat Policies**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1905.09751)
    
    Xinkun Nie, Emma Brunskill, Stefan Wager.

1. **Learning Neural Causal Models from Unknown Interventions**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1910.01075) [code](https://github.com/nke001/causal_learning_unknown_interventions)
    
    Nan Rosemary Ke, Olexa Bilaniuk, Anirudh Goyal, Stefan Bauer, Hugo Larochelle, Chris Pal, Yoshua Bengio.

1. **Counterfactual Policy Optimization Using Domain-Adversarial Neural Networks**, *ICML*, 2018. [paper](http://medianetlab.ee.ucla.edu/papers/cf_treat_v5)
    
    Onur Atan, William R. Zame, Mihaela van der Schaar.

1. **Causal Bandits: Learning Good Interventions via Causal Inference**, *NIPS*, 2016. [paper](https://papers.nips.cc/paper/6195-causal-bandits-learning-good-interventions-via-causal-inference)
    
    Finnian Lattimore, Tor Lattimore, Mark D. Reid.

1. **Counterfactual Risk Minimization: Learning from Logged Bandit Feedback**, *arXiv*, 2015. [paper](https://arxiv.org/abs/1502.02362)
    
    Adith Swaminathan, Thorsten Joachims.

## [Causal recommendation](#content) 

1. **The Deconfounded Recommender: A Causal Inference Approach to Recommendation**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1808.06581) [code](https://github.com/blei-lab/deconfounder_tutorial)
    
    Yixin Wang, Dawen Liang, Laurent Charlin, David M. Blei. 

1. **The Blessings of Multiple Causes**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1805.06826)
    
    Yixin Wang, David M. Blei. 

<details><summary> comments </summary> 

3. **Comment: Reflections on the Deconfounder**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1910.08042)

    Alexander D'Amour

1. **On Multi-Cause Causal Inference with Unobserved Confounding: Counterexamples, Impossibility, and Alternatives**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1902.10286)

    Alexander D'Amour

1. **Comment on "Blessings of Multiple Causes"**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1910.05438)
    
    Elizabeth L. Ogburn, Ilya Shpitser, Eric J. Tchetgen Tchetgen.

1. **The Blessings of Multiple Causes: A Reply to Ogburn et al. (2019)**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1910.07320)
    
    Yixin Wang, David M. Blei.

</details>

7. **Recommendations as Treatments: Debiasing Learning and Evaluation**, *PMLR*, 2016. [paper](http://proceedings.mlr.press/v48/schnabel16.html)
    
    Tobias Schnabel, Adith Swaminathan, Ashudeep Singh, Navin Chandak, Thorsten Joachims.

1. **Collaborative Prediction and Ranking with Non-Random Missing Data**, *RecSys*, 2009. [paper](http://www.cs.toronto.edu/~zemel/documents/acmrec2009-MarlinZemel.pdf)
    
    Benjamin M. Marlin, Richard S. Zemel.

## [Causal reinforcement learning](#content) 

1. **Counterfactual Multi-Agent Policy Gradients**, *AAAI*, 2018. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/17193)
    
    Jakob N. Foerster, Gregory Farquhar, Triantafyllos Afouras, Nantas Nardelli, Shimon Whiteson. 

## [Feature Selection in causal inference](#content)

1. **Ultra-high dimensional variable selection for doubly robust causal inference**, *Biometrics*, 2022. [paper](https://arxiv.org/abs/2007.14190) [code](https://github.com/dingketang/ultra-high-DRCI) [slides](https://drive.google.com/file/d/1OlwNi9eMu_MQe3TyiHpHg2ULdfGD2x0S/view?usp=sharing)

    Dingke Tang, Dehan Kong, Wenliang Pan, Linbo Wang

1. **Outcome‐adaptive lasso: variable selection for causal inference**, *Biometrics* 2017. [paper](https://onlinelibrary.wiley.com/doi/pdf/10.1111/biom.12679?casa_token=_xFuHHhoWlAAAAAA:gKO0JyJC0g54pOfbOVlNew7t1M29UD_A46yJJUAGiLAuxO87p4lGmMneYklKfuWGiHCitIbvKtjfEMAN)  [video](https://crossminds.ai/video/variable-selection-for-causal-inference-outcome-adaptive-lasso-6070a5f9fa08279acdb2124a/)

    Susan M. Shortreed, Ashkan Ertefaie

## [Applications](#content)

### [Social sciences](#content)

1. **State-Building through Public Land Disposal? An Application of Matrix Completion for Counterfactual Prediction**, *arXiv*, 2021. [paper](https://arxiv.org/abs/1903.08028) [code](https://github.com/jvpoulos/homesteads)
    
    Jason Poulos.

1. **RNN-based counterfactual prediction, with an application to homestead policy and public schooling**, *JRSS-C*, 2021. [paper](http://jasonvpoulos.com/papers/17117351.pdf) [code](https://github.com/jvpoulos/rnns-causal)
    
    Jason Poulos, Shuxi Zeng.

1. **Estimating Treatment Effects with Causal Forests: An Application**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1902.07409)
    
    Susan Athey, Stefan Wager.

1. **Ensemble Methods for Causal Effects in Panel Data Settings**, *AER P&P*, 2019. [paper](https://arxiv.org/abs/1903.10079)
    
    Susan Athey, Mohsen Bayati, Guido W. Imbens, Zhaonan Qu.

### [Text](#content)

1. **Counterfactual Data Augmentation for Neural Machine Translation**, *ACL*, 2021. [paper](https://www.aclweb.org/anthology/2021.naacl-main.18/) [code](https://github.com/xxxiaol/GCI)
    
     Qi Liu, Matt Kusner, Phil Blunsom.

1. **Everything Has a Cause: Leveraging Causal Inference in Legal Text Analysis**, *arXIv*, 2021. [paper](https://arxiv.org/abs/2104.09420) [code](https://github.com/xxxiaol/GCI)
    
     Xiao Liu, Da Yin, Yansong Feng, Yuting Wu, Dongyan Zhao.

1. **Causal Effects of Linguistic Properties**, *arXIv*, 2021. [paper](https://arxiv.org/abs/2010.12919)
    
     Reid Pryzant, Dallas Card, Dan Jurafsky, Victor Veitch, Dhanya Sridhar.

1. **Sketch and Customize: A Counterfactual Story Generator**, *arXIv*, 2021. [paper](https://arxiv.org/abs/2104.00929)
    
    Changying Hao, Liang Pang, Yanyan Lan, Yan Wang, Jiafeng Guo, Xueqi Cheng.

1. **Counterfactual Generator: A Weakly-Supervised Method for Named Entity Recognition**, *EMNLP*, 2020. [paper](https://github.com/xijiz/cfgen/blob/master/docs/cfgen.pdf) [code](https://github.com/xijiz/cfgen)
    
    Xiangji Zeng, Yunliang Li, Yuchen Zhai, Yin Zhang.

1. **Using Text Embeddings for Causal Inference**, *arXIv*, 2019. [paper](https://arxiv.org/abs/1905.12741) [code](https://github.com/blei-lab/causal-text-embeddings)
    
    Victor Veitch, Dhanya Sridhar, David M. Blei.

1. **Counterfactual Story Reasoning and Generation**, *arXIv*, 2019. [paper](https://arxiv.org/abs/1909.04076)
    
    Lianhui Qin, Antoine Bosselut, Ari Holtzman, Chandra Bhagavatula, Elizabeth Clark, Yejin Choi.

1. **How to Make Causal Inferences Using Texts**, *arXIv*, 2018. [paper](https://arxiv.org/abs/1802.02163)

    Naoki Egami, Christian J. Fong, Justin Grimmer, Margaret E. Roberts, Brandon M. Stewart.

### [Health](#content)

1. **Targeted learning in observational studies with multi-level treatments: An evaluation of antipsychotic drug treatment safety for patients with serious mental illnesses**, *arXIv*, 2022. [paper](https://arxiv.org/abs/2206.15367)
    
     Jason Poulos, Marcela Horvitz-Lennon, Katya Zelevinsky, Thomas Huijskens, Pooja Tyagi, Jiaju Yan, Jordi Diaz, Tudor Cristea-Platon, Sharon-Lise Normand.

## [Resources](#content)

### [Workshops](#content)

1. **NeurIPS 2021 Workshop** [link](https://why21.causalai.net/)

1. **UAI 2021 Workshop** [link](https://sites.google.com/uw.edu/causaluai2021/home?authuser=0)

1. **KDD 2021 Workshop** [link](https://bcirwis2021.github.io/cfp.html)

1. **ICML 2021 Workshop** [link](https://sites.google.com/view/naci2021/home)

1. **EMNLP 2021 Workshop** [link](https://causaltext.github.io/2021/)

1. **NeurIPS 2020 Workshop** [link](https://www.cmu.edu/dietrich/causality/neurips20ws/)

1. **NeurIPS 2019 Workshop** [link](http://tripods.cis.cornell.edu/neurips19_causalml/)

1. **NIPS 2018 Workshop** [link](https://sites.google.com/view/nips2018causallearning/home)

1. **NIPS 2017 Workshop** [link](https://sites.google.com/view/causalnips2017)

1. **NIPS 2016 Workshop** [link](https://sites.google.com/site/whatif2016nips/)

1. **NIPS 2013 Workshop** [link](http://clopinet.com/isabelle/Projects/NIPS2013/)

### [Proceedings](#content)

1. **PMLR, Volume 6: Causality: Objectives and Assessment, 12 December 2008, Whistler, Canada** [link](http://proceedings.mlr.press/v6/)

### [Code libraries](#content)

1. **Causal Inference 360: A Python package for inferring causal effects from observational data.** [link](https://github.com/IBM/causallib)

1. **WhyNot: A Python package connecting tools from causal inference and reinforcement learning with a range of complex simulators** [link](https://github.com/zykls/whynot)

1. **EconML: A Python Package for ML-Based Heterogeneous Treatment Effects Estimation** [link](https://github.com/microsoft/EconML)

1. **Uplift modeling and causal inference with machine learning algorithms** [link](https://github.com/uber/causalml)

### [Benchmark datasets](#content)

1. **IHDP, Jobs, and News benchmarks** [link](https://fredjo.com/)

1. **Twins** [link](http://www.nber.org/data/linked-birth-infant-death-data-vitalstatistics-data.htm)

1. **Causality workbench** [link](http://www.causality.inf.ethz.ch/repository.php?page=data)

### [Courses](#content)

1. **CS7792 - Counterfactual Machine Learning** [link](http://www.cs.cornell.edu/courses/cs7792/2016fa/)

1. **Introduction to Causal Inference** [link](https://www.bradyneal.com/causal-inference-course)

1. **Machine Learning & Causal Inference: A Short Course** [link](https://www.youtube.com/playlist?list=PLxq_lXOUlvQAoWZEqhRqHNezS30lI49G-)

1. **KDD 2020: Lecture Style Tutorials: Casual Inference Meets Machine Learning** [link](https://www.youtube.com/watch?v=DbW2e2q8Gjs)

### [Industry](#content)

1. **Causality and Machine Learning: Microsoft Research** [link](https://www.microsoft.com/en-us/research/group/causal-inference/#!publications)

### [Groups](#content)

1. **Society for Causal Inference** [link](https://sci-info.org/)

1. **Research Laboratory led by Prof. Mihaela van der Schaar** [link](http://www.vanderschaar-lab.com/NewWebsite/causal_inference_and_treatment_effects.html)

### [Lists](#content)

1. **An index of algorithms for learning causality with data** [link](https://github.com/rguo12/awesome-causality-algorithms)

1. **An index of datasets that can be used for learning causality** [link](https://github.com/rguo12/awesome-causality-data)

1. **Papers about Causal Inference and Language** [link](https://github.com/causaltext/causal-text-papers)

### [Books](#content)

1. **Causal Machine Learning** [link](https://www.manning.com/books/causal-machine-learning)
