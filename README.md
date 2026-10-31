# Auto Auction

Split stacks fast and list items on the Auction House without retyping commands. Client-side only, so it works in singleplayer and on servers without any server install.

## Features

**Hotbar Item Splitter**
- Give each of the 9 hotbar slots its own split amount: 64, 32, 16, 8, 4, 2 or 1, or turn the slot off.
- Selecting a hotbar slot makes its amount the active one.
- Split the held stack with a keybind, or Ctrl + Right-click any stack in your inventory.
- The stack becomes exactly your amount and the rest moves to a free slot. 64 merges matching stacks.
- Uses normal inventory clicks only. If something goes wrong, items go back to your inventory and are never dropped or duplicated.

**Configuration GUI**
- Pick a slot, pick an amount, enable or disable it, or reset to defaults.
- Everything saves automatically and is kept between sessions.

**Auction House Quick Sell (optional)**
- Shows the item in your hand and a price box that accepts `2500`, `10k` or `2.5m`.
- Four editable price shortcuts.
- One click sends a single normal `/ah sell <price>` command, the same as typing it yourself. Nothing is automated.
- `/quicksell 10k` does the same without opening the screen.

## Controls (all rebindable)
`K` open GUI · `V` split held stack · `J` toggle splitter · `U` Auction House settings

## Requirements
Minecraft 1.21.11 · Fabric Loader · Fabric API · Java 21

## Notes
Always follow your server's rules. This mod does not bypass any server restrictions.
