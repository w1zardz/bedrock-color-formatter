# Bedrock Color Formatter

Online gradient and HEX color code generator for **Minecraft Bedrock Edition** and **PocketMine-MP** (PMMP) servers.

## 🎨 Features

- **Gradient generator** — smooth color transitions across any text with 2-8 color stops
- **Multiple output formats** — PMMP `§x`, config `&x`, MOTD `\u00a7`, and raw HEX
- **Live preview** — see your colored text in real time
- **Bold support** — add `§l` bold formatting
- **8 preset palettes** — Sunset, Ocean, Neon, Fire, Forest, Royal, Gold, Ice
- **Mobile-first** — fully responsive, works great on phones and tablets
- **Copy to clipboard** — one-click copy, paste directly into `config.yml` or `Main.php`

## 🚀 How to Use

1. Enter your text (e.g., rank name, title, bossbar message)
2. Pick 2-8 gradient colors or choose a preset
3. Select output format (PMMP §x, &x config, MOTD, or raw HEX)
4. Copy the generated code into your plugin config or PHP source

## 📋 Output Formats

| Format | Example | Use Case |
|--------|---------|----------|
| **PMMP §x** | `§x§F§F§0§0§0§0` | Direct use in PocketMine-MP PHP code |
| **&x config** | `&x&F&F&0&0&0&0` | YAML config files with & color codes |
| **MOTD \\u00a7** | `\u00a7x\u00a7F\u00a7F...` | Server MOTD / query settings |
| **RAW hex** | `[FF0000]` | Reference / other tools |

## 🔧 For PocketMine-MP Developers

Bedrock Edition (1.19.80+) supports custom HEX colors via the `§x§R§R§G§G§B§B` format. This tool generates properly formatted color codes that you can use in:

- **Titles** (`$player->sendTitle()`)
- **Boss bars** (`BossBar::setTitle()`)
- **Chat messages** (`$player->sendMessage()`)
- **Scoreboards**
- **Item names** (`$item->setCustomName()`)
- **Permission group prefixes**
- **Server MOTD**

## 🌐 Live Demo

**[Open Bedrock Color Formatter →](https://w1zardz.github.io/bedrock-color-formatter/)**

## License

MIT
