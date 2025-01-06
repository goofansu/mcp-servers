# mcp-servers

The [Model Context Protocol](https://modelcontextprotocol.io/) servers on my machine. 

## Requirements
- Claude Desktop ([Download](https://claude.ai/download))
- uv ([Install](https://docs.astral.sh/uv/getting-started/installation/))

## Install

```shell
gh repo clone goofansu/mcp-servers
cd mcp-servers
uv venv
uv sync
```

### Inspect servers
```
uv dev weather.py
```

### Install servers
```shell
uv install weather.py
```

Restart Claude Desktop app and you'll see tools.

## References
- https://modelcontextprotocol.io/quickstart/server
- https://modelcontextprotocol.io/quickstart/user
- https://github.com/modelcontextprotocol/python-sdk
