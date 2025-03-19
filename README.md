# Awesome-Trustworthy-GUI-Agents
A curated list of papers on trustworthy GUI agents

## Contents

- [Introduction](#introduction)
- [Security and Privacy](#security-and-privacy)
- [Reliability and Safety](#reliability-and-safety)
- [Explainability and Transparency](#explainability-and-transparency)
- [Ethical Implications](#ethical-implications)
- [Evaluation Frameworks](#evaluation-frameworks)
- [Future Directions](#future-directions)
- [Related Surveys](#related-surveys)

## Introduction

GUI agents, powered by large foundation models, interact with digital interfaces through mouse and keyboard actions, enabling applications in web automation, mobile navigation, and software testing. However, their increasing autonomy raises critical concerns about security, privacy, and reliability. This repository collects research papers addressing these challenges across multiple dimensions to foster the development of more trustworthy GUI agents.

## Security and Privacy

### Attack Vectors & Vulnerabilities

- [Imprompter: Tricking LLM Agents into Improper Tool Use](https://arxiv.org/abs/2410.14923) - Wu et al. (2024)
- [Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents](https://arxiv.org/abs/2410.13886) - Kumar et al. (2024)
- [WIPI: A New Web Threat for LLM-Driven Web Agents](https://arxiv.org/abs/2402.16965) - Wu et al. (2024)
- [AdvWeb: Controllable Black-Box Attacks on VLM-Powered Web Agents](https://arxiv.org/abs/2410.17401) - Xu et al. (2024)
- [AEIA-MN: Evaluating the Robustness of Multimodal LLM-Powered Mobile Agents Against Active Environmental Injection Attacks](https://arxiv.org/abs/2502.13053) - Chen et al. (2025)
- [Dissecting Adversarial Robustness of Multimodal LM Agents](https://arxiv.org/abs/2406.12814) - Wu et al. (2024)
- [Security Matrix for Multimodal Agents on Mobile Devices: A Systematic and Proof of Concept Study](https://arxiv.org/abs/2407.09295) - Yang et al. (2024)

### Privacy Risks

- [CLEAR: Towards Contextual LLM-Empowered Privacy Policy Analysis and Risk Generation for Large Language Model Applications](https://arxiv.org/abs/2410.13387) - Chen et al. (2024)
- [EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage](https://arxiv.org/abs/2409.11295) - Liao et al. (2024)
- [When LLMs Go Online: The Emerging Threat of Web-Enabled LLMs](https://arxiv.org/abs/2410.14569) - Kim et al. (2024)
- [Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats in LLM-Based Agents](https://arxiv.org/abs/2411.09523) - Gan et al. (2024)
- [Protecting Users from Themselves: Safeguarding Contextual Privacy in Interactions with Conversational Agents](https://arxiv.org/abs/2502.18509) - Ngong et al. (2025)

### Defense & Mitigation

- [GuardAgent: Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning](https://arxiv.org/abs/2406.09187) - Xiang et al. (2024)
- [AdversaFlow: Visual Red Teaming for Large Language Models with Multi-Level Adversarial Flow](https://dl.acm.org/doi/abs/10.1109/TVCG.2024.3456150) - Deng et al. (2024)
- [PAPILLON: PrivAcy Preservation from Internet-based and Local Language Model Ensembles](https://arxiv.org/abs/2410.17127) - Siyan et al. (2024)
- [Defending Language Models Against Image-Based Prompt Attacks via User-Provided Specifications](https://www.computer.org/csdl/proceedings-article/spw/2024/548700a112/1YiWkfh8fV6) - Sharma et al. (2024)
- [G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems](https://arxiv.org/abs/2502.11127) - Wang et al. (2025)

## Reliability and Safety

### Visual Hallucination

- [Caution for the Environment: Multimodal Agents are Susceptible to Environmental Distractions](https://arxiv.org/abs/2408.02544) - Ma et al. (2024)
- [OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation](https://arxiv.org/abs/2311.17911) - Huang et al. (2024)
- [Volcano: Mitigating Multimodal Hallucination Through Self-Feedback Guided Revision](https://arxiv.org/abs/2311.07362) - Lee et al. (2023)
- [Hallucination Augmented Contrastive Learning for Multimodal Large Language Model](https://arxiv.org/abs/2312.06968) - Jiang et al. (2024)
- [Mitigating Large Vision-Language Model Hallucination at Post-hoc via Multi-agent System](https://ojs.aaai.org/index.php/AAAI-SS/article/view/31780) - Yu et al. (2024)
- [Unified Hallucination Detection for Multimodal Large Language Models](https://arxiv.org/abs/2402.03190) - Chen et al. (2024)

### Content Safety

- [CoCA: Regaining Safety-awareness of Multimodal Large Language Models with Constitutional Calibration](https://arxiv.org/abs/2409.11365) - Gao et al. (2024)
- [Improving Alignment and Robustness with Circuit Breakers](https://arxiv.org/abs/2406.04313) - Zou et al. (2024)
- [RapGuard: Safeguarding Multimodal Large Language Models via Rationale-aware Defensive Prompting](https://arxiv.org/abs/2412.18826) - Jiang et al. (2024)
- [LLM Self Defense: By Self Examination, LLMs Know They Are Being Tricked](https://arxiv.org/abs/2308.07308) - Phute et al. (2023)
- [Defending ChatGPT against Jailbreak Attack via Self-Reminders](https://www.nature.com/articles/s42256-023-00765-8) - Xie et al. (2023)
- [AI Control: Improving Safety Despite Intentional Subversion](https://arxiv.org/abs/2312.06942) - Greenblatt et al. (2023)
- [Towards Safer Large Language Models through Machine Unlearning](https://arxiv.org/abs/2402.10058) - Liu et al. (2024)

### Human Value Alignment

- [TrustAgent: Towards Safe and Trustworthy LLM-based Agents](https://arxiv.org/abs/2402.01586) - Hua et al. (2024)
- [Responsible Task Automation: Empowering Large Language Models as Responsible Task Automators](https://arxiv.org/abs/2306.01242) - Zhang et al. (2023)
- [FREYR: A Framework for Recognizing and Executing Your Requests](https://arxiv.org/abs/2501.12423) - Gallotta et al. (2025)
- [Evaluating Cultural and Social Awareness of LLM Web Agents](https://arxiv.org/abs/2410.23252) - Qiu et al. (2024)
- [Cooperate or Collapse: Emergence of Sustainability in a Society of LLM Agents](https://arxiv.org/abs/2404.16698) - Piatti et al. (2024)
- [Auto-Intent: Automated Intent Discovery and Self-Exploration for Large Language Model Web Agents](https://arxiv.org/abs/2410.22552) - Kim et al. (2024)
- [VisualCritic: Making LMMs Perceive Visual Quality Like Humans](https://arxiv.org/abs/2403.12806) - Huang et al. (2024)

## Explainability and Transparency

### Explaining Agent Behavior

- [Explainable Behavior Cloning: Teaching Large Language Model Agents through Learning by Demonstration](https://arxiv.org/abs/2410.22916) - Guan et al. (2024)
- [PC-Agent: A Hierarchical Multi-Agent Collaboration Framework for Complex Task Automation on PC](https://arxiv.org/abs/2502.14282) - Liu et al. (2025)
- [MOBA: A Two-Level Agent System for Efficient Mobile Task Automation](https://arxiv.org/abs/2410.13757) - Zhu et al. (2024)
- [XAgent: A Conversational XAI Agent Harnessing the Power of Large Language Models](https://ceur-ws.org/Vol-3793/paper_35.pdf) - Nguyen et al. (2024)
- [OSCAR: Operating System Control via State-Aware Reasoning and Re-Planning](https://arxiv.org/abs/2410.18963) - Wang et al. (2024)

### Transparency in Decision-Making

- [Explainable Multi-Modal Data Exploration in Natural Language via LLM Agent](https://arxiv.org/abs/2412.18428) - Nooralahzadeh et al. (2024)
- [Towards Explainable Network Intrusion Detection Using Large Language Models](https://arxiv.org/abs/2408.04342) - Houssel et al. (2024)
- [Explainable Search and Discovery of Visual Cultural Heritage Collections with Multimodal Large Language Models](https://arxiv.org/abs/2411.04663) - Arnold et al. (2024)
- [Web Agents with World Models: Learning and Leveraging Environment Dynamics in Web Navigation](https://arxiv.org/abs/2410.13232) - Chae et al. (2024)
- [Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents](https://arxiv.org/abs/2411.06559) - Gu et al. (2024)

### User-Centric Explanations

- [Digital Forms for All: A Holistic Multimodal Large Language Model Agent for Health Data Entry](https://dl.acm.org/doi/10.1145/3659624) - Cuadra et al. (2024)
- [Towards Human-Level Understanding of Complex Process Engineering Schematics: A Pedagogical, Introspective Multi-Agent Framework for Open-Domain Question Answering](https://arxiv.org/abs/2409.00082) - Srinivas et al. (2024)
- [Enhancing User Experience and Trust in Advanced LLM-based Conversational Agents](https://ojs.acad-pub.com/index.php/CAI/article/view/1467
) - Xu et al. (2024)

## Ethical Implications

### Cultural and Social Awareness

- [Evaluating Cultural and Social Awareness of LLM Web Agents](https://arxiv.org/abs/2410.23252) - Qiu et al. (2024)
- [Cooperate or Collapse: Emergence of Sustainability in a Society of LLM Agents](https://arxiv.org/abs/2404.16698) - Piatti et al. (2024)
- [Digital Forms for All: A Holistic Multimodal Large Language Model Agent for Health Data Entry](https://dl.acm.org/doi/10.1145/3659624) - Cuadra et al. (2024)
- [Culture is Not Trivia: Sociocultural Theory for Cultural NLP](https://arxiv.org/abs/2502.12057) - Zhou et al. (2025)

### Policy Implications

- [Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats in LLM-Based Agents](https://arxiv.org/abs/2411.09523) - Gan et al. (2024)
- [CLEAR: Towards Contextual LLM-Empowered Privacy Policy Analysis and Risk Generation for Large Language Model Applications](https://arxiv.org/abs/2410.13387) - Chen et al. (2024)
- [ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://arxiv.org/abs/2410.06703) - Levy et al. (2024)
- [Decentralised Governance-Driven Architecture for Designing Foundation Model based Systems: Exploring the Role of Blockchain in Responsible AI](https://arxiv.org/abs/2308.05962) - Liu et al. (2023)

### Guidelines and Principles

- [Towards Responsible Generative AI: A Reference Architecture for Designing Foundation Model Based Agents](https://arxiv.org/abs/2311.13148) - Lu et al. (2023)
- [Responsible Task Automation: Empowering Large Language Models as Responsible Task Automators](https://arxiv.org/abs/2306.01242) - Zhang et al. (2023)
- [TrustAgent: Towards Safe and Trustworthy LLM-based Agents](https://arxiv.org/abs/2402.01586) - Hua et al. (2024)
- [OS-Atlas: A Foundation Action Model for Generalist GUI Agents](https://arxiv.org/abs/2410.23218) - Wu et al. (2024)
- [Authenticated Delegation and Authorized AI Agents](https://arxiv.org/abs/2501.09674) - South et al. (2025)
- [Conversational AI Powered by Large Language Models Amplifies False Memories in Witness Interviews](https://arxiv.org/abs/2408.04681) - Chan et al. (2024)

## Evaluation Frameworks

### Security & Privacy Evaluation

- [InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents](https://arxiv.org/abs/2403.02691) - Zhan et al. (2024)
- [BrowserART: Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents](https://arxiv.org/abs/2410.13886) - Kumar et al. (2024)
- [AdvWeb: Controllable Black-Box Attacks on VLM-Powered Web Agents](https://arxiv.org/abs/2410.17401) - Xu et al. (2024)
- [EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage](https://arxiv.org/abs/2409.11295) - Liao et al. (2024)
- [PAPILLON: PrivAcy Preservation from Internet-based and Local Language MOdel ENsembles](https://arxiv.org/abs/2410.17127) - Siyan et al. (2024)
- [Dissecting Adversarial Robustness of Multimodal LM Agents](https://arxiv.org/abs/2406.12814) - Wu et al. (2024)

### Safety & Reliability Assessment

- [Agent-SafetyBench: Evaluating the Safety of LLM Agents](https://arxiv.org/abs/2412.14470) - Zhang et al. (2024)
- [AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/abs/2410.09024) - Andriushchenko et al. (2024)
- [MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control](https://arxiv.org/abs/2410.17520) - Lee et al. (2024)
- [ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://arxiv.org/abs/2410.06703) - Levy et al. (2024)
- [GUI Testing Arena: A Unified Benchmark for Advancing Autonomous GUI Testing Agent](https://arxiv.org/abs/2412.18426) - Zhao et al. (2024)
- [AHA!: Facilitating AI Impact Assessment by Generating Examples of Harms](https://arxiv.org/abs/2306.03280) - Bucinca et al. (2023)

### Multimodal Safety & Cultural Alignment

- [MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models](https://arxiv.org/abs/2311.17600) - Liu et al. (2023)
- [Multimodal Situational Safety](https://arxiv.org/abs/2410.06172) - Zhou et al. (2024)
- [CASA: Evaluating Cultural and Social Awareness of LLM Web Agents](https://arxiv.org/abs/2410.23252) - Qiu et al. (2024)
- [ChEF: A Comprehensive Evaluation Framework for Standardized Assessment of Multimodal Large Language Models](https://arxiv.org/abs/2311.02692) - Shi et al. (2023)

## Future Directions

- **Security Architecture**: Developing trusted UI layers for content sanitization, dynamic verification of web elements, and security policies specialized for GUI tasks
- **Privacy-Preserving Frameworks**: Building federated processing, minimal data retention strategies, and fine-grained access controls for sensitive domains
- **Adaptive Defense Mechanisms**: Combining machine learning anomaly detection with rule-based constraints to balance caution and responsiveness
- **Multimodal Defense Systems**: Creating resilient multimodal analysis methods and adversarial simulation environments that stress-test agents against emerging threats
- **Value-Aligned Safety Protocols**: Implementing context-aware moderation systems and violation tracking across action sequences
- **Human-Agent Teamwork**: Designing intuitive user controls, real-time preference interfaces, explainable override options, and GUI-specific reinforcement learning from human feedback

## Related Surveys

- [GUI Agents: A Survey](https://arxiv.org/abs/2412.13501) - Nguyen et al. (2024)
- [Large Language Model-Brained GUI Agents: A Survey](https://arxiv.org/abs/2411.18279) - Zhang et al. (2025)
- [The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies](https://arxiv.org/abs/2407.19354) - He et al. (2024)
- [Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats in LLM-Based Agents](https://arxiv.org/abs/2411.09523) - Gan et al. (2024)
- [Jailbreak Attacks and Defenses against Multimodal Generative Models: A Survey](https://arxiv.org/abs/2411.09259) - Liu et al. (2024)
- [On the Trustworthiness of Generative Foundation Models: Guideline, Assessment, and Perspective](https://arxiv.org/abs/2502.14296) - Huang et al. (2025)
- [A Comprehensive Survey of Hallucination in Large Language, Image, Video and Audio Foundation Models](https://aclanthology.org/2024.findings-emnlp.685.pdf) - Sahoo et al. (2024)
- [Large Model Based Agents: State-of-the-Art, Cooperation Paradigms, Security and Privacy, and Future Trends](https://arxiv.org/abs/2409.14457) - Wang et al. (2024)

## Contributing

Contributions welcome!
