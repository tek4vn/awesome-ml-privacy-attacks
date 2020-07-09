# Awesome atacks on ML privacy   [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
This repository contains a curated list of papers related to privacy attacks against machine learning. A code repository is provided when available. For corections, suggestions and missing papers, please either open an issue or submit a pull request.

## Table of Contents

 - [Surveys and Overviews](#surveys)
 - [Papers](#papers)

# Surveys and Overviews
- [**An Overview of Privacy in Machine Learning**](https://arxiv.org/pdf/2005.08679) (De Cristofaro, 2020)
- **A Survey of Privacy Attacks in Machine Learning** (Rigaki and Garcia, 2020)
 
# Papers and Code

## Membership inference
- [**Membership inference attacks against machine learning models**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7958568) (Shokri et al., 2017) ([code](https://github.com/csong27/membership-inference))
- [**Understanding membership inferences on well-generalized learning models**](https://arxiv.org/pdf/1802.04889)(Long et al., 2018)
- [**Privacy risk in machine learning:Analyzing the connection to overfitting**](https://ieeexplore.ieee.org/document/8429311), (Yeom et al., 2018) ([code](https://github.com/samuel-yeom/ml-privacy-csf18))
- [**Comprehensive privacy analysis of deep learning: Passive and active white-box inference attacks against centralized and federated learning.**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8835245) (Nasr et al., 2019) ([code](https://github.com/privacytrustlab/ml_privacy_meter))
- [**Logan: Membership inference attacks against generative models.**](https://content.sciendo.com/downloadpdf/journals/popets/2019/1/article-p133.xml) (Hayes et al. 2019) ([code](https://github.com/jhayes14/gen_mem_inf))
- [**Evaluating differentially private machine learning in practice**](https://www.usenix.org/system/files/sec19-jayaraman.pdf) (Jayaraman and Evans, 2019) ([code](https://github.com/bargavj/EvaluatingDPML)) 
- [**Membership inference attack against differentially private deep learning model**](http://www.tdp.cat/issues16/tdp.a289a17.pdf) (Rahman ett al., 2018)
- [**Ml-leaks: Model and data independent membership inference attacks and defenses on machine learning models**](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-1_Salem_paper.pdf) (Salem et al., 2019) ([code](https://github.com/AhmedSalem2/ML-Leaks))
- [**Privacy risks of securing machine learning models against adversarial examples**](https://dl.acm.org/doi/pdf/10.1145/3319535.3354211) (Song L. et al., 2019) ([code](https://github.com/inspire-group/privacy-vs-robustness))
- [**White-box vs Black-box: Bayes Optimal Strategies for Membership Inference**](http://proceedings.mlr.press/v97/sablayrolles19a.html) (Sablayrolles etal., 2019)
- [**Privacy risks of explaining machine learning models**](https://arxiv.org/abs/1907.00164) (Shokri et al., 2019)
- [**Demystifying membership inference attacks in machine learning as a service**](https://ieeexplore.ieee.org/abstract/document/8634878) (Truex et al., 2019)
- [**Monte carlo and reconstruction membership inference attacks against generative models**](https://content.sciendo.com/view/journals/popets/2019/4/article-p232.xml) (Hilprecht et al., 2019)
- [**MemGuard: Defending against Black-Box Membership Inference Attacks via Adversarial Examples**](https://arxiv.org/abs/1909.10594) (Jia et al., 2019) ([code](https://github.com/jjy1994/MemGuard))
- [**Gan-leaks: A taxonomy of membership inference attacks against gans**](https://arxiv.org/pdf/1909.03935.pdf) (Chen,et al., 2019))
- [**Membership Inference Attacks on Sequence-to-Sequence Models: Is My Data In Your Machine Translation System?**](https://www.mitpressjournals.org/doi/full/10.1162/tacl_a_00299) (Hisamoto et al., 2020) 

## Reconstruction
Reconstruction attacks cover also attacks known as *model inversion* and *attribute inference*.
- [**Privacy in pharmacogenetics: An end-to-end case study of personalized warfarin dosing**](https://www.usenix.org/system/files/conference/usenixsecurity14/sec14-paper-fredrikson-privacy.pdf) (Fredrikson et al., 2014)
- [**Model inversion attacks that exploit confidence information and basic countermeasures**](https://dl.acm.org/doi/pdf/10.1145/2810103.2813677) (Fredrikson et al., 2015) ([code](https://github.com/yashkant/Model-Inversion-Attack))
- [**A methodology for formalizing model-inversion attacks**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7536387) (Wu et al., 2016)
- [**Deep models under the gan: Information leakage from collaborative deep learning**](https://dl.acm.org/doi/pdf/10.1145/3133956.3134012) (Hitaj et al., 2017) 
- [**Machine learning models that remember too much**](https://dl.acm.org/doi/pdf/10.1145/3133956.3134077) (Song, C. et al., 2017) ([code](https://github.com/csong27/ml-model-remember))
- [**Model inversion attacks for prediction systems: Without knowledge of non-sensitive attributes**](https://ieeexplore.ieee.org/iel7/8476191/8476869/08476925.pdf?casa_token=VQ_s2jcJFp8AAAAA:Hg-wdpPcESm9UUsZHxCLzIvYqVEqW11_OCXEyjARxW5K2cFYi6EFNXlH8IKKjNSgv6oQoQJlsw) (Hidano et al., 2017)
- [**The secret sharer: Evaluating and testing unintended memorization in neural networks**](https://www.usenix.org/system/files/sec19-carlini.pdf) (Carlini et al., 2019)
- [**Deep leakage from gradients**](https://papers.nips.cc/paper/9617-deep-leakage-from-gradients.pdf) (Zhu et al., 2019) ([code](https://github.com/mit-han-lab/dlg))
- [**Model inversion attacks against collaborative inference**](https://dl.acm.org/doi/abs/10.1145/3359789.3359824) (He et al., 2019) ([code](https://github.com/zechenghe/Inverse_Collaborative_Inference))
- [**Beyond Inferring Class Representatives: User-Level Privacy Leakage From Federated Learning**](https://ieeexplore.ieee.org/document/8737416) (Wang et al., 2019)
- [**Neural network inversion in adversarial setting via background knowledge alignment**](https://dl.acm.org/doi/pdf/10.1145/3319535.3354261?casa_token=lDNQ40-4Wa4AAAAA:p9olQ3qMdDZ0n2sl-nNIgk4sOuLRMBTGVTxycZ5wjGpnFPf5lTz-MYw0e8ISggSseHC9T46it5yX) (Yang et al., 2019)
- [**iDLG: Improved Deep Leakage from Gradients**](https://arxiv.org/pdf/2001.02610) (Zhao et al., 2020) ([code](https://github.com/PatrickZH/Improved-Deep-Leakage-from-Gradients))
- [**Privacy Risks of General-Purpose Language Models**](https://www.researchgate.net/profile/Xudong_Pan3/publication/340965355_Privacy_Risks_of_General-Purpose_Language_Models/links/5ea7ca55a6fdccd7945b6a7d/Privacy-Risks-of-General-Purpose-Language-Models.pdf) (Pan et al., 2020)
- [**The secret revealer: generative model-inversion attacks against deep neural networks**](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_The_Secret_Revealer_Generative_Model-Inversion_Attacks_Against_Deep_Neural_Networks_CVPR_2020_paper.pdf)) ([link](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_The_Secret_Revealer_Generative_Model-Inversion_Attacks_Against_Deep_Neural_Networks_CVPR_2020_paper.pdf) (Zhang et al., 2020)
- [**Inverting Gradients - How easy is it to break privacy in federated learning?**](https://arxiv.org/abs/2003.14053)(Geiping et al., 2020)


## Property inference
- [**Hacking smart machines with smarter ones: How to extract meaningful data from machine learning classifiers**](https://dl.acm.org/doi/10.1504/IJSN.2015.071829) (Ateniese et al., 2015)
- [**Property inference attacks on fully connected neural networks using permutation invariant representations**](https://dl.acm.org/doi/pdf/10.1145/3243734.3243834) (Ganju et al., 2018)
- [**Exploiting unintended feature leakage in collaborative learning**](https://ieeexplore.ieee.org/iel7/8826229/8835208/08835269.pdf) (Melis et al., 2019) ([code](https://github.com/csong27/property-inference-collaborative-ml))
- [**Overlearning Reveals Sensitive Attributes**](https://openreview.net/pdf?id=SJeNz04tDS) (Song C. et al., 2020) ([code](https://drive.google.com/file/d/1hu0PhN3pWXe6LobxiPFeYBm8L-vQX2zJ/view?usp=sharing))

## Model extraction
- [**Stealing machine learning models via prediction apis**](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_tramer.pdf) (Tramèr et al., 2016) ([code](https://github.com/ftramer/Steal-ML))
- [**Stealing hyperparameters in machine learning**](https://ieeexplore.ieee.org/iel7/8418581/8418583/08418595.pdf)(Wang B. et al., 2018)
- [**Copycat CNN: Stealing Knowledge by Persuading Confession with Random Non-Labeled Data**](https://ieeexplore.ieee.org/document/8489592) (Correia-Silva et al., 2018) ([code](https://github.com/jeiks/Stealing_DL_Models))
- [**Towards reverse-engineering black-box neural networks.**](https://openreview.net/forum?id=BydjJte0-)(Oh et al., 2018) ([code](https://github.com/coallaoh/WhitenBlackBox))
- [**Knockoff nets: Stealing functionality of black-box models**](http://openaccess.thecvf.com/content_CVPR_2019/papers/Orekondy_Knockoff_Nets_Stealing_Functionality_of_Black-Box_Models_CVPR_2019_paper.pdf) (Orekondy et al., 2019) ([code](https://github.com/tribhuvanesh/knockoffnets))
- [**PRADA: protecting against DNN model stealing attacks**](https://ieeexplore.ieee.org/document/8806737) (juuti et al., 2019) ([code](https://github.com/SSGAalto/prada-protecting-against-dnn-model-stealing-attacks))
- [**Model Reconstruction from Model Explanations**](https://dl.acm.org/doi/abs/10.1145/3287560.3287562) (Milli et al., 2019)
- [**Exploring connections between active learning and model extraction**](https://www.usenix.org/system/files/sec20summer_chandrasekaran_prepub.pdf) (Chandrasekaran et al., 2020)
- [**High Accuracy and High Fidelity Extraction of Neural Networks**](https://www.usenix.org/conference/usenixsecurity20/presentation/jagielski) (Jagielski et al., 2020)
- [**Thieves on Sesame Street! Model Extraction of BERT-based APIs**](https://openreview.net/attachment?id=Byl5NREFDr&name=original_pdf) (Krishna et al., 2020) ([code](https://github.com/google-research/language/tree/master/language/bert_extraction))