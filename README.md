# Mohammed Ehtesham ul Hassan Shaik

CS engineer from Guntur, India. I build trading systems in Python, and I'm interested in how machine learning systems fail, especially when someone is trying to make them fail. I'm applying to PhD programs for 2027.

## What I'm working on

### April
My current project, and the successor to QuantBot. It trades Indian (NSE) and US equities as two separate systems. The two markets work differently, so each side has its own logic rather than one engine trying to handle both. Still in active development.

### QuantBot
An intraday opening range breakout system for NSE, now on its fourth version. The strategy itself is simple. Most of the work went into making sure I could trust the results:

- Walk-forward testing, so parameters are always checked on data they weren't tuned on
- Monte Carlo stress tests to see how bad a run of losses could realistically get
- Correlation-aware position limits, so it doesn't stack up several trades that are really the same bet
- Post-trade analytics and strategy versioning, so every result can be traced back to the exact version that produced it
- YAML config profiles, so strategies can be changed without touching the code

Live data comes from Angel One SmartAPI or Kite Connect. There's an ML layer planned (XGBoost first, then reinforcement learning), but it stays switched off until there are 50 to 100 real trades to train on.

I'm cleaning up both projects before making the code public.

## Research interests

- Security of machine learning systems, especially adversarial attacks and data poisoning
- Security of embedded and cyber-physical systems
- Machine learning applied to finance

## Background

B.E. in Computer Science and Engineering, Sathyabama University, Chennai (2015 to 2019), where I was vice president of the Entrepreneurship Club. Worked as a systems engineer at Mount Square Technologies in Hyderabad, and in engineering and operations at ARFA Techno Industries. Currently studying data science and ML at Masai School.

## Tools

Python, C, SQL, pandas, NumPy, scikit-learn, XGBoost, FastAPI, Git, Linux

## Contact

[LinkedIn](https://www.linkedin.com/in/mohammed-ehtesham-ul-hassan-shaik-290536108/)
