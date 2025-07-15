```bash
claude mcp add --scope user context7 -- npx -y @upstash/context7-mcp
claude mcp add-json --scope user "sequential-thinking" '{"command":"npx","args":["-y","@modelcontextprotocol/server-sequential-thinking"]}'
claude mcp add-json --scope user "puppeteer" '{"command":"npx","args":["-y","@modelcontextprotocol/server-puppeteer"]}'
claude mcp add-json --scope user "sqlite" '{"command":"uvx","args":["mcp-server-sqlite","--db-path","${input:db_path}"]}'
```
