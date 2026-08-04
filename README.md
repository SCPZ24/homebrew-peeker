# Homebrew Peeker

Official Homebrew Tap for [Peeker](https://github.com/SCPZ24/Peeker), a native
macOS dynamic-island utility for low-distraction daily progress.

Peeker 的官方 Homebrew Tap。Peeker 是一个用于低干扰每日进度管理的原生 macOS
灵动岛工具。

## Install / 安装

Peeker requires an Apple Silicon Mac running macOS 26 or later.

Peeker 需要运行 macOS 26 或更高版本的 Apple Silicon Mac。

```bash
brew install --cask SCPZ24/peeker/peeker
```

The fully-qualified command registers this Tap automatically. You can also tap
first and then use the short cask name:

完整命令会自动注册本 Tap。也可以先注册 Tap，再使用短名称安装：

```bash
brew tap SCPZ24/peeker
brew install --cask peeker
```

Upgrade or uninstall with:

升级或卸载：

```bash
brew upgrade --cask peeker
brew uninstall --cask peeker
```

## First launch / 首次启动

Peeker is ad-hoc signed and is not notarized because the project does not have
an Apple Developer ID. After the first blocked launch, open **System Settings →
Privacy & Security**, click **Open Anyway** for Peeker, then confirm **Open**.
Do not disable Gatekeeper.

由于项目没有 Apple Developer ID，Peeker 使用 ad-hoc 签名且未经 Apple 公证。
首次启动被拦截后，请打开**系统设置 → 隐私与安全**，为 Peeker 点击**仍要打开**，
然后确认**打开**。无需也不应关闭 Gatekeeper。

## Release source / 发布源

The Cask downloads immutable versioned assets from
[SCPZ24/Peeker Releases](https://github.com/SCPZ24/Peeker/releases) and verifies
them with SHA-256.

Cask 从 [SCPZ24/Peeker Releases](https://github.com/SCPZ24/Peeker/releases)
下载不可变的版本化资产，并使用 SHA-256 校验。
