# Auto Ball

Auto Ball is an arcade soccer **autobattler**. You build a team of animal characters, each with their own stats and abilities, then send them onto the field and watch them play the match on their own — no twitchy controls to master. Your job is picking the right team, not pressing the right buttons.

This repo hosts ready-to-run builds. No code, no Unity install, no setup — just download and play.

> **Early access:** Auto Ball is a young, actively-developed project (currently `v0.1.x`). Expect missing features and rough edges, and check back often — new builds land regularly.

## Download & Install

Grab the latest version for your platform from the [Releases page](https://github.com/dfavs00/auto-ball-releases/releases).

### macOS (Apple Silicon — M1/M2/M3/M4)

1. Download `autoball-macos-arm64.zip` and double-click to unzip it.
2. Builds aren't signed yet, so macOS Gatekeeper will block the first launch. To get past it:
   - Right-click the app → **Open** → **Open** again in the popup that appears.
   - If that doesn't work, open Terminal and run `xattr -dr com.apple.quarantine`, then drag the app into the Terminal window and press Enter.
3. After that first launch, you can open it normally any time.

*Intel Macs aren't supported yet — only Apple Silicon builds are available.*

### Windows (x64)

1. Download `autoball-windows-x86_64.zip`.
2. Right-click the file → **Extract All...**
3. Open the extracted folder and run the `.exe`.
4. Windows SmartScreen will likely warn "Windows protected your PC" since the build isn't signed yet. Click **More info** → **Run anyway**.

*Linux builds aren't available yet.*

## How to Play

Auto Ball is an autobattler, so you don't drive a character around with a keyboard or controller. Instead:

1. **Build a team** — your roster is made up of animal characters, each with their own stats (speed, strength, stamina) and a unique ability.
2. **Start the match** — once it kicks off, your characters play automatically: chasing the ball, defending the goal, and using their abilities.
3. **Watch it play out** — whichever team scores more goals wins.

The current roster includes **Dash the Cheetah** and **Ronny the Raccoon**, with more characters, abilities, and team-building options on the way. Since this is an early `v0.1.x` build, you're mostly watching a live match unfold right now — deeper drafting and customization features are still being built and will show up in future releases.

## Something Broken?

Bugs are expected this early on. If something crashes or looks wrong, [open an issue](https://github.com/dfavs00/auto-ball-releases/issues) with what happened and your OS — it genuinely helps.

## Staying Up to Date

There's no auto-updater yet. New versions are posted to the [Releases page](https://github.com/dfavs00/auto-ball-releases/releases) — just re-download and reinstall when one drops.
