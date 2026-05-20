# MH6822-Team-Homework
# OTC Derivatives Compliance Engine

## Team Members:
Wang Yue (G2505294E, yue024@e.ntu.edu.sg), Yu Xuerui (G2505243G, xuerui002@e.ntu.edu.sg), Peng Yulong (G2505383A, yulong002@e.ntu.edu.sg), Yang Lin (G2506924C, YANG1030@e.ntu.edu.sg)

## Files

| File | Description |
|------|-------------|
| `OTC_Derivatives_Compliance_Engine.ipynb` | Main program (engine + dashboard) |
| `trades.json` | Test data (33 trades) |
| `compliance_report.json` | Compliance results (generated after running) |
| `compliance_dashboard.html` | Visual dashboard (generated after running) |
| `MH6822-Written Analysis.pdf` | Technical and Regulatory Report |
| `MH6822 Recorded Presentation.mp4` | https://drive.google.com/file/d/1B7AuiJy9NLlYTF0uneuWBkUM_hmZbYOG/view?usp=sharing |
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
