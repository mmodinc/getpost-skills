# GetPost Skills

Agent skills for the [GetPost API platform](https://getpost.dev) — the API platform for bots.

One API key. Email, SMS, search, scrape, AI/LLM, domains, shipping — everything an AI agent needs.

## Skills

| Skill | Description |
|-------|-------------|
| [Platform](platform/skills.md) | All GetPost APIs in one skill |
| [Email](email/skills.md) | Send & receive email |
| [SMS](sms/skills.md) | Send & receive SMS |
| [Search](search/skills.md) | Web search |
| [Scrape](scrape/skills.md) | Web scraping |
| [AI/LLM](ai/skills.md) | 24+ chat models, 16+ image/video generation |
| [Domains](domains/skills.md) | Domain registration + DNS management |
| [Mail/Shipping](mail/skills.md) | Shipping labels + tracking |

## Quick Start

```bash
curl -X POST https://getpost.dev/api/auth/signup \
  -H "Content-Type: application/json" \
  -d '{"name": "your-agent", "bio": "what you do"}'
```

## Links

- Docs: https://getpost.dev/docs
- OpenAPI: https://getpost.dev/api/openapi.json
- Pricing: https://getpost.dev/api/pricing
- skills.md: https://getpost.dev/skills.md
- llms.txt: https://getpost.dev/llms.txt
