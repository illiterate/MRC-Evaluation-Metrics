# MRC2018 Evaluation Metrics with Bounce
## Metric Details
Please refer to 
> Evaluation Metrics.docx

## How to run the script
Run the demo data:
> python mrc_eval.py demo_data/pred.json demo_data/ref.json
Result:
```JSON
{'ROUGE-L': 56.67, 'BLEU-4': 24.45}
```
In this evaluation we set alpha=1.0, beta=1.0, gamma=1.2 by default.
