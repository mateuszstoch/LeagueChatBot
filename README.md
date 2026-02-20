# 🎮 QuickChat

**QuickChat** is a universal gaming overlay that allows you to quickly send predefined messages to the chat without taking your hands off the keyboard. Boost your team's morale or taunt your opponents with just a few keystrokes!

## ✨ Features

*   **In-Game Overlay:** A transparent window that automatically positions itself over your active game client.
*   **Fast Navigation:** Fully controlled via keyboard shortcuts.
*   **Message Categories:** Messages are organized into clear categories (e.g., "Taunts", "Morale boosters").
*   **Auto-Typing:** The bot automatically opens the chat, types the message, and sends it.
*   **Chat Mode Toggle:** Easily switch between sending messages to All Chat or Team Chat on the fly.
*   **Fully Configurable:** Easily add your own custom messages (`text_lines.json`), adjust overlay visuals, and remap all hotkeys (`config.toml`).

## 🚀 Installation & Usage

1.  **Download the latest release:**
    Go to the [Releases](https://github.com/mateuszstoch/QuickChat/releases) page and download the `QuickChat.exe` file.

2.  **Prepare configuration files:**
    Make sure to have the `text_lines.json` and `config.toml` files in the same folder as the executable. You can download the default ones from the repository or customize them.

3.  **Run the application:**
    Double-click `QuickChat.exe` to start the bot.

4.  **Start your game:**
    *   *Note: For the overlay to work correctly, most games must be running in **"Borderless"** or **"Windowed"** mode.*

## ⌨️ Controls

| Key | Action |
| :---: | :--- |
| **`\`** | Show / Hide Menu |
| **`.`** | Next Page |
| **`,`** | Previous Page |
| **`/`** | Return to Categories |
| **`6` - `0`** | Select Option (Items 1-5 on the list respectively) |
| **`Insert`** | Toggle All Chat / Team Chat mode |
| **`F10`** | Close Application |

*(Note: All hotkeys can be changed in `config.toml`)*

## ⚙️ Configuration

### 📝 Messages (`text_lines.json`)

You can edit the list of messages in the `text_lines.json` file. The format is standard JSON:

```json
{
    "Category Name": [
        "Message 1",
        "Message 2"
    ]
}
```

### 🛠️ Settings (`config.toml`)

The application can be fully customized using the `config.toml` file.

*   **`[visuals]`**: Change overlay transparency (`alpha`), background colors, and text colors.
*   **`[hotkeys]`**: Remap all keyboard shortcuts, including GUI toggle, navigation, message selection, chat mode toggle, and app exit.
*   **`[chat]`**: Configure the chat opening key (default `<enter>`) and chat command prefixes (e.g., `/all`, `/team`).

Example `config.toml`:

```toml
[visuals]
alpha = 150
background_color = [10,10,10]
text_color = [200,200,200]

[hotkeys]
toggle_gui = '\'
toggle_chat = '<insert>'
```

## ⚠️ Warning

This tool is an external macro script. Use it at your own risk. We recommend reviewing your game developer's policy regarding "Third Party Tools".

## 📚 License
This software is licensed under the PolyForm Noncommercial License 1.0.0.
It is free for personal, hobby, and educational use. Commercial use is strictly prohibited.
See the LICENSE file for the full text.
