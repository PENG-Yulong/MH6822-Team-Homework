# MH6822-Team-Homework
# OTC Derivatives Compliance Engine

## Team Members:
Wang Yue (G2505294E), Yu Xuerui (G2505243G), Peng Yulong (G2505383A), Yang Lin (G2506924C)

## Files

| File | Description |
|------|-------------|
| `OTC_Derivatives_Compliance_Engine.ipynb` | Main program (engine + dashboard) |
| `trades.json` | Test data (33 trades) |
| `compliance_report.json` | Compliance results (generated after running) |
| `compliance_dashboard.html` | Visual dashboard (generated after running) |

## Requirements

```bash
pip install numpy matplotlib jupyter

How to Run
jupyter notebook OTC_Derivatives_Compliance_Engine.ipynb
Run Cell 1 → generates compliance_report.json
Run Cell 2 → generates charts/ and compliance_dashboard.html
Results
•	Total trades: 33
•	Compliance rate: 84.8% (28/33)
•	Non-compliant: 15.2% (5/33)
