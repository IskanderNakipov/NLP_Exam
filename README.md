# NLP_Exam
Showcase your NLP skills


Question #1 - Goal - train sentiment classifier

Use https://huggingface.co/datasets/FinanceInc/auditor_sentiment#data-fields dataset to fine-tune 
https://huggingface.co/roberta-base model

1. First freeze all the layers expect of classifier and tune head only (5.0)
2. Then unfreeze last 3 layers of the model and tune them (10.0)
3. Evaluate finetuned model (5.0)
4. Use Pipelines to create prediction pipline (5.0)

Question #2 - Goal - Identify Top Keywords (See provided dataset in csv)

Questions to answer:
1. Please briefly describe your approach (10.0)
2. How did you define what “top” is? (5.0)
3. List the top 10 keywords here along with the metrics. If you’d like to show us a visualization for it, you could do that (20.0)
4. If you were unable to complete your code in the allotted time, please describe what more you originally intended to implement. (5.0)
5. If you had a few weeks (say 4-8) to do this task, what other approaches would you try and implement for this problem? (10.0)

