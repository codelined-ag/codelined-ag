<p align="center">
  <a href="https://github.com/codelined-ag/Extracto">
    <img src="https://raw.githubusercontent.com/codelined-ag/Extracto/main/extracto-banner.png" alt="Extracto" width="80%">
  </a>
</p>

<p align="center">
  <strong>We build self-hosted AI tools.</strong><br/>
  No SaaS, no lock-in. One Docker container, your machine, your model, your data.
</p>

---

## Flagship: Extracto

**Your private document brain.** PDFs in, RAG out. Self-hosted. Plug everywhere.

Drop a document, get clean markdown. Chunk + embed + store into Chroma, Qdrant, or Weaviate. Query from Claude, Cursor, or Codex via MCP, from your code via the REST API, or from a browser via the UI. Any vision model: local Ollama, Mistral OCR, OpenRouter, any OpenAI-compatible endpoint.

```bash
docker run -d --name extracto -p 3000:3000 \
  -v extracto-data:/app/data \
  -e AUTH_SECRET="$(openssl rand -hex 32)" \
  ghcr.io/codelined-ag/extracto:latest
```

[**Repo**](https://github.com/codelined-ag/Extracto) · [**Docs**](https://extracto.help) · [**API**](https://extracto.help/api/overview) · [**MCP**](https://extracto.help/agents/overview) · [**Container**](https://github.com/codelined-ag/Extracto/pkgs/container/extracto)

---

## Get in touch

Issues, PRs, and discussions on [the Extracto repo](https://github.com/codelined-ag/Extracto/issues). For anything else: [support@codelined.com](mailto:support@codelined.com).
