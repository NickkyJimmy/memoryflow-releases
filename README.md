# MemoryFlow Releases

CLI binaries and install scripts for MemoryFlow.

## Install

### macOS / Linux

```bash
curl -fsSL https://raw.githubusercontent.com/nickkyjimmy/memoryflow-releases/main/install.sh | bash
```

### Windows (PowerShell)

```powershell
irm https://raw.githubusercontent.com/nickkyjimmy/memoryflow-releases/main/install.ps1 | iex
```

Then connect to your server:

```bash
memoryflow setup self-host --server-url https://<your-api-host> --app-url https://<your-app-host>
```
