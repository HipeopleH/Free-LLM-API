# Free AI Directory

A community-maintained directory of free AI providers, API gateways, and model access services.

Find providers, compare their free quotas, check API compatibility, and see whether their advertised models have actually been verified.

> **Important:** A provider advertising a model does not mean it has been independently verified to serve that model. Advertised and verified models are tracked separately.

---

## Provider Directory

| Provider       | Website                                | Access Method | Quota   | Model Verification | Automation         |
| -------------- | -------------------------------------- | ------------- | ------- | ------------------ | ------------------ |
| Puter.js       | [Website](https://puter.com/)          | Universal       | 30 req / 10 sec | Legit           | Hard               |
| 1min.ai        | [Website](https://1min.ai/)            | Web chat       | Unknown | Untested           | Easy               |
| GPTChatly Opus | [Website](https://opus.gptchatly.com/) | Web chat      | Unknown | Legit           | Medium / IP           |
| Doraverse      | [Website](https://doraverse.com/)      | Web chat      | Unknown | Legit           | Easy               |
| Poe            | [Website](https://poe.com/)            | Web chat      | I forgot | Legit           | Phone verification |

*Initial entries are based on repository notes and prior observations. Unknown means information has not yet been established.*

---

## Provider Information

Each provider has its own entry containing the following information.

### 1. Access Methods

| Method            | Description                          |
| ----------------- | ------------------------------------ |
| Web chat          | Use the provider through its website |
| API               | Direct API access                    |
| Desktop app       | Dedicated desktop application        |
| Browser extension | Browser-based integration            |
| CLI               | Command-line interface               |
| Coding agent      | Integration with an AI coding agent  |

### 2. Quota System

| Quota Type  | Description                        |
| ----------- | ---------------------------------- |
| One-time    | Credits that can only be used once |
| Daily       | Quota that resets daily            |
| Weekly      | Quota that resets weekly           |
| Monthly     | Quota that resets monthly          |
| Referral    | Credits earned through referrals   |
| Promotional | Temporary promotional credits      |
| Unlimited   | No meaningful usage limit          |
| BYOK        | Bring Your Own Key                 |

### 3. Model Verification

| Status               | Meaning                                               |
| -------------------- | ----------------------------------------------------- |
| Legit                | Genuine model inference independently confirmed       |
| Fake routing         | Advertised model demonstrably routes to another model |
| Third-party verified | Tested by an independent testing organization         |
| Untested             | Model authenticity has not been established           |
| Disputed             | Conflicting or inconclusive test results              |

Verification records should include the tester, date, testing method, and evidence.

### 4. API Compatibility

| Compatibility | Description              |
| ------------- | ------------------------ |
| OpenAI        | OpenAI-compatible API    |
| Anthropic     | Anthropic-compatible API |
| Google        | Gemini-compatible API    |
| Custom        | Provider-specific API    |
| None          | No public API            |

### 5. Registration Methods

| Method          | Description                    |
| --------------- | ------------------------------ |
| Google OAuth    | Sign in with Google            |
| GitHub OAuth    | Sign in with GitHub            |
| Microsoft OAuth | Sign in with Microsoft         |
| Discord OAuth   | Sign in with Discord           |
| Email           | Email registration             |
| Phone           | Phone number registration      |
| Card required   | Payment card required          |
| ID required     | Identity verification required |

Only applicable registration methods will be displayed on individual provider pages.

### 6. Models Provided

Models are grouped by their advertised model provider.

| Model Provider | Examples                   |
| -------------- | -------------------------- |
| Anthropic      | Claude Opus, Sonnet, Haiku |
| OpenAI         | GPT models                 |
| Google         | Gemini models              |
| Moonshot AI    | some models                |
| xAI            | Grok models                |
| DeepSeek       | DeepSeek models            |
| Alibaba        | Qwen models                |
| Other          | Additional model providers |

Advertised models and independently verified models are stored separately.

### 7. Automation Compatibility

Automation compatibility describes how difficult a provider is to integrate with software and automated workflows.

| Rating      | Meaning                                |
| ----------- | -------------------------------------- |
| Easy        | Straightforward integration            |
| Medium      | Some additional configuration required |
| Hard        | Significant technical complexity       |
| Unsupported | No supported automation method         |
| Unknown     | Not yet investigated                   |

This rating is informational and does not indicate whether a provider is legitimate.

---

## Additional Provider Information

| Field                | Description                                 |
| -------------------- | ------------------------------------------- |
| API Endpoint         | Public API base URL                         |
| Account Required     | Whether registration is necessary           |
| Country Restrictions | Geographic availability                     |
| Data Retention       | Provider's prompt and data retention policy |
| Privacy Policy       | Link to privacy policy                      |
| Terms of Service     | Link to terms                               |
| Last Tested          | Date of most recent testing                 |
| Availability         | Operational, degraded, or offline           |

---

## Verification Standards

The directory distinguishes between different levels of evidence.

| Evidence Level       | Meaning                                           |
| -------------------- | ------------------------------------------------- |
| Advertised           | Provider claims to offer the model                |
| Community tested     | Users have tested the provider                    |
| Independently tested | A third party has performed testing               |
| Confirmed            | Strong evidence establishes genuine model routing |

A model name in an API response is not sufficient proof of model authenticity.

Provider information should be updated when quotas, models, registration requirements, or API endpoints change.

---

## Contributing

Contributions are welcome!

You can help by:

- Submitting new free AI providers.
- Reporting outdated quotas or model catalogs.
- Testing API compatibility.
- Investigating model authenticity.
- Reporting broken endpoints.
- Submitting independent verification results.

Please include evidence and a testing date whenever possible.

---

**Goal:** Make finding genuinely useful free AI access easier, while making misleading model claims and outdated provider information easier to identify.
