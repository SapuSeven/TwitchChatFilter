# TwitchChatFilter
My attempt to make the Twitch.tv Chat more enjoyable.

_Note: This project is still WIP but basic functionality is already present._

## Installation

This is a UserScript, so you need to install a script manager like [GreaseMonkey](https://greasespot.net/) or [TamperMonkey](https://tampermonkey.net/) first.

After that, you can [open the raw script file](https://github.com/SapuSeven/TwitchChatFilter/raw/main/TwitchChatFilter.user.js) and your manager will prompt you to install the script.

You have to reload any opened Twitch.tv pages for the changes to take effect.

## Available filters

- Remove single word messages
- Remove single emote messages
- Remove commands
- Reduce repeating characters
- Merge repeated words
- Merge repeated emotes

## Known issues

- Settings are not yet implemented and filters cannot be configured
- Only the first visited chat will be filtered; A reload is required after navigating to another stream 

## Notes

Messages with purple background indicate an error during filtering.
