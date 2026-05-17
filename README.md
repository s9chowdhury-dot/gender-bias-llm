Gender Bias in Language Models

Investigating whether LLMs exhibit gender stereotypes when evaluating job applicants by measuring surprisal across gendered names.

Research Question

Are LLMs sensitive to gender stereotypes when evaluating applicants for different careers?
Methods
Tested 11 minimal pair sentences across three models (GPT-2, DistilGPT-2, GPT-Neo 1.3B). Each pair was identical except for a male or female name. Measured surprisal to quantify how unexpected each name was in a given job context.
Findings
All three models showed slightly higher surprisal for female names than male names, suggesting the models have internalized gender-career associations from their training data.

Stack

Python · HuggingFace Transformers · Pandas · Matplotlib · Seaborn · PyTorch

Author

Samin Chowdhury
