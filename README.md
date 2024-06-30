# Symbolic Regression:<br> A Pathway To Interpretability Towards Automated Scinetific Discovery
## Tutorial@KDD2024, Sunday, August 25, 10:00 am - 1:00 pm

  Symbolic regression is a machine learning technique employed for learning mathematical equations directly from data. Mathematical equations capture both functional and causal relationships in the data. In addition, they are simple, compact, generalizable, and interpretable models, making them the best candidates for i) learning inherently transparent models and ii) boosting scientific discovery. Symbolic regression has received a growing interest since the last decade and is tackled using different approaches in supervised and unsupervised deep learning, thanks to the enormous progress achieved in deep learning in the last twenty years. 
  Symbolic regression remains underestimated in conference coverage as a primary form of interpretable AI and a potential candidate for automating scientific discovery. This tutorial overviews symbolic regression: problem definition, approaches, and key limitations, discusses why physical sciences are beneficial to symbolic regression, and explores possible future directions in this research area.

  
This note aims to collect references for symbolic regression (SR) [methods](#methods) and [datasets](#datasets) as part of the recent [review](https://arxiv.org/abs/2211.10873) entitled "**Interpretable Scientific Discovery with Symbolic Regression: A Review**". The latter review SR methods and state-of-the-art applications of SR, along with existing datasets usually used in testing SR methods, and discusses their main strength and weakness.

<!-- [<img src="https://s18955.pcdn.co/wp-content/uploads/2018/02/github.png" width="25"/>](https://github.com/user/repository/subscription) -->

**A living review for symbolic regression is first** proposed in the mentioned review in analogy with "A Living Review of Machine Learning for Particle Physics" which can be found [here](https://iml-wg.github.io/HEPML-LivingReview/). The goal is to list all research works on symbolic regression so it is expected that ***this list will continue to evolve***. The fact that a paper is listed in this document does not endorse or validate its content - that is for the community (and for peer-review) to decide.

Symbolic regression is an emerging branch of machine learning that aims to learn analytical form of underlying model in data, by searching the space of mathematical functions. A growing interest in symbolic regression is taking place in the AI community because it pomotes interpretability, which is a critical factor for a safe AI application.

## Methods 
The symbolic regression problem can be approached and solved in different manners, depending on the way the target mathematical expression f(x) is defined. References (for SR) are categorized in an as easy and useful manner as possible, with a summary given in the table below. 

