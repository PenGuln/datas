### Table 1: Using the same generated examples as losing responses in PO methods.

| Method | MMLU | TruthfulQA | HellaSwag | Winogrande | GSM8k | ARC | IFEval | Avg. |
|--------|------|------------|-----------|------------|-------|-----|--------|------|
| DFT      |61.69 |  52.23     |  83.95    |  78.37     | 48.22 |64.25 |  51.20  | **62.84**|
| SFT $\rightarrow$ DPO | 61.11 |  62.22 |  85.31 | 78.69 | 30.71 |         65.53 | 26.43 | 58.57 |
| SFT $\rightarrow$ SimPO | 60.59 | 66.47 |  85.65 | 78.22 | 2.43 |        66.13 | 39.37 | 56.98 |

### Table 2: Comparison with ORPO and DPO-p
| Method   | MMLU | TruthfulQA | HellaSwag | Winogrande | GSM8k | ARC  | IFEval | Avg. |
|----------|------|------------|-----------|------------|-------|------|--------|------|
| DFT      |61.69 |  52.23     |  83.95    |  78.37     | 48.22 |64.25 |  51.20  | **62.84**|
| ORPO     |62.26 |  48.26     |  83.07    |  79.16     | 45.41 |62.20  |  53.41 | 61.97|
| DPO-p    |62.01 |  48.66     |  84.03    |  78.61     | 40.48 |62.20  |  25.32 | 57.33|