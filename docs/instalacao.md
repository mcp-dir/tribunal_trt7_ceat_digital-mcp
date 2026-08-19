# Instalação detalhada

Tribunal TRT7: Certidão Eletrônica de Ações Trabalhistas (CEAT) - Processos Digitais é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_trt7_ceat_digital`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_trt7_ceat_digital` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_trt7_ceat_digital` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_trt7_ceat_digital` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_trt7_ceat_digital` (ou `servers.tribunal_trt7_ceat_digital` no VS Code) do config do cliente e reinicie.
