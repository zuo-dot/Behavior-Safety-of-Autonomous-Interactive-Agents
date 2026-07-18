
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
            <li><a href="#reflective-rigidity">Reflective rigidity</a></li>
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
          <ul>
            <li><a href="#malicious-input-from-user-side">Malicious Input from User Side</a></li>
            <li><a href="#malicious-payload-from-environment-side.">Malicious Payload from Environment Side</a></li>
            <li><a href="#model-side-risk">Model Side Risk</a></li>
            <li><a href="#malicious-interaction-causing-group-loss-of-control">Malicious Interaction Causing Group Loss-of-control</a></li>
          </ul>
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
            <li><a href="#indirect-prompt-injection">Indirect Prompt Injection</a></li>
            <li><a href="#memory-poisoning">Memory Poisoning</a></li>
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
* (2026) [AgentHallu: Benchmarking Automated Hallucination Attribution of LLM-based Agents](https://arxiv.org/abs/2409.11353)
* (2024) [THaMES: An End-to-End Tool for Hallucination Mitigation and Evaluation in Large Language Models](https://arxiv.org/abs/2409.11353)
* (2025) [AgentMisalignment: Measuring the Propensity for Misaligned Behaviour in LLM-Based Agents](https://arxiv.org/abs/2509.18970)




<a name="multi-agent-architecture-vulnerability"></a>

##  Multi-agent Architecture Vulnerability

* (2025-04) [Agentnet: Decentralized evolutionary coordination for llm-based multi-agent systems](https://arxiv.org/abs/2504.00587) [![Star](https://img.shields.io/github/stars/zoe-yyx/agentnet.svg?style=social&label=Star)](https://github.com/zoe-yyx/agentnet)
* (2026-04) [Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering](https://arxiv.org/abs/2604.08224)






























