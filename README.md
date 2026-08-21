# LLM4Fin — Automated FinTech Test Case Generation

Implementation of ISSTA 2024 paper:
**"LLM4Fin: Fully Automating LLM-Powered Test Case Generation
for FinTech Software Acceptance Testing"**

## Project Overview
Fully automated pipeline that generates acceptance test cases
from SEC filing documents using fine-tuned FinBERT models.

## Files
- `LLM4Fin_implementation.ipynb` — Main implementation notebook
- `financial_ner_dataset(10,000).csv` — Dataset used
- `ends_ppt.pptx` — Project presentation
- `final_report.pdf` — Project report
- `base_paper.pdf` — Reference paper (ISSTA 2024)

## Results
| Metric | Value |
|---|---|
| Rule Filter Accuracy | 97.91% |
| NER Entity F1 | 78.46% |
| Test Cases Generated | 15,320 |
| Business Scenario Coverage | 100% |
| Processing Time | 1.5 seconds |

## Technologies
Python, HuggingFace Transformers, FinBERT, seqeval, pandas, Google Colab GPU

## Team
- Nayana Yogeshwari P M(231AI023)
- Lekhana (231AI016)
- Nandeesh Nayak (231AI022)

National Institute of Technology Karnataka, Surathkal
