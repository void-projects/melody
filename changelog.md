# Changelog

## Versions

### 1.2.9

Removed some commands and simplified them. Many commands can now only be used inside servers and not DMs.

* Update `cmds/`
  * All files have been updated
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.8

Now uses my API for `topic`, `joke`, `pickup`, `roast`, and `toast`

* Update `cmds/`
  * Update `cmds/topic.js`
  * Update `cmds/joke.js`
  * Update `cmds/pickup.js`
  * Update `cmds/roast.js`
  * Update `cmds/toast.js`
  * Remove `cmds/fun.json`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.7

Most of the old commands have been revised with error catches to prevent bot crashes. There are a few new commands, bug and suggest, to bring users to the GitHub Issue page.

* Update `cmds/`
  * Update `cmds/avatar.js`
  * Update `cmds/ban.js`
  * Create `cmds/bug.js`
  * Update `cmds/endthebot.js`
  * Update `cmds/help.js`
  * Update `cmds/help.json`
  * Update `cmds/kick.js`
  * Update `cmds/ping.js`
  * Update `cmds/serverinfo.js`
  * Create `cmds/suggest.js`
  * Update `cmds/userinfo.js`
  * Update `cmds/version.js`
  * Update `cmds/whoareyou.js`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.6

New commands and some edits to commands

* Update `cmds/`
  * Update `cmds/fun.json`
  * Update `cmds/help.js`
  * Create `cmds/help.json`
  * Create `cmds/roast.js`
  * Create `cmds/toast.js`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.5

Now uses KSoft.Si API for hug and kiss commands

* Update `cmds/`
  * Update `cmds/hug.js`
  * Update `cmds/kiss.js`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.4

Now has two more commands!

> The `meme` and `wholesome` commands have a slight delay

* Update `cmds/`
  * Create `cmds/meme.js`
  * Create `cmds/wholesome.js`
  * Update `cmds/help.js`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.3

Now featured on top.gg

* Update `bot.js`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.2

Kissing and hugging

* Update `cmds/`
  * Create `cmds/kiss.js`
  * Update the following files:
    * `cmds/help.js`
    * `cmds/hug.js`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.1

New commands, embeds for command responses, code cleanup.

* Update `cmds/`
  * Create `cmds/hug.js`
  * Update the following files:
    * `cmds/help.js`
    * `cmds/joke.js`
    * `cmds/pickup.js`
    * `cmds/ping.js`
    * `cmds/topic.js`
    * `cmds/version.js`
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.2.0

Updated the command handler

### 1.1.3

This will be the final push with new features for a while. I am going to try and rewrite the code and use a better form of command handling. See the status of this project in [Issue \#25](https://github.com/void-melody/melody/issues/25).

* Update `bot.js`
  * Cleaned up some spacing and added a way to log in what servers Melody is in.
* Update `CHANGELOG.md`
* Update `README.md`
* Update `package.json` and `package-lock.json`

### 1.1.2

* Update commands 
  * Create `cmds/pickup.js`
    * Melody will send pickup lines --- whether good or bad.
  * Added "pickup" to the list of commands in `cmds/help.js`
* Update `CHANGELOG.md`
* Update `README.md`
  * Added "pickup" to the list of commands
* Update `package.json` and `package-lock.json`

### 1.1.1

* Update commands
  * Added new jokes to `cmds/jokes.js`
  * Added new questions to `cmds/topics.js`
  * Added "whoareyou" command to `cmds/help.js` after finding out it wasn't listed. 
  * Update `cmds/help.js`
    * Rearranged the help responses
  * Added new admin commands
    * Added "kick" to kick the user from server
    * Added "ban" to ban the user from server
* Update `CHANGELOG.md`
* Update `README.md`
  * Added "whoareyou" command after finding out it wasn't listed.
  * Added new commands to the list
* Update `package.json` and `package-lock.json`

### 1.1.0

**Directory Update** After doing some testing, I've found a way to create a command directory.

* Create `cmds/*`
  * Moved commands from `bot.js` to their own files
* Update `CHANGELOG.md`
* Update `bot.js`
  * Set up the command directory
* Update `package.json` and `package-lock.json`

### 1.0.8

* Update `CHANGELOG.md`
* Update `bot.js`
  * Found out that the "version" command was not properly listed in the "help" command's response, so I fixed that up.
  * Created "userinfo" command to get basic user information
  * Created "serverinfo" command to get basic server information
  * Fixed "userinfo" and "serverinfo" conflicts with "ping"
* Update `README.md`
  * Added the new commands to the list presented
* Update `package.json` and `package-lock.json`

### 1.0.7

* Created `CHANGELOG.md`
  * Moved the changelogs that was in `README.MD` to this file
* Update `bot.js`
  * Added "avt"/"avatar" command back after doing some command testing
  * Updated "help" to match the command updates
* Update `README.md`
  * Moved the changelog to this file
  * Added list of commands
  * Added links links to other important files
* Update `package.json` and `package-lock.json`

### 1.0.6

**Release**

* Added bot to the [Discord Bots List](https://top.gg/bot/662469470618648576)
* Update `bot.js`
  * Removed "avt" command because the bot would not respond to the command
  * Updated "help" command to match the command updates
  * Added "whoareyou" command to let the bot tell some info about itself
* Update `README.md`
* Update `package.json`
* Update `app.json`

### 1.0.5

**General Maintenance**

* Update  `bot.js`
  * Removed "user" command since there is an issue getting the proper information
  * Cleaned up spacing
* Update `README.md`
* Update `package.json`

### 1.0.4

**Jokes**

> Got rid of moderation commands because there were a bunch of errors with the permissions

* Update `bot.js`
  * "j"/"joke" - Simple jokes and punch lines
* Update `README.md`
* Update `package.json`

### 1.0.3

**Topic Command!**

* Update `bot.js`
  * "t"/"topic" - Going to be used as a way to start conversations in servers.
* Update `README.md`
* Update `package.json`

**Adding role IDs to Heroku**

* Update `bot.js`
  * Removed IDs
  * Added Heroku configuration variables
  * Reorganized scripts and snippets
* Update `README.md`
* Update `package.json`

### 1.0.2

**Secured the Discord bot token**

* Removed `settings.json`
* Update `README.md`
* Update `package.json`

### 1.0.1

**Fixed role bugs**

* Update `bot.js`
  * Fixed moderation role permissions
* Update `README.md`
* Update `package.json`

### 1.0.0 Alpha

**Renamed files and merged everything to be named "Melody"**

* Recreated `README.md`
  * Renamed old `README.md` to `OLD_README.md`
* Updated information in `package.json` and `app.json` to reflect the new name change
* Changed GitHub and Heroku repo names and changed the name on Discord

