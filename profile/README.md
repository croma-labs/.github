<a href="https://usecroma.com">
  <img src="assets/banner.png" alt="Croma: the API for government data. 414 endpoints, 143 official sources, 11 countries." width="100%">
</a>

<p align="center">
  <a href="https://usecroma.com"><b>Website</b></a> ·
  <a href="https://docs.usecroma.com"><b>Docs</b></a> ·
  <a href="https://platform.usecroma.com/sign-up"><b>Get an API key</b></a> ·
  <a href="https://usecroma.com/changelog"><b>Changelog</b></a> ·
  <a href="https://status.croma.run"><b>Status</b></a>
</p>

## Official records, one API

Croma turns public-sector data into a single, consistent API: court cases, company registries, tax and sanctions lists, procurement, property, legislation and live transit, from Colombia, the United States, Chile, Mexico, Peru, El Salvador, Brazil, Guatemala, Bolivia, Japan and Venezuela.

Every endpoint answers in the same shape, names its source, and is documented with a runnable example.

```bash
curl https://api.croma.run/co/transmilenio/vehicles/v1 \
  -H "Authorization: Bearer $CROMA_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{ "route": "B10" }'
```

The full list of endpoints is public: [`api.croma.run/catalog`](https://api.croma.run/catalog) and [`api.croma.run/openapi`](https://api.croma.run/openapi).

## Built for agents

The same catalog is an MCP server. Point Claude, ChatGPT, Cursor or your own agent at it and every source becomes a tool.

```
https://api.croma.run/mcp
```

## Open source

| Project | What it is |
| --- | --- |
| [**paradero**](https://github.com/croma-labs/paradero) | The open app for getting around Bogotá. A Digital Public Good built on TransMilenio open data. |
| [**transmilenio-live**](https://github.com/croma-labs/transmilenio-live) | Every TransMilenio bus in Bogotá, moving on one [live map](https://transmi.usecroma.com). |
| [**ventanilla**](https://github.com/croma-labs/ventanilla) | [Answers about the Colombian State](https://gov.usecroma.com), from official sources. |
| [**croma-chat-template**](https://github.com/croma-labs/croma-chat-template) | A production-ready [AI chat](https://chat.usecroma.com) over live public data. Deploy it in one click. |
| [**croma-notebooks**](https://github.com/croma-labs/croma-notebooks) | Economic analyses with official data, one reproducible notebook per newsletter issue. |
| [**dian-facturacion-example**](https://github.com/croma-labs/dian-facturacion-example) | Example Next.js app that reads issued and received electronic invoices. |
| [**croma-n8n-templates**](https://github.com/croma-labs/croma-n8n-templates) | n8n workflow templates for public records over REST and MCP. |

## Digital Public Goods

Some of what we build belongs to everyone. Paradero and the live TransMilenio map are open, free and offered to the public entities whose data they run on, to adopt and publish as their own.

<p align="center">
  <sub>Public data infrastructure · <a href="https://usecroma.com">usecroma.com</a> · <a href="mailto:cris@usecroma.com">cris@usecroma.com</a></sub>
</p>
