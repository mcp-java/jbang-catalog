# Java MCP Server Catalog

This is a catalog of Java MCP Servers.

Curated and created by the community.

You can list these using any of the following commands:

### JBang

`jbang catalog list mcp-java`

### UVX 

`uvx jbang catalog list mcp-java`

### NPM

`npx -y @jbangdev/jbang catalog list mcp-java`

## Use in MCP Client

Below are example commands for using the MCP Servers in various MCP clients. It uses `containers@java-mcp` as an example but in practice you can use any of the MCP Servers.

<details>
<summary>Claude Desktop</summary>

Add the following to your `claude_desktop_config.json` file:

```json
 {
  "mcpServers": {
    "containers": {
      "command": "jbang",
      "args": [
       "containers@quarkus-mcp"
      ]
    }
  }
}
```
</details>

<details>
<summary>Cursor</summary>

Add the following to your `mcp.json` file:

```json
 {
    "mcpServers": {
      "containers": {
        "command": "jbang",
        "args": [
          "containers@quarkus-mcp"
        ]
      }
    }
}
```
</details>
