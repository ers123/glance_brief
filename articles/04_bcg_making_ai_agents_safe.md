# Making AI Agents Safe for the World

**Source:** BCG (in collaboration with BCG's Center for Leadership in Cyber Strategy)
**Date:** October 2025
**Type:** Research Article (Article-only, No PDF)
**URL:** https://www.bcg.com/publications/2025/making-ai-agents-safe-for-world

---

## Executive Summary

AI agents are powerful tools that can help companies achieve important business objectives, but unsecured they come with big risks with potentially catastrophic financial, reputational, and legal ramifications. BCG developed the **FAST Framework** (Framework for Agentic AI Secure Transformation) to help organizations structure their approach to securely deploying GenAI agentic systems.

---

## Key Statistics

- **45% annual growth** expected in AI agent market between 2024-2030 (Grand View Research)
- BCG has been building AI agents with clients since **2023**
- Agents create value including increases in revenues, EBIT, market share, and customer satisfaction

---

## Real-World Risk Scenarios

### Documented Incidents (BCG & Mandiant Exercises)
1. **Wellness Spa Attack:** Attackers influenced chatbot to recommend unsafe products by altering agent's understanding of user preferences → Customers hospitalized
2. **Bank Chatbot Breach:** Hackers intercepted consumer loan chatbot, stole sensitive information (income, loan status, personal IDs), secured 0% loans

### Potential Scenarios (GenAI-Generated)
3. **M&A Information Leak:** AI agent circulated confidential target company info to broader group including target's CFO's spouse
4. **Auto-Renewal Failure:** Procurement AI renewed multimillion-dollar contract with underperforming vendor due to missing feedback loop

---

## Three Types of Critical Risk

### 1. Semantic Prompt Manipulation
- Prompts guide AI agent responses and behavior
- Flexibility makes systems inherently unpredictable
- Even benign inputs can yield unintended outputs
- Malicious actors craft prompts to reveal sensitive info or perform unauthorized actions

### 2. Lateral System Spread
- GenAI interfaces with multiple components: APIs, databases, authentication services, cloud platforms
- Each integration point = potential entry point for exploitation
- Nondeterministic LLM outputs can ripple through connected systems
- Contamination of traditional security components

### 3. Adaptive Exploitation (Context Poisoning)
- Attackers manipulate system over time through strategic malign inputs
- Alters agent's contextual understanding
- Exploits learning processes
- Degrades reliability gradually rather than through single exploit

---

## Trust: The Core Requirement

**Reliable:** Systems behave as expected in any situation
**Secure:** Systems operate without causing harm

### Three Essential Safeguards

1. **Intent-Aware Input Validation**
   - Detect and block adversarial prompts
   - Analyze intent and structure without restricting legitimate queries
   - Agent trained for detection (not rules-based)

2. **Robust API Security**
   - Strong authentication (OAuth 2.0)
   - Thorough input sanitization
   - Zero-trust standards (never trust, always verify)
   - Principle of least privilege

3. **Real-Time Monitoring**
   - Continuous behavior monitoring
   - Anomaly detection
   - Regular audits for drift or degradation

---

## FAST Framework

**Framework for Agentic AI Secure Transformation** - Two Pillars:

### Pillar 1: ADAPT (Agentic Design, Architecture, and Platform Technology)

**Six Key Capabilities:**

1. **Set the Strategy**
   - Align business needs, technical architecture, security requirements
   - Cross-functional effort including business, AI architects, data owners, security champions

2. **Deploy Models**
   - Choose, test, host, maintain models
   - Analyze use cases, define selection criteria
   - Monitor performance including drift detection

3. **Tailor Models**
   - Customize for specific use cases
   - Behavioral, functional, ethical validation tests
   - Complete documentation of customization process

4. **Orchestrate Agents**
   - Coordinate interactions among models, tools, APIs, agents, humans
   - Structure logical sequences, conditional decision making, control points
   - Governance in multiagent systems

5. **Build Platform Architecture**
   - Unified cloud-native architecture
   - Stringent security, governance, observability
   - Industrialize use cases, streamline development

6. **Activate Cloud Services**
   - Govern and supervise cloud services
   - AI services (LLMs, APIs, vector databases)
   - Infrastructure and monitoring services

### Pillar 2: SSQC (Security, Safety, and Quality Control)

**Six Capabilities:**

1. **Policies and Planning**
   - Structured, auditable security strategies
   - Risk classification aligned with regulatory standards
   - Qualification, verification, revalidation, audit mechanisms

2. **Data Strategy**
   - Secure, traceable, governed data access
   - Data lineage, criticality classification, consent policies
   - Threat models: ATLAS, OWASP, LLM, SAIF

3. **Cybersecurity Guardrails**
   - Fit-for-purpose safeguards for GenAI attack surface
   - Zero-trust standards
   - Threat modeling approach (failure mode analysis, fault tree analysis)

4. **Bias Awareness**
   - Identify discriminatory/stereotyping behaviors
   - Debiasing and mitigation methods
   - Ensure fairness, transparency, nondiscrimination

5. **Real-Time Monitoring**
   - Continuous monitoring of inputs, behaviors, outputs
   - Detect anomalies, drifts, behavioral risks
   - Integrate with existing security operations

6. **Cloud Services Activation**
   - Center of excellence for cloud services
   - Managed vs self-hosted strategy
   - Cost, performance, availability control

---

## Four Maturity Levels

1. **Exploratory:** Basic prototyping without structured governance
2. **Experimental:** Limited deployments with preliminary integration and basic security
3. **Operational:** Fully integrated with robust supervision and active risk management
4. **Strategic:** Enterprise-grade with active governance, automated monitoring, comprehensive risk management

---

## Conclusion

Agentic AI is rewriting the rules of enterprise operations. It can observe, decide, and act, turning organizations into augmented systems. Only a demanding framework that integrates strategy, security, and trust can unlock its full value while containing the risks.

**"FAST turns fear into focus and experimentation into execution, ensuring that agentic AI becomes not a liability but the next great competitive advantage."**

---

*Estimated reading time: 15-20 minutes*
*Word count: ~3,000 words*
