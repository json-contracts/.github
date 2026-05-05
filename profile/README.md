# JSON Contracts

**JSON contracts for AI agents.**

JSON Contracts is a local MCP server for natural-language-to-JSON workflows using Git-controlled JSON contracts and JSON Schema validation.

## 30-second quickstart

```bash
mkdir my-json-contracts
cd my-json-contracts
npx -y json-contracts@latest init
npx -y json-contracts-studio@latest
```

Open:

```text
http://127.0.0.1:5177
```

## Repositories

- [json-contracts](https://github.com/json-contracts/json-contracts) — local stdio MCP server, CLI validator, starter contracts, and MCP Registry package
- [json-contracts-studio](https://github.com/json-contracts/json-contracts-studio) — local browser Studio for testing natural-language-to-JSON contracts, repair loops, and contract drafting

## Install

MCP server:

```bash
npx -y json-contracts@latest
```

Studio:

```bash
npx -y json-contracts-studio@latest
```

MCP Registry:

```text
io.github.json-contracts/json-contracts
```

npm:

- https://www.npmjs.com/package/json-contracts
- https://www.npmjs.com/package/json-contracts-studio
