<div id="top"></div>

<p align="center">
  <img src="banner_.svg" width="100%" alt="Awesome AI Security banner">
</p>

<h1 align="center">Awesome AI Security</h1>

<p align="center">
  🔐🤖 A curated list of AI/LLM security tools, frameworks, guides, papers, and training — focused on open-source and community resources.
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg" alt="CC0 License"></a>
  <a href="https://github.com/brinhosa/awesome-ai-security/stargazers"><img src="https://img.shields.io/github/stars/brinhosa/awesome-ai-security?style=social" alt="GitHub stars"></a>
  <a href="https://github.com/brinhosa/awesome-ai-security/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <img src="https://img.shields.io/github/last-commit/brinhosa/awesome-ai-security?logo=github" alt="Last Commit">
</p>

<div align="center">
  <a href="#about">ℹ️ About</a> •
  <a href="#-ai-security-testing-tools">🧪 Testing Tools</a> •
  <a href="#-prompt-injection-resources">🧨 Prompt Injection</a> •
  <a href="#-jailbreak-detection--red-teaming">🕵️ Jailbreak & Red Team</a> •
  <a href="#-deliberately-vulnerable-ai-applications">🧩 DV AIs</a> •
  <a href="#-training-labs--ctf-challenges">🎓 Training & CTF</a> •
  <a href="#-books--publications">📚 Books</a> •
  <a href="#-cheatsheets--guides">📎 Cheatsheets</a> •
  <a href="#-frameworks--standards">🧭 Frameworks</a> •
  <a href="#-defense--guardrails">🛡️ Guardrails</a> •
  <a href="#-certifications--courses">🎓 Certs</a> •
  <a href="#-conferences--events">🎤 Events</a> •
  <a href="#-research-papers--datasets">📄 Papers</a> •
  <a href="#-observability--monitoring">📈 Observability</a> •
  <a href="#-penetration-testing-tools">🗡️ Pentest</a> •
  <a href="#-mcp-security">🔐 MCP Security</a> •
  <a href="#-awesome-lists">⭐ Awesome Lists</a> •
  <a href="#-podcasts--newsletters">📰 Pods & News</a> •
  <a href="#-youtube-channels">📺 YouTube</a> •
  <a href="#-other-resources">🧰 Other</a> •
  <a href="#-thought-leaders">👤 Thought Leaders</a> •
  <a href="#contributions">🤝 Contribute</a>
</div>

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
- Model Context Protocol (MCP) security
- AI supply chain security

> 📌 Please read the [Contributions](#contributions) section before opening a pull request.

---

## 🧪 AI Security Testing Tools
| Name | Author | Description |
| ---- | ------ | ----------- |
| [garak](https://github.com/NVIDIA/garak) | [NVIDIA](https://github.com/NVIDIA) | LLM vulnerability scanner – tests 120+ categories (hallucination, data leakage, prompt injection, misinformation, toxicity, jailbreaks). |
| [PyRIT](https://github.com/Azure/PyRIT) | [Microsoft](https://github.com/Azure) | Python Risk Identification Tool for GenAI; adversarial testing automation with multi-turn orchestration. |
| [promptmap](https://github.com/utkusen/promptmap) | [utkusen](https://github.com/utkusen) | Automated prompt injection scanner with white-box testing. |
| [aiapwn](https://github.com/karimhabush/aiapwn) | [karimhabush](https://github.com/karimhabush) | Automatic prompt injection testing with tailored payload generation. |
| [FuzzyAI](https://github.com/cyberark/FuzzyAI) | [CyberArk](https://github.com/cyberark) | LLM fuzzing framework to identify jailbreaks and vulns. |
| [LLMFuzzer](https://github.com/mnns/LLMFuzzer) | [mnns](https://github.com/mnns) | Fuzzing framework for LLM API integrations. |
| [promptfoo](https://www.promptfoo.dev) | promptfoo | Dynamic adversarial probes, context-aware test cases, and MCP testing capabilities. |
| [LLM Warden](https://github.com/jackhhao/llm-warden) | [jackhhao](https://github.com/jackhhao) | Simple jailbreak detection (Hugging Face model). |
| [Vigil](https://github.com/deadbits/vigil-llm) | [deadbits](https://github.com/deadbits) | Modular scanners (vectors, YARA, transformers) via lib & REST API. |
| [picklescan](https://github.com/mmaitre314/picklescan) | [mmaitre314](https://github.com/mmaitre314) | Detects malicious code in Python pickle model files. |
| [ModelScan](https://github.com/protectai/modelscan) | [Protect AI](https://github.com/protectai) | Multi-format ML model file scanner (pickle, SavedModel, etc.). |
| [Open-Prompt-Injection](https://github.com/liu00222/Open-Prompt-Injection) | Yupei Liu et al. | Toolkit/benchmark for prompt injection attacks/defenses. |
| **New:** [CAI (Cybersecurity AI)](https://github.com/GangGreenTemperTatum/cai) | [GangGreenTemperTatum](https://github.com/GangGreenTemperTatum) | Open-source framework for AI-powered offensive/defensive security with 300+ models, built-in guardrails, and battle-tested in CTFs. |
| **New:** [ARTKIT](https://github.com/BCG-X-Official/artkit) | [BCG-X](https://github.com/BCG-X-Official) | Open-source framework for automated LLM red-teaming with multi-turn attacker-target interactions. |
| **New:** [Giskard](https://github.com/Giskard-AI/giskard) | [Giskard AI](https://github.com/Giskard-AI) | Advanced automated red-teaming platform with 50+ specialized probes and adaptive attack engine. |
| **New:** [Mindgard](https://mindgard.ai/) | [Mindgard](https://mindgard.ai/) | DAST-AI platform for automated red teaming across the AI lifecycle with artifact scanning. |
| **New:** [CodeGate](https://codegate.ai/) | [Stacklok](https://www.stacklok.com/) | Security proxy for LLMs and IDEs that filters input/output to prevent API key leakage and insecure code. |
| **New:** [AIJack](https://github.com/Koukyosyumei/AIJack) | [Koukyosyumei](https://github.com/Koukyosyumei) | Open-source simulator for modeling security and privacy threats targeting ML systems. |
| **New:** [Strix](https://github.com/usestrix/strix) | [usestrix](https://usestrix.com/) | "AI hacker" agents for CLI & CI/CD with automated security testing. |

---

## 🧨 Prompt Injection Resources
| Name | Author | Description |
| ---- | ------ | ----------- |
| [PayloadsAllTheThings – Prompt Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Prompt%20Injection/README.md) | [swisskyrepo](https://github.com/swisskyrepo) | Prompt injection payloads and bypasses. |
| [PIPE – Prompt Injection Primer](https://github.com/jthack/PIPE) | [jthack](https://github.com/jthack) | Attack scenarios and payloads for engineers. |
| [Basic-ML-prompt-injections](https://github.com/Zierax/Basic-ML-prompt-injections) | [Zierax](https://github.com/Zierax) | Educational payloads. |
| [OWASP LLM Prompt Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Prevention cheat sheet and best practices. |
| **New:** [Prompt Security](https://promptsecurity.com/) | [Prompt Security](https://promptsecurity.com/) | Runtime protection for AI apps with prompt injection filtering and attack detection. |
| **New:** [NeuralTrust AI Guide](https://neuraltrust.ai/) | [NeuralTrust](https://neuraltrust.ai/) | Comprehensive guide to implementing prompt injection detection with real-time alerting. |
| **New:** [Microsoft AI Prompt Shields](https://developer.microsoft.com/en-us/microsoft-365/blogs/securing-ai-prompt-shields/) | [Microsoft](https://www.microsoft.com/) | AI Prompt Shields for defending against direct and indirect prompt injection in MCP. |
| **New:** [OpenAI Prompt Injection Detection](https://openai.github.io/guardrails-python/) | [OpenAI](https://openai.com/) | Guardrails for detecting prompt injection in function calls and outputs. |

---

## 🕵️ Jailbreak Detection & Red Teaming
| Name | Author | Description |
| ---- | ------ | ----------- |
| [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | [IBM / LF AI](https://github.com/Trusted-AI) | Defenses against evasion, poisoning, extraction, inference attacks with 39 attack modules and 29 defense modules. |
| [HEART](https://github.com/IBM/heart-library) | [IBM](https://github.com/IBM) | Hardened ART extension for T&E workflows. |
| [Rebuff](https://github.com/protectai/rebuff) | [Protect AI](https://github.com/protectai) | Self-hardening prompt injection detector (multi-layer). |
| [PurpleLlama](https://github.com/meta-llama/PurpleLlama) | [Meta](https://github.com/meta-llama) | Llama Guard, CyberSecEval, and more. |
| **New:** [HarmBench](https://github.com/centerforaisafety/HarmBench) | [Center for AI Safety](https://www.safe.ai/) | Standardized evaluation framework for automated red teaming with 18 methods comparison. |
| **New:** [AutoRedTeamer](https://github.com/autoredteam/AutoRedTeamer) | [AutoRedTeam](https://github.com/autoredteam) | Autonomous red teaming with lifelong attack integration and memory-guided selection. |
| **New:** [MAD-MAX](https://github.com/madmax-ai/madmax) | [MAD-MAX](https://github.com/madmax-ai) | Modular and Diverse Malicious Attack Mixtures for automated LLM red teaming. |
| **New:** [UDora](https://github.com/udora-ai/UDora) | [UDora AI](https://github.com/udora-ai) | Unified red teaming framework for LLM agents that dynamically hijacks their reasoning. |
| **New:** [Splx AI](https://splx.ai/) | [Splx AI](https://splx.ai/) | Commercial platform for multi-modal AI red teaming with CI/CD integration. |
| **New:** [Lasso MCP Gateway](https://github.com/lasso-security/mcp-gateway) | [Lasso Security](https://lasso.security/) | Open-source MCP Gateway for Model Context Protocol security testing. |

---

## 🧩 Deliberately Vulnerable AI Applications
| Name | Author | Description |
| ---- | ------ | ----------- |
| [AI Goat](https://github.com/dhammon/ai-goat) | [dhammon](https://github.com/dhammon) | Local LLM CTF challenges; no fees/sign-ups. |
| [Gandalf](https://gandalf.lakera.ai/) | [Lakera](https://www.lakera.ai/) | Prompt injection game with difficulty levels (world's largest red team experiment). |
| [LLM Security CTF](https://github.com/TrustAI-laboratory/LLM-Security-CTF) | [TrustAI-laboratory](https://github.com/TrustAI-laboratory) | Free web-based vulnerable LLM CTFs. |
| [DamnVulnerableLLMProject](https://github.com/harishsg993010/DamnVulnerableLLMProject) | [harishsg993010](https://github.com/harishsg993010) | DV LLM app for training/education. |

---

## 🎓 Training, Labs & CTF Challenges
| Organization | Name | Description |
| ------------ | ---- | ----------- |
| SANS | [SEC545: GenAI & LLM AppSec](https://www.sans.org/cyber-security-courses/genai-llm-application-security/) | Hands-on GenAI security. |
| SANS | [SEC495: Building & Securing RAG](https://www.sans.org/cyber-security-courses/leveraging-llms-building-securing-rag/) | RAG security training. |
| SANS | [SEC411: AI Security Principles](https://www.sans.org/cyber-security-courses/ai-security-principles-practices/) | Fundamentals with Docker labs. |
| **New:** SANS | [SANS AI Cybersecurity Summit 2025](https://www.sans.org/cyber-security-summit/) | Hands-on workshops and live demos for AI/ML integration in cybersecurity (Denver, March 31 – April 7, 2025). |
| AppSecEngineer | [AI Combat & Construct](https://www.appsecengineer.com/) | Attack/defend AI apps. |
| Practical DevSecOps | [CAISP](https://www.practical-devsecops.com/certified-ai-security-professional/) | 60 days of labs; MITRE ATLAS defenses. |
| HackAPrompt | [HackAPrompt 1.0](https://www.hackaprompt.com/) | Prompt hacking competition. |
| HackAPrompt | [HackAPrompt 2.0](https://www.hackaprompt.com/) | Large-scale red-teaming hackathon. |
| AI Village | [DEF CON AI CTF](https://www.kaggle.com/competitions/ai-village-ctf) | Annual LLM security CTF. |

---

## 📚 Books & Publications
| Author(s) | Publisher | Name | Description |
| ----------- | --------- | -----| ----------- |
| Various | Springer | [Large Language Models in Cybersecurity: Threats, Exposure and Mitigation](https://link.springer.com/book/10.1007/978-3-031-54827-7) | Open-access guide (2024). |
| Various | Springer | [Generative AI Security: Theories and Practices](https://link.springer.com/book/10.1007/978-981-97-5443-8) | GenAI impacts across security (2024). |
| Various | Springer | [AI-Driven Cybersecurity and Threat Intelligence](https://link.springer.com/book/10.1007/978-3-031-15030-2) | AI x security (2024). |
| Steve Wilson | O'Reilly | [Developer's Playbook for LLM Security](https://www.amazon.com/Developers-Playbook-Large-Language-Security/dp/109816220X) | Practical LLM AppSec (2024). |

---

## 📎 Cheatsheets & Guides
| Name | Author | Description |
| ---- | ------ | ----------- |
| [OWASP LLM Prompt Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Prevention best practices. |
| [LangChain Security Policy](https://python.langchain.com/docs/security/) | [LangChain](https://www.langchain.com/) | "Four Perimeters" and app hardening. |
| [CISA AI Security Best Practices](https://www.cisa.gov/ai) | [CISA](https://www.cisa.gov/) | AI system security guidance. |
| **New:** [NVIDIA AI Red Team Practical Advice](https://developer.nvidia.com/blog/practical-llm-security-advice-from-the-nvidia-ai-red-team/) | [NVIDIA](https://www.nvidia.com/) | Key findings from AIRT assessments on securing AI-powered applications. |
| **New:** [Salesforce Prompt Injection Detection Guide](https://www.salesforce.com/blog/prompt-injection-detection/) | [Salesforce](https://www.salesforce.com/) | Building trusted AI systems against prompt injection threats. |

---

## 🧭 Frameworks & Standards
| Name | Org | Description |
| ---- | --- | ----------- |
| [OWASP Top 10 for LLM Apps (2025)](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | OWASP | LLM01–LLM10 risks including new entries: System Prompt Leakage (LLM07), Vector and Embedding Weaknesses (LLM08), Misinformation (LLM09), Unbounded Consumption (LLM10). |
| [NIST AI RMF + GenAI Profile](https://www.nist.gov/itl/ai-risk-management-framework) | NIST | Govern, Map, Measure, Manage. |
| [MITRE ATLAS](https://atlas.mitre.org/) | MITRE | AI adversary TTPs (modeled after ATT&CK). |
| [CISA AI Guidelines](https://www.cisa.gov/ai) | CISA | Joint guidance for AI/ML systems. |
| **New:** [OWASP Top 10 2025](https://owasp.org/Top10/) | OWASP | Updated to include A03: Software Supply Chain Failures and A10: Mishandling of Exceptional Conditions. |

---

## 🛡️ Defense & Guardrails
| Name | Author | Description |
| ---- | ------ | ----------- |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | [NVIDIA](https://github.com/NVIDIA) | Programmable input/output/dialog/retrieval/execution controls. |
| [LLM Guard](https://llm-guard.com/) | [Protect AI](https://protectai.com/) | Runtime scanning, PII redaction, content filtering. |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | [Guardrails AI](https://www.guardrailsai.com/) | Validation rules & structured outputs using RAIL. |
| [Lakera Guard](https://www.lakera.ai/) | [Lakera](https://www.lakera.ai/) | Real-time prompt injection/jailbreak detection with near-real-time alerts. |
| **New:** [Prompt Armor](https://promptarmor.com/) | [Prompt Armor](https://promptarmor.com/) | Real-time detection and filtering of malicious prompts. |
| **New:** [HiddenLayer AIM Security](https://hiddenlayer.com/) | [HiddenLayer](https://hiddenlayer.com/) | AI application monitoring, real-time threat detection, and zero-trust access controls. |
| **New:** [CalypsoAI Moderator](https://www.calypsoai.com/) | [CalypsoAI](https://www.calypsoai.com/) | Commercial tool with audit trails, malicious code detection, and data loss protection. |

---

## 🎓 Certifications & Courses
| Org | Name | Description |
| --- | ---- | ----------- |
| ISACA | [AAISM™](https://www.isaca.org/credentialing/aaism) | AI Security Management (CISM/CISSP req.). |
| **New:** CompTIA | [SecAI+ (Launching Feb 2026)](https://www.comptia.org/certifications/secai) | First comprehensive certification focused on AI systems security and secure AI application in cybersecurity operations. Covers: Basic AI Concepts (17%), Securing AI Systems (40%), AI-Assisted Security (24%), AI GRC (19%). |
| ISC2 | [Building AI Strategy Certificate](https://www.isc2.org/) | Strategy, governance, risk. |
| Practical DevSecOps | [CAISP](https://www.practical-devsecops.com/certified-ai-security-professional/) | Hands-on certification with labs. |
| Securiti | [AI Security & Governance](https://education.securiti.ai/certifications/ai-governance/) | Governance, privacy, compliance. |

---

## 🎤 Conferences & Events
| Name | Date | Location | Description |
| ---- | ---- | -------- | ----------- |
| [DEF CON](https://defcon.org/) | Aug 2025 | Las Vegas | AI Village & GenAI red team challenges. |
| [Black Hat USA](https://www.blackhat.com/) | Aug 2025 | Las Vegas | AI Security Summit & trainings. |
| [RSA Conference](https://www.rsaconference.com/) | Apr-May 2025 | San Francisco | AI security tracks, expo. |
| **New:** [OWASP AI Security Summit @ RSAC 2025](https://genai.owasp.org/rsac-2025/) | Apr 30, 2025 | San Francisco (Moscone South RM 308) | Safeguarding GenAI & Agentic Apps, Top 10 Risks in 2025. 8:30 AM – 12:30 PM PDT. |
| **New:** [AI Agent Security Summit](https://zenity.io/ai-agent-security-summit/) | Oct 8, 2025 | San Francisco | Industry's first AI Agent Security Summit with 17 sessions on-demand. |
| **New:** [AI Risk Summit](https://airisksummit.com/) | Aug 19-20, 2025 | Ritz-Carlton, Half Moon Bay, CA | Security executives, AI researchers, and policymakers discuss adversarial AI, deepfakes, and regulatory challenges. |
| **New:** [GCSCC AI Cybersecurity Conference 2025](https://gcscc.ox.ac.uk/) | 2025 | Oxford, UK | Securing the Cyber Future: Cyber Resilience in the Age of AI and Geopolitical Uncertainty. |
| **New:** [AI Security & Privacy Conference 2025](https://aisecurityconf.com/) | 2025 | TBD | 400+ CISOs and C-Level Executives with expert-led discussions and case studies. |
| **New:** [Cyber-AI 2025 Conference](https://cyber-ai.org/) | 2025 | Varna, Bulgaria | Four-day conference on cutting-edge advancements in cybersecurity and AI. |
| [AI Village](https://aivillage.org/) | Ongoing | Virtual/Various | Community, meetups, and CTFs. |

---

## 📄 Research Papers & Datasets
| Name | Topic | Description |
| ---- | ----- | ----------- |
| [Ignore This Title and HackAPrompt](https://arxiv.org/abs/2311.16119) | Prompt Injection | EMNLP'23; taxonomy of prompt hacking. |
| [SelfCheckGPT](https://arxiv.org/abs/2303.08896) | Hallucination | Self-consistency for hallucination detection. |
| Survey on Model Extraction Attacks (2025) | Model Security | Survey of extraction attacks/defenses. |
| [SECURE Benchmark](https://arxiv.org/abs/2405.20441) | Cybersecurity | Multi-dataset security evaluation suite. |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA) | Safety | Truthfulness under misconceptions. |
| [ToxiGen](https://github.com/microsoft/TOXIGEN) | Safety | Toxicity dataset & benchmarks. |
| **New:** [In-The-Wild Jailbreak Prompts Dataset](https://huggingface.co/datasets/TrustAIRLab/in-the-wild-jailbreak-prompts) | Jailbreak | 15,140 prompts with 1,405 jailbreak prompts from Reddit, Discord, websites (2022-2023). |
| **New:** [JailbreakBench](https://jailbreakbench.github.io/) | Jailbreak | Open-source robustness benchmark with 200 distinct behaviors and jailbreak artifacts. |
| **New:** [JailBreakV-28K](https://huggingface.co/datasets/JailbreakV-28K/JailBreakV-28k) | Jailbreak | 28,000 jailbreak test cases for MLLMs (20K text-based, 8K image-based). |
| **New:** [Forbidden Question Set](https://huggingface.co/datasets/TrustAIRLab/forbidden_question_set) | Safety | Curated dataset of forbidden questions across high-risk categories. |
| **New:** [LLM Jailbreak + Safety Data](https://www.kaggle.com/datasets/llm-jailbreak-safety) | Jailbreak | ~10K fine-tuning examples and ~3K adversarial prompts for chatbot safety. |
| **New:** [PoisonBench](https://arxiv.org/abs/poisonbench) | Data Poisoning | First benchmark for evaluating poisoning in LLMs during preference learning. |
| **New:** [AART: AI-Assisted Red-Teaming](https://arxiv.org/abs/2311.29119) | Red Teaming | Automated data generation and augmentation pipeline for diverse red-teaming scenarios. |
| **New:** [PyRIT Framework Paper](https://arxiv.org/abs/2410.00001) | Red Teaming | Framework for security risk identification in GenAI systems. |

---

## 📈 Observability & Monitoring
| Name | Author | Description |
| ---- | ------ | ----------- |
| [LangSmith](https://www.langchain.com/langsmith) | [LangChain](https://www.langchain.com/) | Tracing + evals for LLM apps. |
| [Weights & Biases](https://wandb.ai/) | [Weights & Biases](https://wandb.ai/) | Experiment tracking & prompt management for LLMs. |
| [Langfuse](https://langfuse.com/) | [Langfuse](https://langfuse.com/) | Open-source tracing & cost monitoring. |
| [Phoenix](https://phoenix.arize.com/) | [Arize AI](https://arize.com/) | Open-source eval/monitoring. |
| [Helicone](https://www.helicone.ai/) | [Helicone](https://www.helicone.ai/) | Proxy-based logging & analytics. |
| **New:** [WhyLabs LLM Security](https://whylabs.ai/) | [WhyLabs](https://whylabs.ai/) | Comprehensive LLM observability and safeguarding with vulnerability checks and bias detection. |
| **New:** [Dynatrace Davis AI](https://www.dynatrace.com/) | [Dynatrace](https://www.dynatrace.com/) | AI-driven root cause analysis with multidimensional baselining and predictive analytics. |

---

## 🗡️ Penetration Testing Tools
| Name | Author | Description |
| ---- | ------ | ----------- |
| [PentestGPT](https://github.com/GreyDGL/PentestGPT) | [GreyDGL](https://github.com/GreyDGL) | GPT-powered pentesting assistant. |
| [AI-penetration-testing](https://github.com/Mr-Infect/AI-penetration-testing) | [Mr-Infect](https://github.com/Mr-Infect) | Curated offensive/defensive AI pentest techniques. |
| [PentAGI](https://github.com/vxcontrol/pentagi) | [vxcontrol](https://github.com/vxcontrol) | Autonomous agent system for pentesting. |
| [AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) | [antoninoLorenzo](https://github.com/antoninoLorenzo) | Assistant for exploit dev & research. |
| [HackSynth](https://github.com/aielte-research/HackSynth) | [aielte-research](https://github.com/aielte-research) | Planner + summarizer pentest agent. |
| [HexStrike AI MCP](https://github.com/0x4m4/hexstrike-ai) | [0x4m4](https://github.com/0x4m4) | 150+ tools + AI agents automation. |
| [Strix](https://github.com/usestrix/strix) | [usestrix](https://usestrix.com/) | "AI hacker" agents; CLI & CI/CD. |
| **New:** [BurpGPT](https://portswigger.net/burp/extensions) | [Burp Suite](https://portswigger.net/) | Burp Suite extension integrating LLMs for enhanced vulnerability scanning and traffic analysis. |

---

## 🔐 MCP Security
*New section dedicated to Model Context Protocol (MCP) security resources*

| Name | Author | Description |
| ---- | ------ | ----------- |
| **New:** [Windows 11 MCP Security Architecture](https://blogs.windows.com/windowsdeveloper/2025/05/18/securing-mcp/) | [Microsoft](https://www.microsoft.com/) | Fundamental security capabilities for MCP with proxy-mediated communication and tool-level authorization. |
| **New:** [Palo Alto Networks MCP Security Overview](https://www.paloaltonetworks.com/blog/mcp-security/) | [Palo Alto Networks](https://www.paloaltonetworks.com/) | Comprehensive guide to MCP risks including prompt injection, credential leakage, and tool poisoning. |
| **New:** [Red Hat MCP Security Guide](https://www.redhat.com/en/blog/mcp-security) | [Red Hat](https://www.redhat.com/) | Understanding security implications and best practices for MCP implementations. |
| **New:** [Pillar Security MCP Analysis](https://pillar.security/mcp-risks/) | [Pillar Security](https://pillar.security/) | Analysis of MCP security risks and attack vectors. |
| **New:** [Strobes MCP Vulnerabilities](https://strobes.co/mcp-vulnerabilities/) | [Strobes](https://strobes.co/) | Critical vulnerabilities in MCP including session IDs in URLs and weak authentication. |
| **New:** [Equixly MCP Security](https://equixly.com/mcp-security/) | [Equixly](https://equixly.com/) | Protocol fundamentals and missing secure-by-design principles in MCP. |
| **New:** [Lasso MCP Gateway](https://github.com/lasso-security/mcp-gateway) | [Lasso Security](https://lasso.security/) | First security-centric open-source solution for Model Context Protocol. |

---

## ⭐ Awesome Lists
| Name | Author | Description |
| ---- | ------ | ----------- |
| [awesome-llm-security](https://github.com/corca-ai/awesome-llm-security) | [corca-ai](https://github.com/corca-ai) | LLM Security resources. |
| [awesome-gpt-security](https://github.com/cckuailong/awesome-gpt-security) | [cckuailong](https://github.com/cckuailong) | Security tools & cases for GPT apps. |
| [awesome-llm-cybersecurity-tools](https://github.com/tenable/awesome-llm-cybersecurity-tools) | [Tenable](https://github.com/tenable) | LLM tools for cybersecurity. |
| [Awesome-LLMSecOps](https://github.com/wearetyomsmnv/Awesome-LLMSecOps) | [wearetyomsmnv](https://github.com/wearetyomsmnv) | LLM SecOps lifecycle & threats. |
| [awesome-llm-supply-chain-security](https://github.com/ShenaoW/awesome-llm-supply-chain-security) | [ShenaoW](https://github.com/ShenaoW) | Supply chain security resources. |
| [awesome-MLSecOps](https://github.com/RiccardoBiosas/awesome-MLSecOps) | [RiccardoBiosas](https://github.com/RiccardoBiosas) | MLSecOps tools & best practices. |
| [awesome-hallucination-detection](https://github.com/EdinburghNLP/awesome-hallucination-detection) | [EdinburghNLP](https://github.com/EdinburghNLP) | Hallucination detection papers. |
| **New:** [oss-llm-security](https://github.com/kaplanlior/oss-llm-security) | [kaplanlior](https://github.com/kaplanlior) | Curated list of open-source LLM security tools including EasyJailbreak, fast-llm-security, and more. |

---

## 📰 Podcasts & Newsletters
| Name | Host/Author | Description |
| ---- | ----------- | ----------- |
| [AI Security Podcast](https://www.aisecuritypodcast.com/) | Ashish Rajan & Caleb Sima | Vendor-neutral AI security conversations. |
| [The AI Fix Podcast](https://theaifix.com/) | Graham Cluley & Mark Stockley | Deepfakes, policy, and security. |
| [Smashing Security](https://www.smashingsecurity.com/) | Graham Cluley & Carole Theriault | Weekly infosec pod with AI topics. |
| [Resilient Cyber Newsletter](https://resilientcyber.io/) | Chris Hughes | AI, supply chain, cloud, AppSec. |

---

## 📺 YouTube Channels
*New section for cybersecurity and AI security YouTube channels*

| Name | Focus | Description |
| ---- | ----- | ----------- |
| **New:** [PowerDMARC](https://www.youtube.com/@PowerDMARC) | Email Security | Email authentication, DMARC, spoofing, phishing, and fraud tactics. |
| **New:** [John Hammond](https://www.youtube.com/@_JohnHammond) | General Cybersecurity | 1.28M subscribers; CTF challenges, hacking tutorials, and real-time problem-solving. |
| **New:** [The Cyber Mentor](https://www.youtube.com/@TCMSecurityAcademy) | Ethical Hacking | Practical ethical hacking, penetration testing, and step-by-step tutorials. |
| **New:** [NetworkChuck](https://www.youtube.com/@NetworkChuck) | Networking & Security | Exploring cybersecurity, networking, and technology concepts. |
| **New:** [Hak5](https://www.youtube.com/@hak5) | Hacking Tools | Cybersecurity tools, privacy, tech gadgets, and entertaining tutorials. |
| **New:** [MalwareTech](https://www.youtube.com/@MalwareTechBlog) | Malware Analysis | Deep-dive malware analysis, cybersecurity research, and threat intelligence. |
| **New:** [David Bombal](https://www.youtube.com/@davidbombal) | Network Security | Ethical hacking, network security, and certifications. |
| **New:** [LiveOverflow](https://www.youtube.com/@LiveOverflow) | Binary Exploitation | Low-level security, reverse engineering, and CTF writeups. |
| **New:** [CyberRisk TV](https://www.youtube.com/@CyberRiskTV) | AI Security | Black Hat 2025 coverage with focus on AI security, agentic AI, and trust. |

---

## 🧰 Other Resources
| Name | Author | Description |
| ---- | ------ | ----------- |
| [Rez0's AI Security Blog](https://josephthacker.com/) | Joseph Thacker | AI hacking fundamentals & techniques. |
| [Simon Willison's Blog](https://simonwillison.net) | Simon Willison | Prompt injection & agent security. |
| [Lakera AI Blog](https://www.lakera.ai/blog) | Lakera Team | GenAI security thought leadership. |
| [Anthropic Transparency Hub](https://www.anthropic.com/transparency) | Anthropic | System cards & red team reports. |
| [OpenAI Red Teaming Network](https://openai.com/red-teaming-network/) | OpenAI | Red teaming docs & invites. |
| [MLSecOps Community](https://mlsecops.com/) | Community | Best practices & community. |
| **New:** [OWASP GenAI Security Project](https://genai.owasp.org/) | [OWASP](https://owasp.org) | Global community-driven initiative for GenAI security guidance and resources. |
| **New:** [OWASP AI Security Solutions Landscape](https://genai.owasp.org/ai-security-solutions/) | [OWASP](https://owasp.org) | Landmark guide outlining key risks and critical controls for securing LLMs and GenAI applications. |
| **New:** [Lasso Security Blog](https://lasso.security/blog/) | [Lasso Security](https://lasso.security/) | Resources on LLM & AI cybersecurity, MCP security, and red teaming. |
| **New:** [AI Security on Splunk](https://www.splunk.com/en_us/blog/learn/ai-security.html) | [Splunk](https://www.splunk.com/) | AI security insights and best practices from Splunk. |

---

## 👤 Thought Leaders
| Name | Platform | Notability |
| ---- | -------- | ----------- |
| Simon Willison | [Twitter/X](https://twitter.com/simonw) / Blog | Prompt injection & agent security. |
| Joseph Thacker (rez0) | [Twitter/X](https://twitter.com/rez0__) / Blog | Prolific AI vuln research & guides. |
| Lakera Team | [Twitter/X](https://twitter.com/lakeraai) | Gandalf & Lakera Guard creators. |
| NVIDIA AI Red Team | [Twitter/X](https://twitter.com/NVIDIAAIDev) | Team behind garak and practical security guidance. |
| Microsoft AI Red Team | [Twitter/X](https://twitter.com/MSFTSecurity) | PyRIT & public red teaming lessons. |
| **New:** Steve Wilson | [LinkedIn](https://www.linkedin.com/in/wilsonsd/) | OWASP Top 10 for LLM Applications Project Lead. |
| **New:** Ads Dawson | [LinkedIn](https://www.linkedin.com/in/adamdawson0/) | Technical Lead & Vulnerability Entries Lead for OWASP Top 10 LLMs. |

---

## Contributions
1. **Purpose:** Collect AI/LLM security & prompt-injection resources. Prefer open-source/community content.  
2. **Out of Scope:** Ads, closed-source/proprietary, trials/freemium, or items needing private details.  
3. **Relevance:** Must directly relate to AI/LLM security, jailbreaks, red teaming, model/app security.  
4. **No Duplicates:** Avoid redundant entries.  
5. **Thought Leaders:** Prefer figures tied to content/tools listed here.  
6. **Accuracy:** Authors can open issues/PRs to update their entries.  
7. **Books:** Paid books allowed for educational value.

**How to contribute**
- Fork → Branch → Edit `README.md` → Open PR with a clear description.  
- See GitHub's [Quickstart: Contributing to Projects](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).

---

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

> To the extent possible under law, the contributors have waived all copyright
> and related or neighboring rights to this work.

---

<p align="center">
  <a href="#top">⬆️ Back to top</a>
</p>
