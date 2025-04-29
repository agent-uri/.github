# Agent URI Reference Implementation

This Org and repositories contains implementations and SDKs of the `agent://` protocol as defined in the [protocol specification](https://github.com/agent-uri/agent-uri/tree/main/docs/rfc/draft-narvaneni-agent-uri-01.md).

## Overview

The `agent://` protocol is a URI-based framework for addressing, invoking, and interoperating with autonomous and semi-autonomous software agents. It introduces a layered architecture that supports minimal implementations (addressing and transport) and extensible features (capability discovery, contracts, orchestration).

This reference implementation provides a complete implementation of the protocol, including:

- URI parsing and validation
- Agent descriptor handling
- Resolution framework
- Transport bindings (HTTPS, WebSocket, Local)
- Security implementations
- Client and server SDKs
- Integration with other protocols (Agent2Agent, MCP)
- Example implementations and tools

## Architecture

The implementation follows a modular, layered architecture:

```
agent-uri/
├── README.md                    # Project overview, setup instructions
├── docs/                        # Documentation
│   ├── architecture.md          # Architecture overview
│   ├── api-reference.md         # API documentation
│   ├── examples.md              # Usage examples
│   ├── rfc/                     # RFC documents
│   ├── spec/                    # Specification details
│   └── archive/                 # Archived documents
├── packages/                    # Core packages
│   ├── uri-parser/              # URI parsing and manipulation
│   ├── descriptor/              # Agent descriptor handling
│   ├── resolver/                # Resolution framework
│   ├── transport/               # Transport bindings
│   │   ├── transports/          # Transport implementations
│   │   └── registry             # Transport registry
│   ├── client/                  # Client SDK
│   ├── server/                  # Server SDK
│   └── common/                  # Shared utilities and types
└── examples/                    # Example implementations
    └── echo-agent/              # Echo agent example
```

## Getting Started

*Coming soon*

## Documentation

- [Architecture Overview](https://github.com/agent-uri/agent-uri/tree/main/docs/architecture.md)
- [API Reference](https://github.com/agent-uri/agent-uri/tree/main/docs/api-reference.md)
- [Usage Examples](https://github.com/agent-uri/agent-uri/tree/main/docs/examples.md)
- [Protocol Specification](https://github.com/agent-uri/agent-uri/tree/main/docs/rfc/draft-narvaneni-agent-uri-01.md)

## License

[BSD 3-Clause License](./LICENSE)
