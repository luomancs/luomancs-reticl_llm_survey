
# Survey on Retrieval Methods in LLMs

This repository contains an organized overview of various research papers categorized by their use of Large Language Models (LLMs), retrieval methods, retrieval corpora, evaluation tasks, retriever training techniques, and retrieval strategies.

## LLMs (Large Language Models)

- **GPT-3**: [SYNCHROMESH](https://arxiv.org/abs/2105.00828), [KATE](https://arxiv.org/abs/2212.02551), [EPR](https://arxiv.org/abs/2106.01120), [Z-ICL](https://arxiv.org/abs/2212.09865), [MemPrompt](https://arxiv.org/abs/2201.06009), [IC-DST](https://arxiv.org/abs/2210.09150), [Vote-k](https://arxiv.org/abs/2210.13179), [Auto-CoT](https://arxiv.org/abs/2210.06726), [DSP](https://arxiv.org/abs/2212.14024), [PromptPG](https://arxiv.org/abs/2206.02336), [Self-Prompting](https://arxiv.org/abs/2212.08635)
- **CODEX**: [EPR](https://arxiv.org/abs/2106.01120), [XRICL](https://arxiv.org/abs/2212.03113), [Self-Prompting](https://arxiv.org/abs/2212.08635), [Cover-LS](https://arxiv.org/abs/2212.06800), [Dynamic Least-to-Most](https://arxiv.org/abs/2212.05880), [CEIL](https://arxiv.org/abs/2302.05698), [RetICL](https://arxiv.org/abs/2305.14502), [Ambig-ICL](https://arxiv.org/abs/2309.07900)
- **GPT-J**: [EPR](https://arxiv.org/abs/2106.01120), [Vote-k](https://arxiv.org/abs/2210.13179), [Z-ICL](https://arxiv.org/abs/2212.09865), [UDR](https://arxiv.org/abs/2305.04320)
- **GPT-Neo**: [Z-ICL](https://arxiv.org/abs/2212.09865), [Vote-k](https://arxiv.org/abs/2210.13179), [UPRISE](https://arxiv.org/abs/2303.08518), [MoT](https://arxiv.org/abs/2305.05181)
- **T5-11B**: [TeachMe](https://arxiv.org/abs/2204.13074)
- **PaLM, Flan-PaLM**: [Dr.ICL](https://arxiv.org/abs/2305.14128), [Ambig-ICL](https://arxiv.org/abs/2309.07900)
- **LLaMA**: [ICL-ML](https://arxiv.org/abs/2307.09288), [LLM-R](https://arxiv.org/abs/2307.07164)
- **XGLM**: [R-BM25](https://arxiv.org/abs/2212.02437), [ICL-MC](https://arxiv.org/abs/2303.02913)
- **OPT**: [UPRISE](https://arxiv.org/abs/2303.08518)
- **BLOOM**: [UPRISE](https://arxiv.org/abs/2303.08518), [ICL-MC](https://arxiv.org/abs/2303.02913)
- **InstructGPT**: [Self-Prompting](https://arxiv.org/abs/2212.08635)
- **ChatGPT**: [MoT](https://arxiv.org/abs/2305.05181)
- **DODEX**: [Dynamic Least-to-Most](https://arxiv.org/abs/2212.05880)

## Retrieval Methods

- **SBERT**: [SYNCHROMESH](https://arxiv.org/abs/2105.00828), [EPR](https://arxiv.org/abs/2106.01120), [Z-ICL](https://arxiv.org/abs/2212.09865), [MemPrompt](https://arxiv.org/abs/2201.06009), [IC-DST](https://arxiv.org/abs/2210.09150), [Vote-k](https://arxiv.org/abs/2210.13179), [Auto-CoT](https://arxiv.org/abs/2210.06726), [XRICL](https://arxiv.org/abs/2212.03113), [DSP](https://arxiv.org/abs/2212.14024), [PARC](https://arxiv.org/abs/2212.09651), [ICL-ML](https://arxiv.org/abs/2307.09288), [MoT](https:...
- **BM25**: [TeachMe](https://arxiv.org/abs/2204.13074), [R-BM25](https://arxiv.org/abs/2212.02437), [ICL-MC](https://arxiv.org/abs/2303.02913), [CEIL](https://arxiv.org/abs/2302.05698), [Dr.ICL](https://arxiv.org/abs/2305.14128), [Ambig-ICL](https://arxiv.org/abs/2309.07900)
- **RoBERTa+kNN**: [KATE](https://arxiv.org/abs/2212.02551)
- **Fine-tuned Retriever**: [EPR](https://arxiv.org/abs/2106.01120), [IC-DST](https://arxiv.org/abs/2210.09150), [XRICL](https://arxiv.org/abs/2212.03113), [PromptPG](https://arxiv.org/abs/2206.02336), [ICL-ML](https://arxiv.org/abs/2307.09288), [UPRISE](https://arxiv.org/abs/2303.08518), [LLM-R](https://arxiv.org/abs/2307.07164), [UDR](https://arxiv.org/abs/2305.04320), [Dr.ICL](https://arxiv.org/abs/2305.14128)
- **Clustering with SBERT**: [Auto-CoT](https://arxiv.org/abs/2210.06726)
- **ColBERTv2**: [DSP](https://arxiv.org/abs/2212.14024)
- **Query Transformation + SBERT**: [MemPrompt](https://arxiv.org/abs/2201.06009)
- **Multilingual SBERT**: [PARC](https://arxiv.org/abs/2212.09651)
- **Diversity Selection**: [Cover-LS](https://arxiv.org/abs/2212.06800)
- **Tree Structure Similarity**: [Dynamic Least-to-Most](https://arxiv.org/abs/2212.05880)
- **Iterative LSTM with Reinforcement Learning**: [RetICL](https://arxiv.org/abs/2305.14502)
