# Hi, I'm Keerthana (கீர்த்தனா) Madhavan 👋

**MSc in CS + AI @ University of Guelph** | **Cybersecurity Engineer III @ American Express
Researching **AI Safety**, **Multi-Agent Systems**, and **Bias Evaluation & Mitigation**.

> solving hard problems  
> building frameworks  
> making messy systems clear  
> protecting people through security  
> doing research  
> creating something original  
> being trusted with difficult work  
> seeing your intelligence become useful  

I turn ambiguous AI/security problems into frameworks, architecture decisions, and practical execution paths.

💬 *HMU if you're bored and want to work on a fun project!*

---


### 🌟 Featured Contribution: Google DeepMind — Concordia

* **Contribution Type:** `Feature` (New Game Master Component in `contrib`)
* **Author & Contributor:** [`ControlledProfilePresentation`](https://github.com/google-deepmind/concordia/blob/main/concordia/contrib/components/game_master/controlled_profile_presentation.py) ([PR #404](https://github.com/google-deepmind/concordia/pull/404) / [Commit 3cef724](https://github.com/google-deepmind/concordia/commit/3cef724d1132987d21be2d5661e587b8f4e87977))
* **Reviewed & Approved by:** [Joel Z. Leibo](https://github.com/jzleibo) *(Principal Research Scientist & Project Lead @ Google DeepMind)*

> *"This looks good to me! Certainly useful to have such a thing. Thank you! I just approved the PR on github."*  
> — **[Joel Z. Leibo](https://github.com/jzleibo)**, Principal Research Scientist & Project Lead @ Google DeepMind


#### 🎯 Problem & Purpose
When evaluating bias in LLM multi-agent simulations (e.g., peer review, resume screening, or prestige bias experiments), modifying agent self-instructions or renaming entity instances introduces severe experimental confounds.

#### 🛠️ What I Built
* **Decoupled Identity & Presentation**: Built an idiomatic Game Master component (`ContextComponent` & `ComponentWithLogging`) in `concordia/contrib/components/game_master/` that decouples canonical entity identities from displayed observer presentations.
* **Declarative Condition Policies**: Implemented blinding (`visible_fields=()`), selective attribute disclosure, and counterbalanced attribute swapping (`swaps={'Author-A': 'Author-B', ...}`) for counterfactual evaluations.
* **Natural Language & JSON Formatting**: Formatted profile cards into human-readable narratives to prevent LLM prompt artifacts, alongside structured representations.
* **Cryptographic Exposure Tracking**: Implemented SHA-256 fingerprinting and verification helpers (`verify_field_not_disclosed`) to mathematically verify zero information leakage in experimental logs across simulation trials.
* **Full Test Suite & Integration**: Shipped 640+ lines of Python with comprehensive unit test coverage (`9/9` passing), fully integrated into Concordia's sequential simulation engine.

---

### 🔬 Research Interests
* **AI Safety & Alignment**: Evaluating and mitigating bias, manipulation, and unintended behaviors in generative agents.
* **Multi-Agent Simulations & Game Theory**: Information boundaries, partial observability, cooperation, and collective behavior in LLM societies.
* **Cybersecurity & AI Assurance**: Security evaluation of AI models and agentic workflows.

---

### 📬 Connect With Me
* **Twitter / X**: [@keeana01](https://twitter.com/keeana01)
* **GitHub**: [@simplykeerthana](https://github.com/simplykeerthana)
