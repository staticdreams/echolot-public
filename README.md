# Echolot

Echolot is a native macOS client for HTTP, GraphQL, gRPC and MCP APIs, with a command-line runner, an MCP server for AI agents and a built-in assistant. This repository is its public side; the source code is private.

- **Download:** the notarized `Echolot-<version>.dmg` from [Releases](../../releases/latest). Echolot needs macOS 15 or later on Apple silicon.
- **Updates:** once installed, Echolot updates itself (Echolot › Check for Updates…). The feed it reads is [`appcast.xml`](appcast.xml), served at `https://staticdreams.github.io/echolot-public/appcast.xml`; every update is signed.
- **Command line:** the `echolot` tool ships inside the app (`Echolot.app/Contents/Helpers/echolot`), and each release also has it on its own as `echolot-<version>-macos.zip` (universal).
- **Claude Desktop:** `Echolot-<version>.mcpb` installs Echolot's MCP server as an extension.
