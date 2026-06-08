# AI4comms Deliverables

Claude Code plugin for AI4comms branded deliverables

## Prerequisites

- Claude Code v2.1.49+
- Node.js 18+, Python 3.11+ with [uv](https://docs.astral.sh/uv/)
- GitHub access to this repo (`gh auth login`)

## Installation

Via marketplace:
```bash
/plugin marketplace add stromy-org/ai4comms-marketplace
/plugin install ai4comms
```

For local development:
```bash
git clone https://github.com/stromy-org/ai4comms.git
cd ai4comms
npm install
uv sync
claude --plugin-dir .
```

## Skills

Skills are split between MCP-hosted stubs (fetched at runtime via
`ReadMcpResourceTool`) and locally-authored skills (frontmatter `_local: true`).
See `skills/README.md` for the maintenance workflow; the maintainer skill
`plugin-maintain` covers add / refresh / release.

## Updating

```bash
/plugin update ai4comms
```

## License

See [LICENSE](LICENSE) for terms.
