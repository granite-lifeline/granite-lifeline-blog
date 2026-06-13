# Granite Lifeline — Project Blog

[![pages-build-deployment](https://github.com/granite-lifeline/granite-lifeline-blog/actions/workflows/pages/pages-build-deployment/badge.svg)](https://granite-lifeline.github.io/granite-lifeline-blog)

This repository contains the source code for the [Granite Lifeline project blog](https://granite-lifeline.github.io/granite-lifeline-blog), built with [Jekyll](https://jekyllrb.com) and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, hosted on GitHub Pages.

## About the Project

Granite Lifeline is an IBM-sponsored MSc Computer Science group project at the University of Bristol. The project builds an end-to-end predictive maintenance system for engine components, using OBD-II time-series data to detect anomalies and generate human-readable diagnostic reports powered by IBM Granite.

For source code, see the [main repository](https://github.com/granite-lifeline).

## Contributing a Post

### File naming

Posts go in the `_posts/` directory and must follow this naming format:

```
YYYY-MM-DD-sprintN-topic.md
```

For example:

```
2026-06-17-sprint1-summary.md
```

### Front matter

Every post must include the following front matter at the top of the file:

```yaml
---
title: "Your Post Title"
date: YYYY-MM-DD
categories: [Sprint Updates]
tags: [sprint1, topic]
author: Granite Lifeline Team
---
```

### Categories

| Category | When to use |
|---|---|
| Sprint Updates | Sprint kickoff and closing summaries |
| Technical | Architecture decisions, interface design, model selection, implementation write-ups |
| IBM Granite | Content specific to Granite TTM or LLM integration |
| Milestone | IBM iteration deliveries and other key project milestones |

### Tags

Use tags to describe the content in more detail. Tags can be combined freely.

| Group | Available tags |
|---|---|
| Sprint | `sprint1` `sprint2` `sprint3` `sprint4` `sprint5` `sprint6` `sprint7` |
| Layer | `data-layer` `model-layer` `report-layer` `dashboard` |
| Technical | `obd2` `feature-engineering` `anomaly-detection` `granite-ttm` `granite-llm` `prompt-engineering` `streamlit` |
| Workflow | `workflow` `jira` `github` `ci-cd` `interface` |
| Delivery | `ibm-iteration` `milestone` `kickoff` `retrospective` |

Example:

```yaml
tags: [sprint1, kickoff, workflow, jira, github]
```

### Author

| Situation | Author format |
|---|---|
| Team-wide posts (Sprint Summaries, Milestones) | `Granite Lifeline Team` |
| Layer-specific technical posts | `Name · Your belonged Layer` |

### Commit format

```
docs(sprintN): brief description of post
```

No issue key required in this repository.

### Review process

PRs to `main` do not require cross-team review. A quick check on front matter format and file naming is sufficient before merging.

## License

This project blog is published under the [MIT License](LICENSE).
