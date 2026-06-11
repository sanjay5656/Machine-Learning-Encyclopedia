# 🧠 Machine Learning Encyclopedia

> **A structured Machine Learning knowledge base for understanding algorithms, their use cases, mathematical foundations, implementations, and real-world applications.**

**GitHub:** [github.com/sanjay5656](https://github.com/sanjay5656) &nbsp;|&nbsp;
**Portfolio:** [suvsan-mldev.netlify.app](https://suvsan-mldev.netlify.app)

---

## 📌 Why I Created This Repository

Machine Learning contains hundreds of algorithms, and new algorithms continue to be developed every year.

My goal is not to master every algorithm in existence.

**Instead, I want to:**
1. Build strong expertise in the major algorithms used across industry and research.
2. Maintain a structured reference system for the broader Machine Learning landscape.
3. Understand which algorithms are suitable for different types of real-world problems.
4. Create a long-term knowledge base that I can revisit during projects, interviews, research, and future learning.

When solving a new problem, the challenge is often not writing code—it is knowing which approach to consider.

**This repository helps me answer questions such as:**

1. Is this a regression, classification, clustering, or forecasting problem?
2. Which algorithms are commonly used for this problem type?
3. What are the strengths and limitations of each approach?
4. Which algorithm should I study or experiment with next?

Over time, this repository will grow into a personal Machine Learning encyclopedia containing algorithm summaries, mathematical intuition, implementations, practical examples, and learning notes.



---

## 🎯 How I Learn Every Single Algorithm (The 5-Layer System)

> No algorithm is marked complete until all 5 layers are done. No exceptions.

| Layer | What I Do | Why It Matters |
|-------|-----------|----------------|
| **1. Intuition** | Explain the problem it solves in plain words, with a real-world analogy | Understanding before memorizing |
| **2. Math** | Derive the core equation from scratch — loss function, update rule, proof | Knowing why, not just what |
| **3. Code from scratch** | Implement using NumPy only — no sklearn, no shortcuts | Forces every decision to be conscious |
| **4. Real dataset** | Apply on a real, messy dataset — evaluate properly with multiple metrics | Clean synthetic data is a lie |
| **5. Teach it back** | Write the README as if teaching someone else — where I stumble = my gaps | The Feynman technique — if you can't explain it, you don't understand it |

**🚀 Current Focus (Major Algorithms)**

These are the algorithms I am currently prioritizing for deep understanding:

**Supervised Learning:**

Linear Regression

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

XGBoost

**Unsupervised Learning**

K-Means Clustering

PCA

DBSCAN

**Ensemble Learning**

Gradient Boosting

LightGBM

CatBoost

**Anomaly Detection**

Isolation Forest

The remaining algorithms in this repository serve as a categorized reference map that helps identify potential approaches when encountering new problem statements in the future.


---

## 🗺️ Category → Problem Type Guide

> Before picking an algorithm, identify your problem type. This table is your map.

| Problem Type | Description | Real Example | Algorithm Family |
|---|---|---|---|
| **Regression** | Predict a continuous number | House price, salary, temperature | Supervised — Regression |
| **Binary classification** | Predict yes or no | Spam or not, fraud or not, churn or not | Supervised — Classification |
| **Multi-class classification** | Predict one of 3+ categories | Handwritten digit (0–9), disease type | Supervised — Classification |
| **Clustering** | Group similar items, no labels | Customer segments, document topics | Unsupervised — Clustering |
| **Dimensionality reduction** | Compress features, visualize data | Visualize 100-dim embeddings in 2D | Unsupervised — Dim Reduction |
| **Anomaly detection** | Find rare unusual points | Fraud transaction, defective product | Anomaly Detection |
| **Time series forecasting** | Predict future values in a sequence | Monthly sales, stock price, demand | Time Series |
| **Ranking** | Order items by relevance | Search results, product recommendations | Ranking / Recommendation |
| **Association** | Find items that appear together | "Customers who bought X also bought Y" | Association Rule Mining |
| **Reinforcement** | Agent learns from trial and reward | Game playing, robot control | Reinforcement Learning |
| **Density estimation** | Model the probability of data | Generative models, outlier scoring | Bayesian / Probabilistic |

---

## 📚 Complete Algorithm Index

> `⭐ MAJOR` = used in 80% of real industry projects. Learn these first.
> All others: know they exist, go deep when your project needs them.

---

### 📂 01 · Supervised Learning — Regression

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 01 | [Linear Regression](./01_regression/01_linear_regression/) | ⭐ MAJOR | Predict a number via weighted sum of features | ⬜ todo |
| 02 | [Ridge Regression (L2)](./01_regression/02_ridge_regression/) | ⭐ MAJOR | Linear regression + L2 penalty — prevents overfitting | ⬜ todo |
| 03 | [Lasso Regression (L1)](./01_regression/03_lasso_regression/) | | Ridge variant that zeroes out irrelevant features | ⬜ todo |
| 04 | [ElasticNet](./01_regression/04_elasticnet/) | | Combined L1+L2 — best of Ridge and Lasso | ⬜ todo |
| 05 | [Polynomial Regression](./01_regression/05_polynomial_regression/) | | Extends linear regression with x², x³ features | ⬜ todo |
| 06 | [Support Vector Regression (SVR)](./01_regression/06_svr/) | | SVM applied to regression using an epsilon-tube | ⬜ todo |
| 07 | [Bayesian Linear Regression](./01_regression/07_bayesian_linear/) | | Linear regression with uncertainty — outputs a distribution | ⬜ todo |
| 08 | [Huber Regression](./01_regression/08_huber/) | | MSE + MAE hybrid — robust to outliers | ⬜ todo |
| 09 | [Quantile Regression](./01_regression/09_quantile/) | | Predict a specific percentile, not the mean | ⬜ todo |
| 10 | [Isotonic Regression](./01_regression/10_isotonic/) | | Fits a non-decreasing step function to data | ⬜ todo |
| 11 | [Partial Least Squares (PLS)](./01_regression/11_pls/) | | Regression when features are highly correlated | ⬜ todo |

---

### 📂 02 · Supervised Learning — Classification

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 12 | [Logistic Regression](./02_classification/01_logistic_regression/) | ⭐ MAJOR | Binary classification using sigmoid + cross-entropy | ⬜ todo |
| 13 | [Decision Tree](./02_classification/02_decision_tree/) | ⭐ MAJOR | Splits data on best feature at each node — interpretable | ⬜ todo |
| 14 | [K-Nearest Neighbors (KNN)](./02_classification/03_knn/) | | Classifies by majority vote of K nearest training points | ⬜ todo |
| 15 | [Naive Bayes — Gaussian](./02_classification/04_naive_bayes_gaussian/) | | Probabilistic classifier for continuous features | ⬜ todo |
| 16 | [Naive Bayes — Multinomial](./02_classification/05_naive_bayes_multinomial/) | | Probabilistic classifier for word count / text data | ⬜ todo |
| 17 | [Naive Bayes — Bernoulli](./02_classification/06_naive_bayes_bernoulli/) | | Probabilistic classifier for binary features | ⬜ todo |
| 18 | [SVM — Linear](./02_classification/07_svm_linear/) | | Maximum margin classifier for linearly separable data | ⬜ todo |
| 19 | [SVM — Kernel (RBF, Poly)](./02_classification/08_svm_kernel/) | | SVM with kernel trick for non-linear boundaries | ⬜ todo |
| 20 | [Linear Discriminant Analysis (LDA)](./02_classification/09_lda/) | | Finds axes maximizing between-class vs within-class variance | ⬜ todo |
| 21 | [Quadratic Discriminant Analysis (QDA)](./02_classification/10_qda/) | | LDA without equal covariance assumption — curved boundary | ⬜ todo |
| 22 | [Perceptron](./02_classification/11_perceptron/) | | Single-layer neural network — origin of deep learning | ⬜ todo |
| 23 | [Passive-Aggressive Classifier](./02_classification/12_passive_aggressive/) | | Online learning for streaming / large-scale data | ⬜ todo |
| 24 | [SGD Classifier](./02_classification/13_sgd_classifier/) | | Linear classifiers trained with stochastic gradient descent | ⬜ todo |

---

### 📂 03 · Ensemble Methods

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 25 | [Random Forest](./03_ensemble/01_random_forest/) | ⭐ MAJOR | 100s of diverse trees vote together — robust and powerful | ⬜ todo |
| 26 | [Gradient Boosting (vanilla)](./03_ensemble/02_gradient_boosting/) | ⭐ MAJOR | Sequential trees, each correcting the previous tree's errors | ⬜ todo |
| 27 | [XGBoost](./03_ensemble/03_xgboost/) | ⭐ MAJOR | Optimized gradient boosting — industry standard for tabular data | ⬜ todo |
| 28 | [LightGBM](./03_ensemble/04_lightgbm/) | ⭐ MAJOR | Fastest gradient booster — leaf-wise growth, scales to millions | ⬜ todo |
| 29 | [CatBoost](./03_ensemble/05_catboost/) | | Gradient boosting with native categorical feature handling | ⬜ todo |
| 30 | [AdaBoost](./03_ensemble/06_adaboost/) | | Boosts weak classifiers by upweighting misclassified examples | ⬜ todo |
| 31 | [Extra Trees](./03_ensemble/07_extra_trees/) | | Random Forest with fully random splits — faster, sometimes better | ⬜ todo |
| 32 | [Bagging](./03_ensemble/08_bagging/) | | Train any model on bootstrap samples — reduces variance | ⬜ todo |
| 33 | [Voting (Hard & Soft)](./03_ensemble/09_voting/) | | Majority vote or averaged probabilities across models | ⬜ todo |
| 34 | [Stacking](./03_ensemble/10_stacking/) | | Meta-model trained on predictions of base models | ⬜ todo |
| 35 | [Blending](./03_ensemble/11_blending/) | | Simplified stacking — holdout set instead of cross-validation | ⬜ todo |
| 36 | [HistGradientBoosting](./03_ensemble/12_hist_gradient_boosting/) | | sklearn's fast native boosting — handles missing values natively | ⬜ todo |

---

### 📂 04 · Unsupervised Learning — Clustering

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 37 | [K-Means](./04_clustering/01_kmeans/) | ⭐ MAJOR | Partition data into K clusters by nearest centroid | ⬜ todo |
| 38 | [K-Means++](./04_clustering/02_kmeans_plus/) | | K-Means with smarter initialization — avoids bad starts | ⬜ todo |
| 39 | [Mini-Batch K-Means](./04_clustering/03_minibatch_kmeans/) | | K-Means on random mini-batches — faster on large data | ⬜ todo |
| 40 | [DBSCAN](./04_clustering/04_dbscan/) | | Density-based — finds arbitrary shapes, marks outliers | ⬜ todo |
| 41 | [HDBSCAN](./04_clustering/05_hdbscan/) | | DBSCAN that handles varying density automatically | ⬜ todo |
| 42 | [Gaussian Mixture Models (GMM)](./04_clustering/06_gmm/) | | Soft cluster assignments using Expectation-Maximization | ⬜ todo |
| 43 | [Hierarchical Agglomerative](./04_clustering/07_hierarchical/) | | Bottom-up tree of clusters — no K needed upfront | ⬜ todo |
| 44 | [Divisive Hierarchical](./04_clustering/08_divisive/) | | Top-down tree splitting — opposite of agglomerative | ⬜ todo |
| 45 | [Mean Shift](./04_clustering/09_mean_shift/) | | Moves points toward density peaks — finds K automatically | ⬜ todo |
| 46 | [OPTICS](./04_clustering/10_optics/) | | DBSCAN variant with ordering — handles varying density | ⬜ todo |
| 47 | [Spectral Clustering](./04_clustering/11_spectral/) | | Uses graph structure — great for non-convex shapes | ⬜ todo |
| 48 | [Affinity Propagation](./04_clustering/12_affinity_propagation/) | | No K needed — data points vote for cluster representatives | ⬜ todo |
| 49 | [Birch](./04_clustering/13_birch/) | | Tree-based incremental clustering — scales to large data | ⬜ todo |

---

### 📂 05 · Dimensionality Reduction

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 50 | [PCA](./05_dimensionality_reduction/01_pca/) | ⭐ MAJOR | Projects data onto directions of max variance | ⬜ todo |
| 51 | [Kernel PCA](./05_dimensionality_reduction/02_kernel_pca/) | | PCA with kernel trick — captures non-linear structure | ⬜ todo |
| 52 | [Incremental PCA](./05_dimensionality_reduction/03_incremental_pca/) | | PCA on data too large to fit in memory | ⬜ todo |
| 53 | [Sparse PCA](./05_dimensionality_reduction/04_sparse_pca/) | | PCA with sparse components — interpretable loadings | ⬜ todo |
| 54 | [t-SNE](./05_dimensionality_reduction/05_tsne/) | | Non-linear — best for visualizing clusters in 2D/3D | ⬜ todo |
| 55 | [UMAP](./05_dimensionality_reduction/06_umap/) | | Faster than t-SNE, preserves global structure better | ⬜ todo |
| 56 | [LDA (as reducer)](./05_dimensionality_reduction/07_lda_reducer/) | | Supervised reduction — uses class labels to find best axes | ⬜ todo |
| 57 | [Truncated SVD (LSA)](./05_dimensionality_reduction/08_truncated_svd/) | | SVD on sparse matrices — used in text (Latent Semantic Analysis) | ⬜ todo |
| 58 | [NMF](./05_dimensionality_reduction/09_nmf/) | | Factorizes into non-negative parts — interpretable components | ⬜ todo |
| 59 | [ICA](./05_dimensionality_reduction/10_ica/) | | Finds statistically independent components — signal separation | ⬜ todo |
| 60 | [Factor Analysis](./05_dimensionality_reduction/11_factor_analysis/) | | Models observed variables as linear combinations of latent factors | ⬜ todo |
| 61 | [Random Projection](./05_dimensionality_reduction/12_random_projection/) | | Very fast dimensionality reduction — preserves distances | ⬜ todo |
| 62 | [Autoencoder](./05_dimensionality_reduction/13_autoencoder/) | | Neural network bottleneck — non-linear compression | ⬜ todo |
| 63 | [Variational Autoencoder (VAE)](./05_dimensionality_reduction/14_vae/) | | Autoencoder with probabilistic latent space — generative | ⬜ todo |

---

### 📂 06 · Anomaly Detection

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 64 | [Isolation Forest](./06_anomaly_detection/01_isolation_forest/) | ⭐ MAJOR | Anomalies are easy to isolate — short path in random trees | ⬜ todo |
| 65 | [Local Outlier Factor (LOF)](./06_anomaly_detection/02_lof/) | | Low density relative to neighbors = outlier | ⬜ todo |
| 66 | [One-Class SVM](./06_anomaly_detection/03_one_class_svm/) | | Boundary around normal data — no anomaly labels needed | ⬜ todo |
| 67 | [Elliptic Envelope](./06_anomaly_detection/04_elliptic_envelope/) | | Fits a Gaussian — Mahalanobis distance threshold | ⬜ todo |
| 68 | [Autoencoder-based](./06_anomaly_detection/05_autoencoder_anomaly/) | | High reconstruction error = anomaly | ⬜ todo |

---

### 📂 07 · Time Series

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 69 | [ARIMA](./07_time_series/01_arima/) | | Univariate forecasting via autoregression + moving average | ⬜ todo |
| 70 | [SARIMA](./07_time_series/02_sarima/) | | ARIMA with seasonal components | ⬜ todo |
| 71 | [Prophet](./07_time_series/03_prophet/) | ⭐ MAJOR | Additive model — trend + seasonality + holidays | ⬜ todo |
| 72 | [Exponential Smoothing](./07_time_series/04_exponential_smoothing/) | | Weighted average — recent data weighted more | ⬜ todo |
| 73 | [VAR](./07_time_series/05_var/) | | Multivariate time series — captures inter-variable dynamics | ⬜ todo |
| 74 | [XGBoost for Time Series](./07_time_series/06_xgboost_ts/) | ⭐ MAJOR | Lag features + rolling stats → standard GBM | ⬜ todo |
| 75 | [LightGBM for Time Series](./07_time_series/07_lgbm_ts/) | | Same as XGBoost TS but faster on large data | ⬜ todo |

---

### 📂 08 · Bayesian Methods

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 76 | [Bayesian Linear Regression](./08_bayesian/01_bayesian_linear/) | | Prediction with uncertainty — outputs distribution | ⬜ todo |
| 77 | [Gaussian Process Regression](./08_bayesian/02_gpr/) | | Non-parametric Bayesian — prior over functions | ⬜ todo |
| 78 | [Gaussian Process Classification](./08_bayesian/03_gpc/) | | GPR applied to classification problems | ⬜ todo |
| 79 | [Bayesian Optimization](./08_bayesian/04_bayesian_optimization/) | | Smart hyperparameter tuning using surrogate model | ⬜ todo |
| 80 | [Hidden Markov Model (HMM)](./08_bayesian/05_hmm/) | | Sequence modeling with hidden states | ⬜ todo |
| 81 | [MCMC](./08_bayesian/06_mcmc/) | | Sampling from posterior distributions | ⬜ todo |

---

### 📂 09 · Semi-supervised & Self-supervised

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 82 | [Label Propagation](./09_semi_supervised/01_label_propagation/) | | Spread labels from labeled to unlabeled via graph | ⬜ todo |
| 83 | [Label Spreading](./09_semi_supervised/02_label_spreading/) | | Softer version of label propagation | ⬜ todo |
| 84 | [Self-Training](./09_semi_supervised/03_self_training/) | | Pseudo-label high-confidence predictions, retrain | ⬜ todo |
| 85 | [Co-Training](./09_semi_supervised/04_co_training/) | | Two models train each other on different feature views | ⬜ todo |
| 86 | [Contrastive Learning](./09_semi_supervised/05_contrastive/) | | Learn representations by pulling similar, pushing dissimilar | ⬜ todo |

---

### 📂 10 · Association Rule Mining

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 87 | [Apriori](./10_association/01_apriori/) | | Find frequent itemsets via candidate generation | ⬜ todo |
| 88 | [FP-Growth](./10_association/02_fp_growth/) | | Frequent itemsets via FP-tree — 10-100x faster than Apriori | ⬜ todo |
| 89 | [Eclat](./10_association/03_eclat/) | | FP-Growth variant using vertical data format | ⬜ todo |

---

### 📂 11 · Ranking & Recommendation

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 90 | [Collaborative Filtering — User-based](./11_recommendation/01_cf_user/) | | Recommend based on similar users' preferences | ⬜ todo |
| 91 | [Collaborative Filtering — Item-based](./11_recommendation/02_cf_item/) | | Recommend based on similar items | ⬜ todo |
| 92 | [Matrix Factorization (SVD/ALS)](./11_recommendation/03_matrix_factorization/) | | Decompose user-item matrix into latent factors | ⬜ todo |
| 93 | [Content-Based Filtering](./11_recommendation/04_content_based/) | | Recommend based on item features, not user history | ⬜ todo |
| 94 | [LTR — Pointwise](./11_recommendation/05_ltr_pointwise/) | | Rank via regression/classification on individual items | ⬜ todo |
| 95 | [LTR — Pairwise (RankNet)](./11_recommendation/06_ltr_pairwise/) | | Rank by comparing pairs — which item is better? | ⬜ todo |
| 96 | [LTR — Listwise (LambdaMART)](./11_recommendation/07_ltr_listwise/) | | Optimize ranking metrics (NDCG) directly | ⬜ todo |

---

### 📂 12 · Reinforcement Learning

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 97 | [Q-Learning](./12_reinforcement/01_q_learning/) | | Agent learns action-value table from reward signals | ⬜ todo |
| 98 | [Deep Q-Network (DQN)](./12_reinforcement/02_dqn/) | | Q-learning with neural network function approximator | ⬜ todo |
| 99 | [SARSA](./12_reinforcement/03_sarsa/) | | On-policy Q-learning variant | ⬜ todo |
| 100 | [Policy Gradient (REINFORCE)](./12_reinforcement/04_policy_gradient/) | | Directly optimizes the policy via gradient ascent on reward | ⬜ todo |
| 101 | [Actor-Critic (A2C/A3C)](./12_reinforcement/05_actor_critic/) | | Policy gradient + value function baseline | ⬜ todo |
| 102 | [PPO](./12_reinforcement/06_ppo/) | | Stable policy gradient — prevents too-large updates | ⬜ todo |
| 103 | [Multi-Armed Bandit](./12_reinforcement/07_bandit/) | | Explore vs exploit tradeoff — simpler RL setting | ⬜ todo |
| 104 | [MCTS](./12_reinforcement/08_mcts/) | | Tree search guided by simulation — used in AlphaGo | ⬜ todo |

---

### 📂 13 · Optimization Algorithms

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 105 | [Batch Gradient Descent](./13_optimization/01_batch_gd/) | ⭐ MAJOR | Full dataset per parameter update | ⬜ todo |
| 106 | [Stochastic GD (SGD)](./13_optimization/02_sgd/) | ⭐ MAJOR | One sample per update — noisy but fast | ⬜ todo |
| 107 | [Mini-Batch GD](./13_optimization/03_minibatch_gd/) | ⭐ MAJOR | Best of batch + SGD — standard in practice | ⬜ todo |
| 108 | [SGD with Momentum](./13_optimization/04_momentum/) | | Accumulates velocity — smooths oscillations | ⬜ todo |
| 109 | [RMSprop](./13_optimization/05_rmsprop/) | | Adaptive learning rate per parameter | ⬜ todo |
| 110 | [Adam](./13_optimization/06_adam/) | | Momentum + RMSprop — default for neural networks | ⬜ todo |
| 111 | [AdaGrad](./13_optimization/07_adagrad/) | | Large LR for rare features, small for frequent | ⬜ todo |
| 112 | [L-BFGS](./13_optimization/08_lbfgs/) | | Quasi-Newton — very fast on small/medium problems | ⬜ todo |
| 113 | [Coordinate Descent](./13_optimization/09_coordinate_descent/) | | Optimize one parameter at a time — used in Lasso | ⬜ todo |
| 114 | [Genetic / Evolutionary](./13_optimization/10_genetic/) | | Population-based search — no gradient needed | ⬜ todo |
| 115 | [Bayesian Optimization](./13_optimization/11_bayesian_opt/) | | Gaussian Process surrogate — smart HPO | ⬜ todo |

---

### 📂 14 · Specialized Statistical ML

| # | Algorithm | Major | What It Solves | Status |
|---|-----------|-------|----------------|--------|
| 116 | [Cox Proportional Hazards](./14_statistical/01_cox/) | | Survival analysis — time until event | ⬜ todo |
| 117 | [Kaplan-Meier](./14_statistical/02_kaplan_meier/) | | Non-parametric survival curve estimation | ⬜ todo |
| 118 | [Random Survival Forest](./14_statistical/03_random_survival_forest/) | | Random forest for survival outcomes | ⬜ todo |
| 119 | [Poisson Regression](./14_statistical/04_poisson/) | | Predict counts — calls per hour, accidents per day | ⬜ todo |
| 120 | [Multinomial Logistic (Softmax)](./14_statistical/05_softmax/) | | Multi-class classification via softmax | ⬜ todo |
| 121 | [Ordinal Regression](./14_statistical/06_ordinal/) | | Predict ordered categories — low/medium/high | ⬜ todo |

---

## 📁 Folder Structure (Every Algorithm)

```
01_regression/
└── 01_linear_regression/
    ├── README.md              ← theory, math, results, key insight, failure story
    ├── 01_scratch_numpy.py    ← from-scratch NumPy implementation
    ├── 02_sklearn_apply.py    ← sklearn on real dataset
    ├── 03_evaluation.py       ← all metrics, learning curve, residual plots
    └── plots/
        ├── loss_curve.png
        ├── predictions_vs_actual.png
        └── residual_plot.png
```

**Every `README.md` inside an algorithm folder contains:**
- Intuition (plain words + analogy)
- The core math (derived, not copy-pasted)
- Implementation notes (what was hard, what was surprising)
- Dataset used + results table (train/val metrics)
- Key insight learned
- Failure story (what broke first and how I fixed it)
- When to use / when NOT to use
- Resources used

---

## 📊 Progress Tracker

| # | Algorithm | Family | Status | Date Completed | Key Insight |
|---|-----------|--------|--------|---------------|-------------|
| 1 | Linear Regression | Regression | ⬜ todo | — | — |
| 2 | Logistic Regression | Classification | ⬜ todo | — | — |
| 3 | Decision Tree | Classification | ⬜ todo | — | — |
| 4 | Random Forest | Ensemble | ⬜ todo | — | — |
| 5 | Gradient Boosting | Ensemble | ⬜ todo | — | — |
| 6 | XGBoost | Ensemble | ⬜ todo | — | — |
| 7 | LightGBM | Ensemble | ⬜ todo | — | — |
| 8 | K-Means | Clustering | ⬜ todo | — | — |
| 9 | PCA | Dim Reduction | ⬜ todo | — | — |
| 10 | Isolation Forest | Anomaly Detection | ⬜ todo | — | — |
| 11 | Ridge Regression | Regression | ⬜ todo | — | — |
| 12 | Prophet | Time Series | ⬜ todo | — | — |
| 13 | XGBoost for TS | Time Series | ⬜ todo | — | — |
| 14 | Gradient Descent (all variants) | Optimization | ⬜ todo | — | — |

> Start with the 14 MAJOR algorithms. Everything else follows.

---

## 📖 ML Terms, Words & Their Meanings

> Every term defined clearly — not dictionary definitions, but real intuitive understanding.

---

### Core Concepts

| Term | Clear Definition |
|------|-----------------|
| **Machine learning** | Teaching a computer to find patterns from data, instead of writing the rules yourself |
| **Supervised learning** | Learning from labeled examples — input X and correct output y both provided |
| **Unsupervised learning** | Finding patterns in data that has no labels — the algorithm discovers structure itself |
| **Reinforcement learning** | An agent learns by taking actions and receiving rewards or penalties — like training a dog |
| **Model** | A mathematical function that maps inputs → outputs after learning from data |
| **Parameter** | A value inside the model learned from data — weights, biases, tree splits |
| **Hyperparameter** | A setting you choose before training — learning rate, number of trees, max depth |
| **Feature** | One measurable property of the data used as input — one column in your dataset |
| **Label / Target** | The output variable the model is trying to predict — also called y or ground truth |
| **Inference** | Using a trained model to make predictions on new data — the production phase |
| **Inductive bias** | The assumptions an algorithm makes to generalize beyond training data |

---

### Data & Preprocessing

| Term | Clear Definition |
|------|-----------------|
| **Training set** | Data the model learns from — parameters are adjusted on this |
| **Validation set** | Data used to tune hyperparameters — model doesn't train on this |
| **Test set** | Held-out data touched only once — final honest evaluation |
| **Data leakage** | When information from outside training sneaks into the model — causes fake good results |
| **Feature engineering** | Creating, transforming, or selecting features to help the model learn better |
| **Feature scaling** | Transforming features to comparable scales — StandardScaler, MinMaxScaler |
| **One-hot encoding** | Converting a categorical variable into binary columns — Red → [1,0,0] |
| **Missing values** | Data points with no recorded value — must handle before fitting |
| **Outlier** | A data point far from the rest — can distort MSE-based models |
| **Class imbalance** | One class has far more examples than another — accuracy becomes a useless metric |
| **MCAR / MAR / MNAR** | Missing Completely At Random / At Random / Not At Random — why data is missing determines how to handle it |
| **EDA** | Exploratory Data Analysis — understand your data before modeling |

---

### Training & Optimization

| Term | Clear Definition |
|------|-----------------|
| **Loss function** | Measures how wrong predictions are — what training minimizes |
| **MSE** | Mean Squared Error — average of squared differences between predicted and actual |
| **Cross-entropy** | Loss for classification — penalizes confident wrong predictions heavily |
| **Gradient descent** | Move parameters in the direction that reduces the loss — like walking downhill blindfolded |
| **Gradient** | The slope of the loss with respect to each parameter — tells us which direction is uphill |
| **Learning rate (α)** | Controls step size during gradient descent — too high = overshoot, too low = slow |
| **Epoch** | One full pass through the entire training dataset |
| **Batch size** | Number of examples processed before each parameter update |
| **Backpropagation** | Chain rule applied backwards through a neural network to compute gradients |
| **Convergence** | When the loss stops improving — training is done |
| **Overfitting** | Model memorizes training data including noise — fails on new data |
| **Underfitting** | Model too simple to capture the pattern — fails on both train and new data |
| **Bias** | Error from wrong assumptions — underfitting |
| **Variance** | Error from sensitivity to training data — overfitting |
| **Bias-variance tradeoff** | Simple models have high bias, complex models have high variance — find the balance |

---

### Regularization

| Term | Clear Definition |
|------|-----------------|
| **Regularization** | Adding a penalty to the loss to prevent overfitting by constraining parameter size |
| **L1 (Lasso)** | Penalty = sum of absolute weights — drives irrelevant weights to exactly zero |
| **L2 (Ridge)** | Penalty = sum of squared weights — shrinks all weights toward zero |
| **ElasticNet** | L1 + L2 combined — feature selection + weight shrinkage |
| **Dropout** | Randomly deactivate neurons during training — prevents co-adaptation in neural nets |
| **Early stopping** | Stop training when validation loss stops improving — prevents over-training |
| **λ (lambda)** | Regularization strength — higher = more penalty, more shrinkage |

---

### Evaluation & Metrics

| Term | Clear Definition |
|------|-----------------|
| **Accuracy** | Correct predictions / total predictions — misleading on imbalanced data |
| **Precision** | Of all positive predictions, how many were actually positive — TP/(TP+FP) |
| **Recall** | Of all actual positives, how many did we find — TP/(TP+FN) |
| **F1 score** | Harmonic mean of precision and recall — balances both |
| **AUC-ROC** | Area under ROC curve — model's ability to rank positives above negatives |
| **Confusion matrix** | 2×2 table of TP, FP, TN, FN — full picture of classifier performance |
| **RMSE** | Root Mean Squared Error — prediction error in same units as y |
| **MAE** | Mean Absolute Error — robust version of RMSE |
| **R² score** | Fraction of variance in y explained by the model — 1 = perfect, 0 = useless |
| **Cross-validation** | Evaluate on multiple train/val splits — more reliable than a single split |
| **Learning curve** | Plot of train vs val loss across training — diagnoses overfit/underfit |
| **Residual** | Actual - predicted — should be random and centered at zero |

---

### Algorithm-Specific Terms

| Term | Clear Definition |
|------|-----------------|
| **Decision boundary** | The line (or surface) separating predicted classes |
| **Support vectors** | The training points closest to the SVM margin — only these define the boundary |
| **Kernel trick** | Compute dot products in high-dimensional space without actually going there |
| **Entropy** | Measure of impurity in a node — 0 = pure (all one class), 1 = maximum mix |
| **Gini impurity** | Alternative impurity measure — probability of misclassifying a random sample |
| **Information gain** | Entropy reduction from a split — how much a feature helps separate the classes |
| **Bootstrap sampling** | Sampling with replacement — foundation of Random Forest's diversity |
| **Bagging** | Train models on bootstrap samples, average results — reduces variance |
| **Boosting** | Train models sequentially, each fixing the previous one's errors |
| **Residuals (boosting)** | The errors the current model makes — what the next tree learns to fix |
| **Silhouette score** | Measures cluster quality — 1 = perfect separation, 0 = overlapping |
| **Elbow method** | Plot inertia vs K for K-Means — bend = good K |
| **Eigenvalue / Eigenvector** | Eigenvectors = directions of variance in PCA, eigenvalues = amount of variance |
| **Latent factor** | Hidden representation learned by matrix factorization — encodes user/item taste |
| **Anomaly score** | How unusual a point is — higher = more anomalous |
| **OOB error** | Out-of-bag error in Random Forest — free validation from bootstrap samples not used |
| **Softmax** | Converts raw scores into probabilities summing to 1 — used in multi-class output |
| **Sigmoid** | Maps any real number to (0,1) — used in logistic regression for probability |

---

### Production & MLOps Terms

| Term | Clear Definition |
|------|-----------------|
| **Pipeline** | Chain preprocessing + model into one object — prevents data leakage |
| **Model drift** | Model performance degrades over time as data distribution changes |
| **Data drift** | Input feature distribution changes — users behave differently over time |
| **Concept drift** | Relationship between inputs and outputs changes — e.g. post-pandemic patterns |
| **Serialization** | Saving a trained model to disk — joblib for sklearn, state_dict for PyTorch |
| **Serving** | Deploying a model behind an API to receive real-time predictions |
| **Latency** | Time taken to return one prediction — must be fast in production |
| **Feature store** | Central repository of features — reuse across models, avoid recomputing |
| **A/B testing** | Compare two model versions on real traffic to measure which is better |
| **Baseline** | Simplest possible model — always build this first to have a comparison point |
| **SHAP values** | Per-feature contribution score for each individual prediction — gold standard for explainability |
| **Pseudo-labeling** | Using model's own high-confidence predictions as training labels |
| **Hyperparameter tuning** | Searching for the best hyperparameter values — grid search, random, Bayesian |
| **Stratified split** | Train/val/test split that preserves class proportions — essential for imbalanced data |

---

## 🛣️ Learning Path After This Repo

Once every major ML algorithm is complete in this repo with all 5 layers documented:

```
Core ML (this repo)
        ↓
Deep Learning — same 5-layer system
 Neural nets from scratch → CNNs → RNNs/LSTMs → Transformers
        ↓
Specialization (pick one lane)
 Computer Vision  OR  NLP / LLMs
        ↓
MLOps & Deployment
 FastAPI → Docker → CI/CD → Model monitoring
        ↓
End-to-end projects (2-3 complete, deployed, documented)
        ↓
Same encyclopedia structure for DL, NLP, CV
```

---

## ⚙️ Setup & Running Code

```bash
# clone the repo
git clone https://github.com/sanjay5656/Machine-Learning-Encyclopedia.git
cd Machine-Learning-Encyclopedia

# create virtual environment
python -m venv ml-env
source ml-env/bin/activate        # Linux/Mac
ml-env\Scripts\activate           # Windows

# install dependencies
pip install -r requirements.txt

# run any algorithm
cd 01_regression/01_linear_regression
python 01_scratch_numpy.py
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
lightgbm
scipy
statsmodels
optuna
joblib
fastapi
uvicorn
```

---

## 📬 Connect

If you are learning ML and found this useful, or if you are a recruiter:

- **GitHub:** [github.com/sanjay5656](https://github.com/sanjay5656)
- **Portfolio:** [suvsan-mldev.netlify.app](https://suvsan-mldev.netlify.app)
- **LinkedIn:** [linkedin.com/in/sanjay-s](https://linkedin.com/in/sanjay-s)

---

*Built with the goal of understanding every algorithm at PhD depth — not just using it, but knowing why it works, when it fails, and how to fix it.*