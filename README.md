# Survey on Retrieval Methods in LLMs

This page presents an organized overview of various research papers in the survey paper [In-context Learning with Retrieved Demonstrations for Language Models: A Survey](https://arxiv.org/pdf/2401.11624).

## LLMs (Large Language Models)

- **GPT-3**: SYNCHROMESH, KATE, EPR, Z-ICL, MemPrompt, IC-DST, Vote-k, Auto-CoT, DSP, PromptPG, Self-Prompting, R-BM25, UPRISE, Dr.ICL, LLM-R, UDR, MoT
- **CODEX**: EPR, XRICL, Self-Prompting, Cover-LS, Dynamic Least-to-Most, CEIL, RetICL, Ambig-ICL
- **GPT-J**: EPR, Vote-k, Z-ICL, UDR
- **GPT-Neo**: Z-ICL, Vote-k, UPRISE, MoT
- **T5-11B**: TeachMe
- **PaLM, Flan-PaLM**: Dr.ICL, Ambig-ICL
- **LLaMA**: ICL-ML, LLM-R
- **XGLM**: R-BM25, ICL-MC
- **OPT**: UPRISE
- **BLOOM**: UPRISE, ICL-MC
- **InstructGPT**: Self-Prompting
- **ChatGPT**: MoT
- **DODEX**: Dynamic Least-to-Most

## Retrieval Methods

- **SBERT**: SYNCHROMESH, EPR, Z-ICL, MemPrompt, IC-DST, Vote-k, Auto-CoT, XRICL, DSP, PARC, ICL-ML, MoT
- **BM25**: TeachMe, R-BM25, ICL-MC, CEIL, Dr.ICL, Ambig-ICL
- **RoBERTa+kNN**: KATE
- **Fine-tuned Retriever**: EPR, IC-DST, XRICL, PromptPG, ICL-ML, UPRISE, LLM-R, UDR, Dr.ICL
- **Clustering with SBERT**: Auto-CoT
- **ColBERTv2**: DSP
- **Query Transformation + SBERT**: MemPrompt
- **Multilingual SBERT**: PARC
- **Diversity Selection**: Cover-LS
- **Tree Structure Similarity**: Dynamic Least-to-Most
- **Iterative LSTM with Reinforcement Learning**: RetICL

## Retrieval Corpus

- **In Domain**: SYNCHROMESH, KATE, EPR, MemPrompt, TeachMe, IC-DST, Vote-k, XRICL, DSP, Cover-LS, PromptPG, Dynamic Least-to-Most, R-BM25, ICL-ML, UDR, Dr.ICL
- **Cross Domain**: XRICL, PARC, ICL-MC, UPRISE
- **Free Form Corpus**: Z-ICL, Self-Prompting
- **LLM Generated CoT for In Domain**: Auto-CoT
- **Mix Domain**: LLM-R, UDR
- **Unlabelled Queries with LLMs CoT**: MoT

## Evaluation Tasks

- **Code Generation (CodeGen)**: SYNCHROMESH, CEIL
- **Sentiment Analysis (SA)**: KATE, Z-ICL, Vote-k, PARC, ICL-MC, LLM-R, UDR, Ambig-ICL
- **Table to Text Generation (Table2Text)**: KATE
- **Question Answering (QA)**: KATE, TeachMe, Vote-k, XRICL, DSP, PromptPG, CEIL, UPRISE, Dr.ICL, LLM-R, UDR, MoT
- **Semantic Parsing (SP)**: EPR, Cover-LS, Dynamic Least-to-Most, CEIL, UDR
- **Dialogue State Tracking (DST-to-SQL)**: IC-DST
- **Data-to-Text (D2T)**: LLM-R, UDR
- **Summarization (Summ)**: Vote-k, LLM-R
- **Commonsense Reasoning (CSR)**: Vote-k, LLM-R, UDR, MoT
- **Reading Comprehension (RC)**: Vote-k, LLM-R, UPRISE
- **Natural Language Inference (NLI)**: Vote-k, PARC, LLM-R, UPRISE, UDR, MoT, Ambig-ICL
- **Coreference Resolution (CR)**: UPRISE, LLM-R
- **Mathematical Reasoning (MathR)**: Auto-CoT, PromptPG, MoT, Dr.ICL, RetICL
- **Paraphrase Detection (PD)**: CEIL, LLM-R, UPRISE
- **Story Generation (StoryGen)**: UDR
- **Machine Translation (MT)**: R-BM25, ICL-MC
- **Topic Classification (TC)**: PARC, UDR, Ambig-ICL

## Retriever Training

- **Target Similarity Tuning**: SYNCHROMESH
- **Sentence Similarity Embedding**: KATE, MemPrompt, Vote-k, Auto-CoT, Self-Prompting, MoT
- **InfoNCE Loss (Contrastive Learning)**: EPR
- **Contrastive Learning**: IC-DST, UPRISE, Dr.ICL, LLM-R, UDR, Ambig-ICL
- **Distillation by KL Divergence**: XRICL
- **Diversity Training**: Cover-LS, CEIL
- **Policy Gradient**: PromptPG
- **Diversity and Lexical Overlap**: Dynamic Least-to-Most
- **Term-based Similarity**: TeachMe, R-BM25, ICL-MC
- **PPO and GAE**: RetICL

## Retrieval Strategy

- **Top-k**: SYNCHROMESH, KATE, EPR, Z-ICL, MemPrompt, TeachMe, IC-DST, Vote-k, XRICL, PromptPG, R-BM25, ICL-MC, ICL-ML, UPRISE, Dr.ICL, Ambig-ICL
- **Clustering**: Auto-CoT, Self-Prompting, MoT
- **Iterative**: DSP, Cover-LS, Dynamic Least-to-Most, RetICL, CEIL, LLM-R
