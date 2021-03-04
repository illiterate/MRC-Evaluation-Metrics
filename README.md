# MRC Evaluation Metrics from [Baidu DuReader](https://github.com/baidu/DuReader)
百度提供的是Python2版本的，在此基础上修改成了Python3版本的，方便后续使用。

## Metric Details
Please refer to 
> Evaluation Metrics.docx

## How to run the script
Run the demo data:
> python mrc_eval.py demo_data/pred.json demo_data/ref.json

Result:
> {'ROUGE-L': 56.67, 'BLEU-4': 24.45}


In this evaluation we set alpha=1.0, beta=1.0, gamma=1.2 by default.
