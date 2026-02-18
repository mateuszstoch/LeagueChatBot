# 🎮 LeagueChatBot

**LeagueChatBot** is a League of Legends overlay that allows you to quickly send predefined messages to the chat without taking your hands off the keyboard. Boost your team's morale or taunt your opponents with just a few keystrokes!

## ✨ Features

*   **In-Game Overlay:** A transparent window that automatically positions itself over the League of Legends client.
*   **Fast Navigation:** Fully controlled via keyboard shortcuts.
*   **Message Categories:** Messages are organized into clear categories (e.g., "Taunts", "Morale boosters").
*   **Auto-Typing:** The bot automatically opens the chat (defaults to `/all`), types the message, and sends it.
*   **Fully Configurable:** Easily add your own custom messages in a simple JSON file.

## 🚀 Installation & Usage

1.  **Download the latest release:**
    Go to the [Releases](https://github.com/mateuszstoch/LeagueChatBot/releases) page and download the `LeagueChatBot.exe` file.

2.  **Prepare configuration file:**
    Make sure to have the `text_lines.json` file in the same folder as the executable. You can download the default one from the repository or create your own.

3.  **Run the application:**
    Double-click `LeagueChatBot.exe` to start the bot.

4.  **Start League of Legends:**
    *   *Note: For the overlay to work correctly, the game must be running in **"Borderless"** or **"Windowed"** mode.*

## ⌨️ Controls

| Key | Action |
| :---: | :--- |
| **`\`** | Show / Hide Menu |
| **`.`** | Next Page |
| **`,`** | Previous Page |
| **`/`** | Return to Categories |
| **`6` - `0`** | Select Option (Items 1-5 on the list respectively) |
| **`F10`** | Close Application |

## ⚙️ Configuration

You can edit the list of messages in the `text_lines.json` file. The format is standard JSON:

```json
{
    "Category Name": [
        "Message 1",
        "Message 2"
    ]
}
```

## ⚠️ Warning

This tool is an external macro script. Use it at your own risk. We recommend reviewing Riot Games' policy regarding "Third Party Tools".
