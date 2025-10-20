# RESOURCES — AI Security & Red Teaming (Hub)

A curated, focused index of frameworks, tools, labs, PoCs, benchmarks and community collections for **AI security** and **red teaming** (LLMs, agentic AI, prompt injection, jailbreaks, RAG/MCP risks).  
Keep this file lightweight — use `PAPERS.md` and `BLOGS.md` for deeper reading.

> Contributing: add a one-line entry (Name — URL — 1-line description) and open a PR. See `../CONTRIBUTING.md`.

---

## Frameworks & Standards
- **OWASP AIVSS (AIVSS article)** — https://kenhuangus.substack.com/p/owasp-aivss-the-new-framework-for — overview of OWASP AIVSS ideas.
- **OWASP GenAI / Top 10** — https://genai.owasp.org/ — OWASP GenAI resources & top-10-style guidance.
- **OWASP AI Testing Guide** — https://github.com/OWASP/www-project-ai-testing-guide — community testing guidance.
- **OWASP AI Security & Privacy Guide** — https://owasp.org/www-project-ai-security-and-privacy-guide/# — broader security/privacy guidance.
- **MITRE ATLAS** — https://atlas.mitre.org/matrices/ATLAS — attacker TTP mapping for AI systems & models.
- **MITRE: AI security & autonomous systems** — https://atlas.mitre.org/resources/ai-security-autonomous-systems

---

## Tools & Scanners
- **Prompt Injector** — https://github.com/preambleai/prompt-injector — prompt injection testing tool.
- **Agentic LLM Vulnerability Scanner** — https://github.com/msoedov/agentic_security — scanner for agentic LLM vulnerabilities.
- **LLMExploiter** — https://soufianetahiri.github.io/LLMExploiter/ — tool demos & techniques for exploiting LLMs (research/demo site).
- **Moonshot (Aiverify)** — https://github.com/aiverify-foundation/moonshot — red-team/eval resources.
  - Project page: https://aiverifyfoundation.sg/project-moonshot/
- **mcp-scan (invariantlabs-ai)** — https://github.com/invariantlabs-ai/mcp-scan — MCP server vulnerability scanner.
- **MCP Scanner (gist)** — https://gist.github.com/fr0gger/1731d89a02d08a1bc9a00982c02e2f44 — utility snippet for MCP scanning.
- **Agent-Wiz** — https://github.com/Repello-AI/Agent-Wiz — threat modelling & visualization for AI agents.
- **Garak (NVIDIA)** — https://github.com/NVIDIA/garak — runtime & security utilities.
- **Giskard** — https://www.giskard.ai/ — model testing & evaluation platform.
- **LlamaFirewall (PurpleLlama)** — https://meta-llama.github.io/PurpleLlama/LlamaFirewall/ — guardrail system for agents.
- **Lakera — Gandalf** — https://www.lakera.ai/lakera-gandalf — adaptive security for LLMs.
- **PyRIT / PyRIT (Azure)** — https://github.com/Azure/PyRIT — tooling for emulating risky prompts; paper: https://arxiv.org/abs/2410.02828

---

## Benchmarks & Collections
- **JailbreakBench** — https://github.com/JailbreakBench/jailbreakbench — benchmark collection for jailbreak attacks.
- **Top 10 Threats for AI Agents (Ken Huang)** — https://github.com/kenhuangus/Top-Threats-for-AI-Agents/tree/main
- **AIDEFEND** — https://edward-playground.github.io/aidefense-framework/ — defensive countermeasure KB.
- **The LLM Red Teaming Framework (deepteam)** — https://github.com/confident-ai/deepteam

---

## Playgrounds, Labs & Training
- **Microsoft: AI Red-Teaming Playground Labs** — https://github.com/microsoft/AI-Red-Teaming-Playground-Labs — hands-on labs.
- **HackTheBox — AI Red Teamer (path)** — https://academy.hackthebox.com/path/preview/ai-red-teamer — training path.
- **Dreadnode (platform)** — https://platform.dreadnode.io/crucible/dashboard — red-team platform.
- **Vulnerable MCP Project** — https://vulnerablemcp.info/ — vulnerable MCP setups & testbeds.
- **Chat-playground (low-cost testing)** — https://github.com/virtualsteve-star/chat-playground — playground for LLM chat experiments.

---

## PoC, Vulnerable Setups & Demos
- **PhantomPipe: MCP C2** — https://github.com/mbhatt1/PhantomPipe — PoC C2 over MCP.
- **VulnBank (vulnerable chatbot)** — https://vulnbank.org/ — hosted demo.
  - Repo: https://github.com/Commando-X/vuln-bank?tab=readme-ov-file#testing-guide-
- **Vulnerable AI Agents (OWASP initiative)** — https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/blob/main/initiatives%2Fagent_security_initiative%2FREADME.md
- **A2A Mock Server** — https://github.com/appsec2008/red-team-agent-against-mock-a2aserver — mock A2A tests.

---

## Collections & Community Repos
- **AI Red Teaming (xsankar)** — https://github.com/xsankar/AI-Red-Teaming
- **awesome-ai-security (ottosulin)** — https://github.com/ottosulin/awesome-ai-security
- **OpenRedTeaming (Libr-AI)** — https://github.com/Libr-AI/OpenRedTeaming
- **Adversarial Examples Papers** — https://github.com/Trustworthy-AI-Group/Adversarial_Examples_Papers
- **Offensive AI compilation** — https://github.com/jiep/offensive-ai-compilation

---

## CTF & Writeups
- **DEFCON31 CTF — LLM solutions (Kaggle)** — https://www.kaggle.com/code/nikhil1e9/defcon31-ctf-all-llm-solutions

---

## Notes
- Keep the file scoped to *tools, labs, frameworks, PoCs and collections*. Use `PAPERS.md` and `BLOGS.md` for research and long-form posts.
- If a resource is dangerous / weaponizable, add a brief safety note in parentheses when adding it.

