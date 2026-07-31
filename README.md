<p align="center">
  <picture>
    <source media="(max-width: 480px)" srcset="./assets/volyx-terminal-mobile.svg" />
    <img src="./assets/volyx-terminal.svg" width="100%" alt="Joshua Nwachinemere, AI Engineer, presented as an animated VOLYX OS terminal" />
  </picture>
</p>

<p align="center">
  <a href="https://joshua-nwachinemere.pages.dev"><kbd>portfolio</kbd></a>&nbsp;
  <a href="mailto:josh0victor@outlook.com"><kbd>email</kbd></a>&nbsp;
  <a href="https://www.linkedin.com/in/joshua-nwachinemere/"><kbd>linkedin</kbd></a>&nbsp;
  <a href="https://github.com/dk3yyyy"><kbd>github</kbd></a>
</p>

## `❯ cat about.txt`

I build the retrieval, multimodal input, provider integration, evaluation, and backend reliability layers that turn model capability into useful systems.

- **`focus`** RAG, context engineering, multimodal/voice AI, structured outputs, and evals
- **`backend`** Python, FastAPI, asyncio, APIs, webhooks, caching, retries, and idempotency
- **`providers`** OpenAI, Anthropic, Gemini, DeepSeek, and Azure AI Foundry
- **`currently`** building VolyxAI and independently developing Volyx Lens
- **`status`** open to AI Engineer and ML Engineer opportunities

Python is my primary engineering language. My JavaScript and native product work is AI-assisted, with architecture, security boundaries, testing, and verification kept explicit.

## `❯ stack --list --verbose`

**`# AI & ML`**

<kbd>Python</kbd> <kbd>OpenAI</kbd> <kbd>Anthropic</kbd> <kbd>Azure AI Foundry</kbd> <kbd>Deepgram</kbd> <kbd>scikit-learn</kbd> <kbd>XGBoost</kbd>

**`# Backend`**

<kbd>FastAPI</kbd> <kbd>asyncio</kbd> <kbd>Node.js</kbd> <kbd>Express</kbd> <kbd>SQLAlchemy</kbd> <kbd>SQLite</kbd> <kbd>Socket.IO</kbd>

**`# Frontend / Apps`**

<kbd>React</kbd> <kbd>Vite</kbd> <kbd>Electron</kbd> <kbd>Swift</kbd> <kbd>JavaScript</kbd>

**`# Delivery / Automation`**

<kbd>Docker</kbd> <kbd>n8n</kbd> <kbd>GitHub Actions</kbd> <kbd>Playwright</kbd> <kbd>Azure</kbd>

## `❯ ls -la projects/`

### [`./volyx-lens`](https://github.com/dk3yyyy/volyx-lens)

<sub><code>Electron · JavaScript · Swift</code></sub>

> Privacy-oriented macOS assistant for screen, voice, meeting, and coding workflows. Includes provider routing, native capture components, Keychain-backed credentials, and explicit sharing controls. **[product site →](https://dk3yyyy.github.io/volyx-lens/)**

### [`./sol-eth-wallet-analyzer`](https://github.com/dk3yyyy/sol-eth-wallet-analyzer)

<sub><code>FastAPI · React · Telegram</code></sub>

> Read-only Solana and Ethereum analytics with bounded concurrency, caching, retries, partial-failure reporting, and automated API/browser verification. **[live demo →](https://chainscope-wallet-analyzer.onrender.com/)**

### [`./football_predictor`](https://github.com/dk3yyyy/football_predictor) `[experiment]`

<sub><code>Python · XGBoost · FastAPI · Streamlit</code></sub>

> Leakage-resistant chronological evaluation with out-of-fold stacking, calibrated XGBoost and Poisson models, frozen holdouts, and explicit artifact provenance. Across 1,140 untouched EPL test matches, it beat naive baselines but not normalized bookmaker closing probabilities.

<details>
<summary><code>❯ ls projects/secondary</code></summary>
<br />

**[`./telegram-social-video-downloader`](https://github.com/dk3yyyy/telegram-social-video-downloader)**<br />
<sub><code>FastAPI · n8n · Telegram</code></sub>

Self-hosted workflow with signed requests, replay protection, rate limits, isolated media processing, and explicit service boundaries.

**[`./Noughtline`](https://github.com/dk3yyyy/Noughtline)**<br />
<sub><code>Node.js · Socket.IO · React</code></sub>

Real-time multiplayer system with server-authoritative state, reconnect handling, one-time settlement, and a persistent transaction ledger. **[live preview →](https://noughtline.onrender.com/)**

</details>

## `❯ git log --oneline upstream/main`

- **`pydantic-ai-harness`** report unexpected Code Mode session resets to the model
- **`mellea`** add deterministic backend tracing coverage without requiring live Ollama
- **`openai-agents-python`** retry pre-response WebSocket server errors
- **`d9aa36f faststream`** restore FastAPI 0.140 dependency compatibility

- [`pydantic/pydantic-ai-harness#503`](https://github.com/pydantic/pydantic-ai-harness/pull/503) made host-side Code Mode failures visible to the model after session reset, preserving retry context and adding regression coverage.
- [`generative-computing/mellea#1471`](https://github.com/generative-computing/mellea/pull/1471) added deterministic tracing tests for async span duration, context propagation, token usage, span lifetime, and consecutive generations.
- [`openai/openai-agents-python#3991`](https://github.com/openai/openai-agents-python/pull/3991) added bounded retry behavior and regression coverage for retryable and non-retryable WebSocket failures.
- [`ag2ai/faststream#2961`](https://github.com/ag2ai/faststream/pull/2961) adapted FastStream's dependency layer to FastAPI's slotted `Dependant` model while preserving AsyncAPI metadata and adding regression coverage. It was squash-merged as `d9aa36f`.

<details>
<summary><code>❯ git log upstream/main -- more merged contributions</code></summary>
<br />

- [`apache/arrow-rs#10486`](https://github.com/apache/arrow-rs/pull/10486) made the JSON reader reject null children in non-nullable `ListView` and `LargeListView` fields, with regression coverage.
- [`vega/altair#4089`](https://github.com/vega/altair/pull/4089) improved `JupyterChart` behavior when the optional `anywidget` dependency is unavailable and added focused tests.
- [`faststream-community/faststream_fastapi#2`](https://github.com/faststream-community/faststream_fastapi/pull/2) preserved native FastAPI dependant fields and FastStream schema metadata after the slotted-dataclass migration.
- [`calkit/calkit#1028`](https://github.com/calkit/calkit/pull/1028) skipped unrelated subproject preparation for single-item pipeline runs while preserving selected-stage validation.

</details>

All eight contributions are merged upstream.

## `❯ contact --info`

- **`work with me`** AI engineering, ML engineering, model integration, and reliable automation
- **`email`** [josh0victor@outlook.com](mailto:josh0victor@outlook.com)

<p align="center">
  <a href="https://github.com/dk3yyyy"><kbd>github.com/dk3yyyy</kbd></a>&nbsp;
  <a href="https://joshua-nwachinemere.pages.dev"><kbd>portfolio →</kbd></a>&nbsp;
  <a href="https://www.linkedin.com/in/joshua-nwachinemere/"><kbd>linkedin →</kbd></a>&nbsp;
  <a href="mailto:josh0victor@outlook.com"><kbd>email →</kbd></a>
</p>

<p align="center">
  <sub><code>// built with intent. every system a decision.</code></sub>
</p>
