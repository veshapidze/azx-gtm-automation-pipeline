# Automated GTM Account Intelligence & Outreach Pipeline

A functional, automated Go-To-Market infrastructure pipeline built to demonstrate scalable, AI-driven prospect profiling and highly personalized outreach mechanics for AZX targets.

## The Tech Stack
* **Data Orchestration Platform:** Clay.com
* **Large Language Model:** Claude 4.6 Sonnet (via API integration)
* **Target Vector:** Clean Energy / Decarbonization Sector

## Pipeline Workflow Architecture

### 1. Ingestion & Core Enrichment
* Bulk ingestion of priority clean-tech targets via standardized CSV format.
* Automated data orchestration layer extracts company baselines, primary domain data, and core operational descriptions.

### 2. Operational Use-Case Synthesizer (AI Chain Layer 1)
* Executed an LLM routing prompt using Claude 3.5 Sonnet to evaluate the raw company data.
* Structured the AI to identify exactly *one* high-impact, non-obvious operational bottleneck where AZX could provide AI transformation consulting (e.g., automated grid analysis, supply chain optimizations).

### 3. "Vibe-Coded" Outreach Generation (AI Chain Layer 2)
* Chained the output of the Synthesizer directly into a second localized copywriting agent.
* Programmed the model to bypass standard corporate fluff ("I hope this email finds you well") and construct a precise, high-conversion 3-sentence email pitch tailored to the prospect's distinct mission.

## Live Sample Deliverables
The complete data matrix, including dynamically mapped output strings, is preserved in the root directory of this repository: `Automate-Account-Research-Default-view-export-1780005527094.csv`
