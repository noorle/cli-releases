# Noorle CLI Releases

This repository hosts the official releases for Noorle CLI.

Build, test, and deploy WebAssembly plugins and manage MCP gateways for [Noorle](https://noorle.com/) — the managed runtime for AI agents.

- 📦 [Installation guide](https://noorle.com/docs/reference/cli/installation)
- 📖 [CLI command reference](https://noorle.com/docs/reference/cli/commands)
- 🚀 [Five-minute quickstart](https://noorle.com/docs/use/five-minute-quickstart)

## Installation

### Quick Install

```bash
curl -L cli.noorle.dev | sh
```

### Manual Download

Download the appropriate binary for your platform from the [releases page](https://github.com/noorle/cli-releases/releases).

Available binaries:
- `noorle-linux-x64` - Linux x86_64
- `noorle-linux-arm64` - Linux ARM64
- `noorle-darwin-x64` - macOS Intel
- `noorle-darwin-arm64` - macOS Apple Silicon
- `noorle-windows-x64.exe` - Windows x64

### Verify Downloads

Each release includes SHA256 checksums. To verify your download:

```bash
# Download the checksum file
curl -LO https://github.com/noorle/cli-releases/releases/latest/download/noorle-linux-x64.sha256

# Verify the binary
sha256sum -c noorle-linux-x64.sha256
```

### Resources

- [Noorle Official Website](https://noorle.com)
- [Noorle Documentation](https://noorle.com/docs)
- [Noorle CLI Reference](https://noorle.com/docs/reference/cli)
