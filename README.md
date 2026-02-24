# .NET Modernization Tools

AI-powered tools for upgrading and modernizing .NET applications, available as a [Copilot CLI](https://github.com/github/copilot-cli) plugin and as a [Copilot Coding Agent](https://docs.github.com/en/copilot/using-github-copilot/using-copilot-coding-agent) custom agent.

## Copilot CLI Plugin

The **modernize-dotnet** plugin adds an AI agent to Copilot CLI that guides you through upgrading .NET Framework and .NET applications to the latest versions of .NET.

### Quick Start

1. **Add the marketplace:**

   ```
   /plugin marketplace add dotnet/modernize-dotnet
   ```

2. **Install the plugin:**

   ```
   /plugin install modernize-dotnet@modernize-dotnet-plugins
   ```

3. **Use the agent** — see the [plugin README](plugins/modernize-dotnet/README.md) for usage details.

> **Note:** You may need to restart Copilot CLI after installing the plugin before the agent becomes available ([tracking issue](https://github.com/github/copilot-cli/issues/1646)).

## Copilot Coding Agent

A custom agent definition and setup steps are provided for use with [Copilot Coding Agent](https://docs.github.com/en/copilot/using-github-copilot/using-copilot-coding-agent) in GitHub. This allows Copilot to modernize .NET projects directly via pull requests.

See the [coding-agent README](coding-agent/README.md) for setup instructions.

## Repository Structure

```
├── .github/plugin/marketplace.json   # Plugin marketplace definition
├── plugins/modernize-dotnet/         # Copilot CLI plugin
└── coding-agent/                     # Copilot Coding Agent setup
```

## Archive

The previous contents of this repository have been archived to the following branches:

- [`archive/oldua`](https://github.com/dotnet/modernize-dotnet/tree/archive/oldua) — original Upgrade Assistant (last updated January 2024)
- [`archive/mappings`](https://github.com/dotnet/modernize-dotnet/tree/archive/mappings) — API mappings data (last updated December 2024)
