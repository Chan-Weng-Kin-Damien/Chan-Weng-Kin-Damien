# Weng Kin Chan

Year 3 Computer Science and Mathematics student at the University of Edinburgh
(84/100, on track for First Class Honours), on a full-year exchange at the
University of Washington, Seattle, for 2026–27.

I work on ML inference systems and quantitative research.

## Experience

**Research Assistant, School of Informatics, University of Edinburgh** · Jun 2026 – Aug 2026  
AI inference serving: Python, PyTorch, CUDA (MPS), Linux (cpuset/NUMA), SGLang

- Cut p99 time-to-first-chunk 7.8× (27.5 → 3.5 s) and tripled throughput on a
  30B-parameter serving engine at 64 concurrent streams, by tracing queue-dominated
  latency to head-of-line blocking and concurrency caps
- Raised GPU throughput 17% by consolidating inference processes into one NVIDIA MPS
  scheduling domain
- Derived parallelism and CPU/GPU placement rules from 5,400 controlled runs, raising
  per-GPU throughput 26%
- Disproved a deadline-ordered admission policy across 39 controlled trials; instant
  rejection gave 6.3× the goodput of ungated admission under overload

**Control Software Engineer, HYPED (University of Edinburgh Hyperloop Team)** · Oct 2024 – Oct 2025  
Rust, C++, STM32, MATLAB/Simulink

- Ported the levitation control loop from C++ to embedded Rust on an STM32
  microcontroller, with no dynamic memory allocation
- Built a 100 Hz Kalman filter fusing accelerometer, optical and track-marker sensors to
  estimate pod position and speed

**Teaching Support Tutor and Marker, Java OOP, University of Edinburgh**  
Led tutorials and marked assignments for 50+ students

## Projects and competitions

**[Cross-Sectional Crypto Alpha Research](https://github.com/Chan-Weng-Kin-Damien/avenir_hku_web_quant_trading_challenge)**
· Avenir-HKU Web 3.0 Quantitative Trading Challenge, top 3% (Top-12 finalist)  
Walk-forward research pipeline over 120 perpetual futures and 2.2M rows. The
market-neutral strategy was near-flat (−2.4%) over 61 days of paper trading through an
18.6% Bitcoin decline.

**[Limit Order Book Prediction](https://github.com/Chan-Weng-Kin-Damien/LOB-prediction)**
· Wunder Fund RNN Challenge, 417th of 5,062 (top 8%)  
GRU, attention and TCN ensemble predicting forward price indicators from order-book
features, served at 1.6 ms per tick within a single-CPU time limit.

**IMC Prosperity 4** · 742nd of 18,803 teams (top 4%)  
Market making against inventory, volatility-smile fitting for option pricing, and a live
probe trader measuring counterparty fill behaviour.

**ICPC UK & Ireland Programming Contest** · 29th, top 10% nationally  
**AMC 12** · Top 1% globally, Honor Roll of Distinction

## Skills

**Languages:** Python, Rust, C, C++, Java, SQL, MATLAB, Haskell  
**ML / numerical:** PyTorch, NumPy, pandas, SciPy, scikit-learn, XGBoost, LightGBM, ONNX Runtime  
**Systems:** SGLang, CUDA (MPS), Linux (cpuset/NUMA), STM32, Git

## Contact

[LinkedIn](https://linkedin.com/in/weng-kin-chan) · chanwengkindamien@gmail.com
