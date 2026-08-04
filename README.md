# Search Intelligence Portfolio Agent (SIPA)

## Overview

**Search Intelligence Portfolio Agent (SIPA)** is my personal AI agent that transforms completed technical projects into recruiter-ready portfolio assets.

Instead of manually writing documentation for every project, SIPA analyzes project artifacts such as GitHub repositories, Jupyter notebooks, README files, technical notes, and evaluation metrics and generates a consistent career-ready documentation package.

The agent was designed and built during the **FlyRank AI Fluency track** as the MVP of a long-term personal career operating system.

## Who It Is For

SIPA is built for me (Ramya Hegde) as I transition from Senior Operations Analyst to AI/ML Engineer.

It is intended to be used after completing any technical project, including:

* Machine learning projects
* Data analytics projects
* Search intelligence work
* Automation systems
* University capstone projects
* Future engineering and research work

## What SIPA Generates

From a completed technical project, SIPA produces:

* Technical case study
* Resume bullet points
* Portfolio project description
* LinkedIn-ready summary
* Interview preparation notes
* Skills extracted from the project
* Suggested portfolio improvements

## Current MVP

The current version focuses on **one narrow workflow**: analyze a single technical project end-to-end and generate recruiter-ready documentation based on real project artifacts.

The MVP was successfully validated using my **FlyRank Machine Learning repository**.

## Repository Used During Validation

**FlyRank ML Repository**

https://github.com/ramyaa-hegde/flyrank-ml-internship-tasks

## Technology Stack

* GitHub
* GitHub repositories as project inputs
* Claude / ChatGPT as the reasoning engine
* Prompt-driven workflow architecture
* Local filesystem integration through Claude Desktop MCP

## Setup

A stranger can reproduce the setup by following these steps.

### Requirements

* A GitHub account
* Access to Claude Desktop or ChatGPT
* A local project folder containing a technical project
* GitHub repository containing project artifacts

### Steps

1. Clone or download this repository.
2. Open the project in Claude Desktop or ChatGPT.
3. Load the system prompt from `SYSTEM_PROMPT.md`.
4. Provide a GitHub repository or local project folder.
5. Ask SIPA to analyze the project and generate recruiter-ready outputs.

## Usage Example

Example prompt:

Analyze my GitHub repository and generate:

1. A technical case study
2. Three resume bullet points
3. A portfolio project description
4. A LinkedIn-ready summary
5. Five interview questions I should prepare for

Use only evidence available in the repository and clearly flag any missing information.

## Example Output

For a completed machine learning repository, SIPA generates:

* Technical case study
* Resume bullet points
* Portfolio description
* LinkedIn summary
* Interview preparation questions

## Architecture

```text
GitHub Repository / Local Project Files
                |
                v
      SIPA System Prompt
                |
                v
   Project Analysis & Extraction
                |
                v
 Career Documentation Generation
                |
                v
Portfolio • Resume • LinkedIn • Interview Prep
```

## V2 Evaluation Results

The MVP was evaluated using the **FlyRank Machine Learning repository**.

### Successful End-to-End Test

* Repository successfully analyzed
* Project context extracted
* Technical summary generated
* Resume bullet points generated
* Portfolio description generated
* LinkedIn summary generated
* Interview preparation questions generated

### Evaluation Status

| Test                          | Result |
| ----------------------------- | ------ |
| Repository analysis           | Passed |
| Documentation generation      | Passed |
| Resume bullet generation      | Passed |
| Portfolio summary generation  | Passed |
| LinkedIn summary generation   | Passed |
| Interview question generation | Passed |

## Current Limitations

The current MVP has intentionally limited scope.

### Current Limitations

* Analyzes one project at a time
* No automatic GitHub API integration
* No multi-project indexing
* No resume export automation
* No portfolio auto-publishing
* No continuous repository monitoring

These features are intentionally deferred to future versions so that the MVP remains reliable and explainable.

## What I Learned

Building SIPA taught me how to define a narrowly scoped AI agent, document its behavior, validate it against a real project, and think about software in terms of **inputs, outputs, workflows, and guardrails** rather than only prompts.

## Long-Term Vision

SIPA will evolve into a **personal career operating system** capable of documenting machine learning projects, analytics work, automation systems, university projects, hackathons, and future engineering work while keeping my portfolio, resume, and professional profiles synchronized.

The goal is for every completed technical project to become a **publishable, recruiter-ready artifact** with minimal manual work while remaining fully evidence-based and explainable.

