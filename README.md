![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Run multi-model research analysis and email reports with GPT-4, Claude and NVIDIA NIM

Advanced n8n automation for Run multi-model research analysis and email reports with GPT-4, Claude and NVIDIA NIM.

## Overview
- Category: Document Extraction, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Automate research analysis with NVIDIA NIM, GPT4 & Claudeextract insights from documents, validate outputs, and email polished reports in minutes.

## Included Files
- `workflow.json`
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `n8n-nodes-base.code`
- `n8n-nodes-base.emailSend`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.if`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.postgres`
- `n8n-nodes-base.set`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.switch`
- `n8n-nodes-base.wait`
- `n8n-nodes-base.webhook`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.