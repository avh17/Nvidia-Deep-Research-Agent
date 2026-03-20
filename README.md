# Deploying a Deep Research Agent with NVIDIA AI-Q
This researcher notebook is a walkthrough of a fully autonomous deep research agent that can plan investigations, search multiple data sources in parallel, and generate comprehensive cited reports.

## What This Notebook Covers

| Section | Description |
|---------|-------------|
| 1. What is Deep Research? | How deep research differs from traditional search and basic RAG |
| 2. Deploy the AI-Q Research Assistant | Configure environment and launch services via Docker Compose |
| 3. Populate the Knowledge Base | Ingest sample financial and biomedical document collections |
| 4. Conduct Deep Research | End-to-end walkthrough: planning → research → report generation |
| 5. Cleanup | Stop and remove running services |
| 6. Local / On-Prem Deployment | Optional guide for self-hosted GPU deployment |

## Research Agent Overview

Define topic — Enter a research question and desired report structure
Review plan — Approve or edit the AI-generated research plan (human-in-the-loop)
Research execution — Agent runs parallel RAG + web searches (~8–12 minutes)
Refine report — Ask follow-up questions, edit sections, or export as PDF/Markdown



