# AI Agent Design Guide

This repository provides a practical framework for evaluating the design quality of AI agents. The goal is to help teams quickly assess strengths, gaps, and improvement areas in agent behavior, reasoning, reliability, safety, and observability.

This guide is focused on agentic design itself. It is not a replacement for production readiness reviews such as security scanning, load testing, deployment practices, or compliance frameworks.

## What Is Included
- A full design rubric at `docs/rubric.md`
- A short prompt-driven workflow for fast evaluations at `docs/quickstart.md`
- A simple scoring structure for capturing results

## How to Use This Guide

### 1. Read the rubric
The rubric covers four categories:
- Agent Intelligence  
- Technical Foundation  
- Agentic Quality Assurance  
- Observability

### 2. Run a quick assessment
Open your project in a coding assistant and use the prompt in `docs/quickstart.md`.

### 3. Review and adjust
Use the generated results as a first pass and refine scores based on your understanding of the system.

### 4. Track decisions
Use the scoring structure in the rubric to document strengths, weaknesses, and next steps.

## Folder Structure
```text
/
  README.md
  docs/
    rubric.md
    quickstart.md
