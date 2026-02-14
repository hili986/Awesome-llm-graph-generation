[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
# awesome-dynamic-graphgen-benchmark

+ **Update** `(2026-02-13)`: Curated papers from Dynamic_GraphGen_Benchmark2.xlsx, reorganized with finer-grained categories.
+ **Collection**: Deep/LLM-based graph generation and knowledge graph construction, including agentic graph systems and multimodal graph generation.
+ **Collaborate**: PRs are welcome — add missing papers, author lists, stronger venues normalization, and more code links.

## Contents

+ [A. Multimodal Visual Graph Generation (Scene Graph / Panoptic)](#section-a)
+ [B. Molecular Graph Generation (Text-guided Molecules)](#section-b)
+ [C. LLM Graph Generation Capability (Exploration / Benchmarking)](#section-c)
+ [D. Knowledge Graph Construction (Text/Web/Docs → KG)](#section-d)
+ [E. Reliability & Quality Control (RAG / Judge / Verification)](#section-e)
+ [F. Graph-centric LLM Augmentation (Tools / Instruction / Alignment)](#section-f)
+ [G. Temporal Reasoning & Evolving Knowledge Graphs](#section-g)
+ [H. Causal Graph Discovery](#section-h)
+ [I. Agentic Graph Construction & Enrichment](#section-i)
+ [J. Agentic Graph Applications (Analysis / QA / World Models / Evaluation)](#section-j)
+ [K. Social Graph for Social Simulation](#section-k)
+ [L. Multi-agent Systems as Graph Generative Models](#section-l)

<a id="section-a"></a>

## A. Multimodal Visual Graph Generation (Scene Graph / Panoptic)

**Aligning Large Language Models to Create Scene Graphs from Images**
AAAI 2025. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32558)] [[code](https://github.com/EgeOzsoy/SGG-LLM)]


**OpenPSG: Open-set Panoptic Scene Graph Generation via Large Multimodal Models**
arXiv 2025. [[paper](https://arxiv.org/abs/2503.09551)] [[code](https://github.com/Jingkang50/OpenPSG)]


**Relation-Aware Hallucination Prevention for Open-Vocabulary Scene Graph Generation**
CVPR 2025. [[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Lee_Relation-Aware_Hallucination_Prevention_for_Open-Vocabulary_Scene_Graph_Generation_CVPR_2025_paper.html)] [[code](https://github.com/rlqja1107/RAHP)]


**Text-to-Image Generation Models as Graph Generators: A Case Study on Scene Graph Generation**
CVPR 2025. [[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Peng_Text-to-Image_Generation_Models_as_Graph_Generators_A_Case_Study_CVPR_2025_paper.html)] [[code](https://github.com/SJTU-DeepVisionLab/Pix2Grp)]




<a id="section-b"></a>

## B. Molecular Graph Generation (Text-guided Molecules)

**Text-Guided Molecule Generation with Diffusion Language Model**
AAAI 2025. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32833)] [[code](https://github.com/CRIPAC-DIG/tgm-dlm)]




<a id="section-c"></a>

## C. LLM Graph Generation Capability (Exploration / Benchmarking)

**Exploring the Potential of Large Language Models in Graph Generation**
arXiv 2024. [[paper](https://arxiv.org/abs/2403.14358)]




<a id="section-d"></a>

## D. Knowledge Graph Construction (Text/Web/Docs → KG)

**AutoSchemaKG: Autonomous Knowledge Graph Construction through Dynamic Schema Induction from Web-Scale Corpora**
arXiv 2025. [[paper](https://arxiv.org/abs/2505.23628)] [[code](https://github.com/HKUST-KnowComp/AutoSchemaKG)]


**Automated Knowledge Graph Construction using Large Language Models and Sentence Complexity Modelling**
arXiv 2025 (EMNLP 2025-related submission version; see repository naming). [[paper](https://arxiv.org/abs/2509.17289)] [[code](https://github.com/KaushikMahmud/CoDe-KG_EMNLP_2025)]


**Domain-Specific Knowledge Graph Construction via LLM-driven Knowledge Dependency Parsing**
arXiv 2025. [[paper](https://arxiv.org/abs/2505.24163)] [[code](https://github.com/ottoSJTU/LKD-KGC)]


**GKG-LLM: A Unified Framework for Generalized Knowledge Graph Construction**
arXiv 2025. [[paper](https://arxiv.org/abs/2503.11227)] [[code](TBD)]


**Generating Domain-Specific Knowledge Graphs from Large Language Models**
Findings of ACL 2025. [[paper](https://aclanthology.org/2025.findings-acl.602/)] [[code](https://github.com/parovicm/llm-kg-gen)]


**Leveraging Large Language Models for Virtual Knowledge Graph Construction**
IJCAI 2025. [[paper](https://www.ijcai.org/proceedings/2025/525)] [[code](https://github.com/HomuraT/LLM4VKG)]


**Structured Knowledge Extraction from Semi-Structured Documents for Domain Knowledge Graph Construction**
ACL 2025. [[paper](https://aclanthology.org/2025.acl-long.907/)] [[code](https://github.com/thu-pacman/Tree-KG)]


**Docs2KG: Unified Knowledge Graph Construction from Heterogeneous Documents Assisted by Large Language Models**
arXiv 2024. [[paper](https://arxiv.org/abs/2406.02962)] [[code](https://github.com/AI4WA/Docs2KG)]


**Extract, Define, Canonicalize: An LLM-based Framework for Knowledge Graph Construction**
EMNLP 2024. [[paper](https://arxiv.org/abs/2404.03868)] [[code](https://github.com/clear-nus/edc)]


**Extracting and Transforming Materials Science Data with Large Language Models: A Data-Driven Study**
NeurIPS 2024. [[paper](https://papers.nips.cc/paper_files/paper/2024/hash/c53945823af8bd11f017d57fbc7d21e5-Abstract-Conference.html)] [[code](https://github.com/CederGroupHub/MatKG-LLM)]


**LLM-driven Knowledge Graph Construction with a Novel Focus on Rice Literature: A Case Study**
ACL 2024 (Long). [[paper](https://aclanthology.org/2024.acl-long.238/)] [[code](https://github.com/Gitsign/SAC-KG)]




<a id="section-e"></a>

## E. Reliability & Quality Control (RAG / Judge / Verification)

**GraphJudge: Can Large Language Models be a Good Graph Judge for Knowledge Graph Construction?**
EMNLP 2025. [[paper](https://aclanthology.org/2025.emnlp-main.554/)] [[code](https://github.com/hhy-huang/GraphJudge)]


**Graphusion: A RAG Framework for Scientific Knowledge Graph Construction with a Global Perspective**
The Web Conference (WWW) 2025 / arXiv 2024. [[paper](https://arxiv.org/abs/2410.17600)] [[code](https://github.com/IreneZihuiLi/Graphusion)]


**Prompting with Iterative Verification: Improving Graph-based Generative Capability of LLMs**
ACL 2024. [[paper](https://aclanthology.org/2024.findings-acl.400/)] [[code](https://github.com/Jiuzhouh/PiVe)]




<a id="section-f"></a>

## F. Graph-centric LLM Augmentation (Tools / Instruction / Alignment)

**InstructGraph: Boosting Large Language Models via Graph-centric Instruction Tuning and Preference Alignment**
Findings of ACL 2024. [[paper](https://aclanthology.org/2024.findings-acl.801.pdf)] [[code](https://github.com/wjn1996/InstructGraph)]


**Graph-ToolFormer: To Empower LLMs with Graph Reasoning Ability via Prompt Augmented by ChatGPT**
arXiv 2023. [[paper](https://arxiv.org/abs/2304.11116)] [[code](https://github.com/jwzhanggy/Graph_Toolformer)]




<a id="section-g"></a>

## G. Temporal Reasoning & Evolving Knowledge Graphs

**MedKGent: A Large Language Model Agent Framework for Constructing Temporally Evolving Medical Knowledge Graph**
arXiv 2025. [[paper](https://arxiv.org/abs/2508.12393)] [[code](https://github.com/bladedancer957/MedKGent)]


**Large Language Models Can Learn Temporal Reasoning**
ACL 2024. [[paper](https://arxiv.org/abs/2401.06853)] [[code](https://github.com/xiongsiheng/TG-LLM)]




<a id="section-h"></a>

## H. Causal Graph Discovery

**Large Language Models Meet Causal Discovery: An Empirical Study of Faithfulness and Markov Blanket**
arXiv 2024. [[paper](https://arxiv.org/abs/2402.01142)] [[code](https://github.com/HCVE/llm-cd)]




<a id="section-i"></a>

## I. Agentic Graph Construction & Enrichment

**Agentic-KGR: Co-evolutionary Knowledge Graph Construction through Multi-Agent Reinforcement Learning**
arXiv 2025. [[paper](https://arxiv.org/abs/2510.09156v1)]


**GRAPHMASTER: AUTOMATED GRAPH SYNTHESIS VIA LLM
AGENTS IN DATA-LIMITED ENVIRONMENTS**
arXiv 2025. [[paper](https://arxiv.org/abs/2504.00711)] [[code](https://github.com/EnjunDu/GraphMaster)]


**KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment**
arXiv 2025. [[paper](https://arxiv.org/abs/2502.06472v1)] [[code](GitHub - YuxingLu613/KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment)]


**AutoGraph: Autonomous Graph Construction from Textual Documents via LLM-Driven Multi-Agent Collaboration**
arXiv 2024. [[paper](https://arxiv.org/abs/2410.11263)] [[code](https://github.com/AutoGraph2024/AutoGraph)]


**KnoBuilder: A Knowledge Graph Dataset Generator for Biomedical Domain**
arXiv 2024. [[paper](https://arxiv.org/abs/2409.02965)] [[code](https://github.com/yuzhimanhua/KnoBuilder)]


**Large Language Models for Urban Knowledge Graph Construction: A Graph-aware Multi-Agent Framework**
arXiv 2024. [[paper](https://arxiv.org/abs/2410.06835)] [[code](https://github.com/usail-hkust/UrbanKGent)]




<a id="section-j"></a>

## J. Agentic Graph Applications (Analysis / QA / World Models / Evaluation)

**GraphTeam: Facilitating Large Language Model-based Graph Analysis via Multi-Agent Collaboration**
arXiv 2025. [[paper](https://arxiv.org/abs/2410.18032)]


**AriGraph: Learning Knowledge Graph World Models with Episodic Memory for LLM Agents**
IJCAI 2025. [[paper](https://ijcai-preprints.s3.us-west-1.amazonaws.com/2025/7833.pdf)] [[code](https://github.com/AIRI-Institute/AriGraph)]


**Generate-on-Graph: Treat LLM as both Agent and KG for Incomplete Knowledge Graph Question Answering**
ACL2024. [[paper](https://aclanthology.org/2024.emnlp-main.1023.pdf)] [[code](https://github.com/YaooXu/GoG)]


**Way to Specialist: A Medical Agent System towards Standardized and Comprehensive Medical Evaluation**
arXiv 2024. [[paper](https://arxiv.org/abs/2411.19064)] [[code](https://github.com/waynelee0804/WTS)]




<a id="section-k"></a>

## K. Social Graph for Social Simulation

**GRAPHIA: Harnessing Social Graph Data to Enhance LLM-Based Social Simulation**
arXiv 2025. [[paper](https://arxiv.org/abs/2510.24251)] [[code](https://github.com/Ji-Cather/Graphia)]




<a id="section-l"></a>

## L. Multi-agent Systems as Graph Generative Models

**LLM-Based Multi-Agent Systems are Scalable Graph Generative Models**
ACL2025. [[paper](https://aclanthology.org/2025.findings-acl.78.pdf)] [[code](https://github.com/Ji-Cather/GraphAgent)]



