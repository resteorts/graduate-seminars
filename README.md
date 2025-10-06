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
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

---

## Oct 27
**Moderator:** Federico Lazzarini

**Speakers:**
- **Luke Vrotsos**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

- **Bongjung Sung**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

---

## Nov 3 — Faculty Meeting  
- **No Talks**

---

## Nov 10
**Moderator:** Tory Norton 

**Speakers:**
- **Piotr Suder**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

- **Braden Scherting**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

---

## Nov 17
**Moderator:** Arunsoumya Basu

**Speakers:**
- **Suschimita Roy**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

- **Caitrin Murphy**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

---

## Nov 24
**Moderator:** Jun Chen 

**Speakers:**
- **Lorenzo Mauri**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

- **Yen-Chun Liu**  
  - **Title:**  
  - **Abstract:**  
  - **Bio:**  

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
