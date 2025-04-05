# Java MCP Server Catalog

This is a catalog of Java MCP Servers driving the [mcp-java.github.io](https://mcp-java.github.io) page.

You can list these using any of the following commands:

### JBang

`jbang catalog list mcp-java`

### UVX 

`uvx jbang catalog list mcp-java`

### NPM

`npx -y @jbangdev/jbang catalog list mcp-java`

## Use in MCP Client

Use [mcp-java.github.io](https://mcp-java.github.io) page to get configuration for various MCP Clients.


## Contributing your own MCP Server

We accept any server that are:

- Under an open-source OSI Approved license
- Runnable with JBang (i.e. Maven coordinate, a https reachable jar or script)
- has a description

We deserve the right to remove any server that becomes unavailable or deemed a security threat.

To contribute simply git clone this repository and add it, i.e.

```shell
git clone https://github.com/mcp-java/jbang-catalog
cd jbang-catalog
jbang alias add --name funpanda org.acme:funpanda-mcp:1.0.0
```

You can also manually edit the `jbang-catalog.json` but above helps verify it actually works.

Then submit a PR and it will be added if tests passes and show up in the mcp-java catalog.
