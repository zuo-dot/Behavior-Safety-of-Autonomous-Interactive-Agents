
<h1 align="center">Behavior Safety of Autonomous Interactive Agents: Risks, Attacks, Defenses, Evaluation, and Governance</h1>
<div align="center">

[![Visits](https://hits.sh/github.com/zuo-dotBehavior-Safety-of-Autonomous-Interactive-Agents.svg?style=flat-square&label=visits)](https://hits.sh/github.com/zuo-dot/Behavior-Safety-of-Autonomous-Interactive-Agents/)
![Stars](https://img.shields.io/github/stars/zuo-dot/Behavior-Safety-of-Autonomous-Interactive-Agents?style=flat-square)
![Forks](https://img.shields.io/github/forks/zuo-dot/Behavior-Safety-of-Autonomous-Interactive-Agents?style=flat-square)

</div>




## 🧾Paper List

<details open>
  <summary>📂 Table of Contents<em>(click to expand/collapse)</em></summary>
  <ul>
    <li><a href="#intrinsic-cognitive-vulnerability">Intrinsic Cognitive Vulnerability</a>
      <ul>
        <li><a href="#foundation-model-vulnerability">Foundation Model Vulnerability</a>
          <ul>
            <li><a href="#behavioral-objective-deviation">Behavioral Objective Deviation</a></li>
            <li><a href="#memory-shortcuts">Memory Shortcuts</a></li>
            <li><a href="#infinite-planning-loop">Infinite Planning Loop</a></li>
            <li><a href="#reflective-rigidity">Reflective Rigidity</a></li>
            <li><a href="#intention-drift">Intention Drift</a></li>
          </ul>
        <li><a href="#memory-vulnerability">Memory Vulnerability</a>
          <ul>
            <li><a href="#memory-contamination">Memory Contamination</a></li>
            <li><a href="#memory-conflict">Memory Conflict</a></li>
            <li><a href="#memory-misevolution">Memory Misevolution</a></li>
          </ul>
        <li><a href="#tool-invocation-vulnerability">Tool-invocation Vulnerability</a>
        <li><a href="#multi-agent collaboration vulnerability">Multi-agent Collaboration Vulnerability</a>
        </li>
      </ul>
    </li>
    <li><a href="#extrinsic-loss-of-control risk">Extrinsic Loss-of-control Risk</a>
      <ul>
        <li><a href="#supply-chain-manipulation">Supply-Chain Manipulation</a>
          <ul>
            <li><a href="#data-poisoning">Data Poisoning</a></li>
            <li><a href="#backdoor-attacks">backdoor attacks</a></li>
          </ul>
        </li>
        <li><a href="#user-level-manipulation">User-Level Manipulation</a>
          <ul>
            <li><a href="#direct-prompt-injection">Direct Prompt Injection</a></li>
            <li><a href="#jailbreak-jailbreak">Jailbreak Jailbreak</a></li>
            <li><a href="#long-horizon-manipulation">Long-Horizon Manipulation</a></li>
          </ul>
        </li>
        <li><a href="#environment-level-manipulation">Environment-Level Manipulation</a>
          <ul>
            <li><a href="#indirect-prompt-injection">Indirect Prompt Injection</a></li>
            <li><a href="#memory-poisoning">Memory Poisoning</a></li>
          </ul>
        </li>
        <li><a href="#cross-agent-interaction-risks">Cross-Agent Interaction Risks</a>
          <ul>
            <li><a href="#collusion">Collusion</a></li>
            <li><a href="#worm-propagation">Worm Propagation</a></li>
          </ul>
        </li>
      </ul>
    </li>
    <li><a href="#community-safety">Community Safety</a>
      <ul>
        <li><a href="#communication-protocol-risks">Communication Protocol Risks</a></li>
        <li><a href="#third-party-extension-risks">Third-Party Extension Risks</a></li>
        <li><a href="#skill-risks">Skill Riskss</a></li>
      </ul>
    </li>
    <li><a href="#system-safety">System Safety</a>
      <ul>
        <li><a href="#resource-exhaustion">Resource Exhaustion</a></li>
        <li><a href="#isolation-and-permission-failures">Isolation and Permission Failures</a></li>
      </ul>
    </li>
    <li><a href="#evaluation">Evaluation</a>
      <ul>
        <li><a href="#intrinsic-safety-benchmarks">Intrinsic Safety Benchmarks</a></li>
        <li><a href="#extrinsic-attack-benchmarks">Extrinsic Attack Benchmarks</a></li>
      </ul>
    </li>
  </ul>
</details>





<a name="intrinsic-cognitive-vulnerability"></a>
#  Intrinsic Cognitive Vulnerability
* (2024) [Ai agents under threat: A  survey of key security challenges and future pathways]((https://arxiv.org/pdf/2406.02630))
* (2024) [The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies](https://arxiv.org/abs/2407.19354)
* (2024) [Me, Myself, and AI: The Situational Awareness Dataset (SAD) for LLMs](https://proceedings.neurips.cc/paper_files/paper/2024/file/7537726385a4a6f94321e3adf8bd827e-Paper-Datasets_and_Benchmarks_Track.pdf)

<a name="foundation-model-vulnerability"></a>
###  Foundation Model Vulnerability
<a name="behavioral-objective-deviation"></a>
#####  Behavioral Objective Deviation
* (2025) [AgentMisalignment: Measuring the Propensity for Misaligned Behaviour in LLM-Based Agents](https://arxiv.org/abs/2506.04018)
* (2025) [LLM-based Agents Suffer from Hallucinations: A Survey of Taxonomy, Methods, and Directions](https://arxiv.org/abs/2509.18970)
* (2026) [AgentHallu: Benchmarking Automated Hallucination Attribution of LLM-based Agents](https://arxiv.org/html/2601.06818v1)
* (2024) [THaMES: An End-to-End Tool for Hallucination Mitigation and Evaluation in Large Language Models](https://arxiv.org/abs/2409.11353)
* (2024) [FreshLLMs: Refreshing Large Language Models with Search Engine Augmentation](https://arxiv.org/abs/2310.03214)
* (2023) [Enhancing zero-shot chain-of-thought reasoning in large language models through logic](https://arxiv.org/abs/2309.13339)
* (2023) [Chain-of-Verification Reduces Hallucination in Large Language Models](https://arxiv.org/abs/2309.11495)
* (2024) [Learning to Trust Your Feelings: Leveraging Self-awareness in LLMs for Hallucination Mitigation](https://arxiv.org/abs/2401.15449)
* (2024) [SaySelf: Teaching LLMs to Express Confidence with Self-Reflective Rationales](https://arxiv.org/abs/2405.20974)
* (2025) [Hallucination Mitigation using Agentic AI Natural Language-Based Frameworks](https://arxiv.org/abs/2501.13946)
* (2025) [EH-Benchmark Ophthalmic Hallucination Benchmark and Agent-Driven Top-Down Traceable Reasoning Workflow](https://arxiv.org/abs/2507.22929)
* (2025) [Large Language Models Hallucination: A Comprehensive Survey](http://arxiv.org/abs/2510.06265)
* (2024) [Artificial intelligence and increasing misinformation](https://www.cambridge.org/core/journals/the-british-journal-of-psychiatry/article/artificial-intelligence-and-increasing-misinformation/DCCE0EB214E3D375A3006AA69FFB210D)
* (2023) [LM vs LM: Detecting Factual Errors via Cross Examination](https://arxiv.org/abs/2305.13281)
* (2024) [RAC: Efficient LLM Factuality Correction with Retrieval Augmentation](https://arxiv.org/abs/2410.15667)
* (2025) [Improving Factuality with Explicit Working Memory](https://arxiv.org/abs/2412.18069)
* (2025) [Bias recognition and mitigation strategies in artificial intelligence healthcare applications](https://www.nature.com/articles/s41746-025-01503-7)
* (2025) [Ethical and Bias Considerations in Artificial Intelligence/Machine Learning](https://www.sciencedirect.com/science/article/pii/S0893395224002667)
* (2024) [Self-Debiasing Large Language Models: Zero-Shot Recognition and Reduction of Stereotypes](https://arxiv.org/abs/2402.01981)
* (2025) [Social Debiasing for Fair Multi-modal LLMs](https://arxiv.org/abs/2408.06569)
* (2024) [A Multi-LLM Debiasing Framework](https://arxiv.org/abs/2409.13884)
* (2025) [Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework](https://arxiv.org/abs/2412.15504)
* (2025) [Safety Tax: Safety Alignment Makes Your Large Reasoning Models Less Reasonable](https://arxiv.org/abs/2503.00555)
* (2024) [Deliberative Alignment: Reasoning Enables Safer Language Models](https://arxiv.org/abs/2412.16339)
* (2025) [SafeConstellations: Steering LLM Safety to Reduce Over-Refusals Through Task-Specific Trajectory](https://arxiv.org/html/2508.11290v1)
* (2025) [AgentAlign: Navigating Safety Alignment in the Shift from Informative to Agentic Large Language Models](https://arxiv.org/abs/2505.23020)
* (2026) [On-Policy Self-Evolution via Failure Trajectories for Agentic Safety Alignment](https://arxiv.org/abs/2605.11882)
<a name="memory-shortcuts"></a>
#####  Memory Shortcuts
* (2023) [Large Language Models Can be Lazy Learners: Analyze Shortcuts in In-Context Learning](https://arxiv.org/abs/2305.17256)
* (2023) [Shortcut Learning of Large Language Models in Natural Language Understanding](https://arxiv.org/abs/2208.11857)
* (2024) ["My agent understands me better": Integrating Dynamic Human-like Memory Recall and Consolidation in LLM-Based Agents](https://arxiv.org/abs/2404.00573)
* (2024) [Needle in the Haystack for Memory Based Large Language Models](https://arxiv.org/abs/2407.01437)
* (2026) [The Trap of Trajectory: Towards Understanding and Mitigating Spurious Correlations in Agentic Memory](https://arxiv.org/abs/2605.09330)
* (2024) [Larimar: Large Language Models with Episodic Memory Control](https://arxiv.org/abs/2403.11901)
* (2024) [HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model](https://arxiv.org/abs/2408.09559)
* (2025) [A2AS: Agentic AI Runtime Security and Self-Defense](https://arxiv.org/abs/2510.13825)
<a name="infinite-planning-loop"></a>
#####  Infinite Planning Loop
* (2024) [Revealing the Barriers of Language Agents in Planning](https://arxiv.org/abs/2410.12409)
* (2025) [Path Coordination for Robust, Fast, and Scalable Multi-Agent Path Finding Under Unforeseen Delays](https://ieeexplore.ieee.org/abstract/document/11185122)
* (2025) [On the Limits of Innate Planning in Large Language Models](https://arxiv.org/abs/2511.21591)
* (2026) [The cognitive companion: a lightweight parallel monitoring architecture for detecting and recovering from reasoning degradation in LLM agents](https://arxiv.org/abs/2604.13759)
* (2025) [Evaluating Uncertainty-based Failure Detection for Closed-Loop LLM Planners](https://arxiv.org/abs/2406.00430)
* (2025) [ALAS: Transactional and Dynamic Multi-Agent LLM Planning](https://arxiv.org/abs/2511.03094)
* (2025) [On the Limits of Innate Planning in Large Language Models](https://arxiv.org/abs/2511.21591)
* (2025) [Agent-Oriented Planning in Multi-Agent Systems](https://arxiv.org/abs/2410.02189)
<a name="reflective-rigidity"></a>
#####  Reflective Rigidity
* (2024) [Self-Contrast: Better Reflection Through Inconsistent Solving Perspectives](https://aclanthology.org/2024.acl-long.197.pdf)
* (2025) [Illusions of reflection: open-ended task reveals systematic failures in Large Language Models' reflective reasoning](https://arxiv.org/abs/2510.18254)
* (2023) [Self-Correction Bench: Uncovering and Addressing the Self-Correction Blind Spot in Large Language Models](https://arxiv.org/abs/2507.02778)
* (2026) [Think Fast and Slow: Step-Level Cognitive Depth Adaptation for LLM Agents](https://arxiv.org/abs/2602.12662)
* (2026) [Mitigating Cognitive Inertia in Large Reasoning Models via Latent Spike Steering](https://arxiv.org/abs/2601.22484)
<a name="intention-drift"></a>
#####  Intention Drift
* (2025) [Technical Report: Evaluating Goal Drift in Language Model Agents](https://arxiv.org/abs/2505.02709)
* (2026) [The Causal Impact of Tool Affordance on Safety Alignment in LLM Agents](https://arxiv.org/abs/2603.20320)
* (2024) [Semantic Drift Mitigation in Large Language Model Knowledge Retention Using the Residual Knowledge Stability Concept](https://www.techrxiv.org/doi/full/10.36227/techrxiv.173091142.28945162/v1)
* (2026) [Agent Drift: Quantifying Behavioral Degradation in Multi-Agent LLM Systems Over Extended Interactions](https://arxiv.org/abs/2601.04170)
* (2026) [Alignment Tipping Process: How Self-Evolution Pushes LLM Agents Off the Rails](https://arxiv.org/pdf/2510.04860?)
* (2025) [Stay Focused: Problem Drift in Multi-Agent Debate](https://arxiv.org/abs/2502.19559)
* (2026) [Drift-Bench: Diagnosing Cooperative Breakdowns in LLM Agents under Input Faults via Multi-Turn Interaction](https://arxiv.org/abs/2602.02455)
* (2026) [Detecting and Repairing Role Drift in Multi-Agent Collaboration with Lightweight Protocols](https://ieeexplore.ieee.org/document/11453032)
* (2025) [A Survey on Autonomy-Induced Security Risks in Large Model-Based Agents](https://arxiv.org/abs/2506.23844)
* (2026) [PersonalAlign: Hierarchical Implicit Intent Alignment for Personalized GUI Agent with Long-Term User-Centric Records](https://arxiv.org/html/2601.09636v1)
<a name="memory-vulnerability"></a>
###  Memory Vulnerability
<a name="memory-contamination"></a>
#####  Memory Contamination
* (2026) [Memory Poisoning Propagation and Repair Mechanism in Multi-Agent Collaborative Environments](https://dl.acm.org/doi/10.1145/3806262.3806294)
* (2026) [Remembering More, Risking More: Longitudinal Safety Risks in Memory-Equipped LLM Agents](https://arxiv.org/abs/2605.17830)
* (2024) [INMS: Memory Sharing for Large Language Model based Agents](https://arxiv.org/abs/2404.09982)
* (2026) [Mind Your HEARTBEAT! Claw Background Execution Inherently Enables Silent Memory Pollution](https://arxiv.org/abs/2603.23064)
* (2026) [Governing Evolving Memory in LLM Agents: Risks, Mechanisms, and the Stability and Safety Governed Memory (SSGM) Framework](https://arxiv.org/abs/2603.11768)
* (2026) [No Attacker Needed: Unintentional Cross-User Contamination in Shared-State LLM Agents](https://arxiv.org/abs/2604.01350)
<a name="memory-conflict"></a>
#####  Memory Conflict
* (2024) [A Survey on the Memory Mechanism of Large Language Model based Agents](https://arxiv.org/abs/2404.13501)
* (2026) [MemConflict: Evaluating Long-Term Memory Systems Under Memory Conflicts](https://arxiv.org/abs/2605.20926)
* (2025) [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://arxiv.org/abs/2504.19413)
* (2026) [Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning](https://arxiv.org/abs/2508.19828)
* (2026) [Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions](https://arxiv.org/abs/2507.05257)
* (2025) [Zep: A Temporal Knowledge Graph Architecture for Agent Memory](https://arxiv.org/abs/2501.13956)
* (2026) [Memory for Autonomous LLM Agents:Mechanisms, Evaluation, and Emerging Frontiers](https://arxiv.org/abs/2603.07670)
* (2025) [Towards Lifelong Dialogue Agents via Timeline-based Memory Management](https://arxiv.org/abs/2406.10996)
<a name="memory-misevolution"></a>
#####  Memory Misevolution
* (2026) [From Storage to Experience: A Survey on the Evolution of LLM Agent Memory Mechanisms](https://arxiv.org/abs/2605.06716)
* (2026) [When Routine Chats Turn Toxic: Unintended Long-Term State Poisoning in Personalized Agent](https://arxiv.org/abs/2605.06731)
* (2025) [Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents](https://arxiv.org/abs/2509.26354)
* (2026) [Useful Memories Become Faulty When Continuously Updated by LLMs](https://arxiv.org/abs/2605.12978)
* (2026) [Contextual Agentic Memory is a Memo, Not True Memory](https://arxiv.org/abs/2604.27707)
* (2026) [M⋆: Every Task Deserves Its Own Memory Harness](https://arxiv.org/abs/2604.11811)
* (2026) [Cognitive Autonomous Memory Security (CAMS) against injection and extraction attacks in long-term memory of AI agents](https://www.sciencedirect.com/science/article/pii/S1110866526001003)


<a name="tool-invocation-vulnerability"></a>
###  Tool-invocation Vulnerability
* (2026) [AgenTRIM: Tool Risk Mitigation for Agentic AI](https://arxiv.org/abs/2601.12449)
* (2026) [ToolSafe: Enhancing Tool Invocation Safety of LLM-based agents via Proactive Step-level Guardrail and Feedback](https://arxiv.org/abs/2601.10156)
* (2025) [Securing GenAI Multi-Agent Systems Against Tool Squatting: A Zero Trust Registry-Based Approach](https://arxiv.org/abs/2504.19951)
* (2025) [Position: Agent Should Invoke External Tools ONLY When Epistemically Necessary](https://arxiv.org/abs/2506.00886)
* (2025) [SMART: Self-Aware Agent for Tool Overuse Mitigation](https://arxiv.org/abs/2502.11435)
* (2025) [More Vulnerable than You Think: On the Stability of Tool-Integrated LLM Agents](https://arxiv.org/abs/2506.21967)
* (2025) [STAC: When Innocent Tools Form Dangerous Chains to Jailbreak LLM Agents](https://arxiv.org/abs/2509.25624)
* (2024) [ToolSword: Unveiling Safety Issues of Large Language Models in Tool Learning Across Three Stages](https://arxiv.org/abs/2402.10753)
* (2025) [ToolFuzz -- Automated Agent Tool Testing](https://arxiv.org/abs/2503.04479)
* (2026) [When Agents Fail to Act: A Diagnostic Framework for Tool Invocation Reliability in Multi-Agent LLM Systems](https://arxiv.org/abs/2601.16280)
* (2026) [Act Wisely: Cultivating Meta-Cognitive Tool Use in Agentic Multimodal Models](https://arxiv.org/abs/2604.08545)

<a name="multi-agent collaboration vulnerability"></a>
###  Multi-agent Collaboration Vulnerability
* (2024) [On the Resilience of LLM-Based Multi-Agent Collaboration with Faulty Agents](https://arxiv.org/abs/2408.00989)
* (2025) [Multi-Agent Collaboration Mechanisms: A Survey of LLMs](https://arxiv.org/abs/2501.06322)
* (2025) [SentinelAgent: Graph-based Anomaly Detection in Multi-Agent Systems](https://arxiv.org/abs/2505.24201)
* (2026) [Security Considerations for Multi-agent Systems](https://arxiv.org/abs/2603.09002)
* (2025) [Multi-Agent Risks from Advanced AI](https://arxiv.org/abs/2502.14143)
* (2025) [The Trust Paradox in LLM-Based Multi-Agent Systems: When Collaboration Becomes a Security Vulnerability](https://arxiv.org/abs/2510.18563)
* (2026) [Multi-Agent Orchestration: Coordination, Trust, and Cascading Failures](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6734798)
* (2025) [Safety and Risk Pathways in Cooperative Generative Multi-Agent Systems: A Telecom Perspective](https://arxiv.org/abs/2511.17730)
* (2025) [A Comprehensive Survey on Multi-Agent Cooperative Decision-Making: Scenarios, Approaches, Challenges and Perspectives](https://arxiv.org/abs/2503.13415)
* (2026) [Agent Drift: Quantifying Behavioral Degradation in Multi-Agent LLM Systems Over Extended Interactions](https://arxiv.org/abs/2601.04170)
* (2026) [When Agents Fail to Act: A Diagnostic Framework for Tool Invocation Reliability in Multi-Agent LLM Systems]
* (2025) [Can Competition Enhance the Proficiency of Agents Powered by Large Language Models in the Realm of News-driven Time Series Forecasting?](https://arxiv.org/abs/2504.10210)
* (2024) [The Hunger Game Debate: On the Emergence of Over-Competition in Multi-Agent Systems](https://arxiv.org/abs/2509.26126)
* (2025) [M2I2: Learning Efficient Multi-Agent Communication via Masked State Modeling and Intention Inference](https://arxiv.org/abs/2501.00312)
* (2025) [Can Competition Enhance the Proficiency of Agents Powered by Large Language Models in the Realm of News-driven Time Series Forecasting?]
* (2025) [Agentic AI Security: Threats, Defenses, Evaluation, and Open Challenges](https://arxiv.org/abs/2510.23883)
* (2025) [AgentNet: Decentralized Evolutionary Coordination for LLM-based Multi-Agent Systems](https://arxiv.org/abs/2504.00587)
* (2026) [ProvAgent: Threat Detection Based on Identity-Behavior Binding and Multi-Agent Collaborative Attack Investigation](https://arxiv.org/abs/2603.09358)


<a name="extrinsic-loss-of-control risk"></a>
#  Extrinsic Loss-of-control Risk
<a name="supply-chain-manipulation"></a>
###  Supply-Chain Manipulation
<a name="data-poisoning"></a>
#####  Data Poisoning
* (2025) [Security of LLM-based agents regarding attacks, defenses, and applications: A comprehensive survey](https://www.sciencedirect.com/science/article/abs/pii/S1566253525010036)
* (2025) [PoisonBench: Assessing Large Language Model Vulnerability to Data Poisoning](https://arxiv.org/abs/2410.08811)
* (2026) [Threats and Defenses in Large Language Models: A Review of Adversarial and Model Poisoning Techniques](https://www.techrxiv.org/doi/full/10.36227/techrxiv.177040550.02084667/v1)
* (2025) [A Comprehensive Survey in LLM(-Agent) Full Stack Safety: Data, Training and Deployment](https://arxiv.org/abs/2504.15585)
* (2024) [The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies](https://arxiv.org/abs/2407.19354)
* (2025) [Swallowing the Poison Pills: Insights from Vulnerability Disparity Among LLMs](https://arxiv.org/abs/2502.18518)
* (2026) [Trustworthy AI-Driven Dynamic Hybrid RIS: Joint Optimization and Reward Poisoning-Resilient Control in Cognitive MISO Networks](https://arxiv.org/abs/2604.01238)
* (2025) [Targeted Poisoning of Reinforcement Learning Agents](https://openreview.net/forum?id=GrFogzE5N9)
* (2024) [Preference Poisoning Attacks on Reward Model Learning](https://arxiv.org/abs/2402.01920)
* (2025) [Poisoning Attacks to Local Differential Privacy Protocols for Trajectory Data](https://arxiv.org/abs/2503.07483)
* (2026) [Security of Large Model-based Agents: A Survey on Adversarial, Poisoning, and Backdoor Attacks](https://www.techrxiv.org/doi/full/10.36227/techrxiv.177006506.61959855/v1)
* (2025) [Provable Watermarking for Data Poisoning Attacks](https://arxiv.org/abs/2510.09210)

<a name="backdoor-attacks"></a>
#####  Backdoor Attacks
* (2026) [BackdoorAgent: A Unified Framework for Backdoor Attacks on LLM-based Agents](https://arxiv.org/abs/2601.04566)
* (2024) [BadAgent: Inserting and Activating Backdoor Attacks in LLM Agents](https://arxiv.org/abs/2406.03007)
* (2024) [Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents](https://arxiv.org/abs/2402.11208)
* (2025) [Chain-of-Trigger: An Agentic Backdoor that Paradoxically Enhances Agentic Robustness](https://arxiv.org/abs/2510.08238)
* (2024) [AgentPoison: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases](https://arxiv.org/abs/2407.12784)
* (2025) [DemonAgent: Dynamically Encrypted Multi-Backdoor Implantation Attack on LLM-based Agent](https://arxiv.org/abs/2502.12575)
* (2026) [SkillTrojan: Backdoor Attacks on Skill-Based Agent Systems](https://arxiv.org/abs/2604.06811)
* (2025) [Collaborative Shadows: Distributed Backdoor Attacks in LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2510.11246)
* (2025) [Poison Once, Control Anywhere: Clean-Text Visual Backdoors in VLM-based Mobile Agents](https://arxiv.org/abs/2506.13205)
* (2025) [Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents](https://arxiv.org/abs/2505.14418)
* (2025) [VisualTrap: A Stealthy Backdoor Attack on GUI Agents via Visual Grounding Manipulation](https://arxiv.org/abs/2507.06899)
* (2026) [SlowBA: An efficiency backdoor attack towards VLM-based GUI agents](https://arxiv.org/abs/2603.08316)
* (2025) [Your Agent Can Defend Itself against Backdoor Attacks](https://arxiv.org/abs/2506.08336)
* (2025) [A-MemGuard: A Proactive Defense Framework for LLM-Based Agent Memory](https://arxiv.org/abs/2510.02373)

<a name="user-level-manipulation"></a>
###  User-Level Manipulation
<a name="direct-prompt-injection"></a>
#####  Direct Prompt Injection
* (2026) [Prompt Injection Attacks in Large Language Models and AI Agent Systems: A Comprehensive Review of Vulnerabilities, Attack Vectors, and Defense Mechanisms](https://www.mdpi.com/2078-2489/17/1/54)
* (2025) [Prompt Injection 2.0: Hybrid AI Threats](https://arxiv.org/abs/2507.13169)
* (2026) [A white-box prompt injection attack on embodied AI agents driven by large language models](https://www.sciencedirect.com/science/article/abs/pii/S0164121226000166)
* (2025) [To Protect the LLM Agent Against the Prompt Injection Attack with Polymorphic Prompt](https://arxiv.org/abs/2506.05739)
* (2025) [AegisAgent: An Autonomous Defense Agent Against Prompt Injection Attacks in LLM-HARs](https://arxiv.org/abs/2512.20986)
* (2025) [A Multi-Agent LLM Defense Pipeline Against Prompt Injection Attacks](https://arxiv.org/abs/2509.14285)
* (2025) [AgentArmor: Enforcing Program Analysis on Agent Runtime Trace to Defend Against Prompt Injection](https://arxiv.org/abs/2508.01249)
* (2025) [Prompt Injection Detection and Mitigation via AI Multi-Agent NLP Frameworks](https://arxiv.org/abs/2503.11517)
* (2026) [Agentic AI as a Cybersecurity Attack Surface: Threats, Exploits, and Defenses in Runtime Supply Chains](https://arxiv.org/html/2602.19555v1)

<a name="jailbreak-jailbreak"></a>
#####  Jailbreak Jailbreak
* (2026) [BadRobot: Jailbreaking Embodied LLM Agents in the Physical World](https://arxiv.org/abs/2407.20242)
* (2026) [Breaking the Code: Security Assessment of AI Code Agents Through Systematic Jailbreaking Attacks](https://arxiv.org/abs/2510.01359)
* (2025) [Safe in Isolation, Dangerous Together: Agent-Driven Multi-Turn Decomposition Jailbreaks on LLMs](https://aclanthology.org/2025.realm-1.13/)
* (2026) [David vs. Goliath: Verifiable Agent-to-Agent Jailbreaking via Reinforcement Learning](https://arxiv.org/abs/2602.02395)
* (2025) [X-Teaming: Multi-Turn Jailbreaks and Defenses with Adaptive Multi-Agents](https://arxiv.org/abs/2504.13203)
* (2025) [JPRO: Automated Multimodal Jailbreaking via Multi-Agent Collaboration Framework](https://arxiv.org/abs/2511.07315)
* (2025) [MetaCipher: A Time-Persistent and Universal Multi-Agent Framework for Cipher-Based Jailbreak Attacks for LLMs](https://arxiv.org/abs/2506.22557)
* (2025) [Fuzz-Testing Meets LLM-Based Agents: An Automated and Efficient Framework for Jailbreaking Text-To-Image Generation Models](https://arxiv.org/abs/2408.00523)
* (2026) [Every Picture Tells a Dangerous Story: Memory-Augmented Multi-Agent Jailbreak Attacks on VLMs](https://arxiv.org/abs/2604.12616)
* (2025) [Amplified Vulnerabilities: Structured Jailbreak Attacks on LLM-based Multi-Agent Debate](https://arxiv.org/abs/2504.16489)
* (2025) [SafeMobile: Chain-level Jailbreak Detection and Automated Evaluation for Multimodal Mobile Agents](https://arxiv.org/abs/2507.00841)
* (2025) [Guardians of the Agentic System: Preventing Many Shots Jailbreak with Agentic System](https://arxiv.org/abs/2502.16750)

<a name="environment-level-manipulation"></a>
###  Environment-Level Manipulation

<a name="indirect-prompt-injection"></a>
#####  Indirect Prompt Injection
<a name="memory-poisoning"></a>
#####  Memory Poisoning

<a name="cross-agent-interaction-risks"></a>
###  Cross-Agent Interaction Risks

<a name="collusion"></a>
#####  Collusion
<a name="worm-propagation"></a>
#####  Worm Propagation



































