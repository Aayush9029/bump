<p align="center">
  <img src="assets/icon.png" width="128" alt="bump">
  <h1 align="center">bump</h1>
  <p align="center">Bump Xcode project marketing version from the command line</p>
</p>

<p align="center">
  <a href="https://github.com/Aayush9029/bump/releases/latest"><img src="https://img.shields.io/github/v/release/Aayush9029/bump" alt="Release"></a>
  <a href="https://github.com/Aayush9029/bump/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Aayush9029/bump" alt="License"></a>
</p>

## Install

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
bump --check            # show current version only
```

## License

MIT
