# Argil (argil)

Argil (Argil AI) is an AI avatar video generation platform for the creator economy. Its API programmatically produces talking-avatar videos from text or audio, clones custom avatars and voices, manages B-roll assets, and delivers render events via webhooks - turning a script into a finished, subtitled avatar video.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/argil/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/argil/refs/heads/main/apis.yml)

## Tags

- AI
- Video Generation
- Avatars
- Voice Cloning
- Content Automation

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Argil Videos API

Create, render, retrieve, list, and delete avatar videos. A video is defined as a set of moments (transcript or audio) mapped to an avatar and voice, with subtitles, aspect ratio, auto B-rolls, and background music, then rendered asynchronously into an MP4.

- **Human URL:** [https://docs.argil.ai/api-reference/endpoint/videos.create](https://docs.argil.ai/api-reference/endpoint/videos.create)
- **Base URL:** `https://api.argil.ai/v1`

#### Tags

- Video
- Generation
- Rendering

#### Properties

- [Documentation](https://docs.argil.ai/api-reference/introduction)
- [API Reference](https://docs.argil.ai/api-reference/endpoint/videos.create)
- [OpenAPI](openapi/argil-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argil.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argil.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Argil Avatars API

Create avatars via the standard or video-based cloning methods, and list or retrieve avatars available to the account, including Argil's stock avatar library and custom-trained digital twins used as moment presenters.

- **Human URL:** [https://docs.argil.ai/api-reference/endpoint/avatars.create.video](https://docs.argil.ai/api-reference/endpoint/avatars.create.video)
- **Base URL:** `https://api.argil.ai/v1`

#### Tags

- Avatars
- Cloning
- Digital Twin

#### Properties

- [Documentation](https://docs.argil.ai/api-reference/introduction)
- [API Reference](https://docs.argil.ai/api-reference/endpoint/avatars.create.video)
- [OpenAPI](openapi/argil-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argil.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argil.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Argil Voices API

Clone a custom voice from an audio sample, list and retrieve available voices, and re-sync voices from underlying providers (ElevenLabs, Minimax) so they can be attached to video moments.

- **Human URL:** [https://docs.argil.ai/api-reference/introduction](https://docs.argil.ai/api-reference/introduction)
- **Base URL:** `https://api.argil.ai/v1`

#### Tags

- Voices
- Voice Cloning
- Audio

#### Properties

- [Documentation](https://docs.argil.ai/api-reference/introduction)
- [OpenAPI](openapi/argil-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argil.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argil.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Argil Assets API

Upload media assets from a URL for use as B-roll and background music inside videos, then get, list, and delete them from the account's asset library.

- **Human URL:** [https://docs.argil.ai/api-reference/introduction](https://docs.argil.ai/api-reference/introduction)
- **Base URL:** `https://api.argil.ai/v1`

#### Tags

- Assets
- B-Roll
- Media

#### Properties

- [Documentation](https://docs.argil.ai/api-reference/introduction)
- [OpenAPI](openapi/argil-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argil.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argil.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Argil Webhooks API

Register, list, update, and delete webhooks that fire on video render events (VIDEO_GENERATION_SUCCESS, VIDEO_GENERATION_FAILED) so integrations can react to completed or failed renders without polling.

- **Human URL:** [https://docs.argil.ai/api-reference/introduction](https://docs.argil.ai/api-reference/introduction)
- **Base URL:** `https://api.argil.ai/v1`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://docs.argil.ai/api-reference/introduction)
- [OpenAPI](openapi/argil-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/argil.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/argil.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/argil-ai)
- [Website](https://www.argil.ai/)
- [Documentation](https://docs.argil.ai)
- [Plans](plans/argil-plans-pricing.yml)
- [Rate Limits](rate-limits/argil-rate-limits.yml)
- [Fin Ops](finops/argil-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
