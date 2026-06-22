# Gender Bias in Language Models

Investigating whether LLMs exhibit gender stereotypes when evaluating job applicants by measuring surprisal across gendered names.

## Research Question

Are LLMs sensitive to gender stereotypes when evaluating applicants for different careers?

## Methods

Tested 11 minimal pair sentences across GPT-2, DistilGPT-2, and GPT-Neo 1.3B. Each pair was identical except for a male or female name placed in a job-related context (e.g. software engineer, nurse, CEO, mechanic). Measured surprisal using log probability to quantify how unexpected each name was in a given job context.

## Findings

All three models showed higher surprisal for female names than male names across stereotypically male job contexts, suggesting the models have internalized gender-career associations from their training data. Results are consistent with the hypothesis that LLMs reflect human biases present in the text they were trained on.

## Limitations

Job stereotypes, name frequency in training data, and tokenization differences are potential confounds. The surprisal differences may partly reflect how common certain names are in training data rather than purely gender bias.

## Stack

Python · HuggingFace Transformers · Pandas · Matplotlib · Seaborn · PyTorch

## Author

Samin Chowdhury
