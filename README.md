# Saberfy

Search and import tracks from BeatSaver into Beat Saber — with Spotify integration.

> **Status:** Work in progress

## Features

- Find maps for your Spotify liked tracks via BeatSaver
- Search BeatSaver by song name or artist
- One-click map import to Beat Saber
- Map sorting and filtering
- In-app map preview

## Requirements

- Node.js >= 16

## Installation

```bash
git clone git@github.com:dev-okinawa/Saberfy.git
cd Saberfy
npm install
```

## Setup

1. Create a Spotify app at [developer.spotify.com/dashboard](https://developer.spotify.com/dashboard)
2. Add your `clientId` to `src/config/spotify.ts`
3. Start the app:

```bash
npm start
```

## Build

| Command | Output |
|---|---|
| `npm run package` | Standalone executable |
| `npm run make` | Platform installer |

## License

[MIT](LICENSE)
