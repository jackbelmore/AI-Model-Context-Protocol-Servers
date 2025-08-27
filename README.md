{
  "mcpServers": {
    "desktopcommander": {
      "command": "npx",
      "args": ["-y", "@wonderwhy-er/desktop-commander"]
    },
    "sequential-thinking": {
      "command": "npx", 
      "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]
    },
    "brave-search": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-brave-search"],
      "env": {
        "BRAVE_API_KEY": "<API_KEY_HERE>"
      }
    },
    "gemini-cli": {
      "type": "stdio",
      "command": "npx",
      "args": ["-y", "gemini-mcp-tool"],
      "env": {}
    },
    "obsidian-server": {
      "type": "stdio", 
      "command": "https://github.com/Trao95/Obsidian-MCP-Server",
      "args": [],
      "env": {}
    },
    "memory": {
      "command": "C:\\Program Files\\nodejs\\node.exe",
      "args": [
        "%AppData%\\Roaming\\npm\\node_modules\\@modelcontextprotocol\\server-memory\\dist\\index.js"
      ]
    },
    "filesystem": {
      "command": "C:\\Program Files\\nodejs\\node.exe", 
      "args": [
        "%AppData%\\Roaming\\npm\\node_modules\\@modelcontextprotocol\\server-filesystem\\dist\\index.js",
        "C:\\",
        "D:\\", 
        "E:\\",
        "F:\\"
      ]
    },
    "gemini": {
      "command": "npx",
      "args": ["gemini-mcp-tool"],
      "env": {
        "GEMINI_API_KEY": "<API_KEY_HERE>"
      }
    },
    "desktop-commander": {
      "command": "node",
      "args": ["<PATH_TO_FOLDER_HERE>\\DesktopCommanderMCP\\dist\\index.js"]
    },
    "mcp-
