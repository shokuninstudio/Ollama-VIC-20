# Ollama VIC-20

Ollama VIC-20 is a private ultra lightweight frontend for Ollama and designed to stay under 20 kilobytes on disk. 

# Description

Ollama VIC-20's purpose is to give users a no-install frontend that lets conversations be saved easily as a markdown document with one click. 

Why? I had noticed some Ollama frontends were becoming bloated, were not private when they claimed to be, were not showing users where conversations were being stored, and were not deleting conversations from disk after the user thought they were deleted. Ollama VIC-20 resolves that problem by not storing conversations on disk at all unless a user saves the conversation manually.

# Usage

On macOS or Linux simply run 'OLLAMA_ORIGINS=* ollama serve' to get started

```
OLLAMA_ORIGINS=* ollama serve
```

Or just 'ollama serve' on Windows if your environmental variables have been set up.

```
ollama serve
```

Then open the webpage locally to chat. 

# Features

- Chat with supported text documents
- Paste URL to summarise a webpage (as long as the page is static HTML)
- Save conversations as markdown documents

# Easily themeable 

- So easy you don't even need to do it yourself. Give the CSS and HTML to a model like Qwen Coder and ask it to design new themes for you.

Default theme:

[![temp-Images-QAh1w.avif](https://i.postimg.cc/KzZgX28H/temp-Images-QAh1w.avif)](https://postimg.cc/VSVNM2Mq)

