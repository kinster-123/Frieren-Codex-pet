# Frieren · Floating Spellbook Pet

English | [简体中文](README.md)

An unofficial Codex desktop pet inspired by Frieren, accompanied by a floating spellbook. It uses the v2 sprite-sheet format and includes idle, movement, waving, jumping, waiting, failure, reading/work, and 16-direction look animations.

> This is an unofficial fan work. It is not affiliated with, sponsored by, or endorsed by the creators, publishers, production committee of *Frieren: Beyond Journey's End*, or OpenAI. Read the [asset and copyright notice](ASSET_NOTICE.md) before use.

![All animation states](previews/all-states.gif)

## Highlights

- 11 × 8 grid with 192 × 208 px cells in an RGBA PNG
- 73 used animation frames
- 9 animation-state groups and 16 look directions
- Transparent background with no residual chroma-key pixels
- 1536 × 2288 px v2 sprite sheet

## Install

GitHub filters the custom `codex://` protocol, so the install address cannot be used as a clickable README link. Copy the complete address below instead:

```text
codex://pets/install?name=Frieren&imageUrl=https%3A%2F%2Fraw.githubusercontent.com%2Fkinster-123%2FFrieren-Codex-pet%2Fmain%2Ffrieren-floating-book-spritesheet-v2.png&description=Frieren%20with%20a%20floating%20spellbook&spriteVersionNumber=2
```

Then open it using either method:

- Windows: press `Win + R`, paste the address, and press Enter; alternatively, run `Start-Process '<copied address>'` in PowerShell.
- macOS: run `open '<copied address>'` in Terminal.

Codex will open the pet installation confirmation. After installing, select `Frieren` under `Settings > Pets`, then enter `/pet` to show it. If nothing happens, update the desktop app and confirm that Pets are available for your account or workspace.

The address uses a public GitHub Raw HTTPS sprite sheet and `spriteVersionNumber=2`. You can also [download the sprite sheet directly](https://raw.githubusercontent.com/kinster-123/Frieren-Codex-pet/main/frieren-floating-book-spritesheet-v2.png). See the [official OpenAI deep-link reference](https://learn.chatgpt.com/docs/reference/commands#pets).

Compatible third-party loaders can use [`frieren-floating-book-spritesheet-v2.png`](frieren-floating-book-spritesheet-v2.png) directly with sprite version `2`.

## Files

```text
.
├── frieren-floating-book-spritesheet-v2.png  # Final sprite sheet
├── previews/all-states.gif                    # Animation overview
├── README.md                                  # Chinese documentation
├── README.en.md                               # English documentation
└── ASSET_NOTICE.md                            # Asset and copyright notice
```

This repository does not grant a commercial-use license for the depicted character or relicense third-party intellectual property under an open-source license. See [ASSET_NOTICE.md](ASSET_NOTICE.md).
