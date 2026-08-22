# Coval (coval-ai)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
