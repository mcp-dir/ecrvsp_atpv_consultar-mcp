# Instalação detalhada

ECRVSP ATPV (Intenção de Venda): Consultar é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_ecrvsp_atpv_consultar`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_ecrvsp_atpv_consultar` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_ecrvsp_atpv_consultar` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_ecrvsp_atpv_consultar` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.ecrvsp_atpv_consultar` (ou `servers.ecrvsp_atpv_consultar` no VS Code) do config do cliente e reinicie.
