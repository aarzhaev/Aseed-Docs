# Aseed Docs

Official public documentation for [Aseed](https://aseed.ai), an AI-powered platform for qualitative customer and user research.

Aseed supports the research workflow from project setup and interview collection to transcription, structured analysis, project-level synthesis, sharing, and API access.

- **Documentation:** https://docs.aseed.ai
- **Aseed app:** https://app.aseed.ai
- **Website:** https://aseed.ai

## Documentation scope

This repository contains documentation for:

- getting started with Aseed
- projects and AI Interviewer
- interview uploads, transcripts, and transcription
- Single Reports and report types
- Project Reports and cross-interview synthesis
- sharing, exports, and MCP access
- account and billing
- API reference
- changelog

The documentation site is built with [Mintlify](https://mintlify.com).

## Local development

Install dependencies and start the local documentation server:

```bash
npm install
npm run dev
```

Validate the documentation before publishing:

```bash
npm run validate
```

The main Mintlify configuration is in `docs.json`.

## Contributing

Keep documentation aligned with the current behavior of Aseed. Describe shipped functionality and product constraints explicitly, and avoid documenting planned features as if they are already available.

Changes merged into `main` are published through the connected Mintlify deployment.

## License

This repository is licensed under the [MIT License](./LICENSE).
