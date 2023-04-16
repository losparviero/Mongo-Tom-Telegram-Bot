# Mongo Tom Telegram Bot

Talk to the foul mouthed, badass Mongo Tom in Telegram! Powered by GPT-3.

<br>

### Brief Note

This uses the official ChatGPT API which is paid hence will require an API key from OpenAI. You'll be billed for usage accordingly. Refer to OpenAI's website for pricing.

<br>

### Install

1. Clone repo.
2. Run ```npm i``` in project folder.
3. Rename .env.example to .env.
4. Populate .env file with bot token, bot dev ID(s) and OpenAI API key.
5. Run ```node bot``` to start the bot.

<details>

<summary>
.env reference
</summary>

<br>

BOT_ADMIN refers to the user ID of your Telegram account. This is for logging purposes. You can add multiple IDs separated by commas.

API_KEY refers to OpenAI API key.

</details>

#### It's advisable to run the bot using PM2 or any startup manager for persistent execution.

<br>

### Uninstall

1. Use ```rm -rf```.

*Note:* If you're unfamiliar with this command, delete project folder from file explorer.

<br>

### License

AGPL-3.0 ©️ Zubin