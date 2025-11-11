# STA 701 Seminar Schedule (Fall 2025)

## Sep 1 — Labor Day
- **No Talks**

---

## Sep 8 — Faculty Meeting
- **No Talks**

---

## Sep 15
**Moderator:** Instructor  

**Speakers:**
- **Rick Presman**  
  - **Title:** Order-constrained Bayesian ordinal regression for the modeling of neuron degeneration in *C. elegans* (joint work with Amy H. Herring and Joel N. Meyer)  
  - **Abstract:** Neuron degeneration is the underlying mechanism for the progression of many diseases. Quantifying the association between the progression of neuron degradation and the level of toxic exposure is critical to understanding disease development. While efforts have been made in quantifying this progression through the development of scoring systems that assign numerical values to qualitative descriptors of neuron damage, statistical analyses involving these scores are often rudimentary and ignore the ordinal nature of the data, structural relationships between variables, and lack the ability to perform appropriate uncertainty quantification. To account for this gap in the literature, we propose a novel order-restricted Bayesian ordinal regression model that captures the unique nature of neuron damage scores and treatments along with the nonparametric monotonic relationship between them. Our model can be implemented with a straightforward Gibbs sampler, and we demonstrate its interpretability on a real-world dataset along with its comparative performance using a simulation study.  
  - **Bio:** Rick Presman is a sixth year PhD student advised by Jason Xu. [Webpage](https://rpresman.github.io)

- **Christine Shen**  
  - **Title:** Asymptotic Well-Calibration of the Posterior Predictive *p*-value under the Modified Kolmogorov-Smirnov Test  
  - **Abstract:** The posterior predictive *p*-value is a widely used tool for Bayesian model checking. However, under general test statistics, its asymptotic null distribution is more concentrated around 1/2 than the uniform distribution. Consequently, its finite-sample behavior is difficult to interpret and tends to lack power, which is a well-known issue among practitioners. The Kolmogorov-Smirnov test with plug-in estimators is a versatile omnibus test statistic. It is sensitive to model misspecification and provides a global measure of model-data discrepancy. We establish that under this test statistic, the posterior predictive *p*-value converges in distribution to uniform under the null. We further use numerical experiments to demonstrate that this *p*-value is well-behaved in finite samples.  
  - **Bio:** Christine Shen is a fifth year PhD student working with Dr. Surya Tokdar.

---

## Sep 22
**Moderator:** Jannis Bolik  

**Speakers:**
- **Sam Rosen**  
  - **Title:** Weighted Bayesian Bootstrap for Constrained Posterior Distributions
  - **Abstract:** The weighted Bayesian bootstrap and its closely related variants have shown robust ability to approximately sample from complicated posterior distributions. We show, under regularity conditions, that the weighted Bayesian bootstrap can be extended to approximately sample posterior distributions with constrained support. An asymptotic result is provided showing samples converge in conditional distribution to a multivariate normal centered at the true underlying parameters with a covariance that is a function of the Fisher information matrix. The generality of the method is shown by examples in a variety of domains that are well-supported by the convex optimization literature, while giving reasonable uncertainty estimates that account for problem constraints.
  - **Bio:**  Sam Rosen is a fifth-year PhD student working with Jason Xu.

- **Riccardo Rossetti**  
  - **Title:**  Statistical Limits for Finite-Rank Tensor Estimation
  - **Abstract:**  This paper provides a unified framework for analyzing tensor estimation problems that allow for nonlinear observations, heteroskedastic noise, and covariate information. We study a general class of high-dimensional models where each observation depends on the interactions among a finite number of unknown parameters. Our main results provide asymptotically exact formulas for the mutual information (equivalently, the free energy) as well as the minimum mean-squared error in the Bayes-optimal setting. We then apply this framework to derive sharp characterizations of statistical thresholds for two novel scenarios: (1) tensor estimation in heteroskedastic noise that is independent but not identically distributed, and (2) higher-order assignment problems, where the goal is to recover an unknown permutation from tensor-valued observations. 
  - **Bio:**  Riccardo is a 5th year PhD student advised by Prof. Galen Reeves

---

## Sep 29
**Moderator:** Adeli Hutton

**Speakers:**
- **Glenn Palmer**  
  - **Title:**  Two Advances in Joint Factor Analysis for Studying Chemical Mixtures
  - **Abstract:**  In this talk, I briefly highlight two developments in the use of joint factor analysis to evaluate associations between human exposures to environmental chemicals and health outcomes of interest. In "Low-rank longitudinal factor regression with application to chemical mixtures," joint work with Amy Herring and David Dunson, we propose a low-rank longitudinal factor regression (LowFR) model for tractable inference on flexible longitudinal exposure effects. LowFR handles highly-correlated exposures using a Bayesian dynamic factor model, which is fit jointly with a health outcome via a novel factor regression approach. The model collapses on simpler and intuitive submodels when appropriate, while expanding to allow considerable flexibility in time-varying and interaction effects when supported by the data. After demonstrating LowFR’s effectiveness in simulations, we use it to analyze data from the ELEMENT study and find that diethyl and dibutyl phthalate metabolite levels in trimesters 1 and 2 of pregnancy are associated with altered glucose metabolism in adolescence. In "Targeted empirical Bayes for more supervised joint factor analysis," joint work with David Dunson, we propose estimating the residual variance in the response model with an empirical Bayes procedure that targets predictive performance of the response given the predictors. We illustrate that this can lead to substantial improvements in simulation performance. We are particularly motivated by studies assessing the health effects of environmental exposures and provide an illustrative application to NHANES data.
  - **Bio:**  Glenn Palmer is a fifth-year PhD student working with David Dunson.

- **Kevin Li**  
  - **Title:**  Exploiting Concavity Information in Gaussian Process Contextual Bandit Optimization
  - **Abstract:**  The contextual bandit framework is widely used to solve sequential optimization problems where the reward of each decision depends on auxiliary context variables. In settings such as medicine, business, and engineering, the decision maker often possesses additional structural information on the generative model that can potentially be used to improve the efficiency of bandit algorithms. We consider settings in which the mean reward is known to be a concave function of the action for each fixed context. Examples include patient-specific dose-response curves in medicine and expected profit in online advertising auctions. We propose a contextual bandit algorithm that accelerates optimization by conditioning the posterior of a Bayesian Gaussian Process model on this concavity information. We design a novel shape-constrained reward function estimator using a specially chosen regression spline basis and constrained Gaussian Process posterior. Using this model, we propose a UCB algorithm and derive corresponding regret bounds. We evaluate our algorithm on numerical examples and test functions used to study optimal dosing of Anti-Clotting medication.
  - **Bio:**  Kevin Li is a fifth year PhD student. 

---

## Oct 6 — Faculty Meeting  
- **No Talks**

---

## Oct 13 — Fall Break
- **No Talks**

---

## Oct 20
**Moderator:** Cael Elmore

**Speakers:**
- **Cathy Lee**  
  - **Title:** Experimental Design Considerations for Bot or Not: A Sociological Turing Test (joint work with Ben Rochford, Michelle Qiu, Chris Bail, and D. Sunshine Hillygus) 
  - **Abstract:**  We investigate how social media users from different demographic groups--defined by race, gender, and political partisanship--perceive social media profiles as either bot or human. Specifically, we ask whether users are more likely to classify profiles from different demographic subgroups as bots compared to profiles that share their own characteristics. To answer this, we design a conjoint experiment in which participants viewed social media threads containing both human- and AI-generated content. Visual cues for race, gender, and partisanship were randomly assigned to the AI-operated profile in each thread. Our analysis reveals systematic demographic biases in bot detection. In this talk, I will highlight the experimental design considerations leading up to our final design, including: (i) conducting a power analysis of our initial dynamic randomized experiment, (ii) pivoting to a static conjoint survey experiment, (iii) designing the treatment exposures, and (iv) assigning and measuring respondent tasks and responses.
  - **Bio:**  Cathy is a fifth year PhD student working with Dr. Alex Volfovsky.

- **Houjie Wang**  
  - **Title:** Bayesian Multi-Scale Modeling and Monitoring of Large-Scale Agent Flows in Dynamic Networks  
  - **Abstract:**  We discuss dynamic modeling of temporal paths of multiple agents through geographic networks with interest in detecting anomalous behavior of agents or subgroups of agents. The focus is sequential, monitoring incoming (noisy) time-trajectory data on huge numbers of agents on large networks in real time.   Models represent geographical regions as networks of nodes as fine geographic zones.  Interpretable Bayesian dynamic models are multi-scale in space, time and agents (ranging from individuals to subsets of agents defined via multiple intersecting features). Multi-scale models capture transitions over time of individual  agents informed by activities at group levels. Methodology leverages decouple/recouples concepts,  enabling model scalability and efficient computation. Analysis is overlaid with decision-theoretic monitoring customized to anomaly detection.  Examples explore large-scale data arising from collaborative studies on real-time monitoring of human population movements in defined regions of a US city landscape.  This highlights the roles and utilities of the methodology in characterizing normal dynamic patterns of trajectories at individual and group-levels, and in anomaly detection.
  - **Bio:**  Houjie Wang is a fourth-year PhD advised by Prof. Alex Volfovsky and Prof. Mike West.

---

## Oct 27
**Moderator:** Federico Lazzarini

**Speakers:**
- **Luke Vrotsos**  
  - **Title:**  Dynamic graphical models: Theory, structure and counterfactual forecasting
  - **Abstract:**  Simultaneous graphical dynamic linear models (SGDLMs) provide advances in flexibility, parsimony and scalability of multivariate time series analysis, with proven utility in forecasting. Core theoretical aspects of such models are developed, including new results linking dynamic graphical and latent factor models. Methodological developments extend existing Bayesian sequential analyses for model marginal likelihood evaluation and counterfactual forecasting. The latter, involving new Bayesian computational developments for missing data in SGDLMs, is motivated by causal applications. A detailed example concerns the effect of the Affordable Care Act's Medicaid expansion on employment, with advances in model uncertainty and staggered adoptions.
  - **Bio:**  Luke Vrotsos is a fourth-year PhD student in the Statistical Science department at Duke University advised by Mike West and Alex Volfovsky. 

- **Bongjung Sung**  
  - **Title:**  Canonical Polyadic Core Covariance Estimation for Matrix-Variate Data
  - **Abstract:**  We introduce a novel canonical polyadic (CP) core covariance matrix for matrix-variate data. While the separable covariance model is often considered for modeling the covariance of matrix-variate data due to its parsimony, it may tend to overly simplify the correlation structure of the true covariance. Motivated by the fact that every covariance matrix can be uniquely decomposed into a separable and a core component, we introduce a low-dimensional covariance structure by formulating a spiked CP core covariance model.  To this end, we show how a low-rank core component C can be formulated in terms of CP tensor decomposition.  For square data matrices, this C  satisfies the definition of the core.  For a nonsquare case, this C can be still viewed as a weak core in the sense that it partially satisfies the definition of the core. We illustrate how this CP core covariance model is effective for describing heterogeneity of high-dimensional excitation-emission matrices of water samples from the Neuse river in North Carolina.
  - **Bio:**  Bongjung is a fourth year PhD candidate working with Peter Hoff.

---

## Nov 3 — Faculty Meeting  
- **No Talks**

---

## Nov 10
**Moderator:** Tory Norton 

**Speakers:**
- **Piotr Suder**  
  - **Title:** Multi-Agent Action Filtering Bandits 
  - **Abstract:**  Real-world recommender systems often employ a hierarchy of machine learning algorithms
that are applied sequentially to filter and refine choices for a user. In practice, it is common
for these algorithms to be developed in isolated teams, creating coordination challenges that
hinder the system’s ability to converge to a globally optimal solution. To characterize the effects
of coordination among the various components of a recommender system, we introduce the
Multi-Agent Action Filtering Bandits (MAAFB) framework. MAAFB models the system as
a sequence of agents, each using its own bandit algorithm to make decisions with only partial
information about the actions of downstream agents. Our theoretical analysis of the MAAFB
framework provides simple conditions under which such a system will converge to an optimal
solution. Furthermore, we investigate the role of coordination between the agents’ exploration
strategies and provide actionable recommendations for refining large recommender systems
in the wild. We show that while some alignment in exploration can accelerate learning and
improve performance, excessive alignment is detrimental. Over-indexing on alignment introduces
significant bias into the reward estimates learned by upstream agents, ultimately leading to
poor system-wide performance. This highlights a fundamental tradeoff between coordinated
exploration and the need for diverse, independent learning in hierarchical multi-agent systems.
  - **Bio:**  Piotr is a fourth-year PhD student advised by Eric Laber.

- **Braden Scherting**  
  - **Title:**   Ecological Insights from Big Arthropod Biodiversity Data
  - **Abstract:**  Accelerating global biodiversity loss has highlighted the role of complex relationships and shared patterns among species in determining their responses to environmental changes. The structure of an ecological community, represented by patterns of dependence among constituent species, signals its robustness more than individual species distributions. We focus on obtaining community-level insights based on underlying patterns in abundances of bird species in Finland. We propose \texttt{barcode}, a modeling framework to infer latent binary and continuous features of samples and species, expanding the class of concurrent ordinations. This approach introduces covariates and spatial autocorrelation hierarchically to facilitate ecological interpretations of the learned features. By analyzing 132 bird species counts, we infer the dominant environmental drivers of the community, species clusters and regions of common profile. Three of the learned drivers correspond to distinct climactic regions with different dominant forest types. Three further drivers are spatially heterogeneous and signal urban, agricultural, and wetland areas, respectively.
  - **Bio:**  Braden is a fourth year Phd student working with David Dunson. 

---

## Nov 17
**Moderator:** Arunsoumya Basu

**Speakers:**
- **Suchismita Roy**  
  - **Title:**  Improving Coverage of Dynamical Survival Analysis Models through a Latent Gaussian Process
  - **Abstract:**  Stochastic compartmental models are fundamental tools in epidemic modeling. The Dynamical Survival Analysis (DSA) method replaces the stochastic population-level hazard by its large population limit to approximate the original process. While doing so enables more efficient inference based on survival analytic techniques and retains a count-valued stochastic model on the same state space, the deterministic hazard underestimates the variability, leading to biased posterior uncertainty and incorrect frequentist coverage. To address this limitation, we augment the deterministic DSA formulation with a latent Gaussian process (GP) layer, which reintroduces the missing variance component via a hierarchical model. We show that posterior inference is naturally carried out with a data-augmented HMC-within-Gibbs framework. Through simulation studies, we find that the correction leads to marked improvements in coverage of the credible intervals, and note that the convergence rate varies across different parameter regimes. Finally, we demonstrate the utility of our approach on early COVID‑19 epidemic data from Suizhou city, China.
  - **Bio:**  Suchismita Roy is a fourth year PhD student advised by Jason Xu and Alex Fisher. 

- **Caitrin Murphy**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

---

## Nov 24
**Moderator:** Jun Chen 

**Speakers:**
- **Lorenzo Mauri**  
  - **Title:**   Inference on covariance structure in high-dimensional multi-view data
  - **Abstract:**  This work focuses on covariance estimation for multi-view data. Popular approaches rely on factor-analytic decompositions that have shared and view-specific latent factors. Posterior computation is conducted via expensive and brittle Markov chain Monte Carlo (MCMC) sampling or variational approximations that underestimate uncertainty and lack theoretical guarantees. Our proposed methodology employs spectral decompositions to estimate and align latent factors that are active in at least one view. Conditionally on these factors, we choose jointly conjugate prior distributions for factor loadings and residual variances. The resulting posterior is a simple product of normal-inverse gamma distributions for each variable, bypassing MCMC and facilitating posterior computation. We prove favorable increasing-dimension asymptotic properties, including posterior contraction and central limit theorems for point estimators. We apply the methodology to integrate four high-dimensional views from a multi-omics dataset of cancer cell samples. 
  - **Bio:**  Lorenzo is a 4th year student working with David Dunson.

- **Yen-Chun Liu**  
  - **Title:**  Optimal Data Integration and Adaptive Sampling for Efficient Treatment Effect Estimation
  - **Abstract:**  This study addresses the challenge of estimating multiple average treatment effects (ATEs) where complete randomized experimentation is infeasible. We propose two key innovations: (1) a shrinkage estimator that optimally combines observational and experimental data without assuming smooth treatment effects across campaigns, and (2) a Bayesian adaptive experimental design framework that efficiently selects treatments for randomized evaluation that minimizes cumulative risk. Our shrinkage estimator achieves lower risk compared to existing methods by balancing bias-variance tradeoffs, while our adaptive design significantly reduces the costs of campaign randomization. We establish theoretical guarantees including asymptotic normality and regret bounds.
  - **Bio:**  Yen-Chun is a 4th year PhD student.

---

## Dec 2 — Faculty Meeting
**Moderator:** TBD  
- **No Talks**

---

## Notes for Students
- Email your **slides** to Prof. Steorts at least **24 hours before your presentation**.  
- Email your **title, abstract, and bio** at least **two weeks before your presentation**.  
- Presentation length will default to the **shorter format** unless otherwise approved.  
- Be prepared to **introduce your fellow speakers** and lead a short discussion.  
- Check the schedule regularly — it is **your responsibility** to stay up to date.  
- Participation and attendance are required for course credit.  
- Further info regarding the format/expectations are on the 701 Canvas page. If you do not have access, please email Prof. Steorts.
