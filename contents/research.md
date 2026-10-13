<article class="research-item research-item-illustrated">
<figure class="research-figure">
  <a class="research-figure-link" href="static/assets/img/research/opcredit-method.png" target="_blank" rel="noopener" aria-label="Enlarge OpCredit method overview">
    <img src="static/assets/img/research/opcredit-method.png" alt="OpCredit method overview, Figure 2" loading="lazy">
    <span class="figure-zoom">View full size ↗</span>
  </a>
</figure>
<div class="research-copy">


### OpCredit: Operation-Aware Policy Learning for Agentic Knowledge Graph Question Answering  
Conference Paper (Under Review at ACL ARR) | 2026 | First author  

Proposed **OpCredit**, an operation-aware policy-learning framework that addresses the mismatch between trajectory-level rewards and individual KG operations in agentic knowledge graph question answering.

<details class="research-details">
<summary>Technical details</summary>

- Designed **Branch Outcome Credit (BOC)** to compare downstream task rewards after different operations under matched navigation contexts, reusing ordinary rollouts without an additional rollout tree or auxiliary evaluator.
- Introduced **Frontier Transition Credit (FTC)** to measure operation-induced changes in answer-conditioned frontier potential, complementing downstream outcome credit with immediate transition feedback.
- Demonstrated consistent improvements on ComplexWebQuestions, WebQSP, and GrailQA across three LLM backbones, with inference using only the learned policy and standard KG interface.

</details>


</div>
</article>

<article class="research-item research-item-illustrated">
<figure class="research-figure">
  <a class="research-figure-link" href="static/assets/img/research/cd-opd-method.png" target="_blank" rel="noopener" aria-label="Enlarge CD-OPD method overview">
    <img src="static/assets/img/research/cd-opd-method.png" alt="CD-OPD method overview, Figure 3" loading="lazy">
    <span class="figure-zoom">View full size ↗</span>
  </a>
</figure>
<div class="research-copy">


### CD-OPD: Contextual Digest for On-Policy Distillation  
Conference Paper (Under Review at ACL ARR) | 2026 | Second author  

Proposed **CD-OPD**, using a teacher-generated dependency graph to curate relevant problem conditions and preceding reasoning into a Contextual Digest before student continuation.

<details class="research-details">
<summary>Technical details</summary>

- Introduced **Collaboration Failure Rate (CFR)** to quantify incorrect teacher-takeover responses when both the student and teacher independently answer correctly.
- Developed **online meta-reweighting** to favor Digest-segment updates predicted to improve student-only task performance.
- Improved average accuracy by **1.32–7.05 percentage points** across eight benchmarks and reduced CFR by **27.4%–56.4%** relative to existing takeover-based OPD methods.

</details>


</div>
</article>

<article class="research-item research-item-illustrated">
<figure class="research-figure">
  <a class="research-figure-link" href="static/assets/img/research/oacr-method.png" target="_blank" rel="noopener" aria-label="Enlarge OACR method overview">
    <img src="static/assets/img/research/oacr-method.png" alt="OACR method overview, Figure 3" loading="lazy">
    <span class="figure-zoom">View full size ↗</span>
  </a>
</figure>
<div class="research-copy">


### OACR: Outcome-Anchored Credit Reallocation for Agentic Knowledge Graph Question Answering  
Conference Paper (Under Review at ACL ARR) | 2026 | Second author  

Proposed **OACR**, which trains a KG-state outcome model to estimate outcome-reward changes between adjacent KG search states and converts them into operation credit to construct multiplicative token weights, reallocating token-level update magnitudes while preserving the sign of the outcome-level advantage.

<details class="research-details">
<summary>Technical details</summary>

- Identified and empirically analyzed the **trajectory-to-operation mismatch** in outcome-supervised RL (GRPO) for agentic KGQA: the final-answer outcome cannot distinguish whether individual KG operations advance the search, yet all policy-generated tokens receive the same outcome-level advantage.
- The KG-state outcome model is training-only and introduces **no additional inference-time cost**.
- Achieved state-of-the-art performance on WebQSP, ComplexWebQuestions, and GrailQA while using **fewer inference-time LLM calls and tokens** (e.g., 3.8 vs. 22.6 calls/question for ToG) across Qwen2.5-3B/7B and Llama-3.1-8B.

</details>


</div>
</article>

<article class="research-item research-item-illustrated">
<figure class="research-figure">
  <a class="research-figure-link" href="static/assets/img/research/psr-method.png" target="_blank" rel="noopener" aria-label="Enlarge PSR method overview">
    <img src="static/assets/img/research/psr-method.png" alt="PSR method overview, Figure 1" loading="lazy">
    <span class="figure-zoom">View full size ↗</span>
  </a>
</figure>
<div class="research-copy">

### PSR: Efficient Knowledge Graph Question Answering via Plan-Guided Schema-Level Reasoning  
Conference Paper (Findings of EMNLP 2026) | 2025 | Second author  

Proposed PSR, a training-free retrieval-augmented generation framework for multi-hop knowledge graph question answering with a constant number of LLM calls.

<details class="research-details">
<summary>Technical details</summary>

- Introduced a plan-guided schema-level reasoning paradigm that decouples LLM decision-making from iterative graph traversal.
- Designed Plan-Regularized Monte Carlo Tree Search (PR-MCTS) to efficiently retrieve schema-level reasoning paths without additional LLM supervision.
- Reduced LLM interaction cost to exactly three calls per question, independent of reasoning depth.
- Achieved state-of-the-art or competitive accuracy on WebQSP and ComplexWebQuestions while significantly lowering latency and token usage.

</details>


</div>
</article>

<article class="research-item research-item-illustrated">
<figure class="research-figure">
  <a class="research-figure-link" href="static/assets/img/research/loginumsynth-method.png" target="_blank" rel="noopener" aria-label="Enlarge LogiNumSynth method overview">
    <img src="static/assets/img/research/loginumsynth-method.png" alt="LogiNumSynth method overview, Figure 1" loading="lazy">
    <span class="figure-zoom">View full size ↗</span>
  </a>
</figure>
<div class="research-copy">


### LogiNumSynth: Synthesizing Joint Logical–Numerical Reasoning Problems for Language Models  
arXiv Preprint | 2025  

Proposed LogiNumSynth, a fully controllable natural language problem synthesizer for joint logical and numerical reasoning.

<details class="research-details">
<summary>Technical details</summary>

- Designed a formal reasoning framework based on Facts–Rules–Query with an automatically constructed reasoning DAG.
- Enabled fine-grained control over reasoning depth, logical rule complexity, and numerical expression complexity.
- Introduced process-level evaluation, measuring reasoning-step correctness beyond final answer accuracy.
- Conducted large-scale evaluation on 29 LLMs (0.5B–685B), revealing persistent weaknesses in integrated reasoning.
- Demonstrated that targeted synthetic data can improve out-of-domain reasoning performance through supervised fine-tuning.

</details>


</div>
</article>
