# Prerequisite
Install npx
```bash
npm i -g npx
```

Install uv (recommend to be done in a venv) 
```bash
pip install uv
```

# Set environment variables
```bash
export CONFLUENCE_URL=https://hackday-genius.atlassian.net/wiki
export CONFLUENCE_USERNAME=
export CONFLUENCE_API_TOKEN=
export JIRA_URL=https://hackday-genius.atlassian.net
export JIRA_USERNAME=
export JIRA_API_TOKEN=
export ENABLED_TOOLS=
```

# Start MCP in SSE mode
```bash
uvx mcp-atlassian  --transport sse
```
