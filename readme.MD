# Better Undiscord

This is a fork of [Undiscord](https://github.com/victornpb/undiscord) with additional features for managing your Discord account. The original Undiscord functionality for deleting messages is preserved, with these new features added:

## New Features

### 1. Unblock All Users
- Removes all users from your block list
- Supports whitelisting specific users by ID
- Configurable rate limit delay
- Shows progress in real-time
- Can be stopped at any time

### 2. Unfriend All Users
- Removes all users from your friends list
- Supports whitelisting specific users by ID
- Configurable rate limit delay
- Shows progress in real-time
- Can be stopped at any time

### 3. Block All Friends
- Blocks all users in your friends list
- Supports whitelisting specific users by ID
- Configurable rate limit delay
- Shows progress in real-time
- Can be stopped at any time

### 4. Leave All Servers
- Leaves all servers you're in
- Supports whitelisting specific servers by ID
- Configurable rate limit delay
- Shows progress in real-time
- Can be stopped at any time

### 5. Leave All Group Chats
- Leaves all group DMs you're in
- Supports whitelisting specific group chats by ID
- Configurable rate limit delay
- Shows progress in real-time
- Can be stopped at any time

## Rate Limiting

All new features include configurable rate limiting to prevent Discord API restrictions:
- Each feature has its own delay setting
- Default delay is 1000ms (1 second)
- Automatically handles Discord's rate limits
- Shows warnings when rate limited
- Waits appropriate time before continuing

## Usage

1. Install the script using a userscript manager (Tampermonkey, Violentmonkey, etc.)
2. Open Discord in your browser
3. Click the 🗑️ button in the top right corner
4. Navigate to the "Addons" section
5. Use any of the new features:
   - Enter whitelist IDs (comma-separated) if needed
   - Adjust rate limit delays if desired
   - Click the corresponding button to start
   - Use the universal stop button to cancel at any time

## Safety Features

- Confirmation dialogs before starting any operation
- Whitelist support to prevent accidental actions
- Real-time progress logging
- Ability to stop operations at any time
- Rate limit handling to prevent API restrictions

## Original Undiscord Features

All original Undiscord features are preserved:
- Delete messages in channels/DMs
- Filter messages by content, date, or ID
- Support for multiple channels
- Import from Discord data package
- And more...

## ⚠️ Important Notes

- Use at your own risk
- Always double-check whitelist IDs
- Keep your auth token secure
- Consider using streamer mode when sharing screenshots
- Some operations cannot be undone

## Credits

Original Undiscord by [victornpb](https://github.com/victornpb/undiscord)
Edited by honourably and unhonourably :3 