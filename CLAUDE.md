# Claude Code Configuration for Hyperliquid Python SDK Study

## Overview

The purpose of this repo is to study the main Hyperliquid API and the encoded market making reward logic and mechanisms. We are not doing actual development yet, just deep research.

## Documentation Sources

Always check the official Hyperliquid documentation first when answering questions about:

- API endpoints and methods
- SDK usage and examples
- Trading functionality
- WebSocket subscriptions
- Authentication and configuration

### Primary Documentation

- **Main Docs**: <https://hyperliquid.gitbook.io/hyperliquid-docs/>
- **API Reference**: <https://hyperliquid.gitbook.io/hyperliquid-docs/for-developers/api>
- **SDK Examples**: Check `/examples/` directory in this repository
- API implementation details in `/api/` directory

### Auto-fetch Configuration

When answering questions about Hyperliquid main documentation, automatically fetch from:

- `https://hyperliquid.gitbook.io/hyperliquid-docs/*`

## Development Guidelines

### Code Style

- Follow existing code patterns in the repository
- Use type hints consistently
- Run linting and type checking before completing tasks
- Follow the project's black formatting (line length: 120)

### Commit Messages

- Never mention "CLAUDE" in commit messages
- Never sign commits with "Claude", "Anthropic", or similar AI-related signatures
- Focus on what was changed and why
- Use conventional commit format when appropriate
- Keep messages concise and informative

### Project Structure

- `/hyperliquid/` - Main SDK package
- `/examples/` - Usage examples
- `/tests/` - Test files
- `/api/` - API specification files
- `/notes/` - The main output, analysis notes

