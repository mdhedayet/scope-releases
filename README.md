<div align="center">

# Scope

**An AI-native code editor with a built-in coding agent.**

[Website](https://scopeide.com) · [Latest release](https://github.com/mdhedayet/scope-releases/releases/latest) · [All releases](https://github.com/mdhedayet/scope-releases/releases)

</div>

Scope is a desktop IDE where an AI coding agent works next to your editor. It reads your project, edits files, runs commands, and shows every change inline so you stay in control.

This repository hosts the **official downloads** for Scope. The application source is not published here.

## Download

Get the installer for your system from the **[latest release](https://github.com/mdhedayet/scope-releases/releases/latest)**.

| System | File to download |
| --- | --- |
| **macOS**, Apple Silicon (M1/M2/M3/M4) | `Scope-<version>-arm64.dmg` |
| **macOS**, Intel | `Scope-<version>-x64.dmg` |
| **Windows** (works on x64 and ARM64) | `Scope-<version>.exe` |
| **Linux**, Debian / Ubuntu | `Scope-<version>-amd64.deb` (Intel/AMD) or `Scope-<version>-arm64.deb` (ARM) |
| **Linux**, any distribution | `Scope-<version>-x86_64.AppImage` (Intel/AMD) or `Scope-<version>-arm64.AppImage` (ARM) |

Not sure which Mac you have? Open  → About This Mac. "Chip: Apple M…" means Apple Silicon, "Processor: Intel" means Intel.

## Features

- **Agent chat** next to the editor, with threads, tool approvals, image attachments and `@`-mentions. Select code and send it to the chat in one click.
- **Inline diff review.** When the agent edits a file, the changes show in the editor with Accept / Reject for each chunk, plus Accept all / Reject all.
- **Full editor.** Syntax highlighting for 25+ languages, autocomplete, multi-cursor, find and replace, folding, command palette, quick open and project-wide search.
- **Git built in.** Stage, commit and revert per hunk, branch picker, pull / push / stash, file history and blame.
- **Integrated terminal** with a separate working directory per terminal.
- **SSH remote editing.** Open and work on projects on a remote server.
- **Light and dark themes**, and file icons from the Material Icon Theme.

## Install

### macOS

1. Open the `.dmg` and drag **Scope** into **Applications**.
2. The app is not notarized yet, so macOS may say it can't verify the developer. Right-click **Scope** in Applications, choose **Open**, then **Open** again. You only need to do this once.

### Windows

1. Run the `.exe` installer.
2. If Windows SmartScreen shows "Windows protected your PC", click **More info**, then **Run anyway**. The installer is not code-signed yet.

### Linux

**Debian / Ubuntu (`.deb`)**

```sh
sudo apt install ./Scope-<version>-amd64.deb
```

**AppImage (any distribution)**

```sh
chmod +x Scope-<version>-x86_64.AppImage
./Scope-<version>-x86_64.AppImage
```

If the AppImage does not start on a recent Ubuntu, run it with `--no-sandbox`, or install the `.deb` instead.

## Verify your download

Each release lists the exact files that were built by our CI. Only download Scope from this repository's [Releases](https://github.com/mdhedayet/scope-releases/releases) page or from [scopeide.com](https://scopeide.com).

## Updates

Download the newest installer from the latest release and install it over your current version. Your settings and projects are kept.

## Support

- Questions or problems: [support@scopeide.com](mailto:support@scopeide.com)
- Bug reports and feature requests: open an [issue](https://github.com/mdhedayet/scope-releases/issues) in this repository. Please include your OS, the Scope version, and the steps to reproduce.

## License

Scope is proprietary software. The installers in this repository are provided for use under the terms on [scopeide.com](https://scopeide.com). All rights reserved.
