**MCPs** 

- Context7 (docs and examples)
```sh
npx @anthropic-ai/claude-code mcp add context7 -- npx -y @upstash/context7-mcp
```

- Sequential Thinking

```sh
npx @anthropic-ai/claude-code mcp add sequential -- npx -y @modelcontextprotocol/server-sequential-thinking 
```

- Puppeteer

```sh
npx @anthropic-ai/claude-code mcp add puppeteer -- npx -y @modelcontextprotocol/server-puppeteer
```

- Puppeteer Headless

```sh
npx @anthropic-ai/claude-code mcp add puppeteer-headless -- docker run -i --rm --init -e DOCKER_CONTAINER=true mcp/puppeteer
```

- Playwright

```sh
npx @anthropic-ai/claude-code mcp add playwright -- npx -y @playwright/mcp@latest
```

- MongoDB MCP to browse a local database:
```sh
npx @anthropic-ai/claude-code mcp add mongodb-localhost -- npx -y mongodb-mcp-server --connectionString="mongodb://localhost:27017/"
```

- MongoDB Lens MCP to browse a local database:
```sh
npx @anthropic-ai/claude-code mcp add mongodb-localhost -- npx -y mongodb-lens "mongodb://localhost:27017/"
```

- Magic UI
```sh
npx @anthropic-ai/claude-code mcp add magic -- npx -y @21st-dev/cli@latest install claude --api-key "[my-api-key]"
```

- Memory

```sh
npx @anthropic-ai/claude-code mcp add memory -- npx -y @modelcontextprotocol/server-memory
```

- Fetch

```sh
npx @anthropic-ai/claude-code mcp add fetch -- docker run -i --rm mcp/fetch
```

- Time

```sh
npx @anthropic-ai/claude-code mcp add time -- docker run -i --rm mcp/time
```

- Mermaid

```sh
npx @anthropic-ai/claude-code mcp add mermaid -- npx -y @peng-shawn/mermaid-mcp-server
```

- Helm

```sh
npx @anthropic-ai/claude-code mcp add helm -- docker run -d --name mcp-helm -p 8012:8012 --command ghcr.io/zekker6/mcp-helm:v1.0.1 -mode=sse
```

- ArgoCD

```sh
npx @anthropic-ai/claude-code mcp add argocd -- ARGOCD_BASE_URL="<argocd_url>" ARGOCD_API_TOKEN="<argocd_token>" npx -y argocd-mcp@latest stdio
```

- Jira

```sh
npx @anthropic-ai/claude-code mcp add jira -- ATLASSIAN_SITE_NAME="<YOUR_SITE_NAME>" ATLASSIAN_USER_EMAIL="<YOUR_EMAIL>" ATLASSIAN_API_TOKEN="<YOUR_API_TOKEN>" @aashari/mcp-server-atlassian-jira
```

- Excel

```sh
npx @anthropic-ai/claude-code mcp add excel -- uvx excel-mcp-server stdio
```

- OpenAPI

```sh
npx @anthropic-ai/claude-code mcp add openapi -- npx -y @reapi/mcp-openapi@latest --dir ./specs
```

- NixOS

```sh
npx @anthropic-ai/claude-code mcp add nixos -- nix run github:utensils/mcp-nixos --
```

- Pandoc

```sh
npx @anthropic-ai/claude-code mcp add pandoc -- uvx mcp-pandoc
```

- Elasticsearch

```sh
npx @anthropic-ai/claude-code mcp add elasticsearch -- ELASTICSEARCH_HOSTS=<url>" ELASTICSEARCH_USERNAME="<name>" ELASTICSEARCH_PASSWORD="<password>" uvx elasticsearch-mcp-server
```

- Teams

```sh
npx @anthropic-ai/claude-code mcp add teams -- docker run --env-file .env -it inditextech/mcp-teams-server
```
