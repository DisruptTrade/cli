# Disrupt CLI

Trade crypto from your terminal. This repository holds the binary releases of
the Disrupt CLI; the source is maintained upstream.

## Install

Download the binary for your platform from the
[latest release](https://github.com/DisruptTrade/cli/releases/latest), make it
executable and put it on your `PATH`:

| Asset                     | Platform           |
| ------------------------- | ------------------ |
| `disrupt-darwin-arm64`    | Apple Silicon Macs |
| `disrupt-darwin-x64`      | Intel Macs         |
| `disrupt-linux-x64`       | Linux x86_64       |
| `disrupt-linux-arm64`     | Linux arm64        |
| `disrupt-windows-x64.exe` | Windows x64        |

```bash
curl -fsSL https://github.com/DisruptTrade/cli/releases/latest/download/disrupt-darwin-arm64 -o /usr/local/bin/disrupt
chmod +x /usr/local/bin/disrupt
disrupt login
```

Every release ships a `SHA256SUMS` file alongside the binaries.

## Update

```bash
disrupt update
```

On Windows, download the new `.exe` again instead.
