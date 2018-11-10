# Changelog
All notable changes to this project will be documented in this file.

## Unreleased - 9/27/2018
### Added
- Added **ping** command.
- Added **music** commands.
- Added **weather** command.
- Added **auto response** using [Cleverbot API](https://cleverbot.io/).
- Added **message logging**.

## 0.0.1 - 10/2/2018
### Changed
- **Updated client ID and bot token**
- **Reworked music commands** to respond according to the current status of command author and the bot.
- Disabled message logging on servers.
- Updated command restrictions to avoid unwanted abuse of the bot.
- Added icons to most if not all responses.

### Added
- Added **basic moderation** commands such as kick, ban, mute, and unmute.
- Added search commands such as **urban**, **weather**, and **opendota**.
- Added other commands like flip, roll and quote.
- Added diag and uptime to give a detailed info about the bot.

### Removed
- Removed auto response by Cleverbot.
- Removed weather thumbnail.

## 0.0.2 - 10/8/2018
### Changed
- Fixed bot shutdown on unexpected errors.
- Fixed opendota command returning {"statusCode":200,"success":false} when last login is not available.
- Clear now deletes the response message after 5 seconds.
- Major rewrite on play command now returns 5 choices instead of playing track right away.

### Added
- Added **fortnite** command.
- Added **settings** command for server administrators.
- Added **welcome messages** for new members. (Disabled by default)
- Added **unpause** to music commands.

## 0.0.3 - 10/13/2018
### Changed
- **Updated some parts of play command** to improve response time.
- **Enabled changing of bot prefix** for server administrators.

### Added
- Added **serverinfo** and **userinfo** commands.
- Added **brazzers** command.

### Removed
- Completely removed Google command.
## [0.0.4](https://github.com/christianavi/midnight/commit/3d522796b86c9852109e1f6338fc5cfd43c527bd) - 10/15/2018

### Added
- Added **queue** command.
- Added the ability to play music directly from **Youtube URLs**.

### Changed
- **Fixed play command** returning option 4 when no response has been made for 2 minutes.
