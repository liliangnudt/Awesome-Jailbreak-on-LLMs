# Awesome-Jailbreak-on-LLMs

Awesome-Jailbreak-on-LLMs is a collection of state-of-the-art, novel, exciting jailbreak methods on LLMs. It contains papers, codes, datasets, evaluations, and analyses. Any additional things regarding jailbreak, PRs, issues are welcome and we are glad to add you to the contributor list [here](#contributors). Any problems, please contact yliu@u.nus.edu. If you find this repository useful to your research or work, it is really appreciated to star this repository. :sparkles:



## Papers


### Jailbreak Attack


#### White-box Attack
| Year | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **COLD-Attack: Jailbreaking LLMs with Stealthiness and Controllability (COLD-Attack)** |   ICML'24    | [link](https://arxiv.org/pdf/2402.08679)  |                              [link](https://github.com/Yu-Fangxu/COLD-Attack)                               |
| 2024.05 | **AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models (AutoDAN)** |   ICLR'24    | [link](https://arxiv.org/pdf/2310.04451)  |                              [link](https://github.com/SheltonLiu-N/AutoDAN)                               |
| 2024.05 | **AmpleGCG: Learning a Universal and Transferable Generative Model of Adversarial Suffixes for Jailbreaking Both Open and Closed LLMs (AmpleGCG)** |   arXiv    | [link](https://arxiv.org/pdf/2404.07921)  |                              [link](https://github.com/OSU-NLP-Group/AmpleGCG)                               |
| 2024.04 | **AdvPrompter: Fast Adaptive Adversarial Prompting for LLMs (AdvPrompter)** |   arXiv    | [link](https://arxiv.org/pdf/2404.16873)  |            [link](https://github.com/facebookresearch/advprompter)                                                 |
| 2024.02 | **Attacking large language models with projected gradient descent (PGD)** |   arXiv    | [link](https://arxiv.org/pdf/2402.09154)  |                              -                               |
| 2024.02 | **Curiosity-driven red-teaming for large language models (CRT)** |   arXiv    | [link](https://arxiv.org/pdf/2402.19464)  |                              [link](https://github.com/Improbable-AI/curiosity_redteam)                               |
| 2023.12 | **AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models (AutoDAN)** |   arXiv    | [link](https://arxiv.org/abs/2310.15140)  |                              [link](https://github.com/llm-attacks/llm-attacks)                               |
| 2023.10 | **Catastrophic jailbreak of open-source llms via exploiting generation** |   arXiv    | [link](https://arxiv.org/pdf/2310.06987)  |                              [link](https://github.com/Princeton-SysML/Jailbreak_LLM)                               |
| 2023.06 | **Automatically Auditing Large Language Models via Discrete Optimization (ARCA)** |   ICML'23    | [link](https://proceedings.mlr.press/v202/jones23a/jones23a.pdf)  |                              [link](https://github.com/ejones313/auditing-llms)                               |
| 2023.07 | **Universal and Transferable Adversarial Attacks on Aligned Language Models (GCG)** |   arXiv    | [link](https://arxiv.org/pdf/2307.15043)  |                              [link](https://autodan-jailbreak.github.io/)                               |




























#### Black-box Attack

| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **When LLM Meets DRL: Advancing Jailbreaking Efficiency via DRL-guided Search (RLbreaker)** |   arXiv    | [link](https://arxiv.org/pdf/2406.08705) |                              -                               |
| 2024.06 | **ArtPrompt: ASCII Art-based Jailbreak Attacks against Aligned LLMs (ArtPrompt)** |   ACL'24    | [link](https://arxiv.org/pdf/2402.11753) |                              [link](https://github.com/uw-nsl/ArtPrompt)                               |
| 2024.06 | **From Noise to Clarity: Unraveling the Adversarial Suffix of Large Language Model Attacks via Translation of Text Embeddings (ASETF)** |   arXiv    | [link](https://arxiv.org/pdf/2402.16006) |                              -                               |
| 2024.06 | **CodeAttack: Revealing Safety Generalization Challenges of Large Language Models via Code Completion (CodeAttack)** |   arXiv    | [link](https://arxiv.org/pdf/2403.07865) |                              -                               |
| 2024.06 | **Making Them Ask and Answer: Jailbreaking Large Language Models in Few Queries via Disguise and Reconstruction (DRA)** |   USENIX Security'24    | [link](https://arxiv.org/pdf/2402.18104) |                              [link](https://github.com/LLM-DRA/DRA/)                               |
| 2024.06 | **AutoJailbreak: Exploring Jailbreak Attacks and Defenses through a Dependency Lens (AutoJailbreak)** |   arXiv    | [link](https://arxiv.org/pdf/2406.08705) |                              -                               |
| 2024.06 | **Jailbreaking Leading Safety-Aligned LLMs with Simple Adaptive Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2404.02151) |                              [link](https://github.com/tml-epfl/llm-adaptive-attacks)                               |
| 2024.06 | **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts (GPTFuzz)** |   arXiv    | [link](https://arxiv.org/abs/2309.10253) |                              [link](https://github.com/sherdencooper/GPTFuzz)                               |
| 2024.06 | **A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily (ReNeLLM)** |   NAACL'24    | [link](https://arxiv.org/abs/2311.08268) |                              [link](https://github.com/NJUNLP/ReNeLLM)                               |
| 2024.06 | **QROA: A Black-Box Query-Response Optimization Attack on LLMs (QROA)** |   arXiv    | [link](https://arxiv.org/abs/2406.02044) |                              [link](https://github.com/qroa/qroa)                               |
| 2024.05 | **Multilingual Jailbreak Challenges in Large Language Models** |   ICLR'24    | [link](https://arxiv.org/pdf/2310.06474)  |                              [link](https://github.com/DAMO-NLP-SG/multilingual-safety-for-LLMs)                               |
| 2024.05 | **DeepInception: Hypnotize Large Language Model to Be Jailbreaker (DeepInception)** |   arXiv    | [link](https://arxiv.org/pdf/2311.03191)  |                              [link](https://github.com/tmlr-group/DeepInception)                               |
| 2024.05 | **GPT-4 Jailbreaks Itself with Near-Perfect Success Using Self-Explanation (IRIS)** |   ACL'24    | [link](https://arxiv.org/abs/2405.13077) |                              -                               |
| 2024.05 | **GUARD: Role-playing to Generate Natural-language Jailbreakings to Test Guideline Adherence of LLMs (GUARD)** |   arXiv    | [link](https://arxiv.org/pdf/2402.03299) |                              -                               |
| 2024.05 | **"Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models (DAN)** |   CCS'24    | [link](https://arxiv.org/pdf/2308.03825) |                              [link](https://github.com/verazuo/jailbreak_llms)                               |
| 2024.05 | **Gpt-4 is too smart to be safe: Stealthy chat with llms via cipher (SelfCipher)** |   ICLR'24    | [link](https://arxiv.org/pdf/2308.06463) |                              [link](https://github.com/RobustNLP/CipherChat)                               |
| 2024.05 | **Jailbreaking Large Language Models Against Moderation Guardrails via Cipher Characters (JAM)** |   arXiv    | [link](https://arxiv.org/pdf/2405.20413) |                              -                               |
| 2024.05 | **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations (ICA)** |   arXiv    | [link](https://arxiv.org/pdf/2310.06387) |                              -                               |
| 2024.04 | **Many-shot jailbreaking (MSJ)** |   Anthropic    | [link](https://www-cdn.anthropic.com/af5633c94ed2beb282f6a53c595eb437e8e7b630/Many_Shot_Jailbreaking__2024_04_02_0936.pdf) |                              -                              |
| 2024.04 | **Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack (Crescendo)** |   Anthropic    | [link](https://arxiv.org/pdf/2404.01833) |                              -                              |
| 2024.04 | **Fuzzllm: A novel and universal fuzzing framework for proactively discovering jailbreak vulnerabilities in large language models (FuzzLLM)** |   arXiv    | [link](https://arxiv.org/pdf/2309.05274) |                              [link](https://github.com/RainJamesY/FuzzLLM)                              |
| 2024.04 | **Sandwich attack: Multi-language mixture adaptive attack on llms (Sandwich attack)** |   arXiv    | [link](https://arxiv.org/pdf/2404.07242) |                              -                              |
| 2024.03 | **Tastle: Distract large language models for automatic jailbreak attack (TASTLE)** |   arXiv    | [link](https://arxiv.org/pdf/2403.08424) |                              -                               |
| 2024.03 | **DrAttack: Prompt Decomposition and Reconstruction Makes Powerful LLM Jailbreakers (DrAttack)** |   arXiv    | [link](https://arxiv.org/pdf/2402.16914) |                              [link](https://github.com/xirui-li/DrAttack)                               |
| 2024.02 | **PRP: Propagating Universal Perturbations to Attack Large Language Model Guard-Rails (PRP)** |   arXiv    | [link](https://arxiv.org/pdf/2402.15911) |                              -                              |
| 2024.02 | **CodeChameleon: Personalized Encryption Framework for Jailbreaking Large Language Models (CodeChameleon)** |   arXiv    | [link](https://arxiv.org/pdf/2402.16717) |                              [link](https://github.com/huizhang-L/CodeChameleon)                              |
| 2024.02 | **PAL: Proxy-Guided Black-Box Attack on Large Language Models (PAL)** |   arXiv    | [link](https://arxiv.org/abs/2402.09674) |                              [link](https://github.com/chawins/pal)                               |
| 2024.02 | **Jailbreaking Proprietary Large Language Models using Word Substitution Cipher** |   arXiv    | [link](https://arxiv.org/pdf/2402.10601) |                              -                              |
| 2024.02 | **Query-Based Adversarial Prompt Generation** |   arXiv    | [link](https://arxiv.org/pdf/2402.12329) |                              -                              |
| 2024.02 | **Pandora: Jailbreak GPTs by Retrieval Augmented Generation Poisoning (Pandora)** |   arXiv    | [link](https://arxiv.org/pdf/2402.08416) |                              -                               |
| 2024.02 | **Leveraging the Context through Multi-Round Interactions for Jailbreaking Attacks (Contextual Interaction Attack)** |   arXiv    | [link](https://arxiv.org/pdf/2402.09177) |                              -                               |
| 2024.02 | **Semantic Mirror Jailbreak: Genetic Algorithm Based Jailbreak Prompts Against Open-source LLMs (SMJ)** |   arXiv    | [link](https://arxiv.org/pdf/2402.14872) |                              -                               |
| 2024.01 | **Low-Resource Languages Jailbreak GPT-4** |   NeurIPS Workshop'24    | [link](https://arxiv.org/pdf/2310.02446) |                             -                               |
| 2024.01 | **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs (PAP)** |   arXiv    | [link](https://arxiv.org/pdf/2401.06373) |                              [link](https://github.com/CHATS-lab/persuasive_jailbreaker)                               |
| 2023.12 | **Tree of Attacks: Jailbreaking Black-Box LLMs Automatically (TAP)** |   arXiv    | [link](https://arxiv.org/abs/2312.02119) |                              [link](https://github.com/RICommunity/TAP)                               |
| 2023.12 | **Make Them Spill the Beans! Coercive Knowledge Extraction from (Production) LLMs** |   arXiv    | [link](https://arxiv.org/pdf/2312.04782) |                              -                               |
| 2023.12 | **Ignore This Title and HackAPrompt: Exposing Systemic Vulnerabilities of LLMs through a Global Scale Prompt Hacking Competition** |   ACL'24    | [link](https://aclanthology.org/2023.emnlp-main.302/) |                              -                               |
| 2023.11 | **Scalable and Transferable Black-Box Jailbreaks for Language Models via Persona Modulation (Persona)** |   NeurIPS Workshop'23    | [link](https://arxiv.org/pdf/2311.03348) |                              -                               |
| 2023.10 | **Jailbreaking Black Box Large Language Models in Twenty Queries (PAIR)** |   arXiv    | [link](https://arxiv.org/pdf/2310.08419) |                              [link](https://github.com/patrickrchao/JailbreakingLLMs)                               |
| 2023.10 | **Adversarial Demonstration Attacks on Large Language Models (advICL)** |   arXiv    | [link](https://arxiv.org/pdf/2305.14950) |                              -                               |
| 2023.10 | **MASTERKEY: Automated Jailbreaking of Large Language Model Chatbots (MASTERKEY)** |   NDSS'24    | [link](https://arxiv.org/pdf/2307.08715) |                              -                               |
| 2023.10 | **Attack Prompt Generation for Red Teaming and Defending Large Language Models (SAP)** |   EMNLP'23    | [link](https://arxiv.org/pdf/2310.12505) |                              [link](https://github.com/Aatrox103/SAP)                              |
| 2023.10 | **An LLM can Fool Itself: A Prompt-Based Adversarial Attack (PromptAttack)** |   ICLR'24    | [link](https://arxiv.org/pdf/2310.13345) |                              [link](https://github.com/GodXuxilie/PromptAttack)                              |
| 2023.09 | **Multi-step Jailbreaking Privacy Attacks on ChatGPT (MJP)** |   EMNLP Findings'23    | [link](https://arxiv.org/pdf/2304.05197) |                              [link](https://github.com/HKUST-KnowComp/LLM-Multistep-Jailbreak)                                |
| 2023.09 | **Open Sesame! Universal Black Box Jailbreaking of Large Language Models (GA)** |   arXiv    | [link](https://arxiv.org/abs/2309.01446) |                              -                               |
| 2023.05 | **Not what you’ve signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection** |   arXiv    | [link](https://arxiv.org/pdf/2302.12173?trk=public_post_comment-text) |                               [link](https://github.com/greshake/llm-security)                               |
| 2022.11 | **Ignore Previous Prompt: Attack Techniques For Language Models (PromptInject)** |   NeurIPS WorkShop'22    | [link](https://arxiv.org/pdf/2211.09527) |                              [link](https://github.com/agencyenterprise/PromptInject)                              |














#### Multi-modal Attack

| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **Jailbreak Vision Language Models via Bi-Modal Adversarial Prompt** |   arXiv    | [link](https://arxiv.org/pdf/2406.04031) |                              [link](https://github.com/NY1024/BAP-Jailbreak-Vision-Language-Models-via-Bi-Modal-Adversarial-Prompt)                               |
| 2024.05 | **Voice Jailbreak Attacks Against GPT-4o** |   arXiv    | [link](https://arxiv.org/pdf/2405.19103) |                              [link](https://github.com/TrustAIRLab/VoiceJailbreakAttack)                               |
| 2024.04 | **Image hijacks: Adversarial images can control generative models at runtime** |   arXiv    | [link](https://arxiv.org/pdf/2309.00236) |                              [link](https://github.com/euanong/image-hijacks)                               |
| 2024.01 | **Jailbreaking GPT-4V via Self-Adversarial Attacks with System Prompts** |   arXiv    | [link](https://arxiv.org/pdf/2311.09127) |                             -                          |
| 2024.03 | **Visual Adversarial Examples Jailbreak Aligned Large Language Models** |   AAAI'24    | [link](https://ojs.aaai.org/index.php/AAAI/article/view/30150/32038) |                              -                               |
| 2023.10 | **Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models** |   ICLR'24    | [link](https://arxiv.org/pdf/2307.14539) |                              -                               |



















### Jailbreak Defense

#### Learning-based Defense
| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **Jatmo: Prompt Injection Defense by Task-Specific Finetuning (Jatmo)** |   arXiv    | [link](https://arxiv.org/pdf/2312.17673) |                              [link](https://github.com/wagner-group/prompt-injection-defense)                               |
| 2024.06 | **Defending Large Language Models Against Jailbreaking Attacks Through Goal Prioritization (SafeDecoding)** |   ACL'24    | [link](https://arxiv.org/pdf/2311.09096) |                              [link](https://github.com/thu-coai/JailbreakDefense_GoalPriority)                               |
| 2024.06 | **Mitigating Fine-tuning based Jailbreak Attack with Backdoor Enhanced Safety Alignment** |   arXiv    | [link](https://jayfeather1024.github.io/Finetuning-Jailbreak-Defense/) |                              [link](https://github.com/Jayfeather1024/Backdoor-Enhanced-Alignment)                               |
| 2024.06 | **On Prompt-Driven Safeguarding for Large Language Models (DRO)** |   arXiv    | [link](https://arxiv.org/pdf/2401.18018) |                              [link](https://github.com/chujiezheng/LLM-Safeguard)          |
| 2024.06 | **Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks (RPO)** |   arXiv    | [link](https://arxiv.org/pdf/2401.17263) |                              -          |
| 2024.06 | **Fight Back Against Jailbreaking via Prompt Adversarial Tuning (PAT)** |   arXiv    | [link](https://arxiv.org/pdf/2402.06255) |                              [link](https://github.com/rain152/PAT)          |
| 2024.05 | **Detoxifying Large Language Models via Knowledge Editing (DINM)** |   ACL'24    | [link](https://arxiv.org/pdf/2403.14472) |                              [link](https://github.com/zjunlp/EasyEdit/blob/main/examples/SafeEdit.md)          |
| 2023.11 | **MART: Improving LLM Safety with Multi-round Automatic Red-Teaming (MART)** |   ACL'24    | [link](https://arxiv.org/pdf/2311.07689) |                              -          |
| 2023.11 | **Baseline defenses for adversarial attacks against aligned language models** |   arXiv    | [link](https://arxiv.org/pdf/2308.14132) |                              -                               |
| 2023.08 | **Red-Teaming Large Language Models using Chain of Utterances for Safety-Alignment (RED-INSTRUCT)** |   arXiv    | [link](https://arxiv.org/pdf/2308.09662) |                              [link](https://github.com/declare-lab/red-instruct)                                |





























#### Strategy-based Defense

| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **SafeDecoding: Defending against Jailbreak Attacks via Safety-Aware Decoding (SafeDecoding)** |   ACL'24    | [link](https://arxiv.org/pdf/2402.08983) |                              [link](https://github.com/uw-nsl/SafeDecoding)                               |
| 2024.06 | **Defending Against Alignment-Breaking Attacks via Robustly Aligned LLM** |   arXiv    | [link](https://arxiv.org/pdf/2309.14348) |                              -                               |
| 2024.06 | **A Wolf in Sheep’s Clothing: Generalized Nested Jailbreak Prompts can Fool Large Language Models Easily (ReNeLLM)** |   NAACL'24    | [link](https://arxiv.org/abs/2311.08268) |                              [link](https://github.com/NJUNLP/ReNeLLM)                               |
| 2024.06 | **SMOOTHLLM: Defending Large Language Models Against Jailbreaking Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2310.03684) |                              [link](https://github.com/arobey1/smooth-llm)                               |
| 2024.05 | **Enhancing Large Language Models Against Inductive Instructions with Dual-critique Prompting (Dual-critique)** |   arXiv    | [link](https://arxiv.org/pdf/2305.13733) |                             [link](https://github.com/DevoAllen/INDust)                               |
| 2024.05 | **LLM Self Defense: By Self Examination, LLMs Know They Are Being Tricked** |   ICLR Tiny Paper'24    | [link](https://arxiv.org/pdf/2308.07308) |                             [link](https://github.com/poloclub/llm-self-defense)                               |
| 2024.05 | **GradSafe: Detecting Unsafe Prompts for LLMs via Safety-Critical Gradient Analysis (GradSafe)** |   ACL'24    | [link](\https://arxiv.org/pdf/2402.13494) |                             [link](https://github.com/xyq7/GradSafe)                               |
| 2024.05 | **Multilingual Jailbreak Challenges in Large Language Models** |   ICLR'24    | [link](https://arxiv.org/pdf/2310.06474)  |                              [link](https://github.com/DAMO-NLP-SG/multilingual-safety-for-LLMs)                               |
| 2024.05 | **Gradient Cuff: Detecting Jailbreak Attacks on Large Language Models by Exploring Refusal Loss Landscapes** |   arXiv    | [link](https://arxiv.org/pdf/2403.00867)  |                              -                            |
| 2024.05 | **AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2403.04783) |                             [link](https://github.com/XHMY/AutoDefense)                               |
| 2024.05 | **Bergeron: Combating adversarial attacks through a conscience-based alignment framework (Bergeron)** |   arXiv    | [link](https://arxiv.org/pdf/2312.00029) |                             [link](https://github.com/matthew-pisano/Bergeron)                               |
| 2024.05 | **Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations (ICD)** |   arXiv    | [link](https://arxiv.org/pdf/2310.06387)  |                              -                               |
| 2024.04 | **Pruning for Protection: Increasing Jailbreak Resistance in Aligned LLMs Without Fine-Tuning** |   arXiv    | [link](https://arxiv.org/pdf/2401.10862)  |                              [link](https://github.com/CrystalEye42/eval-safety)                                |
| 2024.02 | **Certifying LLM Safety against Adversarial Prompting** |   arXiv    | [link](https://arxiv.org/pdf/2309.02705) |                              [link](https://github.com/aounon/certified-llm-safety)                              |
| 2024.02 | **Break the Breakout: Reinventing LM Defense Against Jailbreak Attacks with Self-Refinement** |   arXiv    | [link](https://arxiv.org/pdf/2402.15180) |                              -                              |
| 2024.02 | **Defending large language models against jailbreak attacks via semantic smoothing (SEMANTICSMOOTH)** |   arXiv    | [link](https://arxiv.org/pdf/2402.16192) |                              [link](https://github.com/UCSB-NLP-Chang/SemanticSmooth)                             |
| 2024.01 | **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs (PAP)** |   arXiv    | [link](https://arxiv.org/pdf/2401.06373) |                              [link](https://github.com/CHATS-lab/persuasive_jailbreaker)                               |
| 2023.12 | **Defending ChatGPT against jailbreak attack via self-reminders (Self-Reminder)** |   Nature Machine Intelligence    | [link](https://xyq7.github.io/papers/NMI-JailbreakDefense.pdf) |                              [link](https://github.com/yjw1029/Self-Reminder/)                               |
| 2023.11 | **Detecting language model attacks with perplexity** |   arXiv    | [link](https://arxiv.org/pdf/2308.14132) |                              -                               |
| 2023.10 | **RAIN: Your Language Models Can Align Themselves without Finetuning (RAIN)** |   arXiv    | [link](https://arxiv.org/pdf/2309.07124) |                              [link](https://github.com/SafeAILab/RAIN)                               |























### Evaluation \& Analysis
| Time | Title                                                        |  Venue  |                            Paper                             |                             Code                             |
| ---- | ------------------------------------------------------------ | :-----: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| 2024.06 | **Bag of Tricks: Benchmarking of Jailbreak Attacks on LLMs** |   arXiv    | [link](https://arxiv.org/pdf/2406.093242) |                             [link](https://github.com/usail-hkust/Bag_of_Tricks_for_LLM_Jailbreaking)                              |
| 2024.06 | **JailbreakZoo: Survey, Landscapes, and Horizons in Jailbreaking Large Language and Vision-Language Models (JailbreakZoo)** |   arXiv    | [link](https://arxiv.org/pdf/2407.01599) |                             [link](https://github.com/Allen-piexl/JailbreakZoo)                              |
| 2024.06 | **Fundamental limitations of alignment in large language models** |   arXiv    | [link](https://arxiv.org/pdf/2304.11082) |                             -                              |
| 2024.06 | **JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models (JailbreakBench)** |   arXiv    | [link](https://arxiv.org/pdf/2404.01318) |                             [link](https://github.com/JailbreakBench/jailbreakbench)                             |
| 2024.06 | **Towards Understanding Jailbreak Attacks in LLMs: A Representation Space Analysis** |   arXiv    | [link](https://arxiv.org/pdf/2406.10794) |                             [link](https://github.com/yuplin2333/representation-space-jailbreak)                              |
| 2024.06 | **JailbreakEval: An Integrated Toolkit for Evaluating Jailbreak Attempts Against Large Language Models (JailbreakEval)** |   arXiv    | [link](https://arxiv.org/pdf/2406.09321) |                              [link](https://github.com/ThuCCSLab/JailbreakEval)                               |
| 2024.05 | **Enhancing Large Language Models Against Inductive Instructions with Dual-critique Prompting (INDust)** |   arXiv    | [link](https://arxiv.org/pdf/2305.13733) |                             [link](https://github.com/DevoAllen/INDust)                               |
| 2024.05 | **Prompt Injection attack against LLM-integrated Applications** |   arXiv    | [link](https://arxiv.org/pdf/2306.05499) |                             -                               |
| 2024.05 | **Tricking LLMs into Disobedience: Formalizing, Analyzing, and Detecting Jailbreaks** |   LREC-COLING'24    | [link](https://arxiv.org/pdf/2305.14965) |                             [link](https://github.com/AetherPrior/TrickLLM)                               |
| 2024.05 | **LLM Jailbreak Attack versus Defense Techniques--A Comprehensive Study** |   NDSS'24    | [link](https://arxiv.org/pdf/2402.13457) |                             -                               |
| 2024.05 | **Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study** |   arXiv    | [link](https://arxiv.org/pdf/2305.13860) |                             -                               |
| 2024.05 | **Detoxifying Large Language Models via Knowledge Editing (SafeEdit)** |   ACL'24    | [link](https://arxiv.org/pdf/2403.14472) |                             [link](https://github.com/zjunlp/EasyEdit/blob/main/examples/SafeEdit.md)                               |
| 2024.04 | **JailbreakLens: Visual Analysis of Jailbreak Attacks Against Large Language Models (JailbreakLens)** |   arXiv    | [link](https://arxiv.org/pdf/2404.08793) |                             -                               |
| 2024.03 | **How (un) ethical are instruction-centric responses of LLMs? Unveiling the vulnerabilities of safety guardrails to harmful queries (TECHHAZARDQA)** |   arXiv    | [link](https://arxiv.org/pdf/2402.15302) |                              [link](https://huggingface.co/datasets/SoftMINER-Group/TechHazardQA)                               |
| 2024.03 | **EasyJailbreak: A Unified Framework for Jailbreaking Large Language Models (EasyJailbreak)** |   arXiv    | [link](https://arxiv.org/pdf/2403.12171) |                              [link](https://github.com/EasyJailbreak/EasyJailbreak)                               |
| 2024.02 | **SPML: A DSL for Defending Language Models Against Prompt Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2402.11755) |                             -                     |
| 2024.02 | **Coercing LLMs to do and reveal (almost) anything** |   arXiv    | [link](https://arxiv.org/pdf/2402.14020) |                             -                     |
| 2024.02 | **A STRONGREJECT for Empty Jailbreaks (StrongREJECT)** |   arXiv    | [link](https://arxiv.org/pdf/2402.10260) |                             [link](https://github.com/alexandrasouly/strongreject)                      |
| 2024.02 | **ToolSword: Unveiling Safety Issues of Large Language Models in Tool Learning Across Three Stages** |   ACL'24    | [link](https://arxiv.org/pdf/2402.10753) |                             [link](https://github.com/Junjie-Ye/ToolSword)                      |
| 2024.02 | **HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal (HarmBench)** |   arXiv    | [link](https://arxiv.org/pdf/2402.04249) |                              [link](https://github.com/centerforaisafety/HarmBench)                               |
| 2023.12 | **Goal-Oriented Prompt Attack and Safety Evaluation for LLMs** |   arXiv    | [link](https://arxiv.org/pdf/2309.11830)  |                             [link](https://github.com/liuchengyuan123/CPAD)                              |
| 2023.12 | **The Art of Defending: A Systematic Evaluation and Analysis of LLM Defense Strategies on Safety and Over-Defensiveness** |   arXiv    | [link](https://arxiv.org/pdf/2401.00287)  |                            -                              |
| 2023.11 | **Summon a Demon and Bind it: A Grounded Theory of LLM Red Teaming in the Wild** |   arXiv    | [link](https://arxiv.org/pdf/2311.06237)  |                             -                               |
| 2023.11 | **Exploiting Large Language Models (LLMs) through Deception Techniques and Persuasion Principles** |   arXiv    | [link](https://arxiv.org/pdf/2311.14876)  |                             -                               |
| 2023.10 | **Explore, establish, exploit: Red teaming language models from scratch** |   arXiv    | [link](https://arxiv.org/pdf/2306.09442)  |                             -                               |
| 2023.08 | **Red-Teaming Large Language Models using Chain of Utterances for Safety-Alignment (RED-EVAL)** |   arXiv    | [link](https://arxiv.org/pdf/2308.09662) |                              [link](https://github.com/declare-lab/red-instruct)                                |
| 2023.07 | **Jailbroken: How Does LLM Safety Training Fail? (Jailbroken)** |   NeurIPS'23    | [link](https://arxiv.org/pdf/2307.02483#page=1.01)  |                             -                               |
| 2023.08 | **Use of LLMs for Illicit Purposes: Threats, Prevention Measures, and Vulnerabilities** |   arXiv    | [link](https://arxiv.org/pdf/2308.12833)  |                              -                               |
| 2023.08 | **From chatgpt to threatgpt: Impact of generative ai in cybersecurity and privacy** |   IEEE Access    | [link](https://ieeexplore.ieee.org/document/10198233?denied=)  |                              -                               |
| 2023.07 | **Llm censorship: A machine learning challenge or a computer security problem?** |   arXiv    | [link](https://arxiv.org/pdf/2307.10719)  |                              -                               |
| 2023.07 | **Universal and Transferable Adversarial Attacks on Aligned Language Models (AdvBench)** |   arXiv    | [link](https://arxiv.org/pdf/2307.15043)  |                              [link](https://github.com/llm-attacks/llm-attacks)                               |
| 2023.06 | **DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models** |   arXiv    | [link](https://blogs.qub.ac.uk/digitallearning/wp-content/uploads/sites/332/2024/01/A-comprehensive-Assessment-of-Trustworthiness-in-GPT-Models.pdf)  |                              [link](https://decodingtrust.github.io/)                               |
| 2023.04 | **Safety Assessment of Chinese Large Language Models** |   arXiv    | [link](https://arxiv.org/pdf/2304.10436)  |                              [link](https://github.com/thu-coai/Safety-Prompts)                              |
| 2023.02 | **Exploiting Programmatic Behavior of LLMs: Dual-Use Through Standard Security Attacks** |   arXiv    | [link](https://arxiv.org/pdf/2302.05733)  |                              -                               |
| 2022.11 | **Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned** |   arXiv    | [link](https://arxiv.org/pdf/2209.07858)  |                              -                               |
| 2022.02 | **Red Teaming Language Models with Language Models** |   arXiv    | [link](https://arxiv.org/pdf/2202.03286)  |                              -                               |











## Contributors

<a href="https://github.com/yueliu1999" target="_blank"><img src="https://avatars.githubusercontent.com/u/41297969?s=64&v=4" alt="yueliu1999" width="96" height="96"/></a> 
<a href="https://github.com/bhooi" target="_blank"><img src="https://avatars.githubusercontent.com/u/733939?v=4" alt="bhooi" width="96" height="96"/></a> 


<p align="right">(<a href="#top">back to top</a>)</p>






















