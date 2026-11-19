# Awesome-AI-Skill-Inspection-Safety-Verification

# Top AI Skill Inspection & Safety Verification Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Agent Skill (`SKILL.md`) & MCP Server Auditing, AI Supply-Chain Security, Automated Red-Teaming, Prompt-Injection Verification & Runtime Safety Guardrails*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Skill Inspection & Safety Verification**. These tools statically and dynamically inspect third-party AI agent skills (`SKILL.md`), Model Context Protocol (MCP) servers, and model weights for hidden malicious instructions, prompt injections, data exfiltration, and unsafe tool permissions—while automating adversarial verification and runtime safety enforcement.

**Examples** include Lakera Guard, Mindgard, Cisco AI Defense (Robust Intelligence), Protect AI, HiddenLayer, Vigil AI, Promptfoo, NVIDIA Garak, Microsoft PyRIT, Meta CyberSecEval, and NVIDIA/SkillSpector (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for AI agent skill & MCP security scanners (`SkillSpector`, `mcp-scan`, `cisco-ai-defense/skill-scanner`), automated vulnerability & red-teaming suites (`Garak`, `PyRIT`, `Promptfoo`), AI supply-chain scanners (`ModelScan`), and programmable safety guardrails (`NeMo Guardrails`, `LLM Guard`, `Llama Guard`) — ideal for AI security engineers, AppSec teams, platform architects, and developers vetting third-party agent extensions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Lakera Guard](https://lakera.ai)**  
  Ultra-low-latency real-time AI security firewall protecting LLM applications and tool-calling agents against prompt injections, malicious skill payloads, jailbreaks, and data leakage.

- **[Protect AI (Guardian & Layer)](https://protectai.com)**  
  Enterprise AI security platform offering ML/AI supply-chain scanning, model and artifact inspection, real-time prompt firewalling, and continuous automated red-teaming.

- **[HiddenLayer](https://hiddenlayer.com)**  
  Enterprise AI security platform delivering real-time adversarial attack detection, model and artifact integrity scanning, prompt injection monitoring, and automated AI red-teaming.

- **[Cisco AI Defense (formerly Robust Intelligence)](https://cisco.com)**  
  Enterprise AI validation and runtime protection suite providing automated algorithmic red-teaming, supply-chain risk verification, and real-time runtime guardrails.

- **[Mindgard](https://mindgard.ai)**  
  Continuous automated AI red-teaming and safety verification platform uncovering jailbreaks, evasion attacks, tool-use exploits, and data poisoning across LLMs and agents.

- **[Vigil AI (Promptfoo Enterprise)](https://promptfoo.dev)**  
  Enterprise continuous AI red-teaming and vulnerability management platform automating OWASP Top 10 for LLMs testing, agent skill verification, and CI/CD regression gating.

- **[Patronus AI](https://patronus.ai)**  
  Automated AI safety and evaluation platform featuring adversarial test generation, specialized hallucination and policy-violation detectors, and enterprise compliance verification.

- **[Arthur Shield (Arthur AI)](https://arthur.ai)**  
  Real-time LLM firewall and governance suite providing prompt injection detection, PII/sensitive data filtering, hallucination scoring, and behavioral safety rails.

- **[Fiddler AI (Fiddler Guardrails)](https://fiddler.ai)**  
  Enterprise AI observability and governance platform offering sub-100ms safety, jailbreak, PII, and faithfulness guardrails alongside continuous drift verification.

- **[Invariant Labs (Snyk AI Security)](https://invariantlabs.ai)**  
  Agentic security and MCP/skill verification platform providing continuous monitoring, tool-call policy enforcement, and supply-chain threat detection for autonomous AI agents.


## Open-Source GitHub Projects

- **[NVIDIA SkillSpector (`NVIDIA/SkillSpector`)](https://github.com)**  
  Open-source AI agent skill inspection and safety verification toolkit from NVIDIA designed to audit `SKILL.md` capability packs and agent extensions for hidden prompt injections, malicious scripts, and unsafe tool behaviors before installation.

- **[Cisco AI Defense Skill Scanner (`cisco-ai-defense/skill-scanner`)](https://github.com)**  
  Open-source (`Apache-2.0`) static and semantic security scanner for AI agent skills (`SKILL.md` and bundled scripts) combining YARA signatures, AST dataflow analysis, and LLM-as-a-judge inspection.

- **[MCP-Scan (`invariantlabs-ai/mcp-scan`)](https://github.com)**  
  Open-source (`Apache-2.0`) security scanner for Model Context Protocol (MCP) servers and agent tools detecting tool poisoning, cross-origin prompt injections, rug-pull schema mutations, and toxic flows.

- **[NVIDIA Garak (`NVIDIA/garak`)](https://github.com)**  
  Industry-standard open-source (`Apache-2.0`) LLM vulnerability scanner from NVIDIA probing models and agent endpoints for prompt injections, jailbreaks, encoding bypasses, and data exfiltration.

- **[Microsoft PyRIT (`Azure/PyRIT`)](https://github.com)**  
  Open-source (`MIT`) Python Risk Identification Tool for generative AI from Microsoft's AI Red Team automating multi-turn adversarial verification and safety stress-testing.

- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com)**  
  Fast open-source (`MIT`) CLI and evaluation harness featuring an automated red-teaming and safety verification engine (`promptfoo redteam`) for CI/CD gating of prompts, skills, and agents.

- **[CyberSecEval / Purple Llama (`meta-llama/PurpleLlama`)](https://github.com)**  
  Open-source safety and cybersecurity verification suite from Meta evaluating LLM susceptibility to prompt injection, insecure code generation, and cyber exploits alongside `Prompt Guard` and `Llama Guard`.

- **[ModelScan (`protectai/modelscan`)](https://github.com)**  
  Open-source (`Apache-2.0`) AI supply-chain security scanner detecting arbitrary code execution exploits (`pickle`, `SavedModel`, `Keras`, `PyTorch`) embedded inside serialized model weights and artifacts.

- **[LLM Guard (`protectai/llm-guard`)](https://github.com)**  
  Comprehensive open-source (`MIT`) security toolkit by Protect AI providing local input/output scanners for prompt injection detection, secrets scanning, PII anonymization, and output sanitization.

- **[NVIDIA NeMo Guardrails (`NVIDIA/NeMo-Guardrails`)](https://github.com)**  
  Flagship open-source (`Apache-2.0`) programmable guardrail runtime using Colang to verify and enforce topical, safety, jailbreak, and tool-execution rails on conversational and agentic systems.

- **[Guardrails AI (`guardrails-ai/guardrails`)](https://github.com)**  
  Popular open-source (`Apache-2.0`) Python framework and validator Hub for enforcing structural, semantic, PII, and safety verification checks on LLM inputs and outputs.

- **[Inspect AI (`UKGovernmentBEIS/inspect_ai`)](https://github.com)**  
  Open-source (`MIT`) safety evaluation and verification framework developed by the UK AI Security Institute (AISI) for testing sandboxed agent tool use, cyber capabilities, and alignment guardrails.

- **[AgentDojo (`ethz-spylab/agentdojo`)](https://github.com)**  
  Open-source (`MIT`) dynamic evaluation environment and benchmark from ETH Zurich specifically designed to verify tool-calling AI agents against indirect prompt injection attacks.

- **[Giskard (`Giskard-AI/giskard-oss`)](https://github.com)**  
  Open-source (`Apache-2.0`) automated QA and safety verification scanner for LLM agents and RAG pipelines probing for prompt injection, sensitive data disclosure, and hallucination vulnerabilities.

- **[Semgrep (`semgrep/semgrep`) & YARA (`VirusTotal/yara`)](https://github.com)**  
  Industry-standard open-source (`LGPL-2.1` / `BSD-3-Clause`) static code analysis and pattern-matching engines used to audit helper scripts (`Python`, `Bash`, `JS`) bundled inside third-party AI skills.

- **[Open Policy Agent / OPA (`open-policy-agent/opa`)](https://github.com)**  
  Declarative open-source (`Apache-2.0`) policy engine (`Rego`) increasingly paired with MCP gateways and agent runtimes to verify and authorize tool calls against least-privilege security policies.

### Additional Strong Open-Source Options

- **[DeepTeam (`confident-ai/deepteam`)](https://github.com)** for an open-source (`Apache-2.0`) LLM red-teaming framework simulating 40+ adversarial attack vectors including excessive agency, BOLA, and prompt probing.
- **[InjecAgent (`uiuc-kang-lab/InjecAgent`)](https://github.com)** and **[BIPIA (`microsoft/BIPIA`)](https://github.com)** for open-source benchmarks verifying indirect prompt-injection resilience across tool-integrated agents.
- **[WildGuard (`allenai/wildguard`)](https://github.com)** and **[ShieldGemma (`google-deepmind/gemma`)](https://github.com)** for compact, open-weight safety moderation and adversarial prompt classifier models runnable locally.
