# Agent Stack Guide

Choose browser agents, computer-use tools and infrastructure with minimal decision-changing questions. Includes an offline questionnaire and cited capability matrix.

## Install

```bash
npx skills add caseymanos/agent-stack-guide --skill choose-agent-stack
```

Ask your agent:

> Use choose-agent-stack to choose a browser automation stack. I need hosted execution, persistent logins, and an API for my product.

Or generate the interactive overview with Python 3:

```bash
python3 skills/choose-agent-stack/scripts/render_overview.py --output-dir ./overview
```

Open `overview/agent-capabilities.html`. Questionnaire and filtering work offline; sources require internet. No Python packages required.

## Evidence boundaries

32 capabilities, 11 surfaces, 352 evidence entries, 58 sources. Baseline checked September 10, 2026; Browserbase/Stagehand September 11; decision analysis September 12. Current recommendations require fresh verification; bundled HTML remains dated. No comparative agent-performance benchmark was run. No accounts, automatic purchases or background network calls are required by the renderer.

Independent community guide; not affiliated with the vendors. Original instructions/code are MIT licensed. Linked source materials remain subject to their owners' rights.

## Distribution

Follows [skills.sh guidance](https://skills.sh/docs/faq): GitHub-hosted skills are discovered through skills CLI installations. Directory indexing is separate from GitHub availability.
