[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
# awesome-dynamic-graphgen-benchmark

+ **Update** `(2026-02-13)`: Curated papers from Dynamic_GraphGen_Benchmark2.xlsx, reorganized with finer-grained categories.
+ **Collection**: Deep/LLM-based graph generation and knowledge graph construction, including agentic graph systems and multimodal graph generation.
+ **Collaborate**: PRs are welcome — add missing papers, author lists, stronger venues normalization, and more code links.

## Contents

+ [A. Multimodal Visual Graph Generation (Scene Graph / Panoptic)](#a-multimodal-visual-graph-generation-scene-graph-panoptic)
+ [B. Molecular Graph Generation (Text-guided Molecules)](#b-molecular-graph-generation-text-guided-molecules)
+ [C. LLM Graph Generation Capability (Exploration / Benchmarking)](#c-llm-graph-generation-capability-exploration-benchmarking)
+ [D. Knowledge Graph Construction (Text/Web/Docs → KG)](#d-knowledge-graph-construction-textwebdocs-kg)
+ [E. Reliability & Quality Control (RAG / Judge / Verification)](#e-reliability-quality-control-rag-judge-verification)
+ [F. Graph-centric LLM Augmentation (Tools / Instruction / Alignment)](#f-graph-centric-llm-augmentation-tools-instruction-alignment)
+ [G. Temporal Reasoning & Evolving Knowledge Graphs](#g-temporal-reasoning-evolving-knowledge-graphs)
+ [H. Causal Graph Discovery](#h-causal-graph-discovery)
+ [I. Agentic Graph Construction & Enrichment](#i-agentic-graph-construction-enrichment)
+ [J. Agentic Graph Applications (Analysis / QA / World Models / Evaluation)](#j-agentic-graph-applications-analysis-qa-world-models-evaluation)
+ [K. Social Graph for Social Simulation](#k-social-graph-for-social-simulation)
+ [L. Multi-agent Systems as Graph Generative Models](#l-multi-agent-systems-as-graph-generative-models)

## A. Multimodal Visual Graph Generation (Scene Graph / Panoptic)

**Aligning Large Language Models to Create Scene Graphs from Images**
*Algorithm: LLM4SGG*
AAAI 2025. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32558)] [[code](https://github.com/EgeOzsoy/SGG-LLM)]


**OpenPSG: Open-set Panoptic Scene Graph Generation via Large Multimodal Models**
*Algorithm: OpenPSG*
arXiv 2025. [[paper](https://arxiv.org/abs/2503.09551)] [[code](https://github.com/Jingkang50/OpenPSG)]


**Relation-Aware Hallucination Prevention for Open-Vocabulary Scene Graph Generation**
*Algorithm: RAHP*
CVPR 2025. [[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Lee_Relation-Aware_Hallucination_Prevention_for_Open-Vocabulary_Scene_Graph_Generation_CVPR_2025_paper.html)] [[code](https://github.com/rlqja1107/RAHP)]


**Text-to-Image Generation Models as Graph Generators: A Case Study on Scene Graph Generation**
*Algorithm: Pix2Grp*
CVPR 2025. [[paper](https://openaccess.thecvf.com/content/CVPR2025/html/Peng_Text-to-Image_Generation_Models_as_Graph_Generators_A_Case_Study_CVPR_2025_paper.html)] [[code](https://github.com/SJTU-DeepVisionLab/Pix2Grp)]




## B. Molecular Graph Generation (Text-guided Molecules)

**Text-Guided Molecule Generation with Diffusion Language Model**
*Algorithm: TGM-DLM*
AAAI 2025. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32833)] [[code](https://github.com/CRIPAC-DIG/tgm-dlm)]




## C. LLM Graph Generation Capability (Exploration / Benchmarking)

**Exploring the Potential of Large Language Models in Graph Generation**
*Algorithm: LLM4GraphGen*
arXiv 2024. [[paper](https://arxiv.org/abs/2403.14358)]




## D. Knowledge Graph Construction (Text/Web/Docs → KG)

**AutoSchemaKG: Autonomous Knowledge Graph Construction through Dynamic Schema Induction from Web-Scale Corpora**
*Algorithm: AutoSchemaKG*
arXiv 2025. [[paper](https://arxiv.org/abs/2505.23628)] [[code](https://github.com/HKUST-KnowComp/AutoSchemaKG)]


**Automated Knowledge Graph Construction using Large Language Models and Sentence Complexity Modelling**
*Algorithm: CoDe-KG*
arXiv 2025（与 EMNLP 2025 相关/投稿版本见仓库命名）. [[paper](https://arxiv.org/abs/2509.17289)] [[code](https://github.com/KaushikMahmud/CoDe-KG_EMNLP_2025)]


**Domain-Specific Knowledge Graph Construction via LLM-driven Knowledge Dependency Parsing**
*Algorithm: LKD-KGC*
arXiv 2025（提交版本）. [[paper](https://arxiv.org/abs/2505.24163)] [[code](https://github.com/ottoSJTU/LKD-KGC)]


**GKG-LLM: A Unified Framework for Generalized Knowledge Graph Construction**
*Algorithm: GKG-LLM*
arXiv 2025. [[paper](https://arxiv.org/abs/2503.11227)] [[code](（未检索到稳定开源仓库，TBD）)]


**Generating Domain-Specific Knowledge Graphs from Large Language Models**
*Algorithm: LLM-KG-Gen*
Findings of ACL 2025. [[paper](https://aclanthology.org/2025.findings-acl.602/)] [[code](https://github.com/parovicm/llm-kg-gen)]


**Leveraging Large Language Models for Virtual Knowledge Graph Construction**
*Algorithm: LLM4VKG*
IJCAI 2025. [[paper](https://www.ijcai.org/proceedings/2025/525)] [[code](https://github.com/HomuraT/LLM4VKG)]


**Structured Knowledge Extraction from Semi-Structured Documents for Domain Knowledge Graph Construction**
*Algorithm: Tree-KG*
ACL 2025. [[paper](https://aclanthology.org/2025.acl-long.907/)] [[code](https://github.com/thu-pacman/Tree-KG)]


**Docs2KG: Unified Knowledge Graph Construction from Heterogeneous Documents Assisted by Large Language Models**
*Algorithm: Docs2KG*
arXiv 2024. [[paper](https://arxiv.org/abs/2406.02962)] [[code](https://github.com/AI4WA/Docs2KG)]


**Extract, Define, Canonicalize: An LLM-based Framework for Knowledge Graph Construction**
*Algorithm: EDC (Extract-Define-Canonicalize)*
EMNLP 2024. [[paper](https://arxiv.org/abs/2404.03868)] [[code](https://github.com/clear-nus/edc)]


**Extracting and Transforming Materials Science Data with Large Language Models: A Data-Driven Study**
*Algorithm: MKG-LLM*
NeurIPS 2024. [[paper](https://papers.nips.cc/paper_files/paper/2024/hash/c53945823af8bd11f017d57fbc7d21e5-Abstract-Conference.html)] [[code](https://github.com/CederGroupHub/MatKG-LLM)]


**LLM-driven Knowledge Graph Construction with a Novel Focus on Rice Literature: A Case Study**
*Algorithm: SAC-KG*
ACL 2024 (Long). [[paper](https://aclanthology.org/2024.acl-long.238/)] [[code](https://github.com/Gitsign/SAC-KG)]




## E. Reliability & Quality Control (RAG / Judge / Verification)

**GraphJudge: Can Large Language Models be a Good Graph Judge for Knowledge Graph Construction?**
*Algorithm: GraphJudge*
EMNLP 2025. [[paper](https://aclanthology.org/2025.emnlp-main.554/)] [[code](https://github.com/hhy-huang/GraphJudge)]


**Graphusion: A RAG Framework for Scientific Knowledge Graph Construction with a Global Perspective**
*Algorithm: Graphusion*
The Web Conference (WWW) 2025 / arXiv 2024. [[paper](https://arxiv.org/abs/2410.17600)] [[code](https://github.com/IreneZihuiLi/Graphusion)]


**Prompting with Iterative Verification: Improving Graph-based Generative Capability of LLMs**
*Algorithm: PiVe*
ACL 2024. [[paper](https://aclanthology.org/2024.findings-acl.400/)] [[code](https://github.com/Jiuzhouh/PiVe)]




## F. Graph-centric LLM Augmentation (Tools / Instruction / Alignment)

**InstructGraph: Boosting Large Language Models via Graph-centric Instruction Tuning and Preference Alignment**
*Algorithm: InstructGraph*
Findings of ACL 2024. [[paper](https://aclanthology.org/2024.findings-acl.801.pdf)] [[code](https://github.com/wjn1996/InstructGraph)]


**Graph-ToolFormer: To Empower LLMs with Graph Reasoning Ability via Prompt Augmented by ChatGPT**
*Algorithm: Graph-ToolFormer*
arXiv 2023. [[paper](https://arxiv.org/abs/2304.11116)] [[code](https://github.com/jwzhanggy/Graph_Toolformer)]




## G. Temporal Reasoning & Evolving Knowledge Graphs

**MedKGent: A Large Language Model Agent Framework for Constructing Temporally Evolving Medical Knowledge Graph**
*Algorithm: MedKGent*
arXiv 2025. [[paper](https://arxiv.org/abs/2508.12393)] [[code](https://github.com/bladedancer957/MedKGent)]


**Large Language Models Can Learn Temporal Reasoning**
*Algorithm: TG-LLM*
ACL 2024. [[paper](https://arxiv.org/abs/2401.06853)] [[code](https://github.com/xiongsiheng/TG-LLM)]




## H. Causal Graph Discovery

**Large Language Models Meet Causal Discovery: An Empirical Study of Faithfulness and Markov Blanket**
*Algorithm: LLM-CD*
arXiv 2024. [[paper](https://arxiv.org/abs/2402.01142)] [[code](https://github.com/HCVE/llm-cd)]




## I. Agentic Graph Construction & Enrichment

**Agentic-KGR: Co-evolutionary Knowledge Graph Construction through Multi-Agent Reinforcement Learning**
*Algorithm: Agentic-KGR*
arXiv 2025. [[paper](https://arxiv.org/abs/2510.09156v1)]


**GRAPHMASTER: AUTOMATED GRAPH SYNTHESIS VIA LLM
AGENTS IN DATA-LIMITED ENVIRONMENTS**
*Algorithm: Graphmaster*
arXiv 2025. [[paper](https://arxiv.org/abs/2504.00711)] [[code](https://github.com/EnjunDu/GraphMaster)]


**KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment**
*Algorithm: KARMA*
arXiv 2025. [[paper](https://arxiv.org/abs/2502.06472v1)] [[code](GitHub - YuxingLu613/KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment)]


**AutoGraph: Autonomous Graph Construction from Textual Documents via LLM-Driven Multi-Agent Collaboration**
*Algorithm: AutoGraph*
arXiv 2024. [[paper](https://arxiv.org/abs/2410.11263)] [[code](https://github.com/AutoGraph2024/AutoGraph)]


**KnoBuilder: A Knowledge Graph Dataset Generator for Biomedical Domain**
*Algorithm: KnoBuilder*
arXiv 2024. [[paper](https://arxiv.org/abs/2409.02965)] [[code](https://github.com/yuzhimanhua/KnoBuilder)]


**Large Language Models for Urban Knowledge Graph Construction: A Graph-aware Multi-Agent Framework**
*Algorithm: UrbanKGent*
arXiv 2024. [[paper](https://arxiv.org/abs/2410.06835)] [[code](https://github.com/usail-hkust/UrbanKGent)]




## J. Agentic Graph Applications (Analysis / QA / World Models / Evaluation)

**GraphTeam: Facilitating Large Language Model-based Graph Analysis via Multi-Agent Collaboration**
*Algorithm: GraphTeam*
arXiv 2025. [[paper](https://arxiv.org/abs/2410.18032)]


**AriGraph: Learning Knowledge Graph World Models with Episodic Memory for LLM Agents**
*Algorithm: AriGraph*
arXiv 2024（可能含 IJCAI 2025 版本，待核对）. [[paper](https://arxiv.org/abs/2407.04363)] [[code](https://github.com/AIRI-Institute/AriGraph)]


**Generate-on-Graph: Treat LLM as both Agent and KG for Incomplete Knowledge Graph Question Answering**
*Algorithm: GoG*
ACL2024. [[paper](https://aclanthology.org/2024.emnlp-main.1023.pdf)] [[code](https://github.com/YaooXu/GoG)]


**Way to Specialist: A Medical Agent System towards Standardized and Comprehensive Medical Evaluation**
*Algorithm: WTS*
arXiv 2024. [[paper](https://arxiv.org/abs/2411.19064)] [[code](https://github.com/waynelee0804/WTS)]




## K. Social Graph for Social Simulation

**GRAPHIA: Harnessing Social Graph Data to Enhance LLM-Based Social Simulation**
*Algorithm: GRAPHIA*
arXiv 2025. [[paper](https://arxiv.org/abs/2510.24251)] [[code](https://github.com/Ji-Cather/Graphia)]




## L. Multi-agent Systems as Graph Generative Models

**LLM-Based Multi-Agent Systems are Scalable Graph Generative Models**
*Algorithm: GAG*
ACL2025. [[paper](https://aclanthology.org/2025.findings-acl.78.pdf)] [[code](https://github.com/Ji-Cather/GraphAgent)]



