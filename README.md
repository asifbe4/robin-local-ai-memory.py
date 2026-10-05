Robin Local AI Memory Builder

A local-first Python utility that converts a ChatGPT conversations.json export into a searchable Markdown memory system for Ollama + Llama + Open WebUI.

What it creates

MASTER_MEMORY.md — compact persistent memory

CONVERSATION_ARCHIVE.md — full extracted conversation archive

PROFILE.md

AI_HARDWARE.md

CREATIVE_PROJECTS.md

WRITING_STYLE.md

SCIENCE_IDEAS.md

WORKFLOWS.md

INDEX.md

Requirements

Python 3.10+

Optional: Ollama running locally

A ChatGPT data export containing conversations.json

No cloud API is required. When Ollama is enabled, the script talks only to 127.0.0.1 by default.

Quick start

ollama serve
ollama pull llama3.2:3b
python3 robin-local-ai-memory.py --input conversations.json --model llama3.2:3b

For a larger model, if your hardware supports it:

python3 robin-local-ai-memory.py --input conversatio
