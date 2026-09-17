````md
# Discord Music Bot

A Discord music bot built with Node.js and Discord.js, featuring music playback, slash commands, 24/7 voice support, autoplay, music request channels, audio filters, and dashboard integration.

## Features

- 🎵 Music playback
- 🎧 Support for YouTube, Spotify, SoundCloud and other supported sources
- ⚡ Slash command support
- 💬 Message command support
- 🖥️ Dashboard support
- 🔊 24/7 voice channel support
- ▶️ Auto-resume functionality
- 📻 Music request channel system
- 🎛️ Audio filters
- 👑 DJ system
- 🚀 Discord.js v14 support
- ☁️ Can be deployed on VPS and similar hosting platforms

## Requirements

- [Node.js](https://nodejs.org/) LTS
- MongoDB
- A Discord Bot Application

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Vedanta-Singh/test-mucic.git
cd test-mucic
````

### 2. Install dependencies

```bash
npm install
```

### 3. Configure the bot

Create a `.env` file and add the required configuration:

```env
TOKEN=
MONGO_URL=
PREFIX=
GUILD_ID=
```

> **Important:** Never publish your Discord bot token, MongoDB credentials, or other private credentials.

### 4. Install additional packages

```bash
npm install @discordjs/opus
npm install zlib-sync@latest
npm install erlpack@latest
```

### 5. Start the bot

```bash
node index.js
```

## Configuration

The bot uses environment variables for configuration.

```env
TOKEN=YOUR_DISCORD_BOT_TOKEN
MONGO_URL=YOUR_MONGODB_CONNECTION_STRING
PREFIX=YOUR_PREFIX
GUILD_ID=YOUR_DISCORD_SERVER_ID
```

## Project Status

**Archived / Educational Project**

This is an older project that I built/experimented with while learning Discord bot development, JavaScript and Node.js. It is being kept public as part of my development history and GitHub portfolio.

The project is not actively maintained.

## Attribution

This project is based on an existing open-source Discord music bot project.

Credit and attribution belong to the original project and its contributors. Please refer to the original source repository and its license for the upstream implementation and licensing information.

## License

MIT License.

See the `LICENSE` file for details.

---

⭐ If you find this project useful, feel free to explore the code and learn from it.

```
```
