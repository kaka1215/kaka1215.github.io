<article class="research-item">

### OpCredit: Operation-Aware Policy Learning for Agentic Knowledge Graph Question Answering  
Conference Paper (Under Review at ACL ARR) | 2026 | First author  

- Proposed **OpCredit**, an operation-aware policy-learning framework that addresses the mismatch between trajectory-level rewards and individual KG operations in agentic knowledge graph question answering.
- Designed **Branch Outcome Credit (BOC)** to compare downstream task rewards after different operations under matched navigation contexts, reusing ordinary rollouts without an additional rollout tree or auxiliary evaluator.
- Introduced **Frontier Transition Credit (FTC)** to measure operation-induced changes in answer-conditioned frontier potential, complementing downstream outcome credit with immediate transition feedback.
- Demonstrated consistent improvements on ComplexWebQuestions, WebQSP, and GrailQA across three LLM backbones, with inference using only the learned policy and standard KG interface.

</article>

<article class="research-item">

### CD-OPD: Contextual Digest for On-Policy Distillation  
Conference Paper (Under Review at ACL ARR) | 2026 | Second author  

- Introduced **Collaboration Failure Rate (CFR)** to quantify incorrect teacher-takeover responses when both the student and teacher independently answer correctly.
- Proposed **CD-OPD**, using a teacher-generated dependency graph to curate relevant problem conditions and preceding reasoning into a Contextual Digest before student continuation.
- Developed **online meta-reweighting** to favor Digest-segment updates predicted to improve student-only task performance.
- Improved average accuracy by **1.32–7.05 percentage points** across eight benchmarks and reduced CFR by **27.4%–56.4%** relative to existing takeover-based OPD methods.

</article>

<article class="research-item">

### OACR: Outcome-Anchored Credit Reallocation for Agentic Knowledge Graph Question Answering  
Conference Paper (Under Review at ACL ARR) | 2026 | Second author  

- Identified and empirically analyzed the **trajectory-to-operation mismatch** in outcome-supervised RL (GRPO) for agentic KGQA: the final-answer outcome cannot distinguish whether individual KG operations advance the search, yet all policy-generated tokens receive the same outcome-level advantage.  
- Proposed **OACR**, which trains a KG-state outcome model to estimate outcome-reward changes between adjacent KG search states and converts them into operation credit to construct multiplicative token weights, reallocating token-level update magnitudes while preserving the sign of the outcome-level advantage.  
- The KG-state outcome model is training-only and introduces **no additional inference-time cost**.  
- Achieved state-of-the-art performance on WebQSP, ComplexWebQuestions, and GrailQA while using **fewer inference-time LLM calls and tokens** (e.g., 3.8 vs. 22.6 calls/question for ToG) across Qwen2.5-3B/7B and Llama-3.1-8B.

</article>

<article class="research-item">

### PSR: Efficient Knowledge Graph Question Answering via Plan-Guided Schema-Level Reasoning  
Conference Paper (Findings of EMNLP 2026) | 2025 | Second author  

- Proposed PSR, a training-free retrieval-augmented generation framework for multi-hop knowledge graph question answering with a constant number of LLM calls.  
- Introduced a plan-guided schema-level reasoning paradigm that decouples LLM decision-making from iterative graph traversal.  
- Designed Plan-Regularized Monte Carlo Tree Search (PR-MCTS) to efficiently retrieve schema-level reasoning paths without additional LLM supervision.  
- Reduced LLM interaction cost to exactly three calls per question, independent of reasoning depth.  
- Achieved state-of-the-art or competitive accuracy on WebQSP and ComplexWebQuestions while significantly lowering latency and token usage.

</article>

<article class="research-item">

### LogiNumSynth: Synthesizing Joint Logical–Numerical Reasoning Problems for Language Models  
arXiv Preprint | 2025  

- Proposed LogiNumSynth, a fully controllable natural language problem synthesizer for joint logical and numerical reasoning.  
- Designed a formal reasoning framework based on Facts–Rules–Query with an automatically constructed reasoning DAG.  
- Enabled fine-grained control over reasoning depth, logical rule complexity, and numerical expression complexity.  
- Introduced process-level evaluation, measuring reasoning-step correctness beyond final answer accuracy.  
- Conducted large-scale evaluation on 29 LLMs (0.5B–685B), revealing persistent weaknesses in integrated reasoning.  
- Demonstrated that targeted synthetic data can improve out-of-domain reasoning performance through supervised fine-tuning.

</article>

<article class="research-item">

### Adaptive Step-Size Decentralized Federated Learning Algorithm  
Undergraduate Thesis | Jan 2025 – Jun 2025  

- Developed a decentralized optimization algorithm that dynamically adjusts step sizes using local gradient information.  
- Designed a method combining gradient momentum, gradient differencing, and second-order estimation.  
- Extended the algorithm to a fully decentralized federated learning framework with dedicated communication and synchronization mechanisms.  
- Improved convergence efficiency while reducing communication overhead in distributed systems.

</article>

<article class="research-item">

### Uncertainty-Aware Knowledge Graph Enhanced Legal Pre-trained Language Models  
Knowledge Graph Laboratory, Southeast University | Sep 2023 – Oct 2024  

- Focused on multi-defendant legal judgment prediction with uncertainty-aware knowledge graphs.  
- Reproduced major models such as BERT, BART, mT5, Transformer, Lawformer, GPT-2, and GPT-3.  
- Proposed a structure-aware encoder for defendant behaviors and legal premises.  
- Introduced a stepwise distillation mechanism to enhance reasoning, significantly improving prediction accuracy.  
- Patent: *A Multi-hop Commonsense Generation Method Based on Structure Awareness and Stepwise Distillation*.

</article>
