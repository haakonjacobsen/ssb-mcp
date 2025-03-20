# SSB-MCP

MCP server for interacting with Statistics Norway (SSB) API - enabling AI agents to access Norwegian statistical data.

## Overview

SSB-MCP is a Machine Communication Protocol (MCP) server that provides a standardized interface for AI agents to interact with Statistics Norway's (SSB) API. This service enables seamless access to Norwegian statistical data through a well-defined API structure.

## Features

- Standardized access to SSB's statistical databases
- Easy-to-use interface for AI agents
- Support for both Norwegian and English queries
- Structured data retrieval from SSB's API
- Caching mechanism for improved performance

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- API key from SSB (if required)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/haakonjacobsen/ssb-mcp.git
cd ssb-mcp
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Start the server:
```bash
npm start
```

## API Documentation

Detailed API documentation will be available once the initial implementation is complete.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Statistics Norway (SSB)](https://www.ssb.no/) for providing the data API
- The MCP framework for standardized agent communication