# AI Threat Models

## Overview

AI systems introduce unique attack surfaces- from data poisoning to prompt injection.
This section documents how to identify, analyze, and mitigate threats specific to AI pipelines.

## Common AI Threats
-**Prompt Injections: ** Manipulating model inputs to override intended behavior.
-** Model Poisoning: ** Inserting malicious data during training to alter model outputs.
-** Data Leakage: ** Sensitive information exposed through model responses or embeddings.
-** Adversarial Inputs: ** Crafted data designed to mislead or confuse models.
-** Unauthorized Fine-Tuning: ** Altering model weights or parameters without approval.
-** Inference Manipulation: ** Exploiting model logic to extract confidential data.

## Mitigation Strategies
-Validate and sanitize all prompts before processing.
-Use secure data pipelines with integrity checks.
-Implement model version control and audit logs.
-Apply adversarial testing and red-team exercises.
-Restrict fine-tuning privileges to authorized personnel.
-Monitor model outputs for anomalies and leakage patterns.





## Tools Used
-** LLM Firewall** - filters malicious prompts.
-** AI Red-Team Toolkit** - Simulates adversarial attacks.
-** Model Scan** - detects poisoned weights.
-** Prompt Guard** - enforce input validation.

## Roles and Responsibilities
-** AI Security Engineer: ** Designs and maintains model protection controls.
-** Data Scientist: ** Ensures training data integrity.
-** Incident Responder: ** Handles AI-related breaches and containment.
-** Governance Lead: ** Oversees compliance and ethical AI use.

## References
-NIST AI Risk Management Framework
-OWASP Top 10 for LLM Applications
-ISO/IEC 42001: AI Management Systems Standard
