# Nutmeg
A Discord bot for an anonymous chatting bridge between servers. Based on omegle
Built for Discord Hack Week.

# Installation

* Clone the repo: `git clone https://github.com/mdean808/nutmeg.git`
* Enter the directory: `cd nutmeg`
* Install dependencies: `npm install`
* Specify your token in `.env/TOKEN`
* Start the bot: `npm start`
* Add the bot to your servers: BOT LINK

# Usage

* ~setup - Set up the bot's permissions
  * Server name: Random or custom
  * Filesharing: true or false
  * Link sharing: true or false
  * Server invitations: true or false
* ~nutmeg [name] - Create's a new channel [name] and matchmakes for another server to connect to.
* ~end - Starts a vote in the active nutmeg channel for the server to decide to disconnect
* ~share - Starts a vote in the active nutmeg channel for the server to share an invite link
