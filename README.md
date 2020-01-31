# Must-read recent papers and resources on {Causal}∩{ML}

Contributions are welcome. Inspired by [GNNpapers](https://github.com/thunlp/GNNPapers).

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Surveys</a></td></tr> 
<tr><td colspan="2"><a href="#counterfactual-prediction">2. Counterfactual prediction / individual treatment effects</a></td></tr>
<tr><td colspan="2"><a href="#representation-learning">3. Representation learning</a></td></tr>
<tr><td colspan="2"><a href="#dimensionality-reduction">4. Dimensionality reduction / regression adjustment</a></td></tr>
<tr><td colspan="2"><a href="#heterogeneous-treatment-effects">5. Heterogeneous treatment effects</a></td></tr>
<tr><td colspan="2"><a href="#missing-data-imputation">6. Missing data imputation</a></td></tr>
<tr><td colspan="2"><a href="#semiparametric-inference">7. Semiparametric / double robust inference</a></td></tr>
<tr><td colspan="2"><a href="#policy-learning">8. Policy learning / causal discovery</a></td></tr>
<tr><td colspan="2"><a href="#causal-recommendation">9. Causal recommendation</a></td></tr>
<tr><td colspan="2"><a href="#applications">10. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="social-sciences">10.1. Social Sciences</a></td>
    <td>&ensp;<a href="#text">10.2. Text</a></td>
</tr> 
<tr><td colspan="2"><a href="#resources">11. Resources</a></td></tr> 
<tr>
    <td>&emsp;<a href="#workshops">11.1. Workshops</a></td>
    <td>&emsp;<a href="#proceedings">11.2. Proceedings</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#code-libraries">11.3. Code libraries</a></td>
    <td>&emsp;<a href="#benchmark-datasets">11.4. Benchmark datasets</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#courses">11.5. Courses</a></td>
    <td>&emsp;<a href="#industry">11.6. Industry</a></td>
</tr> 
</table>

## [Survey papers](#content)
1. **Machine learning and causal inference for policy evaluation**, *KDD*, 2015. [paper](https://dl.acm.org/citation.cfm?id=2785466)
    
    Susan Athey.

## [Counterfactual prediction / individual treatment effects](#content)  

1. **Generative Learning of Counterfactual for Synthetic Control Applications in Econometrics**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1910.07178)
    
    Chirag Modi, Uros Seljak.

1. **Adapting Neural Networks for the Estimation of Treatment Effects**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1906.02120) [code](http://github.com/claudiashi57/dragonnet)
    
    Claudia Shi, David M. Blei, Victor Veitch.

1. **RNN-based counterfactual prediction**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1712.03553) [code](https://github.com/jvpoulos/rnns-causal)
    
    Jason Poulos.

1. **Matrix Completion Methods for Causal Panel Data Models**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1710.10251)
    
    Susan Athey, Mohsen Bayati, Nikolay Doudchenko, Guido Imbens, Khashayar Khosravi.

1. **Forecasting Treatment Responses Over Time Using Recurrent Marginal Structural Networks**, *NIPS*, 2018. [paper](http://proceedings.mlr.press/v70/hartford17a.html)
    
    Bryan Lim, Ahmed Alaa, Mihaela van der Schaar.

1. **GANITE: Estimation of Individualized Treatment Effects using Generative Adversarial Nets**, *ICLR*, 2018. [paper](https://openreview.net/pdf?id=ByKWUeWA-)
    
    Jinsung Yoon, James Jordon, Mihaela van der Schaar.


1. **Estimation of Individual Treatment Effect in Latent Confounder Models via Adversarial Learning**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1811.08943)
    
    Changhee Lee, Nicholas Mastronarde, Mihaela van der Schaar.

1. **Deep IV: A Flexible Approach for Counterfactual Prediction**, *PMLR*, 2017. [paper](http://proceedings.mlr.press/v70/hartford17a.html)
    
    Uri Shalit, Fredrik D. Johansson, David Sontag.

1. **Causal Effect Inference with Deep Latent-Variable Models**, *arXiv*, 2017. [paper](https://arxiv.org/abs/1705.08821)
    
    Christos Louizos, Uri Shalit, Joris Mooij, David Sontag, Richard Zemel, Max Welling.

1. **Estimating individual treatment effect: generalization bounds and algorithms**, *PMLR*, 2017. [paper](http://proceedings.mlr.press/v70/shalit17a.html) [code](https://github.com/clinicalml/cfrnet)
    
    Uri Shalit, Fredrik D. Johansson, David Sontag.

## [Representation learning](#content)   

1. **Representation Learning for Treatment Effect Estimation from Observational Data**, *NeurIPS*, 2019. [paper](https://papers.nips.cc/paper/7529-representation-learning-for-treatment-effect-estimation-from-observational-data.pdf) 
    
    Liuyi Yao et al.

1. **Invariant Models for Causal Transfer Learning**, *JMLR*, 2018. [paper](http://jmlr.org/papers/v19/16-432.html) 
    
    Mateo Rojas-Carulla, Bernhard Schölkopf, Richard Turner, Jonas Peters.

1. **Learning Representations for Counterfactual Inference**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1605.03661) [code](https://github.com/clinicalml/cfrnet)
    
    Fredrik D. Johansson, Uri Shalit, David Sontag.

## [Dimensionality reduction / regression adjustment](#content)  

1. **Robust Synthetic Control**, *JMLR*, 2019. [paper](http://www.jmlr.org/papers/volume19/17-777.pdf)
    
    Muhammad Amjad, Devavrat Shah, Dennis Shen.

1. **ArCo: An artificial counterfactual approach for high-dimensional panel time-series data**, *Journal of Econometrics*, 2018. [paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2823687)
    
    Carlos Carvalho, Ricardo Masini, Marcelo C. Medeiros.

1. **Lasso adjustments of treatment effect estimates in randomized experiments**, *PNAS*, 2016. [paper](https://www.pnas.org/content/113/27/7383.short)
    
    Adam Bloniarz, Hanzhong Liu, Cun-Hui Zhang, Jasjeet S. Sekhon, Bin Yu.

## [Heterogeneous treatment effects](#content)  

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

## [Missing data imputation](#content)  


1. **GP-VAE: Deep Probabilistic Time Series Imputation**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1907.04155) 

    Vincent Fortuin, Dmitry Baranchuk, Gunnar Rätsch, Stephan Mandt.

1. **NAOMI: Non-Autoregressive Multiresolution Sequence Imputation**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1901.10946) 

    Yukai Liu, Rose Yu, Stephan Zheng, Eric Zhan, Yisong Yue.

1. **GAIN: Missing Data Imputation using Generative Adversarial Nets**, *ICML*, 2018. [paper](http://medianetlab.ee.ucla.edu/papers/ICML_GAIN.pdf) [code](https://github.com/jsyoon0823/GAIN)

    Jinsung Yoon, James Jordon, Mihaela van der Schaar.

1. **MIDA: Multiple Imputation using Denoising Autoencoders**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1705.02737) [code](https://github.com/lgondara/loss-to-followup-DAE)

    Lovedeep Gondara, Ke Wang.

1. **Recurrent Neural Networks for Multivariate Time Series with Missing Values**, *Scientific Reports*, 2018. [paper](https://www.nature.com/articles/s41598-018-24271-9) [code](https://github.com/zhiyongc/GRU-D)

    Zhengping Che, Sanjay Purushotham, Kyunghyun Cho, David Sontag, Yan Liu.

1. **BRITS: Bidirectional Recurrent Imputation for Time Series**, *NeurIPS*, 2018. [paper](https://papers.nips.cc/paper/7911-brits-bidirectional-recurrent-imputation-for-time-series.pdf) 

    Wei Cao et al.

1. **Estimating Missing Data in Temporal Data Streams Using Multi-directional Recurrent Neural Networks**, *arXiv*, 2017. [paper](https://arxiv.org/abs/1711.08742) [code](https://github.com/jsyoon0823/MRNN)

    Jinsung Yoon, William R. Zame, Mihaela van der Schaar.

1. **Geometric Matrix Completion with Recurrent Multi-Graph Neural Networks**, *NeurIPS*, 2017. [paper](https://papers.nips.cc/paper/6960-geometric-matrix-completion-with-recurrent-multi-graph-neural-networks.pdf) [code](https://github.com/dtsbourg/magnesium)

    Federico Monti, Michael M. Bronstein, Xavier Bresson.

1. **Modeling Missing Data in Clinical Time Series with RNNs**, *JMLR*, 2016. [paper](http://proceedings.mlr.press/v56/Lipton16.pdf) 

    Zachary C. Lipton, David C. Kale, Randall Wetzel.

## [Semiparametric / double robust inference](#content)  

1. **Sparsity Double Robust Inference of Average Treatment Effects**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1905.00744)
    
    Jelena Bradic, Stefan Wager, Yinchu Zhu.

1. **Time Series Deconfounder: Estimating Treatment Effects over Time in the Presence of Hidden Confounders**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1902.00450)
    
    Ioana Bica, Ahmed M. Alaa, Mihaela van der Schaar.

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

1. **A Meta-Transfer Objective for Learning to Disentangle Causal Mechanisms**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1901.10912)
    
    Yoshua Bengio, Tristan Deleu, Nasim Rahaman, Rosemary Ke, Sébastien Lachapelle, Olexa Bilaniuk, Anirudh Goyal, Christopher Pal.

1. **Causal Discovery with Reinforcement Learning**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1906.04477)
    
    Shengyu Zhu, Zhitang Chen.

1. **Adversarial Generalized Method of Moments**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1803.07164) [code](https://github.com/vsyrgkanis/adversarial_gmm)
    
    Greg Lewis, Vasilis Syrgkanis.

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

1. **The Deconfounded Recommender: A Causal Inference Approach to Recommendation**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1808.06581)
    
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

## [Applications](#content)

### [Social sciences](#content)

1. **State-Building through Public Land Disposal? An Application of Matrix Completion for Counterfactual Prediction**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1903.08028) [code](https://github.com/jvpoulos/homesteads)
    
    Jason Poulos.

1. **Estimating Treatment Effects with Causal Forests: An Application**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1902.07409)
    
    Susan Athey, Stefan Wager.

1. **Ensemble Methods for Causal Effects in Panel Data Settings**, *AER P&P*, 2019. [paper](https://arxiv.org/abs/1903.10079)
    
    Susan Athey, Mohsen Bayati, Guido W. Imbens, Zhaonan Qu.

### [Text](#content)

1. **Using Text Embeddings for Causal Inference**, *arXIv*, 2019. [paper](https://arxiv.org/abs/1905.12741) [code](https://github.com/blei-lab/causal-text-embeddings)
    
    Victor Veitch, Dhanya Sridhar, David M. Blei.

1. **Counterfactual Story Reasoning and Generation**, *arXIv*, 2019. [paper](https://arxiv.org/abs/1909.04076)
    
    Lianhui Qin, Antoine Bosselut, Ari Holtzman, Chandra Bhagavatula, Elizabeth Clark, Yejin Choi.

1. **How to Make Causal Inferences Using Texts**, *arXIv*, 2018. [paper](https://arxiv.org/abs/1802.02163)

    Naoki Egami, Christian J. Fong, Justin Grimmer, Margaret E. Roberts, Brandon M. Stewart.

## [Resources](#content)

### [Workshops](#content)

1. **NeurIPS 2019 Workshop** [link](http://tripods.cis.cornell.edu/neurips19_causalml/)

1. **NIPS 2018 Workshop** [link](https://sites.google.com/view/nips2018causallearning/home)

1. **NIPS 2017 Workshop** [link](https://sites.google.com/view/causalnips2017)s

1. **NIPS 2016 Workshop** [link](https://sites.google.com/site/whatif2016nips/)

1. **NIPS 2013 Workshop** [link](http://clopinet.com/isabelle/Projects/NIPS2013/)

### [Proceedings](#content)

1. **PMLR, Volume 6: Causality: Objectives and Assessment, 12 December 2008, Whistler, Canada** [link](http://proceedings.mlr.press/v6/)

### [Code libraries](#content)

1. **EconML: A Python Package for ML-Based Heterogeneous Treatment Effects Estimation** [link](https://github.com/microsoft/EconML)

1. **Uplift modeling and causal inference with machine learning algorithms** [link](https://github.com/uber/causalml)

### [Benchmark datasets](#content)

1. **IHDP, Jobs, and News benchmarks** [link](https://fredjo.com/)

1. **Twins** [link](http://www.nber.org/data/linked-birth-infant-death-data-vitalstatistics-data.htm)

1. **Causality workbench** [link](http://www.causality.inf.ethz.ch/repository.php?page=data)

### [Courses](#content)

1. **CS7792 - Counterfactual Machine Learning** [link](http://www.cs.cornell.edu/courses/cs7792/2016fa/)

### [Industry](#industry)

1. **Causality and Machine Learning: Microsoft Research** [link] https://www.microsoft.com/en-us/research/group/causal-inference/#!publications
