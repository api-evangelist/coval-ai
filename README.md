# Coval (coval-ai)

Coval is a simulation and evaluation platform for AI voice and chat agents. Inspired by autonomous-vehicle testing, it simulates end customers across realistic scenarios, personas, accents, and background noise, then scores agent behavior with built-in and custom metrics. The REST API manages agents, test sets and test cases, personas, metrics, simulation runs, and production conversations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coval-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coval-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Agents
- Voice AI
- Simulation
- Evaluation
- Testing

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Coval Datasets API

Manage test sets and the individual test cases (scenarios, transcripts, IVR, audio, and scripts) that define the inputs an agent is simulated and evaluated against.

- **Human URL:** [https://docs.coval.dev/api-reference/introduction](https://docs.coval.dev/api-reference/introduction)
- **Base URL:** `https://api.coval.dev/v1`

#### Tags

- Datasets
- Test Sets
- Test Cases

#### Properties

- [Documentation](https://docs.coval.dev/concepts/test-sets/overview)
- [API Reference](https://docs.coval.dev/api-reference/introduction)
- [OpenAPI](openapi/coval-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coval-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coval-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coval Simulations & Runs API

Launch and manage simulation runs that pair an agent, persona, and test set, then inspect the resulting simulations including transcripts, audio, and per-metric outputs. Also covers connecting agents, run templates, and scheduled runs.

- **Human URL:** [https://docs.coval.dev/api-reference/introduction](https://docs.coval.dev/api-reference/introduction)
- **Base URL:** `https://api.coval.dev/v1`

#### Tags

- Simulations
- Test Runs
- Agents

#### Properties

- [Documentation](https://docs.coval.dev/getting-started/welcome)
- [API Reference](https://docs.coval.dev/api-reference/introduction)
- [OpenAPI](openapi/coval-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coval-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coval-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coval Scenarios & Personas API

Configure the simulated callers that drive scenarios - persona prompts, voices, languages, background-sound environments, and conversation behavior - along with helpers to list available voices and phone-number mappings.

- **Human URL:** [https://docs.coval.dev/api-reference/introduction](https://docs.coval.dev/api-reference/introduction)
- **Base URL:** `https://api.coval.dev/v1`

#### Tags

- Scenarios
- Personas
- Voices

#### Properties

- [Documentation](https://docs.coval.dev/getting-started/welcome)
- [API Reference](https://docs.coval.dev/api-reference/introduction)
- [OpenAPI](openapi/coval-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coval-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coval-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coval Metrics & Scorers API

Define the scoring criteria used to evaluate agent behavior - custom and built-in metric types - plus their thresholds and baselines, and list the judge models available for metric evaluation.

- **Human URL:** [https://docs.coval.dev/api-reference/introduction](https://docs.coval.dev/api-reference/introduction)
- **Base URL:** `https://api.coval.dev/v1`

#### Tags

- Metrics
- Scorers
- Evaluation

#### Properties

- [Documentation](https://docs.coval.dev/getting-started/welcome)
- [API Reference](https://docs.coval.dev/api-reference/introduction)
- [OpenAPI](openapi/coval-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coval-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coval-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coval Conversations & Observability API

Submit production conversations and transcripts for evaluation, attach audio, and pull per-conversation metric outputs to run evals on live traffic for ongoing observability and monitoring.

- **Human URL:** [https://docs.coval.dev/guides/observability](https://docs.coval.dev/guides/observability)
- **Base URL:** `https://api.coval.dev/v1`

#### Tags

- Conversations
- Observability
- Monitoring

#### Properties

- [Documentation](https://docs.coval.dev/guides/observability)
- [API Reference](https://docs.coval.dev/api-reference/introduction)
- [OpenAPI](openapi/coval-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coval-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coval-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/coval-ai)
- [LinkedIn](https://www.linkedin.com/company/covaldev)
- [Website](https://www.coval.dev)
- [Documentation](https://docs.coval.dev)
- [Plans](plans/coval-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/coval-ai-rate-limits.yml)
- [Fin Ops](finops/coval-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
