# Shared Data

This repository is used as a shared data workspace for exchanging files and structured data between different applications, environments, and AI-assisted workflows.

## Purpose

The repository provides a simple, version-controlled location for data that needs to be accessed by multiple systems. Typical use cases include:

- Sharing input data between local programs and remote services
- Storing generated reports and analysis results
- Exchanging backtesting inputs and outputs
- Providing data for ChatGPT or other AI tools to review and analyze
- Keeping historical versions of shared data through Git

## Data Guidelines

- Prefer structured formats such as JSON, JSONL, CSV, and Markdown.
- Use clear and consistent file and folder names.
- Avoid storing passwords, API keys, access tokens, or other sensitive credentials.
- Keep generated data organized by purpose and, when appropriate, by date.

## Example Structure

```text
Shared-Data/
├── raw-data/
├── backtest-results/
├── reports/
├── configs/
└── README.md
```

The directory structure can evolve as new data-sharing workflows are added.
