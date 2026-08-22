# ChatGPT (chatgpt)

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

OpenAI's ChatGPT API for conversational AI and language model interactions.

**APIs.json:** [https://platform.openai.com/docs/api-reference](https://platform.openai.com/docs/api-reference)

## Scope

- **Access:** 3rd-Party

## Tags

- Agents
- AI
- ChatGPT
- Embeddings
- Fine-Tuning
- GPT-4
- GPT-5
- Language Model
- OpenAI
- Realtime

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### ChatGPT API

API for accessing OpenAI's ChatGPT language models for chat completions and conversations.

- **Human URL:** [https://platform.openai.com/docs/guides/chat](https://platform.openai.com/docs/guides/chat)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Chatbot
- Conversational AI
- Machine Learning
- Natural Language Processing

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/chat)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/chatgpt-chat-completions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/chatgpt-chat-completion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/chatgpt-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://platform.openai.com/docs/api-reference/authentication)
- [Pricing](https://openai.com/pricing)
- [Rate Limits](https://platform.openai.com/docs/guides/rate-limits)
- [Terms of Service](https://openai.com/terms)
- [Privacy Policy](https://openai.com/privacy)
- [Status Page](https://status.openai.com)
- [Support](https://help.openai.com)
- [GitHub Organization](https://github.com/openai)
- [Getting Started](https://platform.openai.com/docs/quickstart)
- [Changelog](https://platform.openai.com/docs/changelog)
- [Blog](https://openai.com/blog)
- [SDK](https://developers.openai.com/api/docs/libraries/)
- [Security](https://openai.com/business-data/)
- [Models](https://platform.openai.com/docs/models)
- [Sign Up](https://platform.openai.com/signup)
- [Login](https://platform.openai.com/login)

### OpenAI Responses API

The Responses API is OpenAI's recommended API primitive for new projects, an evolution of Chat Completions with built-in tools like web search, file search, code interpreter, and support for agentic workflows.

- **Human URL:** [https://platform.openai.com/docs/api-reference/responses](https://platform.openai.com/docs/api-reference/responses)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Agents
- Artificial Intelligence
- Conversational AI
- Responses
- Tools

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/responses)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/chatgpt-responses-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/chatgpt-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/chatgpt-responses-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### OpenAI Embeddings API

API for generating embedding vectors from input text using models like text-embedding-3-small and text-embedding-3-large, useful for search, clustering, and recommendations.

- **Human URL:** [https://platform.openai.com/docs/api-reference/embeddings](https://platform.openai.com/docs/api-reference/embeddings)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Embeddings
- Machine Learning
- Search

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/embeddings)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Images API

API for generating and editing images from text prompts using DALL-E and GPT Image models, supporting image generations, edits, and variations.

- **Human URL:** [https://platform.openai.com/docs/api-reference/images](https://platform.openai.com/docs/api-reference/images)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Creative AI
- DALL-E
- Image Generation

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/images)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Audio API

API for audio capabilities including text-to-speech generation, speech transcription, and translation using Whisper and other audio models.

- **Human URL:** [https://platform.openai.com/docs/api-reference/audio](https://platform.openai.com/docs/api-reference/audio)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Audio
- Speech
- Text-To-Speech
- Transcription

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/audio)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Moderations API

API for classifying text and images to detect potentially harmful content across categories like hate, violence, and self-harm.

- **Human URL:** [https://platform.openai.com/docs/api-reference/moderations](https://platform.openai.com/docs/api-reference/moderations)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Content Safety
- Moderation
- Trust And Safety

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/moderations)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Fine-Tuning API

API for creating and managing fine-tuning jobs to customize OpenAI models on your own training data, supporting supervised fine-tuning and direct preference optimization.

- **Human URL:** [https://platform.openai.com/docs/api-reference/fine-tuning](https://platform.openai.com/docs/api-reference/fine-tuning)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Fine-Tuning
- Machine Learning
- Model Customization

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/fine-tuning)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Files API

API for uploading and managing files used across OpenAI features including fine-tuning, assistants, batch processing, and vision.

- **Human URL:** [https://platform.openai.com/docs/api-reference/files](https://platform.openai.com/docs/api-reference/files)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Files
- Storage
- Uploads

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/files)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Batch API

API for sending asynchronous groups of requests at lower cost with a separate pool of significantly higher rate limits, supporting chat completions, embeddings, and completions endpoints.

- **Human URL:** [https://platform.openai.com/docs/api-reference/batch](https://platform.openai.com/docs/api-reference/batch)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Asynchronous
- Batch Processing
- Cost Optimization

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/batch)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Uploads API

API for uploading large files in multiple parts, supporting files up to 8 GB for use with fine-tuning, assistants, and batch processing.

- **Human URL:** [https://platform.openai.com/docs/api-reference/uploads](https://platform.openai.com/docs/api-reference/uploads)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Files
- Large Files
- Uploads

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/uploads)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Vector Stores API

API for creating and managing vector stores used by the file search tool, supporting collections of processed files for retrieval-augmented generation.

- **Human URL:** [https://platform.openai.com/docs/api-reference/vector-stores](https://platform.openai.com/docs/api-reference/vector-stores)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- File Search
- Retrieval
- Vector Stores

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/vector-stores)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Realtime API

API for real-time multimodal communication with models over WebRTC, WebSocket, and SIP, supporting speech-to-speech, text, image, and audio inputs and outputs with ultra-low latency.

- **Human URL:** [https://platform.openai.com/docs/api-reference/realtime](https://platform.openai.com/docs/api-reference/realtime)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Audio
- Realtime
- Speech
- WebSocket

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/realtime)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenAI Models API

API for listing and retrieving information about available OpenAI models, including details on permissions and capabilities.

- **Human URL:** [https://platform.openai.com/docs/api-reference/models](https://platform.openai.com/docs/api-reference/models)
- **Base URL:** `https://api.openai.com/v1`

#### Tags

- Artificial Intelligence
- Models

#### Properties

- [Documentation](https://platform.openai.com/docs/api-reference/models)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chatgpt-chat-completions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-chat-completions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/chatgpt-responses-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chatgpt-responses-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://platform.openai.com)
- [Documentation](https://platform.openai.com/docs/api-reference)
- [Getting Started](https://platform.openai.com/docs/quickstart)
- [Authentication](https://platform.openai.com/docs/api-reference/authentication)
- [Pricing](https://openai.com/pricing)
- [Rate Limits](https://platform.openai.com/docs/guides/rate-limits)
- [Changelog](https://platform.openai.com/docs/changelog)
- [Blog](https://openai.com/blog)
- [Status Page](https://status.openai.com)
- [Support](https://help.openai.com)
- [GitHub Organization](https://github.com/openai)
- [SDK](https://developers.openai.com/api/docs/libraries/)
- [Code Examples](https://cookbook.openai.com/)
- [OpenAPI](https://github.com/openai/openai-openapi/blob/master/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Terms of Service](https://openai.com/terms)
- [Privacy Policy](https://openai.com/privacy)
- [Security](https://openai.com/business-data/)
- [Models](https://platform.openai.com/docs/models)
- [Sign Up](https://platform.openai.com/signup)
- [Login](https://platform.openai.com/login)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
**Email:** support@openai.com
**URL:** https://openai.com
