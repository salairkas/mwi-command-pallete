# MWI Command Palette

A command palette for Milky Way Idle that provides quick access to items, actions, marketplace, and wiki pages.

## Features

### Quick Access
- **Cmd+K** (Mac) or **Ctrl+K** (Windows/Linux) to open the command palette from anywhere in the game
- Fast search with autocomplete suggestions
- Works without clicking the chat input

### Smart Search
- Fuzzy matching for typo-tolerant searches
- Token-based matching for partial words (e.g., "rad fib" finds "Radiant Fiber")
- Exact match, starts-with, and contains matching
- Configurable edit distance tolerance for typos

### Multiple Actions
- **Enter**: Open Item Dictionary or navigate to action
- **Shift+Enter**: Open item in Marketplace
- **Cmd/Ctrl+Enter**: Open item in Wiki (new tab)
- **Alt/Option+Enter**: Navigate to item's crafting action or skill

### Dungeon Support
- Specify tier when searching for dungeons: "chimerical 2" opens Chimerical Den tier 2
- Defaults to tier 0 if no tier specified
- Automatically validates and clamps tier to valid range

### Content Coverage
- All game items with Item Dictionary links
- All crafting, gathering, and combat actions
- Individual monsters and dungeons
- Seamless navigation across the entire game

### User Experience
- Arrow keys or mouse for navigation
- ESC to close palette or any open modals
- Visual selection highlighting
- Keyboard shortcut hints displayed in palette

## Installation

1. Install a userscript manager (Tampermonkey, Violentmonkey, etc.)
2. Click the installation link or copy the script
3. Confirm installation in your userscript manager

## Configuration

Edit the `CONFIG` object in the script to customize:
- Keybinds for palette trigger and actions
- Fuzzy matching sensitivity
- Maximum number of suggestions
- Action hints visibility

## Usage Examples

- Type "iron ore" → Enter (open Item Dictionary)
- Type "radiant" → Shift+Enter (open Marketplace)
- Type "cheese" → Cmd+Enter (open Wiki page)
- Type "fishing" → Enter (navigate to Fishing)
- Type "chim 1" → Enter (find party for Chimerical Den tier 1)
- Type "chees bul" → finds "Cheese Bulwark" (fuzzy matching)

## Platform Support

- Milky Way Idle (https://www.milkywayidle.com)
- Test server (https://test.milkywayidle.com)
- Chinese server (https://www.milkywayidlecn.com)

## License

MIT License
