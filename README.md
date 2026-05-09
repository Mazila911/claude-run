<div align="center">

# Claude Run

Browse your Claude Code conversation history in a beautiful web UI

[![npm version](https://img.shields.io/npm/v/claude-run.svg)](https://www.npmjs.com/package/claude-run)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<img src=".github/claude-run.gif" alt="Claude Run Demo" width="800" />

</div>

> **Fork Notice** — This project is forked from [kamranahmedse/claude-run](https://github.com/kamranahmedse/claude-run). I really like this project and started using it as my daily tool. Along the way, I made some adjustments based on my own preferences — UI theme improvements, session search enhancements, and various refinements. Since I'm not sure whether these changes align with the original author's vision, I decided to maintain my own fork and also submitted a PR back to the original repo. I plan to continue optimizing and fixing issues in this fork.
>
> **Changes in this fork:**
> - UI theme system overhaul and component improvements
> - Session ID search in the session list filter
> - Various bug fixes and refinements
>
> Full credit to [Kamran Ahmed](https://github.com/kamranahmedse) for creating this awesome project. This fork is licensed under the same [MIT License](LICENSE).

<br />

Run the project simply by executing

```bash
npx claude-run
```

The browser will open automatically at http://localhost:12001.

## Features

- **Real-time streaming** - Watch conversations update live as Claude responds
- **Search** - Find sessions by prompt text or project name
- **Filter by project** - Focus on specific projects
- **Resume sessions** - Copy the resume command to continue any conversation in your terminal
- **Collapsible sidebar** - Maximize your viewing area
- **Dark mode** - Easy on the eyes
- **Clean UI** - Familiar chat interface with collapsible tool calls

## Usage

Install globally via npm:

```bash
npm install -g claude-run
```

Then run it from any directory:

```bash
claude-run
```

The browser will open automatically at http://localhost:12001, showing all your Claude Code conversations.

```bash
claude-run [options]

Options:
  -V, --version        Show version number
  -p, --port <number>  Port to listen on (default: 12001)
  -d, --dir <path>     Claude directory (default: ~/.claude)
  --no-open            Do not open browser automatically
  -h, --help           Show help
```

## How It Works

Claude Code stores conversation history in `~/.claude/`. This tool reads that data and presents it in a web interface with:

- **Session list** - All your conversations, sorted by recency
- **Project filter** - Focus on a specific project
- **Conversation view** - Full message history with tool calls
- **Session header** - Shows conversation title, project name, and timestamp
- **Resume command** - Copies the command to resume the conversation
- **Real-time updates** - SSE streaming for live conversations

## Requirements

- Node.js 20+
- Claude Code installed and used at least once

## Development

```bash
# Clone the repo
git clone https://github.com/Mazila911/claude-run.git
cd claude-run

# Install dependencies
pnpm install

# Start development servers
pnpm dev

# Build for production
pnpm build
```

## License

MIT © Kamran Ahmed

Originally created by [Kamran Ahmed](https://github.com/kamranahmedse). This fork is maintained by [Mazila911](https://github.com/Mazila911).
