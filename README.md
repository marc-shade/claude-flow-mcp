# Claude Flow MCP Server

Workflow orchestration and agent coordination server for complex multi-step AI tasks.

## Features

- **Workflow Management**: Define and execute multi-step AI workflows
- **Agent Coordination**: Coordinate multiple AI agents working on shared tasks
- **State Management**: Track workflow state and progress
- **Error Handling**: Robust error handling and recovery mechanisms

## Requirements

- Node.js 18+
- Dependencies: express, ws, cors, helmet, yaml

## Installation

```bash
npm install
```

## Usage

```bash
npm start
```

## Architecture

Built with:
- Express.js for HTTP endpoints
- WebSocket for real-time communication
- YAML for workflow definitions

## Integration

Designed to work with Claude Code and other MCP-compatible AI systems for orchestrating complex multi-agent workflows.

## License

MIT
