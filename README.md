Connect from Claude Desktop
Go to Claude Desktop > Settings > Developer > Edit Config > Edit §claude_desktop_config.json` and add:

{
  "mcpServers": {
    "YouTube": {
      "command": "uv",
      "args": [
        "--directory",
        "<ABSOLUTE_PATH_TO_THIS_DIR>",
        "run",
        "server.py"
      ]
    }
  }
}
