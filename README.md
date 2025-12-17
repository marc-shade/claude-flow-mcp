# Claude Flow MCP Server

[![MCP](https://img.shields.io/badge/MCP-Compatible-blue)](https://modelcontextprotocol.io)
[![Python-3.10+](https://img.shields.io/badge/Python-3.10%2B-green)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
[![Part of Agentic System](https://img.shields.io/badge/Part_of-Agentic_System-brightgreen)](https://github.com/marc-shade/agentic-system-oss)

> **Multi-agent workflow orchestration and swarm coordination.**

Part of the [Agentic System](https://github.com/marc-shade/agentic-system-oss) - a 24/7 autonomous AI framework with persistent memory.

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
---

## Part of the MCP Ecosystem

This server integrates with other MCP servers for comprehensive AGI capabilities:

| Server | Purpose |
|--------|---------|
| [enhanced-memory-mcp](https://github.com/marc-shade/enhanced-memory-mcp) | 4-tier persistent memory with semantic search |
| [agent-runtime-mcp](https://github.com/marc-shade/agent-runtime-mcp) | Persistent task queues and goal decomposition |
| [agi-mcp](https://github.com/marc-shade/agi-mcp) | Full AGI orchestration with 21 tools |
| [cluster-execution-mcp](https://github.com/marc-shade/cluster-execution-mcp) | Distributed task routing across nodes |
| [node-chat-mcp](https://github.com/marc-shade/node-chat-mcp) | Inter-node AI communication |
| [ember-mcp](https://github.com/marc-shade/ember-mcp) | Production-only policy enforcement |

See [agentic-system-oss](https://github.com/marc-shade/agentic-system-oss) for the complete framework.
