# Projects  

This is the repository for my personal projects.

## Thesis: Hamiltonian Monte Carlo and No-U-Turn Sampler

Hamiltonian Monte Carlo (HMC) is a Markov chain Monte Carlo (MCMC) method that is able to effectively sample high dimensional target distributions by using Hamilton’s equations to design a proposal mechanism that exploits the target geometry. However, HMC’s performance is highly sensitive to tuning parameters. The No-U-Turn Sampler (NUTS) eliminates the need to hand-tune parameters, whilst showing a competitive performance when compared with a well tuned vanilla HMC. This thesis will provide a background introduction to HMC and describe in detail the NUTS algorithm. Several numerical simulations will illustrate the flexibility of the NUTS algorithm and its practical advantage over vanilla HMC. 



## Project 1: Monte Carlo Convergence Diagnostics Project

Markov chain Monte Carlo (MCMC) is one of the most useful approaches to scientific computing because of its flexible construction, ease of use, and generality. Two critical questions that MCMC practitioners need to address are where to start and when to stop the simulation. Although a great amount of research has gone into establishing convergence criteria and stopping rules with sound theoretical foundation, in practice, MCMC users often decide convergence by applying empirical diagnostic tools. This review article discusses the most widely used MCMC convergence diagnostic tools. 



## Project 2: Vanilla and Generalised Elliptical Slice Sampling

Many probabilistic models introduce strong dependencies between variables using a latent multivariate Gaussian distribution or a Gaussian process. We present a new Markov chain
Monte Carlo algorithm for performing inference in models with multivariate Gaussian priors. Its key properties are: 

1) it has simple, generic code applicable to many models,
2) it has no free parameters, 
3) it works well for a variety of Gaussian process based models.

These properties make our method ideal for use while model building, removing the need to spend time deriving and tuning updates for more complex algorithms.



## Project 3: Real Data Analysis Critique

The paper critiqued was “Lung cancer incidence decreases with elevation: evidence for oxygen as an inhaled carcinogen”, Simeonov & Himmelstein, PeerJ 2015
https://peerj.com/articles/705/

The statistical analyses performed in the paper was critiqued from the point of view of multiple testing and replicability. The validity of the conclusions was also assessed from a statistician’s point of view

Some ideas are: thinking about possible confounding variables, whether the data collected is representative of the claim being made, etc.


