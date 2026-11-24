# PolyAI

PolyAI builds voice agents for customer service. This org holds the tools, SDKs and samples for building on
PolyAI: the Agent Development Kit, the Dialog-RSN-1 realtime API, and the messaging SDKs.

Sign up free at [studio.poly.ai](https://studio.poly.ai) · Docs at [docs.poly.ai](https://docs.poly.ai)

## Build agents with the ADK

The Agent Development Kit lets you build, test and deploy PolyAI voice and chat agents from your terminal.

```bash
pip install polyai-adk
```

| Repo | What it is |
| --- | --- |
| [adk](https://github.com/polyai/adk) | The ADK: build and deploy PolyAI agents from your terminal |
| [example-projects](https://github.com/polyai/example-projects) | Complete Agent Studio projects you can pull, run and edit |
| [adk-repo-template](https://github.com/polyai/adk-repo-template) | Template repository for an ADK-managed agent project |
| [adk-extension](https://github.com/polyai/adk-extension) | VS Code extension for ADK-managed agent projects |

## Build on Dialog-RSN-1

Dialog-RSN-1 is PolyAI's audio-native model for voice agents. It hears the caller, decides when they've
finished, and replies in one pass, spoken by the server or as text for your own TTS. It speaks the OpenAI
Realtime protocol, so any OpenAI Realtime client works once you change the URL, the key and the model name.

Start with [dialog-rsn-1-examples](https://github.com/polyai/dialog-rsn-1-examples), the index of every sample.

| Repo | What it is |
| --- | --- |
| [dialog-rsn-1-python-from-scratch](https://github.com/polyai/dialog-rsn-1-python-from-scratch) | Voice agent on plain `websockets`, with tool calling and a live microphone |
| [dialog-rsn-1-javascript-browser](https://github.com/polyai/dialog-rsn-1-javascript-browser) | Browser microphone through a small key-holding relay |
| [dialog-rsn-1-speech-to-text](https://github.com/polyai/dialog-rsn-1-speech-to-text) | Transcriber and support agent on the `openai` SDK, in Python and Node |
| [dialog-rsn-1-streaming-tts](https://github.com/polyai/dialog-rsn-1-streaming-tts) | Replies spoken through ElevenLabs as they stream, with barge-in |
| [dialog-rsn-1-voice-agent](https://github.com/polyai/dialog-rsn-1-voice-agent) | FastAPI voice agent with Cartesia speech and a browser page |
| [dialog-rsn-1-livekit](https://github.com/polyai/dialog-rsn-1-livekit) | A hotel agent on LiveKit Agents, with a scripted caller |
| [dialog-rsn-1-openai-migration](https://github.com/polyai/dialog-rsn-1-openai-migration) | The same agent on the `openai` SDK, before and after the switch |
| [dialog-rsn-1-realtime-agents](https://github.com/polyai/dialog-rsn-1-realtime-agents) | Multi-agent handoffs, a chat supervisor and a knowledge agent, in plain JavaScript |
| [dialog-rsn-1-skill](https://github.com/polyai/dialog-rsn-1-skill) | Dialog-RSN-1 skill for coding agents: Claude Code, Codex, Cursor and Gemini CLI |
| [dialog-rsn-1-sagemaker](https://github.com/polyai/dialog-rsn-1-sagemaker) | Notebook and client bridge for the Dialog-RSN-1 model package on Amazon SageMaker |
| [dialog-dictate](https://github.com/polyai/dialog-dictate) | Push-to-talk dictation for macOS |
| [dialog-rsn-1-roleplay-training](https://github.com/polyai/dialog-rsn-1-roleplay-training) | Self-paced voice role-play workshop for police training, with a scorer |

## Messaging SDKs

| Repo | What it is |
| --- | --- |
| [ios-sdk](https://github.com/polyai/ios-sdk) | iOS SDK for messaging conversations with the PolyAI runtime |
| [android-sdk](https://github.com/polyai/android-sdk) | Android SDK for messaging conversations with the PolyAI runtime |

## Research

Our research code and datasets, including [conversational-datasets](https://github.com/PolyAI-LDN/conversational-datasets)
and the [Pheme](https://github.com/PolyAI-LDN/pheme) TTS models, are on [PolyAI-LDN](https://github.com/PolyAI-LDN).
