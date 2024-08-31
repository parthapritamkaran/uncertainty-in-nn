# uncertainty-in-nn
 The concept of Deep Learning(DL) is quite prevalent today in the world of Machine Learning. Deep
 Learning tackles complex problems that were traditionally difficult to solve. However, DL models are
 often prone to overfitting which might make them less generalizable [3] as well as prone to different
 attacks (eg: membership inference attacks [6]). The less generalizability problem can lead to drastic
 outcomes in some cases like warning systems, finance-related, etc.
 The traditional DL models are thus prone to uncertainties that need to be mitigated. There have
 been various approaches taken by researchers to understand and quantify the uncertainty in Neural
 Networks like Bayesian Neural Networks, ensemble of neural networks, and test-time data
 augmentation [1], etc. One of the most common ones is Bayesian Neural Networks(BNNs) which as
 the name suggests is based on Bayesian Statistics.
 Supporting the development of learning algorithms in general, the Bayesian paradigm offers a rigorous
 framework for analyzing and training neural networks that account for uncertainty. The Bayesian
 statistics in contrast to the frequentist paradigm supports a probabilistic paradigm. The core idea of
 Bayesian statistics is as follows:
 1. Contrary to what the frequentist paradigm assumes regarding the frequency limit of occurrence
 as the number of samples approaches infinity, probability represents the belief in the occurrence
 of events.
 2. Prior beliefs influence posterior beliefs.

 Thus, in addition to providing a reliable method for quantifying uncertainty in deep learning models, the
 Bayesian paradigm also offers a mathematical framework for comprehending numerous regularisation
 techniques and learning strategies that are already implemented in traditional deep learning.
 Our work mainly focuses on how Bayesian Neural Networks address the problem of uncertainty
 in NNs and discusses the different methods to do Bayesian inference in BNNs like Variational Inference,
 Markov Chain Monte Carlo(MCMC), etc. It also explores the efficiency of these methods on different
 parameters like time, accuracy, etc
