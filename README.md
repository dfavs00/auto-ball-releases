# Auto Ball

[![Latest Release](https://img.shields.io/github/v/release/dfavs00/auto-ball-releases?label=latest%20release)](https://github.com/dfavs00/auto-ball-releases/releases/latest)

Auto Ball is an arcade soccer **autobattler**. You build a team of animal characters, each with their own stats and abilities, then send them onto the field and watch them play. Your job is picking the right team.

This repo hosts ready-to-run builds for macOS and Windows.

> **Early access:** Auto Ball is actively in development (currently `v0.2.x`). Expect missing features and rough edges.

## Download & Install

Grab the latest version for your platform from the [Releases page](https://github.com/dfavs00/auto-ball-releases/releases).

### macOS (Apple Silicon — M1/M2/M3/M4)

1. Download `autoball-macos-arm64.zip` and double-click to unzip it.
2. Builds aren't signed yet, so macOS will block the first launch. To allow it:
   - Try opening the app normally. macOS will show a warning.
   - Go to **System Settings** → **Privacy & Security**, scroll to the bottom, find Auto Ball in the "Security" section, and click **Open Anyway**.
   - If that option doesn't appear, try running this in Terminal: `xattr -dr com.apple.quarantine`, then drag the app into the Terminal window and press Enter.
3. After that, you can open it normally.

*Intel Macs aren't supported yet.*

### Windows (x64)

1. Download `autoball-windows-x86_64.zip`.
2. Right-click the file → **Extract All...**
3. Open the extracted folder and run the `.exe`.
4. Windows SmartScreen will warn "Windows protected your PC" since the build isn't signed. Click **More info** → **Run anyway**.

*Linux builds aren't available yet.*

## How to Play

Auto Ball is an autobattler — your characters play automatically once the match starts.

1. **Start a match** — play online against another player, or test out strategies in sandbox mode.
2. **Build a team** — buy unit from the shop and place them on the field. Each with their own stats, movement patterns, synergies, (speed, strength, stamina) and a unique ability. Characters with the same synergies grant your team enhancements and stat buffs.
3. **Watch it unfold** — your characters chase the ball, defend, and use abilities on their own. Whoever scores more goals wins.
4. Repeat until there is a winner. In online play. The team with the most points at the end of 10 matches winsis the winner.

Since this is `v0.2.x`, there is still more to be done. Please stand by as we continue to add new characters, features and balancing.

## Something Broken?

Bugs are expected this early. If something crashes, [open an issue](https://github.com/dfavs00/auto-ball-releases/issues) with what happened and your OS.

## Staying Up to Date

New versions are posted to the [Releases page](https://github.com/dfavs00/auto-ball-releases/releases). Just re-download when one drops.
