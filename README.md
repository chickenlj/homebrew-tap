# AgentScope Homebrew tap

Install the AgentScope CLI and Runtime Host together:

```bash
brew install chickenlj/tap/agentscope-cli
as version
as connect https://YOUR-SERVICE
as runtime status
```

Supports macOS and Linux on amd64/arm64. The formula downloads prebuilt binaries
from the AgentScope Java GitHub Release and verifies SHA-256. Go is not required.
Install and authenticate your coding agent provider separately.

Update with `brew update` and `brew upgrade chickenlj/tap/agentscope-cli`.

## 中文

运行上面的 brew install 命令会同时安装 as 和 Runtime Host，无需安装 Go。
