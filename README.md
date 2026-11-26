# Cybersecurity Final Project: Intrusion Detection

Case 2 (small PCAP, about 50 packets, multiple protocols) with Isolation Forest.

## Group
- Kostis
- Quinten
- Danish
- Aryan
- Vasilis


## Repo layout
- `data/raw/` : original PCAP 
- `data/processed/` : CSV files produced by the notebook
- `notebooks/intrusion_detection.ipynb` : the single notebook, one heading per section
- `docs/` : notes, CTI links, task split

## Setup
```
python -m venv cybersec_env
source cybersec_env/bin/activate      # Windows: cybersec_env\Scripts\activate
pip install -r requirements.txt
jupyter lab
```
for conda 
```
conda create -n cybersec_env python=3.11
conda activate cybersec_env
pip install -r requirements.txt
jupyter lab

```

Put the PCAP in `data/raw/case2.pcap` and open the notebook.

## Git rules
1. Never commit to `main` directly. Make a branch: `yourname/task`.
2. Run `git pull origin main` before you start and before you push.
3. Open a Pull Request and let one other person approve it.
4. In the notebook, only edit your own section to avoid merge conflicts.

## Deadlines
- Presentation: 30 Nov or 01 Dec (20 min + 5 min questions)
- Report, slides, code: 05 Dec
