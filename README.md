
<div align="center">
  <h1> MCP Notion</h1>
  <p>
  <em>Server for manipulating Notion documents via MCP</em>
  </p>

  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
  [![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-brightgreen)](https://modelcontextprotocol.io)
  [![Node.js](https://img.shields.io/badge/Node.js-%3E=20.0.0-green)](https://nodejs.org/)
    [![MCPB](https://img.shields.io/badge/MCPB-%40anthropic--ai%2Fmcpb-blue)](https://github.com/anthropics/mcpb)

</div>

## Description

Allows you to connect and synchronize data between MCP Server and Notion, making workflow management and automation easier.

## Project Structure

- `manifest.json`: Main configuration file.

## Requirements

- Node.js
- Install the MCPB extension with the following command:

```bash
npm install -g @anthropic-ai/mcpb
```

For more information about MCPB, visit [MCPB on GitHub](https://github.com/modelcontextprotocol/mcpb).

## Installation

## Usage

1. Clone this repository to your local machine.
2. Configure the `manifest.json` file as needed.
3. Obtain and add your Notion credentials in the configuration.
4. Package the extension by running:

    ```bash
    mcpb pack
    ```

    This will generate the `.mcpb` file.

5. Install the `.mcpb` file in Claude Desktop from Settings > Extensions > Advanced Settings > Extension Installation. You will then be prompted to enter your Notion credentials.
6. Start MCP Server and verify the integration with Notion.

For more details about credentials and configuration, see the original project [Notion MCP Server](https://github.com/makenotion/notion-mcp-server).

## License

This project is distributed under the MIT license. See the [LICENSE](./LICENSE) file for full terms.

Part of the code and integration is based on the original project [Notion MCP Server](https://github.com/makenotion/notion-mcp-server), which also uses the MIT license and is copyright Notion Labs, Inc. If you reuse or modify this code, you must keep the copyright notices and respect the terms of the MIT license of the source project.
