# Dice Bot

⚂⚄⚅⚅⚃⚃⚀⚄⚃⚂⚂⚂⚄⚁⚃⚃⚄⚀⚀⚅⚂⚄⚁⚁⚄⚂⚁⚃⚅⚃⚁⚅⚁⚂⚃⚁⚁⚂⚅⚁⚃⚀⚃⚅⚅⚀⚅⚄⚅⚃

Dice Bot is a Discord Bot whose purpose is to facilitate fair fantasy dice rolls in chat.
Dice Bot interprets simple English and [RPG Dice Notation](https://en.wikipedia.org/wiki/Dice_notation).

## Usage

Once Dice Bot is installed, just talk to it. Here are some things you can say:

- A simple roll: `Roll a D20`
- Multiple dice: `Roll 3D6`
- With advantage or disavantage: `Roll a D20 with advantage`
- Percentile: `Roll percentile`
- With modifiers: `Roll 2D4+4`
- Multiple sets: `Roll 2D12 x2`
- Rerolls: `Roll a D8 and reroll ones`
- Drop lowest: `Roll 4D6 and drop the lowest one`
- Take highest: `Roll 4D6 and take the highest three`
- Roll an entire stat block at once: `Roll 4D6, reroll ones, take the top three x6`

## Questions, Issues, Feature Requests

Please [Create an Issue](https://github.com/wizulus/dice-bot/issues) if you notice anything wrong, or have any feature requests.

## Installation

Follow [this link](https://discordapp.com/api/oauth2/authorize?client_id=509733973644279818&permissions=1074120768&scope=bot) to install Dice Bot on your discord server.

### Permissions

- **Send Messages** *(Required)*: Allows Dice Bot to respond to dice roll requests in chat.
- **Embed Links** *(Optional)*: If information requested is too large to fit in a message, such as your roll history, Dice Bot may provide a link to download the information.
- **Attach Files** *(Optional)*: As an alternative to **Embed Links**, Dice-bot may attach requested information as a file.
- **Add Reaction** *(Optional)*: Dice Bot may add reactions to messages from users if the request is confusing, or funny.
- **Read Message History** *(Optional)*: If you ask Dice Bot to roll dice, but edit your message to fix a typo, Dice Bot will update its response with your new criteria. If the original message is too old, it doesn't work without this permission.
- **Manage Emojis** *(Optional)*: Allows Dice Bot to add custom Dice Emojis so you can see the dice, rather that use text, or system emojis.
- **Use External Emojis** *(Optional)*: If **Manage Emojis** is enabled, allows Dice Bot to use the emojis in messages.

