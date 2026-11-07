# Oct 2026 best repos

Ten of the most-starred and fastest-rising open-source AI projects, collected in one place. Each folder is a link (a git submodule) to the original project at a specific version, so this repo stays small and every project keeps its own history, licence and credit.

All links were pinned to each project's latest commit on November 7, 2026.

## Most-starred and most interesting

| Project | Approx. stars* | What it does | Runs where | Folder |
|---|---|---|---|---|
| [OpenClaw](https://github.com/openclaw/openclaw) | ~385K | Local-first personal AI assistant; connects to many messaging channels; supports skills | Your own machine | `popular/openclaw` |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ~175K | The project that made autonomous agents mainstream; more historically important than widely used today | Self-hosted | `popular/autogpt` |
| [Ollama](https://github.com/ollama/ollama) | ~147K | The easiest way to run open models locally | Your own machine | `popular/ollama` |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | ~122K | Inference engine underneath most local AI stacks | Your own machine | `popular/llama.cpp` |
| [LangChain](https://github.com/langchain-ai/langchain) | ~116K | Framework for building LLM apps and agents | Library (Python/JS) | `popular/langchain` |
| [Dify](https://github.com/langgenius/dify) | ~111K | Visual builder for AI workflows and agents | Self-hosted or cloud | `popular/dify` |

## Rising fastest: coding agents

| Project | Stars gained (28 days)* | What it does | Folder |
|---|---|---|---|
| [Claude Code](https://github.com/anthropics/claude-code) | +5.1K | Anthropic's agentic coding tool for the terminal | `coding-agents/claude-code` |
| [OpenCode](https://github.com/anomalyco/opencode) | +3.3K | Open-source AI coding agent for the terminal | `coding-agents/opencode` |
| [Goose](https://github.com/block/goose) | +1.8K | Block's open-source, extensible AI agent | `coding-agents/goose` |
| [Codex](https://github.com/openai/codex) | +1.4K | OpenAI's coding agent for the terminal | `coding-agents/codex` |

\* Star counts are from the list this repo was made from, not live figures.

## Using it

The folders start empty when you clone this repo. Download only the projects you want.

```bash
# Clone the collection (small: links only)
git clone https://github.com/gabrielwsu/Oct-2026-best-repos.git
cd Oct-2026-best-repos

# Download one project
git submodule update --init popular/ollama

# Download all ten (large: several of these are big projects)
git submodule update --init

# Move every link to its project's latest version, then save that
git submodule update --init --remote
git commit -am "Update to latest versions"
```

## Credit

Every project here belongs to its authors and is under its own licence, which you'll find inside its folder once it's downloaded. This repo only links to them.
