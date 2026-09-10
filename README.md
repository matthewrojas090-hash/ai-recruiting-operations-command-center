# AI Recruiting Operations Command Center

A working, browser-based decision-support tool for recruiting operations, requisition prioritization, pipeline health, capacity planning, and leadership reporting.

## Why this project exists

Recruiting teams often manage more open roles than they can treat as equally urgent. This project demonstrates how AI-inspired decision logic can organize verified facts, surface missing information, and create a preliminary action plan—without allowing technology to make final staffing or hiring decisions.

The framework is informed by my experience scaling recruiting operations, leading high-volume technical hiring, developing weekly and monthly business reviews, and using funnel data to guide leaders.

## What the working tool does

- Organizes requisition facts across eight planning dimensions
- Produces a preliminary priority category
- Explains the evidence supporting the recommendation
- Identifies missing information
- Suggests recruiter and leadership actions
- Generates a concise leadership-ready summary
- Preserves human review and responsible-AI safeguards
- Provides an in-product responsible-AI checklist for privacy, evidence verification, human review, and documented overrides

## Use the live tool

[**Open the AI Recruiting Operations Command Center**](https://matthewrojas090-hash.github.io/ai-recruiting-operations-command-center/)

No installation, account, candidate data, or API key is required.

## Repository contents

- `index.html` — complete interactive command center
- `sample-data.csv` — fictional requisition examples
- `docs/methodology.md` — scoring logic and human-review requirements

## Responsible use

- Use only fictional or de-identified data.
- Do not enter candidate names or personal information.
- Do not use the tool to rank or select candidates.
- Validate business impact, approval, deadlines, and risks.
- Treat scores as discussion aids rather than objective facts.
- Keep final decisions with recruiting and business leaders.

## Portfolio context

This is a demonstration project created by **Matthew Rojas**, a Talent Acquisition and recruiting operations leader focused on practical, responsible uses of AI in hiring. All organizations, roles, and data used in examples are fictional.

## Recruiter Phone Screen Copilot

The Command Center now includes a privacy-first Recruiter Phone Screen Copilot that helps recruiters prepare and document deeper initial evaluations.

### What it does

- Accepts a de-identified resume, job description or job family, role level, job-family rubric, and approved leadership principles, company tenets, or interview competencies
- Generates exactly four resume-, role-, level-, and rubric-aligned questions
- Shows the exact resume evidence and company criterion mapped to each question
- Shows strong, acceptable, weak, and unsupported evidence guidance for every question
- Accepts de-identified recruiter notes or a call transcript
- Produces a structured RPS document with a qualification summary, questions, answers, evidence comparisons, preliminary outcome, and next steps
- Requires a recruiter to verify the evidence and own the final disposition
- Downloads the completed RPS document as Markdown
- Processes information only in the browser and does not save or transmit candidate data

### Use the tool

[**Open the Recruiter Phone Screen Copilot**](https://matthewrojas090-hash.github.io/ai-recruiting-operations-command-center/rps-copilot.html)

This portfolio prototype uses transparent, rules-based evidence organization to demonstrate the workflow without sending candidate information to an external AI service. It is not a validated hiring assessment and must not be used as the sole basis for employment decisions.

### Intended impact

The workflow is designed to reduce time spent researching roles, selecting questions, organizing notes, and preparing initial evaluations—targeting 5–10 hours per recruiter per week. In an earlier professional workflow, Matthew Rojas measured approximately 20 hours saved per recruiter per month and a 10-day reduction in time-to-fill. Those prior results provide context and are not guaranteed outcomes for this demonstration.
