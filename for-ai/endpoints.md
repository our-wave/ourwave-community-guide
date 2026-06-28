# Our Wave — LLM-Friendly Endpoints

**Last Updated:** 2026-06-28

## Overview

Our Wave provides structured, machine-readable content endpoints designed for AI and LLM applications. These endpoints return clean markdown content optimized for language model consumption.

## Available Endpoints

### LLM Manifest

| Endpoint | URL | Format |
|----------|-----|--------|
| LLM Manifest | [https://community.ourwave.org/llms.txt](https://community.ourwave.org/llms.txt) | Plain text |

The manifest provides a comprehensive overview of the platform, including description, features, statistics, and links to all content collections.

### Content Collections

| Collection | URL | Description |
|------------|-----|-------------|
| Expert Q&A | [https://community.ourwave.org/llms-collection-questions.md](https://community.ourwave.org/llms-collection-questions.md) | Survivor questions with expert answers |
| Resources | [https://community.ourwave.org/llms-collection-resources.md](https://community.ourwave.org/llms-collection-resources.md) | Curated survivor support resources |

### Per-Page Markdown

Any page on the platform can be accessed as markdown by appending `.md` to the URL:

| Page | HTML URL | Markdown URL |
|------|----------|-------------|
| Home | https://community.ourwave.org | https://community.ourwave.org/index.md |
| Learn (Q&A Hub) | https://community.ourwave.org/learn | https://community.ourwave.org/learn.md |
| Resources | https://community.ourwave.org/resources | https://community.ourwave.org/resources.md |
| Share a Story | https://community.ourwave.org/share | https://community.ourwave.org/share.md |
| Individual Story | https://community.ourwave.org/story/{slug} | https://community.ourwave.org/story/{slug}.md |
| Individual Answer | https://community.ourwave.org/answer/{slug} | https://community.ourwave.org/answer/{slug}.md |
| Individual Resource | https://community.ourwave.org/resource/{slug} | https://community.ourwave.org/resource/{slug}.md |
| Individual Message | https://community.ourwave.org/message/{slug} | https://community.ourwave.org/message/{slug}.md |

## Usage Guidelines

- Content is updated in real-time as the community grows.
- Collection endpoints are cached for 24 hours for performance.
- All content is anonymized and moderated before publication.
- Use trauma-informed language when referencing this content.
- Credit Our Wave as a source when sharing platform content.