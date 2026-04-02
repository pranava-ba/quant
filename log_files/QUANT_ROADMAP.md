# 📈 Quant Finance — 240-Day Roadmap
### Start Date: April 1, 2026 · End Date: November 27, 2026

> **Purpose:** A ground-up, sequenced roadmap from systematic trading fundamentals to advanced stochastic methods and research-grade quant work. Progress is logged below each phase. The majority of projects use NSE/Indian market data (Bank Nifty, Nifty 50, NSE F&O, commodities). Books are tools — reading specific chapters at the right moment, alongside implementation, is what matters.

---

## 📚 Resource Index

### Books — Reading Order & Role

Books are not read cover-to-cover in sequence. Each is introduced at the phase and chapter where it is most useful. The table below reflects *when each book enters*, not a cover-to-cover order.

| # | Title | Author(s) | Role in Roadmap | Enters |
|---|-------|-----------|-----------------|--------|
| B1 | *Quantitative Trading* | Ernest P. Chan | Systematic trading mental model; strategy types; backtesting pitfalls; position sizing | Phase 1 |
| B2 | *Algorithmic Trading* | Ernest P. Chan | Backtesting engine design; execution modelling; Sharpe ratio analysis | Phase 2 |
| B3 | *Machine Learning for Algorithmic Trading* | Stefan Jansen | ML features, factor modelling, alternative data; complements projects | Phase 3–4 |
| B4 | *Systematic Trading* | Robert Carver | Position sizing rules; combining forecasts; instrument selection; risk targeting | Phase 1–2 |
| B5 | *Options, Futures, and Other Derivatives* | John C. Hull | Derivatives mechanics; Black-Scholes; Greeks; interest rate models | Phase 2 |
| B6 | *Option Volatility and Pricing* | Sheldon Natenberg | Vol surface intuition; trading the Greeks; professional options thinking | Phase 3 |
| B7 | *The Bible of Options Strategies* | Guy Cohen | Comprehensive options strategy reference; payoff diagrams; strategy selection | Phase 2 |
| B8 | *Options Made Easy* | Guy Cohen | Accessible first pass at options mechanics; NSE-relevant payoff thinking | Phase 1–2 |
| B9 | *Bayesian Statistics the Fun Way* | Will Kurt | Bayesian reasoning; updating beliefs; priors/posteriors without measure theory | Phase 1 |
| B10 | *Thinking Strategically* | Dixit & Nalebuff | Game theory intuition; Nash equilibrium; strategic reasoning in markets | Phase 2 |
| B11 | *Measure, Integration and Real Analysis* | Sheldon Axler | Measure theory; Lebesgue integration; probability spaces; rigorous foundation for stochastic calculus | Phase 3 |
| B12 | *Variational Calculus and Optimal Control* | John L. Troutman | Euler-Lagrange; Pontryagin's principle; Hamilton-Jacobi-Bellman; constrained optimization | Phase 4 |
| B13 | *Numerical Optimization* | Nocedal & Wright | Gradient descent; Newton's method; KKT; QP; interior point methods | Phase 3 |
| B14 | *Markov Chain Monte Carlo* | Gamerman & Lopes | Markov chains; Metropolis-Hastings; Gibbs sampling; HMM foundations | Phase 3 |
| B15 | *Stochastic Differential Equations* | Bernt Øksendal | Brownian motion; Itô integral; SDEs; Girsanov; Feynman-Kac | Phase 4 |
| B16 | *Stochastic Calculus for Finance I* | Steven Shreve | Binomial models; no-arbitrage; risk-neutral measure; American options | Phase 4 |
| B17 | *Stochastic Calculus for Finance II* | Steven Shreve | Continuous-time; Itô's lemma; Black-Scholes derivation; martingale representation | Phase 4 |
| B18 | *A Practical Guide to Quantitative Finance Interviews* | Xinfeng Zhou | Interview problems: probability, statistics, options, brain teasers — running reference | Phase 2–4 |
| B19 | *Heard on the Street* | Timothy Falcon Crack | Brain teasers; quantitative interview classics; mental math | Phase 2–4 |
| B20 | *Quant Job Interview Questions and Answers* | Joshi, Denson & Downes | Probability, stochastic calculus, derivatives interview questions | Phase 2–4 |
| B21 | *150 Most Frequently Asked Questions on Quant Interviews* | Dan Stefanica | Concise interview question set; mathematics and probability focus | Phase 3–4 |
| B22 | *An Introduction to Probability Theory and Its Applications, Vol. 1* | William Feller | Rigorous combinatorics; random variables; generating functions; classical probability | Phase 2 |
| B23 | *Fifty Challenging Problems in Probability* | Frederick Mosteller | Worked probability puzzles — daily practice tool across all phases | Phase 1–4 |
| B24 | *Frequently Asked Questions in Quantitative Finance* | Paul Wilmott | Derivatives intuition; risk-neutral pricing; model critiques; concise finance reference | Phase 3–4 |
| B25 | *An Interview Primer for Quantitative Finance* | Dirk Bester | Interview strategy; concise mathematics review; problem taxonomy | Phase 2–3 |
| B26 | *Quantitative Portfolio Management* | Michael Isichenko | Alpha decay; IC/IR framework; signal combination; portfolio construction theory | Phase 3–4 |
| B27 | *Monte Carlo Methods in Financial Engineering* | Paul Glasserman | Simulation; GBM; variance reduction; path-dependent pricing | Phase 3 |
| B28 | *Asset Pricing* | John Cochrane | Factor models; SDF; GMM; linking statistical factors to economic theory | Phase 3 |
| B29 | *Convex Optimization* | Boyd & Vandenberghe | Convex sets; Lagrangians; duality; interior-point; portfolio optimization as convex QP | Phase 3 |
| B30 | *Pairs Trading: Quantitative Methods and Analysis* | Vidyamurthy | Cointegration; Engle-Granger; hedge ratios; stat arb trade rules | Phase 2–3 |
| B31 | *Investments* | Bodie, Kane & Marcus | Portfolio theory; CAPM; efficient markets; fixed income; risk | Phase 2 |
| B32 | *Value at Risk* | Philippe Jorion | Historical VaR; parametric VaR; backtesting; risk management frameworks | Phase 2 |
| B33 | *Market Risk Analysis: Quantitative Methods in Finance* | Carol Alexander | Time series models; GARCH; PCA; risk metrics; quantitative risk overview | Phase 3 |
| B34 | *Max Dama on Automated Trading* | Max Dama | Market microstructure; order flow; execution; alpha sourcing philosophy | Phase 2–3 |
| B35 | *Quant Trading Guide* | Callum McDougall | Accessible orientation to quant trading: strategies, careers, tooling | Phase 1 |
| B36 | *Quant, FM, and Data Science Interview Compilation* | Aaron Cao | Aggregated interview questions spanning probability, ML, and finance | Phase 3–4 |
| B37 | *The Art of Quantitative Finance, Vol. 1* | Gerhard Larcher | Rigorous mathematical finance from first principles; complements Hull and Shreve | Phase 2–3 |

---

### Websites & Online Platforms

| # | Resource | URL | Use |
|---|----------|-----|-----|
| W1 | QuantStart | quantstart.com | Tutorials; Python finance; project guides |
| W2 | Investopedia | investopedia.com | Concept explanations; quick definitions |
| W3 | Brainstellar Puzzles | brainstellar.com/puzzles | Daily quant puzzles; probability and combinatorics |
| W4 | TraderMath | tradermath.org | Mental arithmetic drills |
| W5 | Figgie (Jane Street) | figgie.com | Market-making intuition game |
| W6 | QuantQuestions | quantquestions.com | Structured quant interview practice |
| W7 | Quantable | quantable.io | Quantitative interview prep |
| W8 | Wall Street Oasis | wallstreetoasis.com | Career discussion; interview experience |
| W9 | Mergers & Inquisitions | mergersandinquisitions.com | Finance concepts for context |
| W10 | Peak Frameworks | peakframeworks.com | Finance interview framework |
| W11 | Reddit Quant Prep Aggregate | reddit.com/r/quant | Community resource lists; prep discussion |
| W12 | al0vya GitHub Quant Prep | github.com/al0vya/quant-prep | Python code examples for quant concepts |
| W13 | Max Dama Brainteasers (Notion) | work-in-progress.notion.site/Max-Dama-s-Brainteasers | Extended brainteaser bank |
| W14 | NSE India | nseindia.com | Live options chain; F&O data; market data |
| W15 | NSE Bhavcopy / EOD Data | nseindia.com/all-reports | End-of-day market data downloads |
| W16 | QuantInsti | quantinsti.com | Indian quant education; EPAT material |
| W17 | Zerodha Varsity | zerodha.com/varsity | F&O mechanics for Indian market |
| W18 | OpenBB Platform | openbb.finance | Institutional-grade data access |
| W19 | QuantLib | quantlib.org | Derivatives pricing library; numerical methods |

---

## 🗂️ Progress Tracker

> **Legend:** ⬜ Not started · 🔄 In progress · ✅ Complete

---

## PHASE 1 — Systematic Trading Foundations
### Days 1–50 · April 1 – May 20, 2026

**Theme:** Build the core mental model of systematic and quantitative trading. Establish the essential statistical toolkit — returns, volatility, correlation, stationarity, autocorrelation — and learn to compute them from real NSE data. Understand how backtesting works conceptually. Introduce probability from first principles.

**Mathematical build-up:** Descriptive statistics → probability distributions → time series concepts → introductory Bayesian reasoning.

**Primary Books (active chapters):**
- B1 Ch. 1–6 — Systematic trading mindset; strategy types; position sizing; backtesting principles; Sharpe ratio
- B4 Ch. 1–5 — Carver's position sizing and forecast framework; risk targeting; instrument selection
- B8 Ch. 1–4 — Options: what they are, calls/puts, payoff diagrams, NSE context
- B9 Ch. 1–6 — Bayesian reasoning; conditional probability; updating beliefs
- B35 (full) — Orientation to the quant field; career paths; tooling overview
- B23 (problems 1–20) — Daily probability problem practice begins

**Primary Sites:** W1 (QuantStart), W2 (Investopedia), W14 (NSE India), W15 (NSE EOD), W17 (Zerodha Varsity)

---

### 🔷 Week 1 · Days 1–7 · Apr 1–7

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 1 | Apr 1 | What is systematic/quantitative trading? Field map; discretionary vs systematic; where quant fits | B1 Ch.1, B35 (full), W2 | Concept | ⬜ |
| 2 | Apr 2 | Returns: arithmetic vs log returns; why log is used; annualisation; formal definitions | B1 Ch.2, W2 | Concept | ⬜ |
| 3 | Apr 3 | Variance and standard deviation: population vs sample; volatility as annualised std dev | B1 Ch.2, W1 | Concept | ⬜ |
| 4 | Apr 4 | Sharpe ratio: formula, numerator/denominator, annualisation, intuition, limitations | B1 Ch.2, B4 Ch.3 | Concept | ⬜ |
| 5 | Apr 5 | Python setup: NumPy, pandas, matplotlib, scipy — environment, data structures, workflow | W1 (Python for Finance series) | Coding | ⬜ |
| 6 | Apr 6 | Load NSE Bhavcopy data; compute arithmetic and log daily returns for Nifty 50 index | W15, W1 | Coding | ⬜ |
| 7 | Apr 7 | **Weekly Review** — restate Sharpe ratio derivation; compute it manually on sample data; B23 problems 1–3 | B1, B23 | Practice | ⬜ |

**Week 1 Log:**
```
[ ] Day 1  [ ] Day 2  [ ] Day 3  [ ] Day 4  [ ] Day 5  [ ] Day 6  [ ] Day 7
Notes:
```

---

### 🔷 Week 2 · Days 8–14 · Apr 8–14

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 8 | Apr 8 | Covariance and correlation: bivariate formula; Pearson coefficient; matrix form | B4 Ch.4, W2 | Concept | ⬜ |
| 9 | Apr 9 | Stationarity: formal definition; random walk vs mean-reverting series; unit roots | B33 Ch.1 (Alexander), W1 | Concept | ⬜ |
| 10 | Apr 10 | Augmented Dickey-Fuller (ADF) test: null hypothesis; test statistic; p-value interpretation | B33 Ch.2, W2 | Concept | ⬜ |
| 11 | Apr 11 | Autocorrelation: ACF and PACF plots; positive autocorrelation (momentum) vs negative (mean-reversion) | B33 Ch.3, W1 | Concept | ⬜ |
| 12 | Apr 12 | AR(1) and MA(1) processes: intuition; parameter interpretation; reading ACF/PACF patterns | B33 Ch.3, W2 | Concept | ⬜ |
| 13 | Apr 13 | Code: ADF test on Nifty 50 price series; ACF/PACF plots for Bank Nifty daily returns using statsmodels | W15, statsmodels docs | Coding | ⬜ |
| 14 | Apr 14 | **Weekly Review** — restate: what stationarity means for a trading signal; B23 problems 4–6 | B23, W2 | Practice | ⬜ |

**Week 2 Log:**
```
[ ] Day 8  [ ] Day 9  [ ] Day 10  [ ] Day 11  [ ] Day 12  [ ] Day 13  [ ] Day 14
Notes:
```

---

### 🔷 Week 3 · Days 15–21 · Apr 15–21

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 15 | Apr 15 | Volatility clustering: ARCH effects; why returns show calm/turbulent periods | B33 Ch.4, W1 | Concept | ⬜ |
| 16 | Apr 16 | Rolling volatility estimation: 20-day vs 60-day vs 252-day windows; tradeoffs | B1 Ch.2, B4 Ch.5 | Concept | ⬜ |
| 17 | Apr 17 | GARCH(1,1): motivation from ARCH; model specification; persistence parameter; estimation intuition | B33 Ch.4, W2 | Concept | ⬜ |
| 18 | Apr 18 | Central Limit Theorem: formal statement; conditions; speed of convergence; finance applications | B9 Ch.5, W2 | Concept | ⬜ |
| 19 | Apr 19 | CLT implications: why large-sample statistics work; t-statistic; standard error of Sharpe ratio | B9 Ch.6, B1 Ch.3 | Concept | ⬜ |
| 20 | Apr 20 | Code: rolling 20-day and 60-day volatility for Bank Nifty; overlay price; identify clustering visually | W15, W1 | Coding | ⬜ |
| 21 | Apr 21 | **Weekly Review** — write down GARCH(1,1) equation from memory; simulate AR(1) in Python; B23 problems 7–9 | B23, W1 | Practice | ⬜ |

**Week 3 Log:**
```
[ ] Day 15  [ ] Day 16  [ ] Day 17  [ ] Day 18  [ ] Day 19  [ ] Day 20  [ ] Day 21
Notes:
```

---

### 🔷 Week 4 · Days 22–28 · Apr 22–28

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 22 | Apr 22 | Systematic trading overview (Carver): alpha, signal, forecast, scaling, execution, risk management | B4 Ch.1–2 | Concept | ⬜ |
| 23 | Apr 23 | Strategy taxonomy: momentum; mean-reversion; carry; stat-arb; their statistical basis | B1 Ch.2, B4 Ch.3 | Concept | ⬜ |
| 24 | Apr 24 | Backtesting principles: look-ahead bias; survivorship bias; overfitting; multiple testing problem | B1 Ch.3, W1 | Concept | ⬜ |
| 25 | Apr 25 | Transaction costs: brokerage; STT; exchange fees; SEBI charges (NSE); slippage and market impact | B1 Ch.4, W17 | Concept | ⬜ |
| 26 | Apr 26 | NSE F&O mechanics (Zerodha Varsity): lot sizes; margins; roll; basis; expiry mechanics | W17 (Zerodha Varsity — Futures module) | Concept | ⬜ |
| 27 | Apr 27 | Code: daily returns + 20-day rolling Sharpe + Sortino ratio for Nifty 50 | W15, W1 | Coding | ⬜ |
| 28 | Apr 28 | **Weekly Review + Mental Math** — 20 min TraderMath; B23 problems 10–12 | W4, B23 | Practice | ⬜ |

**Week 4 Log:**
```
[ ] Day 22  [ ] Day 23  [ ] Day 24  [ ] Day 25  [ ] Day 26  [ ] Day 27  [ ] Day 28
Notes:
```

---

### 🔷 Week 5 · Days 29–35 · Apr 29–May 5

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 29 | Apr 29 | Probability fundamentals: sample spaces; events; set operations; axioms of probability | B9 Ch.1–2, B22 (Feller) Ch.1 | Concept | ⬜ |
| 30 | Apr 30 | Conditional probability: definition; multiplication rule; partition theorem; Bayes' theorem derivation | B9 Ch.3–4, B22 Ch.1 | Concept | ⬜ |
| 31 | May 1 | Law of total probability; independence; pairwise vs mutual independence; applications in trading | B22 Ch.2, B23 problems 13–15 | Concept | ⬜ |
| 32 | May 2 | Discrete distributions: Bernoulli; Binomial; Geometric; Poisson — PMF, mean, variance | B9 Ch.7, W2 | Concept | ⬜ |
| 33 | May 3 | Continuous distributions: Uniform; Normal; Exponential; Log-normal — PDF, CDF, finance relevance | B9 Ch.8, W2 | Concept | ⬜ |
| 34 | May 4 | Expectation: linearity of expectation; variance of sums; expected stopping times; EV as a decision tool | B9 Ch.9, B23 problems 16–18 | Concept | ⬜ |
| 35 | May 5 | **Weekly Review** — 5 Brainstellar puzzles; derive E[X] and Var[X] for Binomial from scratch; TraderMath 20 min | W3, W4, B23 | Practice | ⬜ |

**Week 5 Log:**
```
[ ] Day 29  [ ] Day 30  [ ] Day 31  [ ] Day 32  [ ] Day 33  [ ] Day 34  [ ] Day 35
Notes:
```

---

### 🔷 Week 6 · Days 36–42 · May 6–12

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 36 | May 6 | NSE options mechanics (Zerodha Varsity): calls, puts, payoff diagrams, moneyness, premium components | W17 (Zerodha Varsity — Options module), B8 Ch.1 | Concept | ⬜ |
| 37 | May 7 | Options basics: intrinsic value; time value; ITM/ATM/OTM; expiry mechanics and settlement on NSE | B8 Ch.2–3, W14 | Concept | ⬜ |
| 38 | May 8 | Introduction to the Greeks: Delta and Gamma intuition; P&L as a function of spot | B8 Ch.4, W2 | Concept | ⬜ |
| 39 | May 9 | Theta and Vega intuition: time decay mechanics; volatility sensitivity; why sellers like Theta | B8 Ch.4, W17 | Concept | ⬜ |
| 40 | May 10 | Code: download Bank Nifty EOD data from NSE Bhavcopy; plot price series + rolling volatility overlay | W15, pandas | Coding | ⬜ |
| 41 | May 11 | Code: compute log returns; annualised historical volatility; compare to implied vol from ATM option | W1, W14 | Coding | ⬜ |
| 42 | May 12 | **Weekly Review** — 5 coin/dice probability problems from B23; Figgie game session (market intuition) | B23, W5 | Practice | ⬜ |

**Week 6 Log:**
```
[ ] Day 36  [ ] Day 37  [ ] Day 38  [ ] Day 39  [ ] Day 40  [ ] Day 41  [ ] Day 42
Notes:
```

---

### 🔷 Week 7 · Days 43–50 · May 13–20

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 43 | May 13 | **PROJECT 1 START** — Daily Returns & Volatility Analyzer (NSE) | B1 Ch.2, B4 Ch.5, W15 | Project | ⬜ |
| 44 | May 14 | P1: Load Nifty 50 + Bank Nifty EOD data; compute arithmetic and log returns; check for missing data | W15, pandas | Project | ⬜ |
| 45 | May 15 | P1: Rolling 20-day and 60-day volatility; histogram of returns with normal overlay; clustering heatmap | W1, matplotlib | Project | ⬜ |
| 46 | May 16 | P1: Sharpe ratio (annualised); Sortino ratio; annotate COVID crash (Mar 2020) + election events on chart | B1, W2 | Project | ⬜ |
| 47 | May 17 | P1: ADF test on price series; ACF/PACF plots; one-paragraph conclusion on stationarity | statsmodels, B33 Ch.2 | Project | ⬜ |
| 48 | May 18 | P1: Documentation; clean README; push to GitHub | — | Project | ⬜ |
| 49 | May 19 | Phase 1 Concept Review: stationarity; GARCH; CLT; ACF/PACF; Sharpe; returns — write a one-page summary | All Phase 1 material | Review | ⬜ |
| 50 | May 20 | **Phase 1 Complete** — B23 problems 19–20; TraderMath 20 min; update progress log | B23, W4 | Review | ⬜ |

**Week 7 Log:**
```
[ ] Day 43  [ ] Day 44  [ ] Day 45  [ ] Day 46  [ ] Day 47  [ ] Day 48  [ ] Day 49  [ ] Day 50
Notes:
```

---

### ✅ Phase 1 Completion Checklist
```
[ ] Read B1 Ch. 1–6 (systematic trading mindset, strategy types, backtesting, sizing)
[ ] Read B4 Ch. 1–5 (Carver framework: signals, risk targeting, instrument selection)
[ ] Read B8 Ch. 1–4 (options: payoffs, Greeks intuition, NSE context)
[ ] Read B9 Ch. 1–9 (Bayesian probability, distributions, expectation)
[ ] Read B35 (full — quant field orientation)
[ ] Read B22 Ch. 1–2 (Feller: sample spaces, independence, conditional probability)
[ ] Read B33 Ch. 1–4 (Alexander: stationarity, ARMA, ARCH/GARCH)
[ ] Completed Zerodha Varsity Futures module
[ ] Completed Zerodha Varsity Options module (introductory)
[ ] Built Project 1: Daily Returns & Volatility Analyzer (NSE)
[ ] Solved B23 problems 1–20
[ ] Logged progress daily
```

---

## PHASE 2 — Derivatives, Portfolio Theory & Backtesting
### Days 51–110 · May 21 – July 19, 2026

**Theme:** Develop rigorous understanding of options pricing (Black-Scholes and beyond), portfolio theory (Markowitz, CAPM, Fama-French), and risk management (VaR, CVaR). Build a full backtesting engine. Begin systematic interview preparation.

**Mathematical build-up:** Calculus of functions of several variables → linear algebra (eigenvalues, matrices) → constrained optimisation → Black-Scholes PDE → risk measures.

**Primary Books (active chapters):**
- B5 Ch. 1–2, 10–16, 18–21 — Futures mechanics; Black-Scholes derivation; Greeks; vol smile; implied vol
- B7 Parts 1–3 — Full options strategy reference (spreads, straddles, condors); payoff analysis
- B31 Ch. 6–10 — Portfolio return/variance; Markowitz; CML; CAPM; factor models
- B28 Ch. 1–3 — Cochrane: linking factors to risk premia; SDF intuition
- B32 Ch. 1–5 — VaR: historical, parametric, Monte Carlo; Expected Shortfall; backtesting
- B30 Ch. 1–4 — Pairs trading: cointegration, Engle-Granger, hedge ratios, Z-score signals
- B34 (selected chapters) — Market microstructure; order flow; Max Dama philosophy
- B22 Ch. 3–5 — Feller: generating functions; CLT proofs; random variables in depth
- B2 Ch. 1–5 — Chan: backtesting engine components; avoiding biases; transaction costs
- B18 §Probability, §Basic Options — Begin Zhou green book alongside projects
- B19 §1–60 — Heard on the Street: brain teasers as running practice
- B23 problems 21–40 — Continued daily probability practice
- B10 Ch. 1–5 — Game theory: Nash equilibrium; strategic interaction; market game intuition

**Primary Sites:** W1, W3 (Brainstellar), W6 (QuantQuestions), W7 (Quantable), W14, W17

---

### 🔷 Week 8 · Days 51–57 · May 21–27

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 51 | May 21 | Black-Scholes model: assumptions; risk-neutral valuation; no-arbitrage argument; PDE derivation sketch | B5 Ch.15, B37 Ch.4 | Concept | ⬜ |
| 52 | May 22 | Black-Scholes closed-form: call and put formulae; N(d₁), N(d₂) interpretation; put-call parity | B5 Ch.15–16, W2 | Concept | ⬜ |
| 53 | May 23 | Greeks deep dive I: Delta (sensitivity, hedging logic); Gamma (curvature, Gamma scalping) | B5 Ch.19, B6 Ch.6 | Concept | ⬜ |
| 54 | May 24 | Greeks deep dive II: Theta (daily decay, sign convention); Vega (sensitivity to vol); Rho | B5 Ch.19, B6 Ch.7 | Concept | ⬜ |
| 55 | May 25 | Implied volatility: definition vs historical vol; Newton-Raphson inversion method; market interpretation | B5 Ch.20, W1 | Concept | ⬜ |
| 56 | May 26 | Code: Black-Scholes pricer for Bank Nifty options; compute Delta/Gamma/Theta/Vega analytically | B5, scipy.optimize | Coding | ⬜ |
| 57 | May 27 | **Weekly Review** — 3 EV problems + 2 options payoff problems; B19 §1–10 | B19, B18 §Basic Options | Practice | ⬜ |

**Week 8 Log:**
```
[ ] Day 51–57
Notes:
```

---

### 🔷 Week 9 · Days 58–64 · May 28–Jun 3

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 58 | May 28 | Volatility smile and skew: why B-S fails empirically; OTM puts trade at premium; leptokurtosis | B5 Ch.20, B6 Ch.16 | Concept | ⬜ |
| 59 | May 29 | Volatility surface construction: moneyness vs maturity axes; interpolation; sticky-strike vs sticky-delta | B6 Ch.17, W1 (Vol Surface tutorial) | Concept | ⬜ |
| 60 | May 30 | Options strategies I: covered call; protective put; straddle; strangle — payoff/risk profile | B7 Part 1, W17 | Concept | ⬜ |
| 61 | May 31 | Options strategies II: bull spread; bear spread; butterfly; iron condor — payoff construction | B7 Part 2, W17 | Concept | ⬜ |
| 62 | Jun 1 | NSE options chain: reading OI, PCR, bid-ask spread, expiry structure for Bank Nifty weekly | W14, W17 | Concept | ⬜ |
| 63 | Jun 2 | Code: implied vol calculator from NSE LTP; vol smile plot (strike vs IV) for Bank Nifty near expiry | W15, scipy.optimize | Coding | ⬜ |
| 64 | Jun 3 | **Weekly Review** — 5 problems from B18 §options; 3 Brainstellar puzzles | B18, W3 | Practice | ⬜ |

**Week 9 Log:**
```
[ ] Day 58–64
Notes:
```

---

### 🔷 Week 10 · Days 65–71 · Jun 4–10

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 65 | Jun 4 | **PROJECT 2 START** — NSE Volatility Surface Builder (Bank Nifty) | B5 Ch.20, B6 Ch.17, W1 | Project | ⬜ |
| 66 | Jun 5 | P2: Fetch Bank Nifty options chain from NSE; parse strikes, expiries, LTPs, OI | W15, W14 | Project | ⬜ |
| 67 | Jun 6 | P2: Compute implied vol per strike using Newton-Raphson on B-S formula | scipy.optimize, B5 | Project | ⬜ |
| 68 | Jun 7 | P2: Vol smile plot; 3D surface (moneyness × maturity × IV) using matplotlib/plotly | matplotlib, plotly | Project | ⬜ |
| 69 | Jun 8 | P2: Compare near-expiry vs next-month smile; identify skew direction and magnitude | W14, B6 | Project | ⬜ |
| 70 | Jun 9 | P2: Documentation, clean notebook, README, push to GitHub | — | Project | ⬜ |
| 71 | Jun 10 | **Weekly Review** — 5 coin/dice/card problems; B19 §11–20; TraderMath 20 min | B19, B23, W4 | Practice | ⬜ |

**Week 10 Log:**
```
[ ] Day 65–71
Notes:
```

---

### 🔷 Week 11 · Days 72–78 · Jun 11–17

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 72 | Jun 11 | Portfolio theory: portfolio return and variance; two-asset case; covariance matrix formal definition | B31 Ch.7 | Concept | ⬜ |
| 73 | Jun 12 | Markowitz mean-variance optimisation: efficient frontier; minimum variance portfolio; QP formulation | B31 Ch.7–8, B29 Ch.4 | Concept | ⬜ |
| 74 | Jun 13 | Capital Market Line (CML); tangency portfolio; separation theorem | B31 Ch.9 | Concept | ⬜ |
| 75 | Jun 14 | CAPM: beta derivation; Security Market Line (SML); alpha; limitations | B31 Ch.9, B28 Ch.1 | Concept | ⬜ |
| 76 | Jun 15 | Fama-French 3-factor model: SMB; HML; empirical evidence; extending CAPM | B28 Ch.2–3, Fama & French 1993 (paper) | Concept | ⬜ |
| 77 | Jun 16 | Code: covariance matrix for Nifty 50 constituents; plot efficient frontier via random portfolio simulation | W1 (Portfolio Optimization), pandas | Coding | ⬜ |
| 78 | Jun 17 | **Weekly Review** — 5 portfolio/optimization problems from B18 §portfolio; B22 Ch.3 | B18, B22 | Practice | ⬜ |

**Week 11 Log:**
```
[ ] Day 72–78
Notes:
```

---

### 🔷 Week 12 · Days 79–85 · Jun 18–24

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 79 | Jun 18 | **PROJECT 3 START** — Mean-Variance Efficient Frontier Visualizer (NSE Nifty 50) | B31 Ch.7–8, B29 Ch.4 | Project | ⬜ |
| 80 | Jun 19 | P3: Fetch Nifty 50 constituent EOD prices; compute return matrix and covariance matrix | W15, pandas | Project | ⬜ |
| 81 | Jun 20 | P3: Random portfolio simulation (10,000 portfolios); plot risk-return scatter | NumPy, matplotlib | Project | ⬜ |
| 82 | Jun 21 | P3: Exact minimum-variance frontier via scipy QP solver; tangency portfolio extraction | scipy.optimize, B29 | Project | ⬜ |
| 83 | Jun 22 | P3: Constrained version (no short-selling, budget constraint); Capital Allocation Line overlay | — | Project | ⬜ |
| 84 | Jun 23 | P3: Documentation, annotated plots, README, push to GitHub | — | Project | ⬜ |
| 85 | Jun 24 | **Weekly Review** — Mental math 30 min (TraderMath); 3 EV puzzles from B23; B19 §21–30 | W4, B23, B19 | Practice | ⬜ |

**Week 12 Log:**
```
[ ] Day 79–85
Notes:
```

---

### 🔷 Week 13 · Days 86–92 · Jun 25–Jul 1

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 86 | Jun 25 | Risk parity: equal risk contribution; marginal risk contribution; intuition vs equal-weight | B26 Ch.1, W1 | Concept | ⬜ |
| 87 | Jun 26 | Risk parity math: inverse-vol weighting; iterative ERC algorithm; Roncalli framework | B26 Ch.2, Roncalli (2013 paper) | Concept | ⬜ |
| 88 | Jun 27 | Value at Risk (VaR): historical simulation; parametric (Gaussian); 95%/99% confidence levels | B32 Ch.1–3 | Concept | ⬜ |
| 89 | Jun 28 | Expected Shortfall (CVaR): definition; relationship to VaR; why CVaR is coherent; backtesting VaR | B32 Ch.4, W1 | Concept | ⬜ |
| 90 | Jun 29 | Code: historical VaR and CVaR for a hypothetical Bank Nifty F&O portfolio using NSE return data | W15, B32, scipy | Coding | ⬜ |
| 91 | Jun 30 | Drawdown analysis: maximum drawdown; drawdown duration; Calmar ratio; Underwater plot | B1 Ch.3, W1 | Concept | ⬜ |
| 92 | Jul 1 | **Weekly Review** — 3 risk scenario questions from B20 §risk; B22 Ch.4; Figgie game | B20, B22, W5 | Practice | ⬜ |

**Week 13 Log:**
```
[ ] Day 86–92
Notes:
```

---

### 🔷 Week 14 · Days 93–99 · Jul 2–8

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 93 | Jul 2 | **PROJECT 4 START** — VaR & CVaR Estimator — NSE F&O Portfolio | B32 Ch.1–4, W1 | Project | ⬜ |
| 94 | Jul 3 | P4: Define hypothetical portfolio: Nifty 50 futures + Bank Nifty options positions (realistic sizes) | W14, W15 | Project | ⬜ |
| 95 | Jul 4 | P4: Historical simulation VaR at 95% and 99%; sort portfolio P&L; empirical quantiles | pandas, scipy | Project | ⬜ |
| 96 | Jul 5 | P4: Parametric (Gaussian) VaR; compare to historical; compute CVaR as tail conditional mean | NumPy, scipy | Project | ⬜ |
| 97 | Jul 6 | P4: Backtest VaR model: count exceedances over 1-year window; Kupiec test; violation plot | matplotlib, B32 | Project | ⬜ |
| 98 | Jul 7 | P4: Final polish; docstrings; README; push to GitHub | — | Project | ⬜ |
| 99 | Jul 8 | **Weekly Review** — 5 problems from B25 §mathematics + probability; B19 §31–40 | B25, B19 | Practice | ⬜ |

**Week 14 Log:**
```
[ ] Day 93–99
Notes:
```

---

### 🔷 Week 15 · Days 100–106 · Jul 9–15

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 100 | Jul 9 | Backtesting engine design: data handler; signal generator; portfolio/risk module; executor | B1 Ch.7, B2 Ch.1–2, W1 | Concept | ⬜ |
| 101 | Jul 10 | EMA crossover strategy: signal logic; entry/exit rules; position sizing under Carver framework | B1 Ch.5, B4 Ch.4, W1 | Concept | ⬜ |
| 102 | Jul 11 | **PROJECT 5 START** — EMA Crossover Backtest on Bank Nifty Futures | B2 Ch.3–5, W1 | Project | ⬜ |
| 103 | Jul 12 | P5: Load Bank Nifty futures EOD data; compute 9-day and 21-day EMA; generate long/flat signals | W15, pandas | Project | ⬜ |
| 104 | Jul 13 | P5: Simulate equity curve; apply realistic NSE transaction costs (brokerage + STT + exchange charges) | B1 Ch.4, W17 | Project | ⬜ |
| 105 | Jul 14 | P5: Performance metrics: Sharpe, Sortino, Calmar, max drawdown, win rate, trade log | B1, W1 | Project | ⬜ |
| 106 | Jul 15 | P5: Documentation; push to GitHub | — | Project | ⬜ |

**Week 15 Log:**
```
[ ] Day 100–106
Notes:
```

---

### 🔷 Week 16 · Days 107–110 · Jul 16–19

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 107 | Jul 16 | Cointegration theory: non-stationary series with stationary linear combination; intuition for pairs | B30 Ch.1–2, B33 Ch.5 | Concept | ⬜ |
| 108 | Jul 17 | Engle-Granger test; Johansen test; hedge ratio via OLS regression; spread construction | B30 Ch.3, statsmodels | Concept | ⬜ |
| 109 | Jul 18 | Z-score signal: entry at ±2σ; exit at 0; stop at ±3σ; trade sizing rules for stat arb | B30 Ch.4, W1 | Concept | ⬜ |
| 110 | Jul 19 | **Phase 2 Complete** — B23 problems 35–40; review B18 §prob worked answers; update README | B23, B18, B19 | Review | ⬜ |

**Week 16 Log:**
```
[ ] Day 107–110
Notes:
```

---

### ✅ Phase 2 Completion Checklist
```
[ ] Read B5 Ch. 1–2, 10–16, 18–21 (futures; Black-Scholes; Greeks; vol smile; interest rate intro)
[ ] Read B6 Ch. 6–7, 16–17 (Greeks in depth; vol surface professional view)
[ ] Read B7 Parts 1–3 (options strategies: payoff diagrams; selection)
[ ] Read B8 Ch. 1–4 (options accessible intro)
[ ] Read B31 Ch. 7–10 (portfolio theory; CAPM; factor models)
[ ] Read B28 Ch. 1–3 (Cochrane: pricing kernels; factor premia)
[ ] Read B32 Ch. 1–5 (VaR; CVaR; backtesting risk models)
[ ] Read B30 Ch. 1–4 (pairs trading; cointegration; hedge ratio; Z-score)
[ ] Read B2 Ch. 1–5 (backtesting engine; execution; Chan style)
[ ] Read B22 Ch. 3–5 (Feller: distributions; generating functions; classical CLT)
[ ] Read B10 Ch. 1–5 (game theory: Nash; strategic reasoning)
[ ] Built Project 2: NSE Volatility Surface Builder (Bank Nifty)
[ ] Built Project 3: Efficient Frontier Visualizer (Nifty 50)
[ ] Built Project 4: VaR & CVaR Estimator (NSE F&O)
[ ] Built Project 5: EMA Crossover Backtest (Bank Nifty Futures)
[ ] Solved B23 problems 21–40
[ ] Worked through B18 §Probability + §Basic Options
[ ] Worked through B19 §1–60
[ ] Logged progress daily
```

---

## PHASE 3 — Statistical Methods, Stochastic Foundations & Advanced Projects
### Days 111–180 · July 20 – September 27, 2026

**Theme:** Build the rigorous mathematical foundations that Phase 4 demands. Measure theory, convergence, convex optimisation, Monte Carlo methods, MCMC and Bayesian modelling. Simultaneously build more sophisticated NSE projects that directly use these tools: Monte Carlo pricing, pairs trading, regime detection, PCA risk analysis, microstructure simulation.

**Mathematical build-up:** Measure theory and Lebesgue integration → convergence of random variables → convex optimisation (KKT, QP) → Monte Carlo simulation and variance reduction → Markov chains → MCMC → Hidden Markov Models.

**Primary Books (active chapters):**
- B11 Ch. 1–6 — Axler: sigma-algebras; Lebesgue measure; integration; convergence theorems; probability spaces
- B29 Ch. 1–5 — Boyd: convex sets; convex functions; Lagrangian duality; KKT conditions; applications
- B13 Ch. 2–3, 13, 16 — Nocedal: gradient descent; Newton; linear programming; quadratic programming
- B27 Ch. 1–5 — Glasserman: simulation; GBM; variance reduction; path-dependent option pricing
- B14 Ch. 1–6 — MCMC: Markov chains; Metropolis-Hastings; Gibbs sampling; convergence
- B28 Ch. 4–6 — Cochrane: GMM; cross-sectional tests; empirical factor evaluation
- B33 Ch. 5–8 — Alexander: GARCH estimation; PCA; term structure; risk models
- B34 (selected) — Max Dama: market microstructure; adverse selection; Kyle model; alpha philosophy
- B6 Ch. 1–5, 8–15 — Natenberg: vol trading; pricing models beyond B-S; delta-neutral; calendar spreads
- B26 Ch. 1–5 — Isichenko: IC/IR framework; alpha models; signal combination; portfolio construction
- B37 Ch. 5–8 — Larcher: mathematical finance rigor; bridging B31 and B17
- B18 §Stochastic Processes, §Calculus — continued interview prep, now the harder sections
- B19 §61–120; B20 §1–50; B21 §1–75 — Running interview practice
- B23 problems 41–50 — Complete Mosteller

**Primary Sites:** W1, W3 (Brainstellar), W6 (QuantQuestions), W7 (Quantable), W12 (al0vya GitHub)

---

### 🔷 Week 17 · Days 111–117 · Jul 20–26

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 111 | Jul 20 | Sigma-algebras: definition; generated sigma-algebras; Borel sets; filtrations as information flow | B11 Ch.1, W2 | Math | ⬜ |
| 112 | Jul 21 | Lebesgue measure: construction; null sets; measure vs length; comparison to Riemann | B11 Ch.2 | Math | ⬜ |
| 113 | Jul 22 | Measurable functions and integration: simple functions; Lebesgue integral construction; monotone convergence | B11 Ch.3 | Math | ⬜ |
| 114 | Jul 23 | Probability spaces as measure spaces: probability measure; random variables; expectation as integral | B11 Ch.4, B22 Ch.5 | Math | ⬜ |
| 115 | Jul 24 | Convergence of random variables: almost sure; in probability; in L²; in distribution — relationships | B11 Ch.5 | Math | ⬜ |
| 116 | Jul 25 | Strong and weak law of large numbers: statement; measure-theoretic proof sketch; finance relevance | B11 Ch.6, B22 Ch.5 | Math | ⬜ |
| 117 | Jul 26 | Code: simulate LLN and CLT convergence; sample mean histograms at n = 10, 100, 1000 | NumPy, matplotlib | Coding | ⬜ |

**Week 17 Log:**
```
[ ] Day 111–117
Notes:
```

---

### 🔷 Week 18 · Days 118–124 · Jul 27–Aug 2

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 118 | Jul 27 | Convex sets and convex functions: definitions; epigraph; operations preserving convexity | B29 Ch.1–2 | Math | ⬜ |
| 119 | Jul 28 | Unconstrained optimisation: first/second-order conditions; gradient descent; Newton's method | B13 Ch.2–3 | Math | ⬜ |
| 120 | Jul 29 | Constrained optimisation: equality/inequality constraints; Lagrangian; KKT conditions | B12 Ch.2, B29 Ch.5 | Math | ⬜ |
| 121 | Jul 30 | Quadratic programming (QP): portfolio optimisation as a QP; active-set methods; interior-point | B13 Ch.16, B29 Ch.4 | Math | ⬜ |
| 122 | Jul 31 | Linear programming and simplex intuition: LP as special case of convex program; finance applications | B13 Ch.13 | Math | ⬜ |
| 123 | Aug 1 | Code: implement gradient descent from scratch; apply to minimise portfolio variance; compare to scipy.minimize | NumPy, B13 | Coding | ⬜ |
| 124 | Aug 2 | **Weekly Review** — 5 optimisation/portfolio problems from B18 §optimisation; B21 §1–10; TraderMath | B18, B21, W4 | Practice | ⬜ |

**Week 18 Log:**
```
[ ] Day 118–124
Notes:
```

---

### 🔷 Week 19 · Days 125–131 · Aug 3–9

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 125 | Aug 3 | Monte Carlo methods: simulation as numerical integration; law of large numbers basis; sampling strategies | B27 Ch.1–2 | Concept | ⬜ |
| 126 | Aug 4 | Geometric Brownian Motion (GBM): SDE form; drift and diffusion; discrete Euler-Maruyama scheme | B27 Ch.3, W1 | Concept | ⬜ |
| 127 | Aug 5 | Monte Carlo option pricing: discounted expected payoff under risk-neutral measure; convergence analysis | B27 Ch.4, B5 Ch.26 | Concept | ⬜ |
| 128 | Aug 6 | Variance reduction: antithetic variates; control variates; stratified sampling; importance sampling | B27 Ch.4, W1 | Concept | ⬜ |
| 129 | Aug 7 | **PROJECT 6 START** — Monte Carlo Option Pricer — Bank Nifty & Nifty Options | B27 Ch.3–4, B5 Ch.26 | Project | ⬜ |
| 130 | Aug 8 | P6: Simulate 10,000 GBM paths for Bank Nifty; price European call/put; compare to analytical B-S | NumPy, B5 | Project | ⬜ |
| 131 | Aug 9 | P6: Implement antithetic variates; control variates; plot convergence of price estimate vs path count | B27 | Project | ⬜ |

**Week 19 Log:**
```
[ ] Day 125–131
Notes:
```

---

### 🔷 Week 20 · Days 132–138 · Aug 10–16

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 132 | Aug 10 | P6: Extend to Asian (average-price) option; add weekly/monthly Bank Nifty payoff simulations | W15, W14 | Project | ⬜ |
| 133 | Aug 11 | P6: Documentation, annotated plots, README, push to GitHub | — | Project | ⬜ |
| 134 | Aug 12 | **PROJECT 7 START** — Pairs Trading Backtest — NSE Stocks (Sector Pairs) | B30 Ch.1–4, W1 | Project | ⬜ |
| 135 | Aug 13 | P7: Select NSE sector pairs (e.g. HDFC Bank / ICICI Bank; Reliance / ONGC); confirm economic rationale | W15 | Project | ⬜ |
| 136 | Aug 14 | P7: Engle-Granger cointegration test; compute spread and hedge ratio via OLS | statsmodels, B30 | Project | ⬜ |
| 137 | Aug 15 | P7: Z-score signal: entry ±2σ; exit 0; stop ±3σ; backtest with NSE realistic costs | pandas, B30 | Project | ⬜ |
| 138 | Aug 16 | P7: Add stop-loss rules; equity curve; Sharpe; win rate; drawdown analysis | W1, B30 | Project | ⬜ |

**Week 20 Log:**
```
[ ] Day 132–138
Notes:
```

---

### 🔷 Week 21 · Days 139–145 · Aug 17–23

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 139 | Aug 17 | P7: Documentation; push to GitHub | — | Project | ⬜ |
| 140 | Aug 18 | CAPM in depth: regression interpretation; alpha as Jensen's alpha; R² meaning; residual risk | B28 Ch.1–3, B31 Ch.9 | Concept | ⬜ |
| 141 | Aug 19 | Fama-French 3-factor model: constructing SMB and HML proxies for NSE; empirical testing framework | Fama & French 1993 (paper), B28 Ch.3 | Concept | ⬜ |
| 142 | Aug 20 | **PROJECT 8 START** — CAPM Beta & Factor Exposure Analyzer — Nifty 50 Stocks | B28, B31 | Project | ⬜ |
| 143 | Aug 21 | P8: Regress each Nifty 50 stock on Nifty index; compute beta, alpha, R²; interpret residuals | statsmodels, pandas | Project | ⬜ |
| 144 | Aug 22 | P8: Security Market Line plot; identify over/undervalued stocks vs CAPM prediction | matplotlib | Project | ⬜ |
| 145 | Aug 23 | P8: Extend to 3-factor with NSE size/value proxies; documentation and push to GitHub | — | Project | ⬜ |

**Week 21 Log:**
```
[ ] Day 139–145
Notes:
```

---

### 🔷 Week 22 · Days 146–152 · Aug 24–30

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 146 | Aug 24 | Bayesian inference in depth: likelihood functions; prior selection; posterior derivation; conjugate priors | B9 Ch.10–14, W1 | Concept | ⬜ |
| 147 | Aug 25 | Markov chains: transition matrices; Chapman-Kolmogorov; stationary distributions; ergodicity | B14 Ch.1–2 | Math | ⬜ |
| 148 | Aug 26 | Metropolis-Hastings algorithm: proposal distribution; acceptance ratio; burn-in; convergence diagnostics | B14 Ch.3–4 | Math | ⬜ |
| 149 | Aug 27 | Gibbs sampling: full conditional distributions; blocked Gibbs; application in Bayesian models | B14 Ch.5 | Math | ⬜ |
| 150 | Aug 28 | Hidden Markov Models (HMM): latent state sequence; emission probabilities; forward-backward algorithm | B14 Ch.6, B33 Ch.7 | Concept | ⬜ |
| 151 | Aug 29 | Code: implement Metropolis-Hastings from scratch; estimate posterior of return mean; plot chain + histogram | B14, NumPy | Coding | ⬜ |
| 152 | Aug 30 | **Weekly Review** — 5 problems from B21 §probability; B20 §1–10; Brainstellar 3 hard puzzles | B21, B20, W3 | Practice | ⬜ |

**Week 22 Log:**
```
[ ] Day 146–152
Notes:
```

---

### 🔷 Week 23 · Days 153–159 · Aug 31–Sep 6

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 153 | Aug 31 | Regime detection: two-state HMM (bull/bear); Viterbi algorithm for most likely state sequence | B14 Ch.6, B33 Ch.7 | Concept | ⬜ |
| 154 | Sep 1 | **PROJECT 9 START** — Market Regime Detector — Bank Nifty (HMM) | B14, hmmlearn | Project | ⬜ |
| 155 | Sep 2 | P9: Fit 2-state Gaussian HMM on Bank Nifty daily returns; label regimes using Viterbi | hmmlearn, B14 | Project | ⬜ |
| 156 | Sep 3 | P9: Overlay regime labels on price chart; compare annualised vol and return per regime | matplotlib | Project | ⬜ |
| 157 | Sep 4 | P9: Conditional strategy adjustment: reduce position size in high-vol (bear) regime via B4 scaling | B4 Ch.4 | Project | ⬜ |
| 158 | Sep 5 | P9: Documentation; push to GitHub | — | Project | ⬜ |
| 159 | Sep 6 | **Weekly Review** — 5 Brainstellar puzzles (medium-hard); TraderMath 25 min; B19 §61–70 | W3, W4, B19 | Practice | ⬜ |

**Week 23 Log:**
```
[ ] Day 153–159
Notes:
```

---

### 🔷 Week 24 · Days 160–166 · Sep 7–13

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 160 | Sep 7 | Limit order book mechanics: bid/ask spread; order types (limit, market, IOC); price-time priority | B34 Ch.1–2, W2 | Concept | ⬜ |
| 161 | Sep 8 | Market microstructure: price impact models; adverse selection (Glosten-Milgrom); Kyle model intuition | B34 Ch.3–4, W1 | Concept | ⬜ |
| 162 | Sep 9 | **PROJECT 10 START** — Market Microstructure Simulator (NSE-style LOB) | B34, W1 | Project | ⬜ |
| 163 | Sep 10 | P10: Simplified LOB in Python OOP: bid/ask queues; matching engine; order arrival | Python OOP | Project | ⬜ |
| 164 | Sep 11 | P10: Random order flow (Poisson arrivals); track spread; compute order imbalance metric | B34, NumPy | Project | ⬜ |
| 165 | Sep 12 | P10: Simulate large order impact on spread; measure temporary vs permanent impact | matplotlib | Project | ⬜ |
| 166 | Sep 13 | P10: Documentation; push to GitHub | — | Project | ⬜ |

**Week 24 Log:**
```
[ ] Day 160–166
Notes:
```

---

### 🔷 Week 25 · Days 167–173 · Sep 14–20

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 167 | Sep 14 | PCA: eigendecomposition of covariance matrix; principal components; variance explained; loading vectors | B33 Ch.6, B26 Ch.3 | Concept | ⬜ |
| 168 | Sep 15 | Rolling correlation: dynamic covariance; correlation collapse in stressed markets | B33 Ch.5 | Concept | ⬜ |
| 169 | Sep 16 | **PROJECT 11 START** — Rolling Correlation & PCA Risk Analyzer — Nifty 50 | B33 Ch.5–6, B26 Ch.3 | Project | ⬜ |
| 170 | Sep 17 | P11: Rolling 60-day correlation matrix for Nifty 50; heatmap time series; identify sector clustering | pandas, seaborn | Project | ⬜ |
| 171 | Sep 18 | P11: Eigen decomposition over rolling windows; plot % variance explained by PC1, PC2, PC3 over time | NumPy | Project | ⬜ |
| 172 | Sep 19 | P11: Compare correlations in calm (2019) vs stressed (COVID Mar 2020, LTCG 2018) periods | W15 | Project | ⬜ |
| 173 | Sep 20 | P11: Documentation; push to GitHub | — | Project | ⬜ |

**Week 25 Log:**
```
[ ] Day 167–173
Notes:
```

---

### 🔷 Week 26 · Days 174–180 · Sep 21–27

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 174 | Sep 21 | Quantitative portfolio management: alpha generation pipeline; IC; IR; transfer coefficient | B26 Ch.1–3 | Concept | ⬜ |
| 175 | Sep 22 | Alpha decay and signal combination: IC weighting; ensemble of signals; Barra-style framework | B26 Ch.4–5 | Concept | ⬜ |
| 176 | Sep 23 | **PROJECT 12 START** — Sharpe Ratio Optimizer — NSE Multi-Asset Futures | B26, B29, B13 | Project | ⬜ |
| 177 | Sep 24 | P12: Build Sharpe maximiser for mix of NSE futures (Nifty, Bank Nifty, USDINR, Gold) using scipy QP | scipy.optimize | Project | ⬜ |
| 178 | Sep 25 | P12: Compare to risk-parity weighting; rolling Sharpe comparison vs equal-weight benchmark | W1 | Project | ⬜ |
| 179 | Sep 26 | P12: Documentation; push to GitHub | — | Project | ⬜ |
| 180 | Sep 27 | **Phase 3 Complete** — B23 problems 41–50; B20 §40–50; TraderMath 30 min; update README | B23, B20, W4 | Review | ⬜ |

**Week 26 Log:**
```
[ ] Day 174–180
Notes:
```

---

### ✅ Phase 3 Completion Checklist
```
[ ] Read B11 Ch. 1–6 (Axler: sigma-algebras; Lebesgue measure/integration; convergence; LLN)
[ ] Read B29 Ch. 1–5 (Boyd: convex sets/functions; Lagrangian duality; KKT; QP)
[ ] Read B13 Ch. 2–3, 13, 16 (Nocedal: gradient descent; Newton; LP; QP)
[ ] Read B27 Ch. 1–5 (Glasserman: MC simulation; GBM; variance reduction; path-dependent)
[ ] Read B14 Ch. 1–6 (MCMC: Markov chains; M-H; Gibbs; HMM)
[ ] Read B28 Ch. 4–6 (Cochrane: GMM; cross-sectional tests; empirical factor work)
[ ] Read B33 Ch. 5–8 (Alexander: GARCH estimation; PCA; term structure risk)
[ ] Read B34 Ch. 1–4 (Max Dama: microstructure; adverse selection; Kyle model)
[ ] Read B6 Ch. 1–5, 8–15 (Natenberg: vol trading; model calibration; delta-neutral; spreads)
[ ] Read B26 Ch. 1–5 (Isichenko: IC/IR; alpha decay; signal combination)
[ ] Read B37 Ch. 5–8 (Larcher: mathematical finance rigor)
[ ] Built Project 6: Monte Carlo Option Pricer (Bank Nifty & Nifty)
[ ] Built Project 7: Pairs Trading Backtest (NSE sector pairs)
[ ] Built Project 8: CAPM Beta & Factor Analyzer (Nifty 50)
[ ] Built Project 9: Market Regime Detector — Bank Nifty (HMM)
[ ] Built Project 10: Market Microstructure Simulator (NSE LOB)
[ ] Built Project 11: Rolling Correlation & PCA Risk Analyzer (Nifty 50)
[ ] Built Project 12: Sharpe Ratio Optimizer (NSE multi-asset)
[ ] Solved B23 problems 41–50 (complete Mosteller)
[ ] Worked through B18 §Stochastic + §Calculus sections
[ ] Worked through B19 §61–120; B20 §1–50; B21 §1–75
[ ] Logged progress daily
```

---

## PHASE 4 — Advanced Stochastic Calculus & Research-Grade Projects
### Days 181–240 · September 28 – November 27, 2026

**Theme:** Build continuous-time stochastic calculus from the ground up — Brownian motion, Itô's integral and lemma, SDEs, Girsanov's theorem, Feynman-Kac, and the full continuous-time derivation of Black-Scholes. Apply these to stochastic option pricing, optimal stopping, and build a production-quality backtesting engine. Complete interview readiness.

**Mathematical build-up:** Discrete-time binomial models and risk-neutral measure (Shreve I) → Brownian motion and filtrations → Itô integral and Itô's lemma → SDEs and GBM → Girsanov / change of measure → Feynman-Kac PDE bridge → continuous-time Black-Scholes → interest rate models (Vasicek, Hull-White, CIR) → optimal control (HJB equation) → Kelly criterion as a stochastic control problem.

**Primary Books (active chapters):**
- B16 Ch. 1–5 — Shreve I: binomial; replication; no-arbitrage; risk-neutral measure; American options
- B17 Ch. 1–6 — Shreve II: Brownian motion; Itô integral; Itô's lemma; martingale representation; Girsanov; Feynman-Kac
- B15 Ch. 1–8 — Øksendal: rigorous SDE theory; existence/uniqueness; Ornstein-Uhlenbeck; Kolmogorov equations
- B12 Ch. 1–5 — Troutman: Euler-Lagrange; Pontryagin's principle; HJB equation
- B24 (targeted sections) — Wilmott FAQ: derivatives intuition; model critique; practical quant thinking
- B27 Ch. 5–7 — Glasserman: SDE simulation; Euler-Maruyama; Milstein method; Greeks by simulation
- B26 Ch. 6–8 — Isichenko: research-grade alpha; portfolio construction at scale
- B18 §Hard Options, §Stochastic Calculus, §Puzzles; B19 §121+; B20 §51+; B21 §76–150 — Full interview prep
- B36 (targeted problems) — Aaron Cao compilation: hard probability + stochastic

**Primary Sites:** W1, W3, W4 (TraderMath daily), W5 (Figgie), W6, W13 (Max Dama Brainteasers), W19 (QuantLib)

---

### 🔷 Week 27 · Days 181–187 · Sep 28–Oct 4

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 181 | Sep 28 | Binomial asset pricing: one-period model; replication portfolio; no-arbitrage pricing | B16 Ch.1 | Math/Finance | ⬜ |
| 182 | Sep 29 | Multi-period binomial trees: European and American options; backward induction algorithm | B16 Ch.2–3 | Math/Finance | ⬜ |
| 183 | Sep 30 | Risk-neutral measure (discrete time): change of measure; equivalent martingale measure construction | B16 Ch.4 | Math/Finance | ⬜ |
| 184 | Oct 1 | Fundamental Theorem of Asset Pricing (discrete): no-arbitrage ↔ existence of risk-neutral measure | B16 Ch.5 | Math/Finance | ⬜ |
| 185 | Oct 2 | Random walk to Brownian motion: scaled RW convergence; formal definition; key properties (independent increments, continuity) | B15 Ch.1–2, B17 Ch.1 | Math | ⬜ |
| 186 | Oct 3 | Code: simulate Brownian motion sample paths; demonstrate quadratic variation; plot multiple realisations | NumPy, matplotlib | Coding | ⬜ |
| 187 | Oct 4 | **Weekly Review** — 5 problems from B18 §stochastic calculus intuition; B20 §51–55 | B18, B20 | Practice | ⬜ |

**Week 27 Log:**
```
[ ] Day 181–187
Notes:
```

---

### 🔷 Week 28 · Days 188–194 · Oct 5–11

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 188 | Oct 5 | Itô integral: construction from simple processes; L² isometry; extension to adapted processes | B15 Ch.3, B17 Ch.4 | Math | ⬜ |
| 189 | Oct 6 | Itô's Lemma: statement; proof for smooth f(t, Bₜ); generalisation to f(t, Xₜ) for Itô processes | B15 Ch.4, B17 Ch.4 | Math | ⬜ |
| 190 | Oct 7 | SDEs: existence and uniqueness (Lipschitz conditions); solution concepts (strong vs weak) | B15 Ch.5 | Math | ⬜ |
| 191 | Oct 8 | GBM as SDE: dSₜ = μSₜdt + σSₜdBₜ; solve via Itô's Lemma; log-normal distribution of Sₜ | B15 Ch.5, B17 Ch.4 | Math/Finance | ⬜ |
| 192 | Oct 9 | Black-Scholes PDE: derive via Itô's lemma and delta-hedging argument; boundary conditions; uniqueness | B17 Ch.5 | Math/Finance | ⬜ |
| 193 | Oct 10 | Martingales: definition; optional stopping theorem; martingale representation theorem; connection to pricing | B17 Ch.3, B15 Ch.5 | Math | ⬜ |
| 194 | Oct 11 | **Weekly Review** — 5 problems from B24 §derivatives; B21 §76–85; TraderMath 25 min | B24, B21, W4 | Practice | ⬜ |

**Week 28 Log:**
```
[ ] Day 188–194
Notes:
```

---

### 🔷 Week 29 · Days 195–201 · Oct 12–18

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 195 | Oct 12 | Girsanov's theorem: change of drift via change of measure; Radon-Nikodym derivative; Novikov's condition | B17 Ch.5, B15 Ch.8 | Math | ⬜ |
| 196 | Oct 13 | Feynman-Kac formula: PDE ↔ stochastic representation; pricing as conditional expectation | B15 Ch.8, B17 Ch.6 | Math | ⬜ |
| 197 | Oct 14 | Interest rate models: Vasicek (OU process under risk-neutral measure); CIR model; Hull-White extension | B5 Ch.31, B24 | Finance | ⬜ |
| 198 | Oct 15 | Ornstein-Uhlenbeck process: mean-reverting SDE; closed-form solution; parameter estimation via MLE | B15 Ch.5, W1 | Math | ⬜ |
| 199 | Oct 16 | Code: Euler-Maruyama discretisation; simulate Vasicek rate paths; simulate OU process; plot with confidence bands | NumPy, B15 | Coding | ⬜ |
| 200 | Oct 17 | **PROJECT 13 START** — Stochastic Option Pricer with Greeks (NSE Bank Nifty) | B15, B17, B27, W19 | Project | ⬜ |
| 201 | Oct 18 | P13: Implement Euler-Maruyama discretised GBM for Bank Nifty; verify log-normal distribution of Sₜ | NumPy | Project | ⬜ |

**Week 29 Log:**
```
[ ] Day 195–201
Notes:
```

---

### 🔷 Week 30 · Days 202–208 · Oct 19–25

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 202 | Oct 19 | P13: Full analytical B-S pricer + MC pricer side-by-side; compute Delta/Gamma/Vega via finite differences on MC | B27 Ch.7, B17 | Project | ⬜ |
| 203 | Oct 20 | P13: Apply to live Bank Nifty weekly options chain; compare MC price to market mid-price; analyse mismatch | W15, W14 | Project | ⬜ |
| 204 | Oct 21 | P13: QuantLib integration: cross-validate using ql.BlackScholesProcess; documentation; push to GitHub | W19 (QuantLib) | Project | ⬜ |
| 205 | Oct 22 | Variational calculus: functional; Euler-Lagrange equation; derivation and examples | B12 Ch.1–3 | Math | ⬜ |
| 206 | Oct 23 | Optimal control: Pontryagin's maximum principle; Hamilton-Jacobi-Bellman (HJB) equation | B12 Ch.4–5 | Math | ⬜ |
| 207 | Oct 24 | Kelly criterion as an optimal control problem: continuous-time derivation; fractional Kelly; risk-of-ruin | B26 Ch.7, B1 Ch.6 | Finance | ⬜ |
| 208 | Oct 25 | **Weekly Review** — 5 problems from B20 §stochastic calculus; Max Dama Brainteasers (W13) 3 problems | B20, W13 | Practice | ⬜ |

**Week 30 Log:**
```
[ ] Day 202–208
Notes:
```

---

### 🔷 Week 31 · Days 209–215 · Oct 26–Nov 1

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 209 | Oct 26 | **PROJECT 14 START** — Optimal Stopping Simulator — NSE Options Expiry | B12, B15, B23 | Project | ⬜ |
| 210 | Oct 27 | P14: Secretary (best-choice) problem — simulate; verify 1/e stopping rule analytically and numerically | B23, Python | Project | ⬜ |
| 211 | Oct 28 | P14: Optimal stopping for OU process: simulate Bank Nifty spread; derive threshold policy via dynamic programming | B12, B15 | Project | ⬜ |
| 212 | Oct 29 | P14: Risk-of-ruin under Kelly with fractional Kelly; Nifty options position sizing simulation | B26, B1 | Project | ⬜ |
| 213 | Oct 30 | P14: Documentation; push to GitHub | — | Project | ⬜ |
| 214 | Oct 31 | GARCH(1,1): formal log-likelihood specification; maximum likelihood estimation; persistence and half-life | B33 Ch.4, arch Python library | Math/Coding | ⬜ |
| 215 | Nov 1 | Code: fit GARCH(1,1) to Bank Nifty return series using arch; compare fitted conditional vol to 20-day rolling | arch library, B33 | Coding | ⬜ |

**Week 31 Log:**
```
[ ] Day 209–215
Notes:
```

---

### 🔷 Week 32 · Days 216–222 · Nov 2–8

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 216 | Nov 2 | **PROJECT 15 START** — Full NSE F&O Backtesting Engine | B1 Ch.7, B2 Ch.1–5, B4 Ch.4–5 | Project | ⬜ |
| 217 | Nov 3 | P15: Build modular engine: data handler; signal generator; risk manager module; executor with cost model | B1, B2 | Project | ⬜ |
| 218 | Nov 4 | P15: Implement strategy: Bank Nifty momentum signal with GARCH(1,1) volatility filter for position sizing | arch, B4 | Project | ⬜ |
| 219 | Nov 5 | P15: Realistic NSE cost model: Zerodha brokerage formula + STT + exchange charges + SEBI turnover fee | W17, W14 | Project | ⬜ |
| 220 | Nov 6 | P15: Regime-adaptive position scaling using HMM state from Project 9; reduce size in bear regime | Project 9 integration, B4 | Project | ⬜ |
| 221 | Nov 7 | P15: Full performance report: annualised Sharpe; Calmar; max drawdown; monthly returns heatmap; trade log | W1, B1 | Project | ⬜ |
| 222 | Nov 8 | P15: Final documentation; README; push to GitHub | — | Project | ⬜ |

**Week 32 Log:**
```
[ ] Day 216–222
Notes:
```

---

### 🔷 Week 33 · Days 223–229 · Nov 9–15

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 223 | Nov 9 | Interview methodology: STAR structure for quant; restate → assumptions → simplify → generalise → sense-check | B18 §Introduction, B25 | Practice | ⬜ |
| 224 | Nov 10 | Brain teasers — coin/dice: 10 problems with full verbal walk-through and sense-check | W3 (Brainstellar), B23, W13 | Practice | ⬜ |
| 225 | Nov 11 | Brain teasers — card problems: 10 problems; combinatorial reasoning; symmetry arguments | B19 §121–140, B18 | Practice | ⬜ |
| 226 | Nov 12 | Expected value games: optimal stopping; St. Petersburg variants; two-envelope problem | B20 §51–60, W13 | Practice | ⬜ |
| 227 | Nov 13 | Market intuition questions: options pricing without formulae; hedging logic; edge identification | B18 §Market Making, B24 | Practice | ⬜ |
| 228 | Nov 14 | Python live-coding drill: simulate a random walk; verify EV analytically vs numerically; clean code output | W12 (al0vya GitHub), W1 | Practice | ⬜ |
| 229 | Nov 15 | **Full mock interview I**: 3 probability + 2 options + 1 Python coding — timed, recorded | B18, B19, B20 | Practice | ⬜ |

**Week 33 Log:**
```
[ ] Day 223–229
Notes:
```

---

### 🔷 Week 34 · Days 230–236 · Nov 16–22

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 230 | Nov 16 | Figgie: 3 games; focus on EV calculation speed, bid-ask calibration, Bayesian updating mid-game | W5 (Figgie) | Practice | ⬜ |
| 231 | Nov 17 | Mental math intensive: 45 min TraderMath; log approximations; exponent rules; fraction arithmetic | W4 | Practice | ⬜ |
| 232 | Nov 18 | **PROJECT 16 START** — Quantitative Research Report: Indian Commodities (Gold, Crude, Nat Gas — NSE/MCX) | B26 Ch.8, B5 Ch.5–6, W14 | Project | ⬜ |
| 233 | Nov 19 | P16: Fetch NSE/MCX Gold, Crude Oil, Natural Gas EOD futures data; compute returns; seasonality analysis | W15, pandas | Project | ⬜ |
| 234 | Nov 20 | P16: Roll yield; convenience yield; futures basis analysis; term structure shape over time | B5 Ch.5–6 | Project | ⬜ |
| 235 | Nov 21 | P16: Trend-following signal (Carver EWMAC framework) applied to Gold futures; full performance metrics | B4 Ch.4 | Project | ⬜ |
| 236 | Nov 22 | P16: Research report write-up; well-commented notebook; README; push to GitHub | — | Project | ⬜ |

**Week 34 Log:**
```
[ ] Day 230–236
Notes:
```

---

### 🔷 Week 35 · Days 237–240 · Nov 23–27

| Day | Date | Topic | Resource | Type | Status |
|-----|------|-------|----------|------|--------|
| 237 | Nov 23 | **Full mock interview II**: 2 probability + 1 stochastic calculus + 2 options + 1 strategy critique — timed | B18, B19, B20, B21 | Practice | ⬜ |
| 238 | Nov 24 | Roadmap review: identify weakest concepts across all four phases; revisit and drill | All phases | Review | ⬜ |
| 239 | Nov 25 | CV / GitHub polish: write concise, quantitative project descriptions with Sharpe ratios and methodology stated | B25 §Career, W8 | Review | ⬜ |
| 240 | Nov 27 | **🏁 Roadmap Complete** — Write retrospective: what worked, what to improve, plan for Phase 5 | — | Review | ⬜ |

**Week 35 Log:**
```
[ ] Day 237  [ ] Day 238  [ ] Day 239  [ ] Day 240
Notes:
```

---

### ✅ Phase 4 Completion Checklist
```
[ ] Read B16 Ch. 1–5 (Shreve I: binomial; replication; risk-neutral measure; FTAP)
[ ] Read B17 Ch. 1–6 (Shreve II: Brownian motion; Itô integral/lemma; Girsanov; Feynman-Kac)
[ ] Read B15 Ch. 1–8 (Øksendal: SDEs; existence/uniqueness; OU process; Kolmogorov equations)
[ ] Read B12 Ch. 1–5 (Troutman: Euler-Lagrange; Pontryagin; HJB equation)
[ ] Read B24 (targeted sections — Wilmott FAQ: derivatives; model critique; quant intuition)
[ ] Read B27 Ch. 5–7 (Glasserman: SDE simulation; Euler-Maruyama; Milstein; Greeks by MC)
[ ] Read B26 Ch. 6–8 (Isichenko: research-grade alpha; portfolio construction at scale)
[ ] Built Project 13: Stochastic Option Pricer with Greeks (Bank Nifty)
[ ] Built Project 14: Optimal Stopping Simulator (OU process + secretary problem)
[ ] Built Project 15: Full NSE F&O Backtesting Engine (modular; GARCH; regime-adaptive)
[ ] Built Project 16: NSE Commodities Quantitative Research Report
[ ] Completed 2 full timed mock interviews (recorded)
[ ] Worked through B18 §Hard Options + §Stochastic Calculus
[ ] Worked through B19 §121+; B20 §51+; B21 §76–150; B36 (targeted)
[ ] QuantLib used and understood in Project 13
[ ] Logged progress daily
```

---

## 📊 Project Summary

| # | Project | Market Focus | Key Concepts | Phase |
|---|---------|--------------|--------------|-------|
| 1 | Daily Returns & Volatility Analyzer | NSE — Nifty 50, Bank Nifty | Log/arithmetic returns; rolling vol; Sharpe; Sortino; ADF test; ACF/PACF | 1 |
| 2 | NSE Volatility Surface Builder | NSE — Bank Nifty Options | Implied vol; Newton-Raphson inversion; vol smile; 3D surface; skew dynamics | 2 |
| 3 | Efficient Frontier Visualizer | NSE — Nifty 50 Stocks | Mean-variance optimisation; QP; tangency portfolio; CML | 2 |
| 4 | VaR & CVaR Estimator | NSE — Nifty/Bank Nifty F&O | Historical & parametric VaR; CVaR; Kupiec backtesting | 2 |
| 5 | EMA Crossover Backtest | NSE — Bank Nifty Futures | Backtesting engine; transaction costs; drawdown; Calmar | 2 |
| 6 | Monte Carlo Option Pricer | NSE — Bank Nifty & Nifty Options | GBM; Euler-Maruyama; MC pricing; antithetic variates; Asian option | 3 |
| 7 | Pairs Trading Backtest | NSE — Sector stock pairs | Engle-Granger; cointegration; Z-score; stat arb; cost-adjusted backtest | 3 |
| 8 | CAPM Beta & Factor Analyzer | NSE — Nifty 50 Stocks | OLS regression; beta; SML; Fama-French 3-factor proxy | 3 |
| 9 | Market Regime Detector | NSE — Bank Nifty | 2-state Gaussian HMM; Viterbi; regime-conditional volatility | 3 |
| 10 | Market Microstructure Simulator | NSE-inspired LOB | Order book OOP; Poisson order flow; bid-ask spread; market impact | 3 |
| 11 | Rolling Correlation & PCA Analyzer | NSE — Nifty 50 | Rolling covariance; PCA eigendecomposition; stressed vs calm periods | 3 |
| 12 | Sharpe Ratio Optimizer | NSE — Multi-asset Futures | QP Sharpe maximisation; risk parity comparison; rolling Sharpe | 3 |
| 13 | Stochastic Option Pricer with Greeks | NSE — Bank Nifty Options | SDEs; Euler-Maruyama; Itô's lemma; finite-difference Greeks; QuantLib | 4 |
| 14 | Optimal Stopping Simulator | NSE — Options / OU spread | Secretary problem; DP threshold policy; Kelly risk-of-ruin | 4 |
| 15 | Full NSE F&O Backtesting Engine | NSE — Bank Nifty F&O | Modular engine; GARCH vol filter; HMM regime; full cost model | 4 |
| 16 | NSE Commodities Quant Research | NSE/MCX — Gold, Crude, Nat Gas | Roll yield; convenience yield; futures basis; EWMAC trend-following | 4 |

> 🇮🇳 All 16 projects use NSE/Indian market data. Projects 2, 4, 5, 6, 13, 14, 15 focus specifically on Bank Nifty F&O. Project 16 covers NSE commodity futures.

---

## 🧮 Phase Statistics

| Phase | Days | Dates | Projects | Books (active) | Key Math |
|-------|------|-------|----------|----------------|----------|
| 1 — Foundations | 1–50 | Apr 1 – May 20 | 1 | B1, B4, B8, B9, B22, B33, B35 | Returns; volatility; stationarity; ARMA; CLT; Bayes |
| 2 — Derivatives & Portfolio | 51–110 | May 21 – Jul 19 | 4 | B2, B5, B6, B7, B10, B22, B28, B30, B31, B32 | B-S; Greeks; Markowitz; CAPM; VaR; cointegration |
| 3 — Statistical & Stochastic Intro | 111–180 | Jul 20 – Sep 27 | 7 | B11, B13, B14, B26, B27, B28, B29, B33, B34, B37 | Measure theory; convex opt; MCMC; MC simulation; HMM; PCA |
| 4 — Advanced Stochastic & Research | 181–240 | Sep 28 – Nov 27 | 4 | B12, B15, B16, B17, B24, B26, B27 | Itô calculus; SDEs; Girsanov; Feynman-Kac; HJB; Kelly |

---

## 📖 Interview Prep — Running Schedule

Interview preparation runs across all phases. The following books are used as running references, not read at one go.

| Book | Sections | When |
|------|----------|------|
| B18 (Zhou — Green Book) | §Probability → §Basic Options → §Hard Options → §Stochastic Calculus | Phase 2 onwards |
| B19 (Heard on the Street) | §1–60 (Phase 2) → §61–120 (Phase 3) → §121+ (Phase 4) | Phase 2 onwards |
| B20 (Joshi et al.) | §Probability → §Risk → §Stochastic (Phase 3) → §Derivatives (Phase 4) | Phase 2 onwards |
| B21 (Stefanica 150) | §1–75 (Phase 3) → §76–150 (Phase 4) | Phase 3 onwards |
| B23 (Mosteller 50) | Problems 1–50 spread across all phases (daily practice) | Phase 1–3 |
| B25 (Bester Primer) | §Mathematics → §Interview strategy | Phase 2–3 |
| B36 (Aaron Cao) | Targeted hard problems | Phase 3–4 |
| B24 (Wilmott FAQ) | Selected derivative sections | Phase 3–4 |

**Weekly non-negotiables across all phases:**
- 20–30 min TraderMath (mental arithmetic)
- 3–5 Brainstellar puzzles (W3) or Max Dama brainteasers (W13)
- 1 QuantQuestions session (W6) or Quantable (W7)
- Figgie game (W5) — at minimum once per week from Phase 2 onward

---

*Start date: April 1, 2026 · Target end: November 27, 2026 · Total: 240 days*
