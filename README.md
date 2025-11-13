# awesome-ai-security

*A collection of awesome AI Security, LLM Security, and Prompt Injection tools and resources.*

- [About](#about)
- [AI Security Testing Tools](#ai-security-testing-tools)
- [Prompt Injection Resources](#prompt-injection-resources)
- [Jailbreak Detection & Red Teaming](#jailbreak-detection--red-teaming)
- [Deliberately Vulnerable AI Applications](#deliberately-vulnerable-ai-applications)
- [Training, Labs & CTF Challenges](#training-labs--ctf-challenges)
- [Books & Publications](#books--publications)
- [Cheatsheets & Guides](#cheatsheets--guides)
- [Frameworks & Standards](#frameworks--standards)
- [Defense & Guardrails](#defense--guardrails)
- [Certifications & Courses](#certifications--courses)
- [Conferences & Events](#conferences--events)
- [Research Papers & Datasets](#research-papers--datasets)
- [Observability & Monitoring](#observability--monitoring)
- [Penetration Testing Tools](#penetration-testing-tools)
- [Awesome Lists](#awesome-lists)
- [Podcasts & Newsletters](#podcasts--newsletters)
- [Other Resources](#other-resources)
- [Thought Leaders](#thought-leaders)
- [Contributions](#contributions)
- [License](#license)

---

## About

The **awesome-ai-security** repository is a community-driven collection of AI Security, LLM Security, and Prompt Injection tools and resources. The focus is on open-source tools and resources that benefit the community.

This repository covers:
- Large Language Model (LLM) security testing and vulnerability assessment
- Prompt injection attacks and defenses
- AI red teaming and adversarial testing
- Jailbreak detection and prevention
- Model poisoning and extraction attacks
- Hallucination detection and prevention
- AI application security best practices
- MLSecOps and LLMOps security

Please read the [Contributions](#contributions) section before opening a pull request.

---

## AI Security Testing Tools

| Name | Author | Description |
| ---- | ------ | ----------- |
| [garak](https://github.com/NVIDIA/garak) | [NVIDIA](https://github.com/NVIDIA) | LLM vulnerability scanner – tests for 120+ categories including hallucination, data leakage, prompt injection, misinformation, toxicity, and jailbreaks. |
| [PyRIT](https://github.com/Azure/PyRIT) | [Microsoft](https://github.com/Azure) | Python Risk Identification Tool for generative AI – used for adversarial testing of GenAI systems. |
| [promptmap](https://github.com/utkusen/promptmap) | [utkusen](https://github.com/utkusen) | Automated prompt injection scanner for custom LLM applications with support for white-box testing. |
| [aiapwn](https://github.com/karimhabush/aiapwn) | [karimhabush](https://github.com/karimhabush) | Automatic prompt injection testing tool that generates custom payloads based on AI behavior. |
| [FuzzyAI](https://github.com/cyberark/FuzzyAI) | [CyberArk](https://github.com/cyberark) | Automated LLM fuzzing framework that helps identify jailbreaks and security vulnerabilities. |
| [LLMFuzzer](https://github.com/mnns/LLMFuzzer) | [mnns](https://github.com/mnns) | Open-source fuzzing framework specifically designed for LLM API integrations. |
| [promptfoo](https://www.promptfoo.dev) | promptfoo | Dynamic LLM testing with adversarial probes that generate context-aware test cases. |
| [LLM Warden](https://github.com/jackhhao/llm-warden) | [jackhhao](https://github.com/jackhhao) | Simple jailbreak detection tool with a fine-tuned model on Hugging Face. |
| [Vigil](https://github.com/deadbits/vigil) | [deadbits](https://github.com/deadbits) | Python library and REST API for LLM security with modular scanners using vector databases, YARA heuristics, and transformer models. |
| **New:** [picklescan](https://github.com/mmaitre314/picklescan) | [mmaitre314](https://github.com/mmaitre314) | Security scanner for malicious code in Python pickle model files; useful for model serialization threats. |
| **New:** [ModelScan](https://github.com/protectai/modelscan) | [Protect AI](https://github.com/protectai) | ML model scanner that checks model files for unsafe code across multiple formats (pickle, SavedModel, etc.). |
| **New:** [Open-Prompt-Injection](https://github.com/liu00222/Open-Prompt-Injection) | Yupei Liu et al. | Toolkit and benchmark for evaluating prompt injection attacks and defenses (from a USENIX Security paper). |

---

## Prompt Injection Resources

| Name | Author | Description |
| ---- | ------ | ----------- |
| [PayloadsAllTheThings – Prompt Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Prompt%20Injection/README.md) | [swisskyrepo](https://github.com/swisskyrepo) | Comprehensive collection of prompt injection payloads, including bypasses for various LLM security controls. |
| [PIPE – Prompt Injection Primer](https://github.com/jthack/PIPE) | [jthack](https://github.com/jthack) | Educational prompt injection resource with attack scenarios and payloads for engineers. |
| [Basic-ML-prompt-injections](https://github.com/Zierax/Basic-ML-prompt-injections) | [Zierax](https://github.com/Zierax) | LLM attack payloads for educational purposes. |
| [OWASP Prompt Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Best practices for preventing prompt injection with input validation and sanitization techniques. |

---

## Jailbreak Detection & Red Teaming

| Name | Author | Description |
| ---- | ------ | ----------- |
| [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | [IBM / LF AI](https://github.com/Trusted-AI) | Python library for ML security defending against evasion, poisoning, extraction, and inference attacks. |
| [HEART](https://github.com/IBM/heart-library) | [IBM](https://github.com/IBM) | Hardened extension of ART supporting test & evaluation workflows for adversarial AI vulnerability assessment. |
| [Rebuff](https://github.com/protectai/rebuff) | [Protect AI](https://github.com/protectai) | Self-hardening prompt injection detector with a multi-layered defense approach. |
| [Plexiglass](https://github.com/invariantlabs/plexiglass) | [Invariant Labs](https://github.com/invariantlabs) | Security toolbox for testing and safeguarding LLMs (CLI tool to detect vulnerabilities in agent systems). |
| [PurpleLlama](https://github.com/meta-llama/PurpleLlama) | [Meta](https://github.com/meta-llama) | Set of tools to assess and improve LLM security (Llama Guard, CyberSecEval, etc.). |

---

## Deliberately Vulnerable AI Applications

| Name | Author | Description |
| ---- | ------ | ----------- |
| [AI Goat](https://github.com/dhammon/ai-goat) | [dhammon](https://github.com/dhammon) | Learn AI security through vulnerable LLM CTF challenges that run locally with no cloud fees or sign-ups required. |
| [Gandalf](https://gandalf.lakera.ai/) | [Lakera](https://www.lakera.ai/) | AI prompt injection game with multiple levels of increasing difficulty. |
| [LLM Security CTF](https://github.com/TrustAI-laboratory/LLM-Security-CTF) | [TrustAI-laboratory](https://github.com/TrustAI-laboratory) | Series of free, web-based vulnerable LLM CTF challenges. |
| [DamnVulnerableLLMProject](https://github.com/harishsg993010/DamnVulnerableLLMProject) | [harishsg993010](https://github.com/harishsg993010) | Deliberately vulnerable LLM application designed for security training and education. |
| [Damn Vulnerable LLM Agent](https://labs.withsecure.com/tools/damn-vulnerable-llm-agent) | [WithSecure Labs](https://labs.withsecure.com/) | Teaches thought/action/observation injection, focusing on agentic LLM systems. |

---

## Training, Labs & CTF Challenges

| Organization | Name | Description |
| ------------ | ---- | ----------- |
| SANS Institute | [SEC545: GenAI and LLM Application Security](https://www.sans.org/cyber-security-courses/genai-llm-application-security/) | Comprehensive GenAI security course with hands-on labs. |
| SANS Institute | [SEC495: Leveraging LLMs – Building & Securing RAG](https://www.sans.org/cyber-security-courses/leveraging-llms-building-securing-rag/) | Hands-on course on securing Retrieval-Augmented Generation applications. |
| SANS Institute | [SEC411: AI Security Principles and Practices](https://www.sans.org/cyber-security-courses/ai-security-principles-practices/) | Docker-based hands-on labs for AI security fundamentals. |
| AppSecEngineer | [AI Combat & Construct](https://www.appsecengineer.com/) | Interactive labs for attacking and defending AI/LLM applications. |
| Practical DevSecOps | [Certified AI Security Professional (CAISP)](https://www.practical-devsecops.com/certified-ai-security-professional/) | 60 days of browser-based labs with 30+ guided exercises and MITRE ATLAS defenses. |
| HackAPrompt | [HackAPrompt 1.0](https://www.hackaprompt.com/) | Prompt hacking competition; results published as the EMNLP 2023 paper “Ignore This Title and HackAPrompt.” |
| HackAPrompt | [HackAPrompt 2.0](https://www.hackaprompt.com/) | Large-scale AI red-teaming hackathon with multi-specialization challenges. |
| AI Village | [DEF CON AI CTF](https://www.kaggle.com/competitions/ai-village-ctf) | Annual LLM security competition at DEF CON. |

---

## Books & Publications

| Author(s) | Publisher | Name | Description |
| ----------- | --------- | -----| ----------- |
| Various (eds. Kucharavy et al.) | Springer | [Large Language Models in Cybersecurity: Threats, Exposure and Mitigation](https://link.springer.com/book/10.1007/978-3-031-54827-7) | Open-access guide to LLM security risks, attacker techniques, and mitigation strategies (2024). |
| Various | Springer | [Generative AI Security: Theories and Practices](https://link.springer.com/book/10.1007/978-981-97-5443-8) | Explores GenAI impacts on data, model, and application security (2024). |
| Various | Springer | [AI-Driven Cybersecurity and Threat Intelligence](https://link.springer.com/book/10.1007/978-3-031-15030-2) | Examines how AI intersects with cybersecurity and intelligent decision-making (2024). |
| Steve Wilson | O’Reilly | [The Developer’s Playbook for Large Language Model Security](https://www.amazon.com/Developers-Playbook-Large-Language-Security/dp/109816220X) | Practical guide aligned with OWASP LLM Top 10; covers prompt injection, data poisoning, and defenses (2024). |
| John Sotiropoulos | Packt | [Adversarial AI Attacks, Mitigations, and Defense Strategies](https://www.packtpub.com/product/adversarial-ai-attacks-mitigations-and-defense-strategies-9781835087985) | Hands-on guide covering adversarial attacks and defenses, MLSecOps, and threat modeling (2024). |

---

## Cheatsheets & Guides

| Name | Author | Description |
| ---- | ------ | ----------- |
| [OWASP LLM Prompt Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Best practices for preventing prompt injection with input validation, output filtering, and context separation. |
| [LangChain Security Policy](https://python.langchain.com/docs/security/) | [LangChain](https://www.langchain.com/) | Security best practices for LangChain applications, including the “Four Perimeters” framework. |
| [AI Security Best Practices](https://www.cisa.gov/ai) | [CISA](https://www.cisa.gov/) | Government guidelines for securing AI systems and data. |

---

## Frameworks & Standards

| Name | Organization | Description |
| ---- | ------------ | ----------- |
| [OWASP Top 10 for LLM Applications 2025](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | [OWASP](https://owasp.org) | Top 10 security risks for LLM applications (LLM01–LLM10). Includes prompt injection and data/model poisoning. |
| [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | [NIST](https://www.nist.gov/) | Voluntary framework with four functions: Govern, Map, Measure, Manage. Includes a Generative AI Profile (2024). |
| [MITRE ATLAS](https://atlas.mitre.org/) | [MITRE](https://www.mitre.org/) | Adversarial Threat Landscape for AI Systems with tactics and techniques (modeled after MITRE ATT&CK). |
| [CISA AI Security Guidelines](https://www.cisa.gov/ai) | [CISA](https://www.cisa.gov/) | Joint guidance (with NSA, FBI, and Five Eyes partners) for securing AI/ML systems. |

---

## Defense & Guardrails

| Name | Author | Description |
| ---- | ------ | ----------- |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | [NVIDIA](https://github.com/NVIDIA) | Toolkit for programmable guardrails with Input, Output, Dialog, Retrieval, and Execution controls. Works with multiple LLMs. |
| [LLM Guard](https://llm-guard.com/) | [Protect AI](https://protectai.com/) | Runtime scanning with input/output filters for PII detection, redaction, and content filtering. |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | [Guardrails AI](https://www.guardrailsai.com/) | Python framework for LLM guardrails with validation rules and structured output enforcement. |
| [Lakera Guard](https://www.lakera.ai/) | [Lakera](https://www.lakera.ai/) | Real-time GenAI security with prompt injection and jailbreak detection. |
| **New:** [CodeGate](https://codegate.ai/) | [Stacklok](https://stacklok.com/) | Open-source security proxy for coding assistants; filters prompts and responses to prevent key leakage and insecure suggestions. |

---

## Certifications & Courses

| Organization | Name | Description |
| ------------ | ---- | ----------- |
| ISACA | [AAISM™ (Certified AI Security Manager)](https://www.isaca.org/credentialing/aaism) | AI Security Management certification requiring an active CISM or CISSP. |
| ISC2 | [Building AI Strategy Certificate](https://www.isc2.org/) | Courses covering AI security strategy, trustworthy AI, governance, and risk management. |
| Practical DevSecOps | [Certified AI Security Professional (CAISP)](https://www.practical-devsecops.com/certified-ai-security-professional/) | Hands-on AI security certification with browser-based labs. |
| Securiti | [AI Security & Governance Certification](https://education.securiti.ai/certifications/ai-governance/) | Focus on AI governance, privacy, and compliance. |

---

## Conferences & Events

| Name | Description |
| ---- | ----------- |
| [DEF CON](https://defcon.org/) | World’s largest hacker conference with an AI Village hosting GenAI red team challenges. Las Vegas, annually. |
| [Black Hat USA](https://www.blackhat.com/) | Premier security conference with AI Security Summit and trainings. Las Vegas, annually. |
| [RSA Conference](https://www.rsaconference.com/) | Large cybersecurity event with AI security tracks and vendors. San Francisco, annually. |
| [AI Village](https://aivillage.org/) | DEF CON’s AI-focused community village organizing the Generative Red Team Challenge and public LLM hacking events. |

---

## Research Papers & Datasets

| Name | Topic | Description |
| ---- | ----- | ----------- |
| [Ignore This Title and HackAPrompt](https://arxiv.org/abs/2311.16119) (EMNLP 2023) | Prompt Injection | Analysis of adversarial prompts from HackAPrompt; introduces a taxonomy of prompt hacking techniques. |
| [SelfCheckGPT](https://arxiv.org/abs/2303.08896) | Hallucination Detection | Zero-resource black-box hallucination detection using sampling-based consistency checking. |
| Survey on Model Extraction Attacks (2025) | Model Security | Survey of model extraction attacks and defenses for LLM APIs and hosted models. |
| [SECURE Benchmark](https://arxiv.org/abs/2405.20441) | Cybersecurity | Benchmark suite with multiple datasets to assess LLM performance on security tasks. |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA) | Safety | Dataset for evaluating truthful response generation on diverse questions. |
| [ToxiGen](https://github.com/microsoft/TOXIGEN) | Safety | Dataset for hate speech detection and toxic vs. benign classification. |

---

## Observability & Monitoring

| Name | Author | Description |
| ---- | ------ | ----------- |
| [LangSmith](https://www.langchain.com/langsmith) | [LangChain](https://www.langchain.com/) | Span-based tracing for LLM apps; lifecycle observability for prompts, responses, and evals. |
| [Weights & Biases (W&B) – LLM Ops](https://wandb.ai/site/llmops) | [Weights & Biases](https://wandb.ai/) | Experiment tracking for GenAI with prompt versioning, dataset logging, and feedback integration. |
| [Langfuse](https://langfuse.com/) | [Langfuse](https://langfuse.com/) | Open-source LLM observability: tracing, user feedback logging, and cost monitoring. |
| [Phoenix](https://phoenix.arize.com/) | [Arize AI](https://arize.com/) | Open-source evaluation and monitoring to analyze outputs and detect failure modes. |
| [Helicone](https://www.helicone.ai/) | [Helicone](https://www.helicone.ai/) | Logging, analytics dashboards, and cost tracking for LLM APIs via proxy. |

---

## Penetration Testing Tools

| Name | Author | Description |
| ---- | ------ | ----------- |
| [PentestGPT](https://github.com/GreyDGL/PentestGPT) | [GreyDGL](https://github.com/GreyDGL) | GPT-powered penetration testing assistant; automates recon and scanning via an interactive agent. |
| [AI-penetration-testing](https://github.com/Mr-Infect/AI-penetration-testing) | [Mr-Infect](https://github.com/Mr-Infect) | Curated offensive and defensive AI pentesting techniques; scripts for prompt injection and model abuse. |
| [PentAGI](https://github.com/vxcontrol/pentagi) | [vxcontrol](https://github.com/vxcontrol) | Autonomous AI agent system for pentesting; integrates many tools with validation utilities. |
| [AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) | [antoninoLorenzo](https://github.com/antoninoLorenzo) | LLM-based assistant for exploit development and vulnerability research. |
| [HackSynth](https://github.com/aielte-research/HackSynth) | [aielte-research](https://github.com/aielte-research) | LLM agent for autonomous pentesting with planner and summarizer modules. |
| [HexStrike AI MCP](https://github.com/0x4m4/hexstrike-ai) | [0x4m4](https://github.com/0x4m4) | Framework combining 150+ security tools with AI agents for automation. |
| **New:** [Strix](https://github.com/usestrix/strix) | [usestrix](https://usestrix.com/) | Autonomous “AI hacker” agents that run code, find vulnerabilities, and validate exploits; CLI and CI/CD integrations. |

---

## Awesome Lists

| Name | Author | Description |
| ---- | ------ | ----------- |
| [awesome-llm-security](https://github.com/corca-ai/awesome-llm-security) | [corca-ai](https://github.com/corca-ai) | Comprehensive curation of LLM Security tools, documents, and projects. |
| [awesome-gpt-security](https://github.com/cckuailong/awesome-gpt-security) | [cckuailong](https://github.com/cckuailong) | Curated list of security tools and experimental projects for LLM/GPT applications. |
| [awesome-llm-cybersecurity-tools](https://github.com/tenable/awesome-llm-cybersecurity-tools) | [Tenable](https://github.com/tenable) | Tenable’s collection of LLM-based tools for cybersecurity research and operations. |
| [Awesome-LLMSecOps](https://github.com/wearetyomsmnv/Awesome-LLMSecOps) | [wearetyomsmnv](https://github.com/wearetyomsmnv) | Resources on LLM Security Operations lifecycle, threats, and defenses. |
| [awesome-llm-supply-chain-security](https://github.com/ShenaoW/awesome-llm-supply-chain-security) | [ShenaoW](https://github.com/ShenaoW) | Resources about LLM supply chain security including model backdoors, trojans, and related CVEs. |
| [awesome-MLSecOps](https://github.com/RiccardoBiosas/awesome-MLSecOps) | [RiccardoBiosas](https://github.com/RiccardoBiosas) | Curated list of Machine Learning Security Operations tools, articles, and best practices. |
| [awesome-hallucination-detection](https://github.com/EdinburghNLP/awesome-hallucination-detection) | [EdinburghNLP](https://github.com/EdinburghNLP) | Collection of academic papers on hallucination detection in LLMs. |

---

## Podcasts & Newsletters

| Name | Host/Author | Description |
| ---- | ----------- | ----------- |
| [AI Security Podcast](https://www.aisecuritypodcast.com/) | Ashish Rajan & Caleb Sima | Vendor-neutral bi-weekly podcast on AI security topics, threats, and best practices. |
| [The AI Fix Podcast](https://theaifix.com/) | Graham Cluley & Mark Stockley | Coverage of deepfakes, misuse of AI, policy, and cybersecurity implications. |
| [Smashing Security](https://www.smashingsecurity.com/) | Graham Cluley & Carole Theriault | Weekly infosec podcast that often discusses AI security, privacy, and current threats. |
| [Resilient Cyber Newsletter](https://resilientcyber.io/) | Chris Hughes | Newsletter on AI security, software supply chain, cloud security, and AppSec. |

---

## Other Resources

| Name | Author | Description |
| ---- | ------ | ----------- |
| [Rez0’s AI Security Blog](https://josephthacker.com/) | Joseph Thacker | AI hacking fundamentals, techniques, and mindset. Includes guides on hacking AI apps. |
| [Simon Willison’s Blog](https://simonwillison.net) | Simon Willison | Expert insights on prompt injection attacks and AI agent vulnerabilities (e.g., “lethal trifecta”). |
| [Lakera AI Blog](https://www.lakera.ai/blog) | Lakera Team | Thought leadership on GenAI security, prompt attack trends, and defense techniques. |
| [Anthropic Transparency Hub](https://www.anthropic.com/transparency) | Anthropic | Model system cards and red-team findings for Anthropic models. |
| [OpenAI Red Teaming Network](https://openai.com/red-teaming-network/) | OpenAI | Red teaming documentation and system cards. |
| [MLSecOps Community](https://mlsecops.com/) | Community | Resources and best practices for Machine Learning Security Operations. |

---

## Thought Leaders

| Name | Platform | Notability |
| ---- | -------- | ----------- |
| Simon Willison | [Twitter/X](https://twitter.com/simonw) / Blog | Co-creator of Django & Datasette; early expert on prompt injection and AI agent security. |
| Joseph Thacker (rez0) | [Twitter/X](https://twitter.com/rez0__) / Blog | Principal AI Engineer at AppOmni; prolific AI vulnerability research and education. |
| Lakera Team | [Twitter/X](https://twitter.com/lakeraai) | Creators of Gandalf and Lakera Guard; frequent conference speakers on GenAI security. |
| NVIDIA AI Red Team | [Twitter/X](https://twitter.com/NVIDIAAIDev) | Team behind garak; research and tooling for LLM security. |
| Microsoft AI Red Team | [Twitter/X](https://twitter.com/MSFTSecurity) | Pioneers in AI red teaming; creators of PyRIT and public guidance on GenAI testing. |

---

## Contributions

1. **Repository Purpose:** Collect AI Security, LLM Security, and Prompt Injection tools and resources. Preference for open-source/community editions, Creative Commons resources, and community-created content.
2. **Out of Scope:** Vendor-specific ads, closed-source/proprietary products, free trials/freemium services, or anything requiring private details.
3. **Relevance:** Must be directly related to AI security, LLM security, prompt injection, jailbreaking, model security, AI red teaming, or AI application security.
4. **Duplicates:** Avoid duplicates or entries that don’t add value beyond existing content.
5. **Thought Leaders:** Prefer individuals tied to tools/content already present here; additions should be well-known contributors.
6. **Content Accuracy:** If you’re an author and see inaccuracies, please open an issue or PR to update.
7. **Book Exceptions:** Paid books are allowed due to educational value.

**How to contribute:**
- Fork the repo and create a new branch.
- Edit `README.md` with your changes.
- Open a pull request with a clear description.

More details: GitHub’s [Quickstart: Contributing to Projects](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright
and related or neighboring rights to this work.
