# [awesome-ai-security](https://github.com/brinhosa/awesome-ai-security)

<h4 align="center">A collection of awesome AI Security, LLM Security, and Prompt Injection tools and resources.</h4>

<p align="center">
  <a href="#about">About</a> •
  <a href="#ai-security-testing-tools">AI Security Testing Tools</a> •
  <a href="#prompt-injection-resources">Prompt Injection Resources</a> •
  <a href="#jailbreak-detection-and-red-teaming">Jailbreak Detection & Red Teaming</a> •
  <a href="#deliberately-vulnerable-ai-applications">Deliberately Vulnerable AI Applications</a> •
  <a href="#training-labs-and-ctf-challenges">Training, Labs & CTF Challenges</a> • </br>
  <a href="#books-and-publications">Books & Publications</a> •
  <a href="#cheatsheets-and-guides">Cheatsheets & Guides</a> •
  <a href="#frameworks-and-standards">Frameworks & Standards</a> •
  <a href="#defense-and-guardrails">Defense & Guardrails</a> •
  <a href="#certifications-and-courses">Certifications & Courses</a> • </br>
  <a href="#conferences-and-events">Conferences & Events</a> •
  <a href="#research-papers-and-datasets">Research Papers & Datasets</a> •
  <a href="#observability-and-monitoring">Observability & Monitoring</a> •
  <a href="#penetration-testing-tools">Penetration Testing Tools</a> • </br>
  <a href="#awesome-lists">Awesome Lists</a> •
  <a href="#podcasts-and-newsletters">Podcasts & Newsletters</a> •
  <a href="#other-resources">Other Resources</a> •
  <a href="#thought-leaders">Thought Leaders</a> •
  <a href="#contributions">Contributions</a>
</p>

---

## About
The awesome-ai-security repository is a collection of awesome AI Security, LLM Security, and Prompt Injection tools and resources.
The focus goes to open-source tools and resources that benefit all the community.

This repository covers:
- Large Language Model (LLM) security testing and vulnerability assessment
- Prompt injection attacks and defenses
- AI red teaming and adversarial testing
- Jailbreak detection and prevention
- Model poisoning and extraction attacks
- Hallucination detection
- AI application security best practices
- MLSecOps and LLMOps security

Please read the <a href="#contributions">contributions</a> section before opening a pull request.

## AI Security Testing Tools
| Name | Author | Description |
| ---- | ------ | ----------- |
| [garak](https://github.com/NVIDIA/garak) | [NVIDIA](https://github.com/NVIDIA) | The LLM vulnerability scanner - Tests for 120+ vulnerability categories including hallucination, data leakage, prompt injection, misinformation, toxicity, and jailbreaks. |
| [PyRIT](https://github.com/Azure/PyRIT) | [Microsoft](https://github.com/Azure) | Python Risk Identification Tool for generative AI - Used by Microsoft AI Red Team for 100+ red teaming operations. Automates adversarial testing of GenAI systems. |
| [promptmap](https://github.com/utkusen/promptmap) | [utkusen](https://github.com/utkusen) | Automated prompt injection scanner for custom LLM applications with support for white-box testing. |
| [aiapwn](https://github.com/karimhabush/aiapwn) | [karimhabush](https://github.com/karimhabush) | Automatic Prompt Injection testing tool that generates custom payloads based on AI behavior. |
| [FuzzyAI](https://github.com/cyberark/FuzzyAI) | [CyberArk](https://github.com/cyberark) | Automated LLM fuzzing framework that identifies jailbreaks and security vulnerabilities. |
| [LLMFuzzer](https://github.com/mnns/LLMFuzzer) | [mnns](https://github.com/mnns) | First open-source fuzzing framework specifically designed for LLM API integrations. |
| [promptfoo](https://www.promptfoo.dev) | promptfoo | Dynamic LLM security testing with adversarial probes that generates context-aware test cases. |
| [LLM Warden](https://github.com/jackhhao/llm-warden) | [jackhhao](https://github.com/jackhhao) | Simple jailbreak detection tool with fine-tuned model on HuggingFace. |
| [Vigil](https://github.com/deadbits/vigil) | [deadbits](https://github.com/deadbits) | Python library and REST API for LLM security with modular scanners using vector databases, YARA heuristics, and transformer models. |

## Prompt Injection Resources
| Name | Author | Description |
| ---- | ------ | ----------- |
| [PayloadsAllTheThings - Prompt Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Prompt%20Injection/README.md) | [swisskyrepo](https://github.com/swisskyrepo) | Comprehensive collection of prompt injection payloads including bypasses for various LLM security controls. |
| [PIPE - Prompt Injection Primer](https://github.com/jthack/PIPE) | [jthack](https://github.com/jthack) | Educational prompt injection resource with attack scenarios and payloads for engineers. |
| [Basic-ML-prompt-injections](https://github.com/Zierax/Basic-ML-prompt-injections) | [Zierax](https://github.com/Zierax) | LLM attack payloads for educational purposes. |
| [OWASP Prompt Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Best practices cheat sheet for preventing prompt injection with input validation and sanitization techniques. |

## Jailbreak Detection and Red Teaming
| Name | Author | Description |
| ---- | ------ | ----------- |
| [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | [IBM/Linux Foundation AI](https://github.com/Trusted-AI) | Python library for ML Security defending against evasion, poisoning, extraction, and inference attacks. Funded by DARPA GARD. |
| [HEART](https://github.com/IBM/heart-library) | [IBM](https://github.com/IBM) | Hardened Extension of ART supporting Test & Evaluation workflows for adversarial AI vulnerability assessment. |
| [Rebuff](https://github.com/protectai/rebuff) | [Protect AI](https://github.com/protectai) | Self-hardening prompt injection detector with four layers of defense. |
| [Plexiglass](https://github.com/invariantlabs/plexiglass) | [Invariant Labs](https://github.com/invariantlabs) | Security toolbox for testing and safeguarding LLMs. |
| [PurpleLlama](https://github.com/meta-llama/PurpleLlama) | [Meta](https://github.com/meta-llama) | Set of tools to assess and improve LLM security from Meta. |

## Deliberately Vulnerable AI Applications
| Name | Author | Description |
| ---- | ------ | ----------- |
| [AI Goat](https://github.com/dhammon/ai-goat) | [dhammon](https://github.com/dhammon) | Learn AI security through vulnerable LLM CTF challenges that run locally with no cloud fees or sign-ups required. |
| [Gandalf](https://gandalf.lakera.ai/) | [Lakera](https://www.lakera.ai/) | AI prompt injection game with 7 levels of increasing difficulty. Over 9M+ interactions from 200K+ users. |
| [LLM Security CTF](https://github.com/TrustAI-laboratory/LLM-Security-CTF) | [TrustAI-laboratory](https://github.com/TrustAI-laboratory) | Series of free, web-based vulnerable LLM CTF challenges. |
| [DamnVulnerableLLMProject](https://github.com/harishsg993010/DamnVulnerableLLMProject) | [harishsg993010](https://github.com/harishsg993010) | LLM explicitly designed for security training and educational purposes. |
| [Damn Vulnerable LLM Agent](https://labs.withsecure.com/tools/damn-vulnerable-llm-agent) | [WithSecure Labs](https://labs.withsecure.com/) | Teaches Thought/Action/Observation injection focusing on agentic LLM systems. |

## Training, Labs and CTF Challenges
| Organization | Name | Description |
| ------------ | ---- | ----------- |
| SANS Institute | [SEC545: GenAI and LLM Application Security](https://www.sans.org/cyber-security-courses/genai-llm-application-security/) | Comprehensive GenAI security course with hands-on labs. |
| SANS Institute | [SEC495: Leveraging LLMs: Building & Securing RAG](https://www.sans.org/cyber-security-courses/leveraging-llms-building-securing-rag/) | Hands-on RAG security training. |
| SANS Institute | [SEC411: AI Security Principles and Practices](https://www.sans.org/cyber-security-courses/ai-security-principles-practices/) | Docker-based hands-on labs for AI security. |
| AppSecEngineer | [AI Combat & Construct](https://www.appsecengineer.com/) | Hands-on labs for attacking and defending AI/LLM applications. |
| Practical DevSecOps | [Certified AI Security Professional (CAISP)](https://www.practical-devsecops.com/certified-ai-security-professional/) | 60 days of browser-based labs with 30+ guided exercises and MITRE ATLAS defenses. |
| HackAPrompt | [HackAPrompt 1.0](https://www.hackaprompt.com/) | First-ever prompt hacking competition with $35,000+ in prizes. 600K+ adversarial prompts generated. |
| HackAPrompt | [HackAPrompt 2.0](https://www.hackaprompt.com/) | World's largest AI red-teaming hackathon with $100,000 prize pool. |
| AI Village | [DEF CON AI CTF](https://www.kaggle.com/competitions/ai-village-ctf) | Annual LLM security competition at DEF CON. 2,244 hackers tested 8 LLMs at DEF CON 31. |

## Books and Publications
| Author      | Publisher | Name | Description |
| ----------- | --------- | -----| ----------- |
| Various | Springer | [Generative AI Security: Theories and Practices](https://link.springer.com/book/10.1007/978-981-97-5443-8) | Covers GenAI impacts on cybersecurity including data security, model security, and application-level security. Published 2024. |
| Various | Springer | [AI-Driven Cybersecurity and Threat Intelligence](https://link.springer.com/book/10.1007/978-3-031-15030-2) | AI technology intersecting with cybersecurity and intelligent decision-making. Published 2024. |

## Cheatsheets and Guides
| Name | Author | Description |
| ---- | ------ | ----------- |
| [OWASP LLM Prompt Injection Prevention](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html) | [OWASP](https://owasp.org) | Best practices for preventing prompt injection with input validation and sanitization. |
| [LangChain Security Policy](https://python.langchain.com/docs/security/) | [LangChain](https://www.langchain.com/) | Security best practices for LangChain applications including Four Perimeters Framework. |
| [AI Security Best Practices](https://www.cisa.gov/ai) | [CISA](https://www.cisa.gov/) | Government guidelines for securing AI systems and data. |

## Frameworks and Standards
| Name | Organization | Description |
| ---- | ------------ | ----------- |
| [OWASP Top 10 for LLM Applications 2025](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | [OWASP](https://owasp.org) | Top 10 security risks for LLM applications including Prompt Injection (LLM01:2025) and Data/Model Poisoning (LLM04:2025). 500+ experts contributed. |
| [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | [NIST](https://www.nist.gov/) | Voluntary framework with four functions: GOVERN, MAP, MEASURE, MANAGE. Generative AI Profile released July 2024. |
| [MITRE ATLAS](https://atlas.mitre.org/) | [MITRE](https://www.mitre.org/) | Adversarial Threat Landscape for AI Systems with 14 tactics, 56 techniques. Modeled after MITRE ATT&CK. |
| [CISA AI Security Guidelines](https://www.cisa.gov/ai) | [CISA](https://www.cisa.gov/) | Joint cybersecurity information with NSA, FBI, and Five Eyes partners for AI security. |

## Defense and Guardrails
| Name | Author | Description |
| ---- | ------ | ----------- |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | [NVIDIA](https://github.com/NVIDIA) | Open-source toolkit for programmable guardrails with 5 types: Input, Dialog, Retrieval, Execution. Works with all LLMs. |
| [LLM Guard](https://llm-guard.com/) | [Protect AI](https://protectai.com/) | Input/output scanners with PII detection, redaction, and topic filtering. |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | [Guardrails AI](https://www.guardrailsai.com/) | Python framework for LLM guardrails with validation and structured outputs. |
| [Lakera Guard](https://www.lakera.ai/) | [Lakera](https://www.lakera.ai/) | Real-time GenAI security with <50ms response time. Industry-leading prompt injection and jailbreak detection. |

## Certifications and Courses
| Organization | Name | Description |
| ------------ | ---- | ----------- |
| ISACA | [AAISM™](https://www.isaca.org/credentialing/aaism) | AI Security Management certification requiring active CISM or CISSP. |
| ISC2 | [Building AI Strategy Certificate](https://www.isc2.org/) | 6 courses covering AI security strategy for CISSP and cybersecurity professionals. |
| Practical DevSecOps | [Certified AI Security Professional (CAISP)](https://www.practical-devsecops.com/certified-ai-security-professional/) | Hands-on AI security certification with browser-based labs. |
| Securiti | [AI Security & Governance Certification](https://education.securiti.ai/certifications/ai-governance/) | Focus on AI governance and compliance. |

## Conferences and Events
| Name | Description |
| ---- | ----------- |
| [DEF CON](https://defcon.org/) | World's largest hacker conference with 30,000+ attendees. Features AI Village with LLM CTF challenges. Annual in Las Vegas. |
| [Black Hat USA](https://www.blackhat.com/) | 22,750+ attendees from 127+ countries. Black Hat AI Summit with Generative AI security tracks. Annual in Las Vegas. |
| [RSA Conference](https://www.rsaconference.com/) | 44,000 attendees with AI security vendor showcase. Annual in San Francisco. |
| [AI Village](https://aivillage.org/) | DEF CON's AI-focused village hosting Generative AI Red Team challenges and the largest public LLM red teaming events. |

## Research Papers and Datasets
| Name | Topic | Description |
| ---- | ----- | ----------- |
| [Ignore This Title and HackAPrompt](https://arxiv.org/abs/2311.16119) | Prompt Injection | Best Theme Paper at EMNLP 2023. Analysis of 600K+ adversarial prompts. |
| [SelfCheckGPT](https://arxiv.org/abs/2303.08896) | Hallucination Detection | Zero-resource black-box hallucination detection using sampling-based consistency checking. |
| [Survey on Model Extraction Attacks](https://arxiv.org/abs/2506.22521) | Model Security | Comprehensive survey on model extraction attacks and defenses for LLMs. |
| [SECURE Benchmark](https://arxiv.org/abs/2405.20441) | Cybersecurity | Security Extraction, Understanding & Reasoning Evaluation with 6 datasets. |
| [TruthfulQA](https://github.com/sylinrl/TruthfulQA) | Safety | Evaluates truthful response generation and measures false/misleading information. |
| [ToxiGen](https://github.com/microsoft/TOXIGEN) | Safety | Hate speech detection and toxic vs benign statement classification. |

## Observability and Monitoring
| Name | Author | Description |
| ---- | ------ | ----------- |
| [LangSmith](https://www.langchain.com/langsmith) | [LangChain](https://www.langchain.com/) | Span-based tracing system with 100K+ users for full lifecycle observability. |
| [Weights & Biases (W&B)](https://wandb.ai/) | [Weights & Biases](https://wandb.ai/) | Weave framework for GenAI with multimodal tracking and online evaluations. |
| [Langfuse](https://langfuse.com/) | [Langfuse](https://langfuse.com/) | Open-source LLM observability with tracing, evaluation, and cost monitoring. |
| [Phoenix](https://phoenix.arize.com/) | [Arize](https://arize.com/) | Open-source LLM observability with real-time monitoring. |
| [Helicone](https://www.helicone.ai/) | [Helicone](https://www.helicone.ai/) | LLM observability platform with cost and performance tracking. |

## Penetration Testing Tools
| Name | Author | Description |
| ---- | ------ | ----------- |
| [PentestGPT](https://github.com/GreyDGL/PentestGPT) | [GreyDGL](https://github.com/GreyDGL) | GPT-empowered penetration testing tool. Presented at USENIX Security 2024. |
| [AI-penetration-testing](https://github.com/Mr-Infect/AI-penetration-testing) | [Mr-Infect](https://github.com/Mr-Infect) | #1 GitHub resource for AI security with offensive and defensive techniques. |
| [PentAGI](https://github.com/vxcontrol/pentagi) | [vxcontrol](https://github.com/vxcontrol) | Fully autonomous AI agents with ctester utility for validation. |
| [AI-OPS](https://github.com/antoninoLorenzo/AI-OPS) | [antoninoLorenzo](https://github.com/antoninoLorenzo) | Open-source LLM-based assistant for exploit development and vulnerability research. |
| [HackSynth](https://github.com/aielte-research/HackSynth) | [aielte-research](https://github.com/aielte-research) | LLM agent for autonomous pentesting with Planner and Summarizer modules. |
| [HexStrike AI MCP Agents](https://github.com/0x4m4/hexstrike-ai) | [0x4m4](https://github.com/0x4m4) | 150+ cybersecurity tools with automated pentesting and bug bounty automation. |

## Awesome Lists
| Name | Author | Description |
| ---- | ------ | ----------- |
| [awesome-llm-security](https://github.com/corca-ai/awesome-llm-security) | [corca-ai](https://github.com/corca-ai) | Comprehensive curation of tools, documents, and projects about LLM Security. |
| [awesome-gpt-security](https://github.com/cckuailong/awesome-gpt-security) | [cckuailong](https://github.com/cckuailong) | Curated list of security tools and experimental cases for LLM/GPT. |
| [awesome-llm-cybersecurity-tools](https://github.com/tenable/awesome-llm-cybersecurity-tools) | [Tenable](https://github.com/tenable) | Large language model tools for cybersecurity research. |
| [Awesome-LLMSecOps](https://github.com/wearetyomsmnv/Awesome-LLMSecOps) | [wearetyomsmnv](https://github.com/wearetyomsmnv) | LLM Security Operations lifecycle and threats. |
| [awesome-llm-supply-chain-security](https://github.com/ShenaoW/awesome-llm-supply-chain-security) | [ShenaoW](https://github.com/ShenaoW) | Resources about LLM supply chain security including papers and CVEs. |
| [awesome-MLSecOps](https://github.com/RiccardoBiosas/awesome-MLSecOps) | [RiccardoBiosas](https://github.com/RiccardoBiosas) | Curated list of MLSecOps tools, articles, and resources. |
| [awesome-hallucination-detection](https://github.com/EdinburghNLP/awesome-hallucination-detection) | [EdinburghNLP](https://github.com/EdinburghNLP) | List of papers on hallucination detection in LLMs. |

## Podcasts and Newsletters
| Name | Host/Author | Description |
| ---- | ----------- | ----------- |
| [AI Security Podcast](https://www.aisecuritypodcast.com/) | Ashish Rajan & Caleb Sima | Vendor-neutral bi-weekly podcast covering AI security topics. |
| [The AI Fix Podcast](https://theaifix.com/) | Graham Cluley & Mark Stockley | Best New Podcast award winner covering deepfakes and ML topics. |
| [Smashing Security Podcast](https://www.smashingsecurity.com/) | Graham Cluley | Award-winning podcast (2018-2024) covering AI and cybersecurity. |
| [Resilient Cyber Newsletter](https://resilientcyber.io/) | Chris Hughes | 30,000+ readers. Covers AI, Supply Chain, and AppSec. |

## Other Resources
| Name | Author | Description |
| ---- | ------ | ----------- |
| [Rez0 Security Blog](https://josephthacker.com/) | Joseph Thacker | AI hacking fundamentals, techniques, and mindset articles. Definitive guide on hacking AI apps. |
| [Simon Willison's Blog](https://simonwillison.net) | Simon Willison | Co-creator of Django. Expert insights on prompt injection attacks and "Lethal Trifecta" concept. |
| [Lakera AI Blog](https://www.lakera.ai/blog) | Lakera Team | Thought leadership in GenAI security from ex-Google/Meta engineers. |
| [Anthropic Transparency Hub](https://www.anthropic.com/transparency) | Anthropic | Model safety reports and red team findings. |
| [OpenAI Red Teaming Network](https://openai.com/index/red-teaming-network/) | OpenAI | Red teaming documentation and system cards. |
| [MLSecOps.com](https://mlsecops.com/) | Community | Community resources and best practices for ML Security Operations. |

## Thought Leaders
| Name | Platform | Description |
| ---- | -------- | ----------- |
| [Simon Willison](https://twitter.com/simonw) | Twitter/Blog | Co-creator of Django, Datasette. Expert on prompt injection attacks. |
| [Joseph Thacker (rez0)](https://twitter.com/rez0__) | Twitter/Blog | Principal AI Engineer at AppOmni. 1,000+ vulnerabilities submitted. |
| [Lakera](https://twitter.com/lakeraai) | Twitter | Creators of Gandalf. GenAI security thought leaders. |
| [NVIDIA AI Red Team](https://twitter.com/NVIDIAAIDev) | Twitter | Creators of garak LLM vulnerability scanner. |
| [Microsoft AI Red Team](https://twitter.com/MSFTSecurity) | Twitter | Creators of PyRIT framework. |

## Contributions

1. **Repository Purpose:** This repository aims to collect AI Security, LLM Security, and Prompt Injection tools and resources. Preference is given to open-source or community editions of tools, Creative Commons resources, and content created by the community for the benefit of the community.

2. **Out of Scope:** Pull requests that involve vendor-specific content, advertisements, commercial or restricted products, free trials, freemium services, closed-source (proprietary) software, or services that require users to provide private details will be considered out of scope and may be closed or ignored.

3. **Relevance:** Contributions must be directly related to AI security, LLM security, prompt injection, jailbreaking, model security, AI red teaming, or AI application security. Materials unrelated to these topics may be discarded.

4. **Duplicates and Relevance:** Duplicate entries or submissions that do not add new, relevant content beyond existing entries will not be considered.

5. **Out of Scope PRs:** Pull requests that fall outside the scope of this repository are likely to be discarded, closed, or ignored without notice.

6. **Thought Leaders Section:** The Thought Leaders section references authors of books, videos, workshops, courses, newsletters, or other content already present in this repository. While this section is somewhat subjective, it has been included as it might be helpful to some visitors of the repository.

7. **Content Accuracy:** If you are an author of tools or content and notice that your description is inaccurate or outdated in any section, please reach out to update it.

8. **Book References:** Books may have an associated cost, which is allowed under certain circumstances as exceptions to the "out-of-scope" rule.

If you think your content fits the above purposes, please:
- Create a new branch
- Change README.md
- Push the new changes
- Open a pull request

For more details check GitHub [quickstart/contributing-to-projects](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
