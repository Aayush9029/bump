# bump

Bump Xcode project marketing version from the command line.

## Installation

```bash
brew install aayush9029/tap/bump
```

Or tap first:

```bash
brew tap aayush9029/tap
brew install bump
```

## Usage

```bash
bump                    # interactive prompt
bump patch              # 1.2.3 → 1.2.4
bump minor              # 1.2.3 → 1.3.0
bump major              # 1.2.3 → 2.0.0
bump 2.0.0              # set version directly
bump ~/MyApp patch      # bump in specific directory
```

## Options

| Flag | Description |
|------|-------------|
| `-h, --help` | Show usage info |
| `-v, --version` | Print version |
| `-c, --check` | Show current version only |

## How it works

1. Finds `.xcodeproj` in the current (or specified) directory
2. Reads `MARKETING_VERSION` from `project.pbxproj`
3. Applies the new version via `sed` replacement
4. Updates all build configurations at once

## Requirements

- macOS

## License

MIT

---

*More CLI tools: [`brew tap aayush9029/tap`](https://github.com/Aayush9029/homebrew-tap)*
