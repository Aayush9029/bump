<img src="assets/icon.png" width="128" alt="bump">

# bump

Bump Xcode project marketing version from the command line.

## Install

```bash
brew install aayush9029/tap/bump
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

---

*More CLI tools: [`brew tap aayush9029/tap`](https://github.com/Aayush9029/homebrew-tap)*
