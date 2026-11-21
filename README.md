# CSET485 – AI and Society · Assignment 1 (German Credit, seed 453)

Stress-testing a credit-approval model on the UCI Statlog German Credit dataset:
OLS vs logistic thresholding, Simpson's paradox, omitted-variable bias, adversarial (confident-but-wrong) cases,
and a fairness threshold sweep (demographic parity, equalized odds, predictive parity).

## Run it

```bash
pip install -r requirements.txt
jupyter notebook CSET485_Assignment1_GermanCredit.ipynb   # then Kernel → Restart & Run All
```

The notebook downloads `german.data` from UCI (falls back to an identical GitHub mirror if UCI is down),
uses `random_state = 453` for the 70/30 split and all other random steps, and writes:

- `results.json`: every number quoted in the report
- `figures/`: every chart in the report

## Files

| File | Contents |
|---|---|
| `CSET485_Assignment1_GermanCredit.ipynb` | Full, documented analysis (preprocessing, Parts 1–2) |
| `CSET485_Assignment1_Report.pdf` | Submitted report (preprocessing, Parts 1–4) |
| `requirements.txt` | Python packages used |
