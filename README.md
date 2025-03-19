# Understanding LLMs
## Transformer-Architecture: 
Implementing Attention is all you need transformer architecture from scratch. 

## Finetuning LLMs:
Finetuning LLMs using LoRA and IA3 implemented through various papers.
- part 1: We evaluate causal model using perplexity and fine-tune sequence classification model: test the model performance on different learning rates
- part 2: Inject LoRA Adapter layers into our causal model and fine-tune it on Wikitext: We observe that there is a significant speedup but there is a tradeoff with accuracy.
- part 3: Inject IA3 into our sequence classificaiton model and see how it affects our model performance

## Memory optimization - Quantization:
Quantization Aware Training and post-training quantization: see how Quantization-Aware Training and post-training Quantization affects our model performance(75% memory optimization)
