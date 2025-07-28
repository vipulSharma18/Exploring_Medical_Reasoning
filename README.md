# Medical AI and LLM-as-a-Judge

## Example Models
From [Abraham et al, 2025]:        
Unimodal comp path: UNI, CONCH, Virchow.    
Multimodal: LLaVA-Med (Microsoft), PathChat (Harvard), CheXagent (Stanford), BiomedCLIP (Microsoft, RoentGen (Stanford+StabilityAI).   

## Using LLM-as-a-Judge for Automated Formalized Evaluation

### Introduction

1. **Why**: consistency, inherent subjectivity, and scale of evaluation.  
2. **Goals**: consistency, bias-free, adaptive to diverse scenarios, and reliability.  
3. **Use cases**: for Models, for Agents, for Data, for Reasoning/Thinking.  
4. **Philosophy**: Formalizing the subjective by using LLMs.  
5. **Alternatives**: Expert-driven, or metric-based evaluation.  
6. **Attacks**: Adversarial prompt manipulation, contextual framing biases.  
7. **Challenges**: Multimodal inputs.  
8. **Future work**:
   - **Reliability**: Self-consistency, uncertainty calibration, bias mitigation.  
   - **Robustness/Adversarial-Resistant Evaluation**: Prompt engineering, and sensitivity to context.  
   - **Generalization**: Multimodal input, domain-adaptive learning, integrating structured knowledge.  
9. **Personal Long Term Goals**: Formalize mech interp and solve the **cherry-picking** problem. **Formalize philosophical** problems.

### Quick Practice

Hands-on practice opportunity in **section 2.5** of [Gu et al, 2025](#).

### Application Domains

Used in **highly complex areas**, such as mathematical reasoning and legal texts.  

**Nuanced** evaluation where **no single correct answer** exists.  

**Multiagent debate** framework for automated evaluation.

### How it relates to my past work / CV:

- **HoneyPot**: Mitigating **biases** using **automated evaluation** is an attempt to do LLM eval using statistical tools.  
- Noise robustness in Foundation models: This was an attempt to implement **self-consistency in the latent space** to ensure robustness.  
- **Computation Histopathology**: More robust and fine-grained evaluation using tile-level gene mutation data.  

### Follow-up Big Knowledge Landmarks

People working in LLM eval need to be familiar with these tools and concepts:

- LLM Arena: Used for LLM Eval.           
- Eleuther AI LLM Eval Harness.  

---

**References**
[1] J. Gu et al., “A Survey on LLM-as-a-Judge,” Mar. 09, 2025, arXiv: arXiv:2411.15594. doi: 10.48550/arXiv.2411.15594.              
[2] Tanishq Mathew Abraham, and Paul Scotti. 2025. “The Medical AI Manifesto - Introducing Sophont.” March 31, 2025. https://www.tanishq.ai/blog/posts/sophont.html.
