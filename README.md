# Solid Snake Sound Pack

**Tactical espionage audio for your coding sessions.**

A [peon-ping](https://github.com/PeonPing/peon-ping) sound pack featuring the legendary Solid Snake from the Metal Gear Solid series. Get iconic voice lines when your AI coding agent needs attention.

## Installation

### Quick Install

```bash
# Install peon-ping if you haven't already
curl -fsSL https://raw.githubusercontent.com/PeonPing/peon-ping/main/install.sh | bash

# Clone this pack
git clone https://github.com/will/openpeon-solid-snake.git
cd openpeon-solid-snake

# Copy to your peon-ping packs directory
cp -r . ~/.claude/hooks/peon-ping/packs/solid_snake/

# Activate the pack
peon packs use solid_snake
```

### Via Registry (Coming Soon)

Once this pack is registered in the [OpenPeon registry](https://github.com/PeonPing/registry), you'll be able to install it directly:

```bash
peon packs install solid_snake
peon packs use solid_snake
```

## What You'll Hear

| Event | Example Quotes |
|---|---|
| **Session starts** | *"Kept you waiting, huh?"*, *"This is Snake"*, *"It's Snake"* |
| **Task acknowledged** | *"Roger that"*, *"Sounds like a plan"*, *"Got it"* |
| **Task complete** | *"Negative, finished"*, *"Watch your friendly fire"*, *"OK"* |
| **Task error** | *"What the hell?"*, *"Damn!"*, *[Snake scream]* |
| **Input required** | *"We've got a job to do"*, *"I need your help"*, *"What am I supposed to do?"* |
| **Resource limit** | *"No"*, *"I can't move"*, *"Running out of time"* |
| **User spam** | *"Give me a break"*, *"You'll pay for that"* |

All 32 voice clips have been volume-normalized for consistent playback.

## Pack Details

- **CESP Version**: 1.0
- **Total Sounds**: 32 MP3 files
- **Language**: English
- **License**: CC-BY-NC-4.0 (for personal/educational use)
- **Audio Sources**: Various Metal Gear Solid games

## Audio Quality

All sounds have been:
- Cleaned and trimmed for quick playback
- Volume normalized using hybrid loudness+peak normalization (-16 LUFS target)
- Encoded at 192 kbps MP3 for quality and small file size
- SHA256 hashed for integrity verification

## Contributing

Found a great Snake quote that's missing? Have suggestions for better sounds? Open an issue or submit a PR!

## Credits

Voice clips are property of Konami and are used under fair use for personal notification purposes. Original voice actor: David Hayter (MGS 1-4, Peace Walker, Ground Zeroes).

Pack created by [@will](https://github.com/will) for the [OpenPeon](https://openpeon.com) sound pack ecosystem.

## Links

- [peon-ping](https://github.com/PeonPing/peon-ping) - Main CLI tool
- [OpenPeon](https://openpeon.com) - CESP spec and pack browser
- [Create your own pack](https://openpeon.com/create) - Pack creation guide
