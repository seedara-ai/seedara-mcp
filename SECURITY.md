# Security policy

This repository contains documentation and client configuration examples for the hosted Seedara MCP server at `https://seedara.ai/api/mcp`.

## Reporting a vulnerability

If you find a security problem in the Seedara MCP server, its OAuth sign-in or the Seedara website, please e-mail **support@seedara.ai** with:

- what you found and where (URL, tool name, client you used);
- steps to reproduce;
- what impact you think it has.

Please do not open a public issue for security problems and do not include other people's data in your report. We will reply by e-mail.

## How access works

- Agents connect through OAuth: you sign in on seedara.ai and press **Allow**. The agent never sees your password, e-mail or payment methods.
- An agent can make generations on your credits and see models, prices, your balance, your generations, elements and uploads. It cannot pay, top up or change sign-in or account settings.
- You can disconnect any agent on [seedara.ai/mcp](https://seedara.ai/mcp) under **Your connections**. Changing your password or **Sign out everywhere** disconnects every agent at once.
