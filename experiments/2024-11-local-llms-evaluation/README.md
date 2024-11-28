# Local LLMs Evaluation

## Usage

- General tasks
- Text completion
- Coding
- Chat & Story generating (esp. SillyTavern)

## Evaled Models

- Phi3 (Microsoft) https://azure.microsoft.com/en-us/products/phi
- LLama 3 (Facebook) https://www.llama.com/
- Mistral (Mistral AI) https://mistral.ai/
- Gemma 2 (Google) https://ai.google.dev/gemma
- Qwen2 (Alibaba) https://qwen2.org/


## Local environment

- Machine: M2 Macbook Pro 14 (2023) 32GB memory.
- Driver: [Ollama](https://ollama.com/)
- Frontend:
  - General tasks: [Chatbox](https://chatboxai.app/)
  - Chat & Story Generating: [SillyTavern](https://sillytavern.app/)
  - Coding: Visudal Studio Code + [Continue](https://www.continue.dev/) extension

## Techniques

### Prompt Engineering

Ref: https://www.promptingguide.ai/

Consider that as fake, since usually you can let llm generate better prompt their selves.

Also see my [prompt examples](./prompts-examples.md).

### SillyTavern Design Guide

#### World Info

https://docs.sillytavern.app/usage/worldinfo/

World Info Encyclopedia: https://rentry.co/world-info-encyclopedia

#### Characters

Ref: https://docs.sillytavern.app/usage/core-concepts/characterdesign/

- Trappu's PLists + Ali:Chat guide: https://wikia.schneedc.com/bot-creation/trappu/creation
- AliCat's Ali:Chat guide: https://rentry.co/alichat
- kingbri's minimalistic guide: https://rentry.co/kingbri-chara-guide

## Suggested Models based on its usage

### General Tasks

- LLama 3.2:3b https://ollama.com/library/llama3.2

### Text Completion

- LLama 3.2:3b https://ollama.com/library/llama3.2
- Mistral-nemo:12b https://ollama.com/library/mistral-nemo

### Coding

- qwen2.5-coder:7b https://ollama.com/library/qwen2.5-coder
- nomic-embed-text https://ollama.com/library/nomic-embed-text for local index

### Chat & Story generating

- Mistral-nemo:12b https://ollama.com/library/mistral-nemo
- Lumimaid-v0.2-12B (NSFW)
- <del>Noromaid-13b-v0.3-T4</del>