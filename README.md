# imperia-custode

> Risen from the ashes of [`realm-guard`](https://github.com/GNUWeeb/realm-guard).

A Telegram group management bot made with Node and Telegraf.

Currently at a WIP stage and is not fit for production use.

## Features

### Generic

- [x] Show bot start message
- [x] Show bot help
  - [ ] Interactive bot help
- [x] Show bot version
- [x] Show user/bot information

### Administration

- [x] Greeting user
  - [x] Setting and resetting welcome message
  - [x] Setting and resetting farewell message
- [x] Banning user
  - [x] Banning user temporarily
  - [x] Banning user silently
- [x] Unbanning user
- [x] Kicking user
- [x] Muting user
  - [x] Muting user temporarily
  - [x] Muting user silently
- [x] Unmuting user
- [x] Warning user
  - [x] Adding user warns
  - [x] Clearing user warns
  - [ ] Resetting user warns
  - [x] Showing user warns
- [x] Purging the group chat
- [x] Reporting user
- [x] Pinning message
- [x] Unpinning message

> Features are subject to change and will probably change depending on the needs

## Running

1. Install the dependencies using `pnpm install` or `npm install` or whichever node package manager you prefer.
2. Copy the example `.env.example` environment table file and rename it to `.env`.
3. Copy your bot token into the environment variable `BOT_TOKEN` as its value.
4. Change the remaining environment variables accordingly. (`BOT_NAME` and `STORAGE_DIR` if you use it)
5. Run `npm run dev` or `pnpm run dev` or `yarn run dev` or whichever node package manager you prefer as long as it runs.
6. Voila!

## Acknowledgements

[GNU/Weeb](https://github.com/GNUWeeb) members used to partake in developing this bot, namely [Alviro Iskandar Setiawan](https://github.com/alviroiskandar) and [Ammar Faizi](https://github.com/ammarfaizi2). I wish to invite them again soon but for now, I will take over the development and clean up the code until I can take further actions towards inviting people to contribute.

So many thanks towards all the people contributing in `realm-guard` development. But I'll take the lead this time.

## License

MIT
