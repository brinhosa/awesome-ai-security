<div id="top"></div>

<p align="center">
  <img src="banner1.svg" width="100%" alt="Awesome AI Security banner">
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
  <a href="#-awesome-lists">⭐ Awesome Lists</a> •
  <a href="#-podcasts--newsletters">📰 Pods & News</a> •
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

> 📌 Please read the [Contributions](#contributions) section before opening a pull request.

---

## 🧪 AI Security Testing Tools
| Name | Author | Description |
| ---- | ------ | ----------- |
| [garak](https://github.com/NVIDIA/garak) | [NVIDIA](https://github.com/NVIDIA) | LLM vulnerability scanner – tests 120+ categories (hallucination, data leakage, prompt injection, misinformation, toxicity, jailbreaks). |
| [PyRIT](https://github.com/Azure/PyRIT) | [Microsoft](https://github.com/Azure) | Python Risk Identification Tool for GenAI; adversarial testing automation. |
| [promptmap](https://github.com/utkusen/promptmap) | [utkusen](https://github.com/utkusen) | Automated prompt injection scanner with white-box testing. |
| [aiapwn](https://github.com/karimhabush/aiapwn) | [karimhabush](https://github.com/karimhabush) | Automatic prompt injection testing with tailored payload generation. |
| [FuzzyAI](https://github.com/cyberark/FuzzyAI) | [CyberArk](https://github.com/cyberark) | LLM fuzzing framework to identify jailbreaks and vulns. |
| [LLMFuzzer](https://github.com/mnns/LLMFuzzer) | [mnns](https://github.com/mnns) | Fuzzing framework for LLM API integrations. |
| [promptfoo](https://www.promptfoo.dev) | promptfoo | Dynamic adversarial probes and context-aware test cases. |
| [LLM Warden](https://github.com/jackhhao/llm-warden) | [jackhhao](https://github.com/jackhhao) | Simple jailbreak detection (Hugging Face model). |
| [Vigil](https://github.com/deadbits/vigil) | [deadbits](https://github.com/deadbits) | Modular scanners (vectors, YARA, transformers) via lib & REST API. |
| **New:** [picklescan](https://github.com/mmaitre314/picklescan) | [mmaitre314](https://github.com/mmaitre314) | Detects malicious code in Python pickle model files. |
| **New:** [ModelScan](https://github.com/protectai/modelscan) | [Protect AI](https://github.com/protectai) | Multi-format ML model file scanner (pickle, SavedModel, etc.). |
| **New:** [Open-Prompt-Injection](https://github.com/liu00222/Open-Prompt-Injection) | Yupei Liu et al. | Toolkit/benchmark for prompt injection attacks/defenses. |

---

## 🧨 Prompt Injection Resources
| Name | Author | Description |
| ---- | ------ | ----------- |
| [PayloadsAllTheThings – Prompt Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Prompt%20Injection/README.md) | [swisskyrepo](https://github.com/swisskyrepo) | Prompt injection payloads and bypasses. |
| [PIPE – Prompt Injection Primer](https://github.com/jthack/PIPE) | [jthack](https://github.com/jthack) | Attack scenarios and payloads for engineers. |
| [Basic-ML-prompt-injections](https://github.com/Zierax/Basic-ML-prompt-injections) | [Zierax](https://github.com/Zierax) | Educational payloads. |
| [OWASP LLM Prompt Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Prevention cheat sheet and best practices. |

---

## 🕵️ Jailbreak Detection & Red Teaming
| Name | Author | Description |
| ---- | ------ | ----------- |
| [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | [IBM / LF AI](https://github.com/Trusted-AI) | Defenses against evasion, poisoning, extraction, inference attacks. |
| [HEART](https://github.com/IBM/heart-library) | [IBM](https://github.com/IBM) | Hardened ART extension for T&E workflows. |
| [Rebuff](https://github.com/protectai/rebuff) | [Protect AI](https://github.com/protectai) | Self-hardening prompt injection detector (multi-layer). |
| [Plexiglass](https://github.com/invariantlabs/plexiglass) | [Invariant Labs](https://github.com/invariantlabs) | Security toolbox for testing/safeguarding LLMs. |
| [PurpleLlama](https://github.com/meta-llama/PurpleLlama) | [Meta](https://github.com/meta-llama) | Llama Guard, CyberSecEval, and more. |

---

## 🧩 Deliberately Vulnerable AI Applications
| Name | Author | Description |
| ---- | ------ | ----------- |
| [AI Goat](https://github.com/dhammon/ai-goat) | [dhammon](https://github.com/dhammon) | Local LLM CTF challenges; no fees/sign-ups. |
| [Gandalf](https://gandalf.lakera.ai/) | [Lakera](https://www.lakera.ai/) | Prompt injection game with difficulty levels. |
| [LLM Security CTF](https://github.com/TrustAI-laboratory/LLM-Security-CTF) | [TrustAI-laboratory](https://github.com/TrustAI-laboratory) | Free web-based vulnerable LLM CTFs. |
| [DamnVulnerableLLMProject](https://github.com/harishsg993010/DamnVulnerableLLMProject) | [harishsg993010](https://github.com/harishsg993010) | DV LLM app for training/education. |
| [Damn Vulnerable LLM Agent](https://labs.withsecure.com/tools/damn-vulnerable-llm-agent) | [WithSecure Labs](https://labs.withsecure.com/) | Focused on agentic T/A/O injection. |

---

## 🎓 Training, Labs & CTF Challenges
| Organization | Name | Description |
| ------------ | ---- | ----------- |
| SANS | [SEC545: GenAI & LLM AppSec](https://www.sans.org/cyber-security-courses/genai-llm-application-security/) | Hands-on GenAI security. |
| SANS | [SEC495: Building & Securing RAG](https://www.sans.org/cyber-security-courses/leveraging-llms-building-securing-rag/) | RAG security training. |
| SANS | [SEC411: AI Security Principles](https://www.sans.org/cyber-security-courses/ai-security-principles-practices/) | Fundamentals with Docker labs. |
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
| Steve Wilson | O’Reilly | [Developer’s Playbook for LLM Security](https://www.amazon.com/Developers-Playbook-Large-Language-Security/dp/109816220X) | Practical LLM AppSec (2024). |
| John Sotiropoulos | Packt | [Adversarial AI Attacks, Mitigations, and Defense Strategies](https://www.packtpub.com/product/adversarial-ai-attacks-mitigations-and-defense-strategies-9781835087985) | Hands-on defenses (2024). |

---

## 📎 Cheatsheets & Guides
| Name | Author | Description |
| ---- | ------ | ----------- |
| [OWASP LLM Prompt Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Prevention best practices. |
| [LangChain Security Policy](https://python.langchain.com/docs/security/) | [LangChain](https://www.langchain.com/) | “Four Perimeters” and app hardening. |
| [CISA AI Security Best Practices](https://www.cisa.gov/ai) | [CISA](https://www.cisa.gov/) | AI system security guidance. |

---

## 🧭 Frameworks & Standards
| Name | Org | Description |
| ---- | --- | ----------- |
| [OWASP Top 10 for LLM Apps (2025)](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | OWASP | LLM01–LLM10 risks. |
| [NIST AI RMF + GenAI Profile](https://www.nist.gov/itl/ai-risk-management-framework) | NIST | Govern, Map, Measure, Manage. |
| [MITRE ATLAS](https://atlas.mitre.org/) | MITRE | AI adversary TTPs (modeled after ATT&CK). |
| [CISA AI Guidelines](https://www.cisa.gov/ai) | CISA | Joint guidance for AI/ML systems. |

---

## 🛡️ Defense & Guardrails
| Name | Author | Description |
| ---- | ------ | ----------- |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | [NVIDIA](https://github.com/NVIDIA) | Programmable input/output/dialog/retrieval/execution controls. |
| [LLM Guard](https://llm-guard.com/) | [Protect AI](https://protectai.com/) | Runtime scanning, PII redaction, content filtering. |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | [Guardrails AI](https://www.guardrailsai.com/) | Validation rules & structured outputs. |
| [Lakera Guard](https://www.lakera.ai/) | [Lakera](https://www.lakera.ai/) | Real-time prompt injection/jailbreak detection. |
| **New:** [CodeGate](https://codegate.ai/) | [Stacklok](https://stacklok.com/) | Open-source security proxy for coding assistants. |

---

## 🎓 Certifications & Courses
| Org | Name | Description |
| --- | ---- | ----------- |
| ISACA | [AAISM™](https://www.isaca.org/credentialing/aaism) | AI Security Management (CISM/CISSP req.). |
| ISC2 | [Building AI Strategy Certificate](https://www.isc2.org/) | Strategy, governance, risk. |
| Practical DevSecOps | [CAISP](https://www.practical-devsecops.com/certified-ai-security-professional/) | Hands-on certification with labs. |
| Securiti | [AI Security & Governance](https://education.securiti.ai/certifications/ai-governance/) | Governance, privacy, compliance. |

---

## 🎤 Conferences & Events
| Name | Description |
| ---- | ----------- |
| [DEF CON](https://defcon.org/) | AI Village & GenAI red team challenges (Las Vegas). |
| [Black Hat USA](https://www.blackhat.com/) | AI Security Summit & trainings (Las Vegas). |
| [RSA Conference](https://www.rsaconference.com/) | AI security tracks, expo (San Francisco). |
| [AI Village](https://aivillage.org/) | Community, meetups, and CTFs. |

---

## 📄 Research Papers & Datasets
| Name | Topic | Description |
| ---- | ----- | ----------- |
| [Ignore This Title and HackAPrompt](https://arxiv.org/abs/2311.16119) | Prompt Injection | EMNLP’23; taxonomy of prompt hacking. |
| [SelfCheckGPT](https://arxiv.org/abs/2303.08896) | Hallucination | Self-consistency for hallucination detection. |
| Survey on Model Extraction Attacks (2025) | Model Security | Survey of extraction attacks/defenses. |
| [SECURE Benchmark](https://arxiv.org/abs/2405.20441) | Cybersecurity | Multi-dataset security evaluation suite. |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA) | Safety | Truthfulness under misconceptions. |
| [ToxiGen](https://github.com/microsoft/TOXIGEN) | Safety | Toxicity dataset & benchmarks. |

---

## 📈 Observability & Monitoring
| Name | Author | Description |
| ---- | ------ | ----------- |
| [LangSmith](https://www.langchain.com/langsmith) | [LangChain](https://www.langchain.com/) | Tracing + evals for LLM apps. |
| [W&B – LLM Ops](https://wandb.ai/site/llmops) | [Weights & Biases](https://wandb.ai/) | Experiment & prompt tracking. |
| [Langfuse](https://langfuse.com/) | [Langfuse](https://langfuse.com/) | Open-source tracing & cost monitoring. |
| [Phoenix](https://phoenix.arize.com/) | [Arize AI](https://arize.com/) | Open-source eval/monitoring. |
| [Helicone](https://www.helicone.ai/) | [Helicone](https://www.helicone.ai/) | Proxy-based logging & analytics. |

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
| **New:** [Strix](https://github.com/usestrix/strix) | [usestrix](https://usestrix.com/) | “AI hacker” agents; CLI & CI/CD. |

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

---

## 📰 Podcasts & Newsletters
| Name | Host/Author | Description |
| ---- | ----------- | ----------- |
| [AI Security Podcast](https://www.aisecuritypodcast.com/) | Ashish Rajan & Caleb Sima | Vendor-neutral AI security conversations. |
| [The AI Fix Podcast](https://theaifix.com/) | Graham Cluley & Mark Stockley | Deepfakes, policy, and security. |
| [Smashing Security](https://www.smashingsecurity.com/) | Graham Cluley & Carole Theriault | Weekly infosec pod with AI topics. |
| [Resilient Cyber Newsletter](https://resilientcyber.io/) | Chris Hughes | AI, supply chain, cloud, AppSec. |

---

## 🧰 Other Resources
| Name | Author | Description |
| ---- | ------ | ----------- |
| [Rez0’s AI Security Blog](https://josephthacker.com/) | Joseph Thacker | AI hacking fundamentals & techniques. |
| [Simon Willison’s Blog](https://simonwillison.net) | Simon Willison | Prompt injection & agent security. |
| [Lakera AI Blog](https://www.lakera.ai/blog) | Lakera Team | GenAI security thought leadership. |
| [Anthropic Transparency Hub](https://www.anthropic.com/transparency) | Anthropic | System cards & red team reports. |
| [OpenAI Red Teaming Network](https://openai.com/red-teaming-network/) | OpenAI | Red teaming docs & invites. |
| [MLSecOps Community](https://mlsecops.com/) | Community | Best practices & community. |

---

## 👤 Thought Leaders
| Name | Platform | Notability |
| ---- | -------- | ----------- |
| Simon Willison | [Twitter/X](https://twitter.com/simonw) / Blog | Prompt injection & agent security. |
| Joseph Thacker (rez0) | [Twitter/X](https://twitter.com/rez0__) / Blog | Prolific AI vuln research & guides. |
| Lakera Team | [Twitter/X](https://twitter.com/lakeraai) | Gandalf & Lakera Guard creators. |
| NVIDIA AI Red Team | [Twitter/X](https://twitter.com/NVIDIAAIDev) | Team behind garak. |
| Microsoft AI Red Team | [Twitter/X](https://twitter.com/MSFTSecurity) | PyRIT & public red teaming lessons. |

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
- See GitHub’s [Quickstart: Contributing to Projects](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).

---

## License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

> To the extent possible under law, the contributors have waived all copyright
> and related or neighboring rights to this work.

---

<p align="center">
  <a href="#top">⬆️ Back to top</a>
</p>
