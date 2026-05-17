<a href="https://collieai.io">
  <img src="https://github.com/user-attachments/assets/bdad882d-6be4-430c-9826-0b2929a358e2" alt="CollieAi — AI Firewall & Guardrails for LLM and AI Apps. Control what your AI can say, do, and discuss." width="100%" />
</a>


<p align="center">
  <a href="https://collieai.io"><img src="https://img.shields.io/badge/Website-collieai.io-blue?style=flat-square" alt="Website" /></a>
  <a href="https://docs.collieai.io"><img src="https://img.shields.io/badge/Docs-docs.collieai.io-green?style=flat-square" alt="Docs" /></a>
  <a href="https://app.collieai.io"><img src="https://img.shields.io/badge/Try_Free-app.collieai.io-purple?style=flat-square" alt="Try Free" /></a>
</p>

---

**One line change. Every LLM call protected.**

CollieAi is an AI firewall that sits between your app and any LLM provider. Swap the base URL - every request and response is inspected, filtered, and logged by the content policies you define. No SDK, no library, no code changes.

```python
client = openai.OpenAI(
    base_url="https://api.collieai.io/v1",  # ← that's it
    api_key="your-openai-key"
)
```

:shield: Prompt injection detection · :lock: PII & financial data masking · :no_entry: Jailbreak prevention · :speech_balloon: Topic restriction policies · :mag: Custom word filtering · :link: URL & link filtering · :key: Secret & API key detection · :brain: Hallucination & quality checks · :bar_chart: Full request/response logging

Unlike SDK-based guardrails, CollieAi works at the network level c any language, any framework, any LLM provider. ~12ms added latency per rule.

**→ [Get started free](https://app.collieai.io)** · [Documentation](https://docs.collieai.io) · [Quick Start](https://docs.collieai.io/getting-started/quick-start) · [llm-firewall repo](https://github.com/CollieAI/llm-firewall)

<sub>
AI firewall · LLM security · content guardrails · prompt injection protection · AI gateway ·
PII detection · content moderation · jailbreak detection · content filtering ·
LLM observability · AI safety · responsible AI · machine learning security ·
hallucination detection · word filtering · topic restriction · LLM proxy
</sub>
