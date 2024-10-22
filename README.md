# LLMs Privacy Literature
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of LLMs Privacy papers (and codes).

Paper are sorted by their released dates in descending order.

## How to Search?
Search keywords like conference name (e.g., ```CCS```), LLMs name (e.g., ```ChatGPT```), or topic (e.g., ```MIA```) over the webpage to quickly locate related papers.

## Quick Links
- [LLMs Privacy-related Papers](#llms-privacy-related-papers-back-to-top)
- [Other Resources](#other-resources-back-to-top)
- [Acknowledgement](#acknowledgement-back-to-top)

## LLMs Privacy-related Papers [[Back to Top](#llms-privacy-literature)]
| Year   | Venue | Title | Topic | LLMs  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|------------|
| 2021 | USENIX'Sec |**Extracting Training Data from Large Languange Models** | Training Data Extraction | GPT-2 | [Link](https://arxiv.org/abs/2012.07805) | [Link](https://github.com/ftramer/LM_Memorization) |
| 2023 | ICML |**Bag of Tricks for Training Data Extraction from Language Models** | Training Data Extraction | GPT-Neo | [Link](https://proceedings.mlr.press/v202/yu23c.html) | [Link](https://github.com/weichen-yu/LM-Extraction) |
| 2023 | arXiv |**Scalable Extraction of Training Data from (Production) Language Models** | Training Data Extraction | Pythia, GPT-Neo, LLaMA, Falcon, ChatGPT | [Link](https://arxiv.org/abs/2311.17035) |  |
| 2023 | ACL |**Membership Inference Attacks against Language Models via Neighbourhood Comparison** | MIA | GPT-2 | [Link](https://aclanthology.org/2023.findings-acl.719/) | [Link](https://github.com/mireshghallah/neighborhood-curvature-mia) |
| 2023 | NIPS |**DECODINGTRUST: A Comprehensive Assessment of Trustworthiness in GPT Models** | Comprehensive Trustworthiness Evaluation |  | [Link](https://arxiv.org/abs//2306.11698) | [Link](https://github.com/AI-secure/DecodingTrust) |
| 2024 | ICML |**Position: TrustLLM: Trustworthiness in Large Language Models** | Comprehensive Trustworthiness Evaluation |  | [Link](https://proceedings.mlr.press/v235/huang24x.html) | [Link](https://github.com/HowieHwong/TrustLLM) |
| 2024 | ACL |**Noisy Neighbors: Efficient membership inference attacks against LLMs** | MIA | GPT-2 | [Link](https://aclanthology.org/2024.privatenlp-1.1/) | [Link](https://github.com/computationalprivacy/document-level-membership-inference) |
| 2024 | USENIX'Sec |**Did the Neurons Read your Book? Document-level Membership Inference for Large Language Models** | MIA (Document) | OpenLLaMA | [Link](https://www.usenix.org/conference/usenixsecurity24/presentation/meeus) | [Link](https://github.com/computationalprivacy/document-level-membership-inference) |
| 2024 | CCS |**Membership Inference Attacks Against In-Context Learning** | MIA (Prompt) | GPT2-XL, LLaMA, Vicuna, GPT-3.5 | [Link](https://arxiv.org/abs/2409.01380) |  |
| 2024 | ICLR |**Detecting Pretraining Data From Large Language Models** | MIA | LLaMA, GPT-Neo, Pythia | [Link](https://openreview.net/forum?id=zWqr3MQuNs) | [Link](https://github.com/swj0419/detect-pretrain-code) |
| 2024 | EMNLP |**ReCaLL: Membership Inference via Relative Conditional Log-Likelihoods** | MIA | Pythia, GPT-NeoX, LLaMA, OPT, Mamba | [Link](https://arxiv.org/abs/2406.15968) | [Link](https://github.com/ruoyuxie/recall) |
| 2024 | EMNLP |**Reconstruct Your Previous Conversations! Comprehensively Investigating Privacy Leakage Risks in Conversations with GPT Models** | Conversations Reconstruction | GPT-3.5, GPT-4 | [Link](https://arxiv.org/abs/2402.02987) |  |
| 2024 | CCS | **PLeak: Prompt Leaking Attacks against Large Language Model Applications** | Prompt Extraction Attack | GPT-J, OPT, Falcon, LLaMA, Vicuna, and 50 LLM applications from Poe | [Link](https://arxiv.org/abs/2405.06823) | [Link](https://github.com/BHui97/PLeak) |
| 2024 | arXiv | **Evaluating Large Language Model based Personal Information Extraction and Countermeasures** | Personal Profile Extraction | PaLM, gemini-pro, Flan-UL2, Vicuna, GPT-3.5-turbo, GPT-4, LLaMA, InternLM | [Link](https://arxiv.org/abs/2408.07291) | [Link](https://github.com/liu00222/LLM-Based-Personal-Profile-Extraction) |
| 2024 | arXiv |**Min-K%++: Improved Baseline for Detecting Pre-Training Data from Large Language Models** | MIA | Pythia, GPT-NeoX, LLaMA, OPT, Mamba | [Link](https://arxiv.org/abs/2404.02936) | [Link](https://github.com/zjysteven/mink-plus-plus) |

## Other Resources [[Back to Top](#llms-privacy-literature)]
- The 1st GenAI Risks Workshop - Jun 2023 [[Website](https://sites.google.com/view/genai-risk-workshop/home?authuser=0)] [[Report](https://www.nowpublishers.com/article/Details/SEC-041)]
- The 2nd GenAI Risks Workshop - Oct 2023 [[Website](https://sites.google.com/view/genai-risks-workshop-oct-2023/home?authuser=0)] [[Report](https://eprint.iacr.org/2024/855)]


## Acknowledgement [[Back to Top](#llms-privacy-literature)]
- GitHub Repo of LLM Security & Privacy by [@chawins](https://github.com/chawins) [[GitHub repo](https://github.com/chawins/llm-sp)]

