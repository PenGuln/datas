### Table 1: Using the same generated examples as losing responses in PO methods.

| Method | MMLU | TruthfulQA | HellaSwag | Winogrande | GSM8k | ARC | IFEval | Avg. |
|--------|------|------------|-----------|------------|-------|-----|--------|------|
| DFT      |61.69 |  52.23     |  83.95    |  78.37     | 48.22 |64.25 |  51.20  | **62.84**|
| SFT --> DPO | 61.11 |  62.22 |  85.31 | 78.69 | 30.71 |         65.53 | 26.43 | 58.57 |
| SFT --> SimPO | 60.59 | 66.47 |  85.65 | 78.22 | 2.43 |        66.13 | 39.37 | 56.98 |