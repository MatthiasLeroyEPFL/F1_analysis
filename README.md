# F1 Tyre Degradation & Lap Time Sensitivity Analysis

Analysis of tyre degradation and lap time sensitivity using real F1 timing data from the 2024 Bahrain Grand Prix.

**Data source:** FastF1 library (official F1 timing data)

**Key findings:**
- Soft compound degrades at ~+0.08s/lap on a normalised per-stint basis
- Track temperature is the strongest environmental driver of lap time
- Significant inter-driver variation in degradation rates points to driving style as a key factor

**Run locally:**
```bash
pip install fastf1 pandas numpy matplotlib seaborn scikit-learn
jupyter notebook f1-analysis.ipynb
```
