# Awesome GPT Realtime

*Unofficial community list for GPT Realtime. Not affiliated with OpenAI or Microsoft. All trademarks belong to their owners.*

A curated list for developers building on gpt realtime, OpenAI's streaming voice model family: GPT-Realtime-2 for reasoning conversations, GPT-Realtime-Translate for live speech translation across 70+ input and 13 output languages, and GPT-Realtime-Whisper for streaming transcription. Every link below comes from the OpenAI developer docs, the May 7, 2026 announcement, or Microsoft's Azure AI Foundry documentation; nothing is guessed.

> Need image, video or audio generation next to your voice agent? [Try Synexa - one REST endpoint and Python SDK for FLUX, video and audio models, pay per run](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=awesome-gpt-realtime&utm_content=readme-top&utm_term=tier-r).

## Official resources

- [gpt-realtime model page](https://developers.openai.com/api/docs/models/gpt-realtime) - the model entry in the OpenAI developer docs; append `.md` to any docs URL for a Markdown version.
- [Advancing voice intelligence with new models in the API](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/) - the announcement introducing GPT-Realtime-2, GPT-Realtime-Translate and GPT-Realtime-Whisper.
- [Pricing & availability](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/#pricing-and-availability) - the section of the announcement that covers rates and rollout.
- [Safety](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/#safety) - how the voice models are moderated.
- [llms.txt](https://developers.openai.com/llms.txt) - the complete documentation index in a form you can hand to a coding agent.
- [API Dashboard](https://platform.openai.com/login) - where keys and usage live.

## Getting started

- [Quickstart](https://developers.openai.com/api/docs/quickstart) - first API call.
- [Audio & voice](https://developers.openai.com/api/docs/guides/audio) - the guide that owns the realtime models.
- [WebSocket mode](https://developers.openai.com/api/docs/guides/websocket-mode) - the persistent-connection transport the streaming models expect.
- [Streaming responses](https://developers.openai.com/api/docs/guides/streaming-responses) - how partial output arrives.
- [OpenAI SDK](https://developers.openai.com/api/docs/libraries) - supported client libraries.
- [OpenAI CLI](https://developers.openai.com/api/docs/libraries/openai-cli) - try calls from the terminal before writing code.

## Tutorials and articles

- [Realtime voice: helping voice models reason and take action](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/#realtime-voice-helping-voice-models-reason-and-take-action) - what GPT-Realtime-2 adds over earlier voice models.
- [Realtime translation](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/#realtime-translation-build-live-multilingual-voice-experiences) - building live multilingual experiences.
- [Realtime transcription](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/#realtime-transcription-build-low-latency-transcription-experiences) - low-latency speech-to-text with GPT-Realtime-Whisper.
- [Conversation state](https://developers.openai.com/api/docs/guides/conversation-state) - what the server remembers between turns and what you must persist yourself.
- [Mid-turn steering](https://developers.openai.com/api/docs/guides/steering) - redirecting the model while it is still speaking.
- [Cookbook](https://developers.openai.com/cookbook) - notebook examples across the API.
- [Showcase](https://developers.openai.com/showcase) - demo apps, several of them voice.

## Tools and integrations

- [Azure AI Foundry realtime audio how-to](https://learn.microsoft.com/en-us/azure/foundry/openai/how-to/realtime-audio) - deploying the realtime models on Azure.
- [Tools guide](https://developers.openai.com/api/docs/guides/tools) - giving the voice model actions to take.
- [Agents guide](https://developers.openai.com/api/docs/guides/agents) - composing a voice agent with other agents.
- [Webhooks](https://developers.openai.com/api/docs/guides/webhooks) - server-side callbacks for long-running work.
- [API reference](https://developers.openai.com/api/reference/overview) - the source of truth for event and parameter names.

## Alternatives

- [Synexa](https://synexa.ai?utm_source=github&utm_medium=ugc&utm_campaign=awesome-gpt-realtime&utm_content=readme-top&utm_term=tier-r) - hosted model API with one REST endpoint and a Python SDK for FLUX, video and audio models, pay per run; for the generation side of a product rather than live conversation.
- [Azure AI Foundry](https://learn.microsoft.com/en-us/azure/foundry/openai/how-to/realtime-audio) - the same models under Azure billing and compliance.

## Related

- [Changelog](https://developers.openai.com/api/docs/changelog) - watch for realtime model updates.
- [Deprecations](https://developers.openai.com/api/docs/deprecations) - older realtime names and their end dates.
- [Production best practices](https://developers.openai.com/api/docs/guides/production-best-practices) - rate limits, retries and cost control.
- [Supported countries](https://developers.openai.com/api/docs/supported-countries) - availability by region.
- [Community](https://developers.openai.com/community) - programs, meetups and support.

## Contributing

Send a pull request with the link, one line on why it belongs, and which official page confirms it.


_Last reviewed: 2026-09-22_
