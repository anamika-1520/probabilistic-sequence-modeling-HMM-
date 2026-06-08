# 📈 Advanced Multivariate Hidden Markov Model for Indian Stock Market Regime Detection

> M.Sc. Thesis Research Project | IIT (ISM) Dhanbad

A novel market regime detection framework for the Indian stock market using a Multivariate Hidden Markov Model (HMM) with volatility-aware state transitions.

This research extends traditional HMM-based financial modeling by incorporating India VIX alongside Nifty 50 returns, enabling more robust identification of hidden market regimes and improved characterization of market uncertainty.

---

## 🎯 Research Objective

Financial markets continuously switch between hidden regimes such as:

- Bull Markets 📈
- Bear Markets 📉
- High Volatility Periods ⚠️
- Stable Growth Phases ✅

Traditional approaches rely only on price returns and often fail to capture extreme market events.

This thesis proposes a multivariate regime-switching framework that jointly models:

- Nifty 50 Returns
- India VIX (Volatility Index)

to better understand hidden market dynamics.

---

## 🚀 Novel Contributions

### 1. Multivariate HMM Framework

**Existing Research**
- Uses only stock returns

**This Research**
- Uses Nifty 50 Returns + India VIX simultaneously

Benefits:
- Better regime separation
- Volatility-aware state detection
- Improved market interpretation

---

### 2. Student-t Distribution Inspired Modeling

Financial returns exhibit:

- Heavy tails
- Extreme crashes
- Rare events

Traditional Gaussian assumptions underestimate these events.

This research incorporates Student-t based analysis concepts to better represent:

- Market crashes
- Sudden volatility spikes
- Tail risk

---

### 3. Indian Market Focus

Most existing studies focus on:

- S&P 500
- US markets

This work specifically studies:

- Nifty 50
- India VIX

making it directly relevant to the Indian financial ecosystem.

---

### 4. Enhanced Regime Detection

The proposed framework identifies market states using:

- Return behavior
- Volatility behavior
- Transition probabilities
- Persistence characteristics

allowing deeper understanding of market structure.

---

## 🛠️ Technology Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- yFinance
- hmmlearn
- SciPy

---

## 📊 Methodology

### Step 1: Data Collection

Weekly market data is collected for:

- Nifty 50 Index
- India VIX

### Step 2: Feature Engineering

Features:

- Log Returns
- Volatility Index Values

### Step 3: Model Selection

Models with multiple hidden states are evaluated using:

- AIC
- BIC
- Log-Likelihood

### Step 4: Hidden State Identification

Hidden Markov Models are trained to identify latent market regimes.

### Step 5: Regime Analysis

Each state is analyzed based on:

- Average Return
- Average VIX
- Persistence Probability
- Market Interpretation

---

## 📈 Visualizations

The project generates:

### Market Regime Segmentation

Visual representation of hidden market states across time.

### Volatility Analysis

India VIX behavior under different regimes.

### Student-t vs Gaussian Comparison

Demonstrates why heavy-tail modeling is important in financial markets.

### Model Fit Analysis

Actual returns vs HMM estimated returns.

### Posterior Regime Probabilities

Probability of stable and unstable market conditions.

### Strategy Performance Comparison

Comparison between:

- Buy & Hold Strategy
- HMM-based Regime Strategy

---

## 📂 Project Structure

Advanced-Multivariate-HMM-Indian-Stock-Market/
│
├── thesis_code.py
├── thesis_all_graphs.png
├── fig7_aic_bic_selection.png
├── fig8_student_t_vs_gaussian.png
├── state_characteristics.csv
├── transition_matrix.csv
├── model_selection.csv
├── requirements.txt
└── README.md

---

## 📌 Key Findings

- Successfully identifies hidden market regimes.
- Captures volatility-aware transitions.
- Provides interpretable state persistence analysis.
- Improves understanding of market uncertainty.
- Demonstrates the usefulness of multivariate regime-switching models for emerging markets.

---

## 🔬 Academic Significance

This work extends classical Hidden Markov Models by incorporating:

- Multiple financial variables
- Volatility-aware regime detection
- Indian market analysis
- Enhanced market state interpretation

The framework can be further extended for:

- Portfolio Optimization
- Risk Management
- Market Forecasting
- Algorithmic Trading
- Financial Decision Support Systems

---

## 👩‍💻 Author

**Anamika**
M.Sc. Mathematics & Computing  
Indian Institute of Technology (ISM) Dhanbad

Interested in:
- Data Science
- Machine Learning
- Artificial Intelligence
- Financial Analytics
- Generative AI

---

## ⭐ Future Enhancements

- Deep Hidden Markov Models
- Bayesian HMMs
- Regime-aware Portfolio Allocation
- Reinforcement Learning Integration
- Real-time Market Regime Detection

---

### If you found this project interesting, feel free to star the repository ⭐
