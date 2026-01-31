# NetherGames Guild Site

This is a little project I made to use the NetherGames Guild API features to automatically invite people to a guild if they meet the requirements.
To make this work you'll want to make a .env file with the following things:
- GUILD_SECRET_KEY = Your NetherGames Guild API Key
- DISCORD_WEBHOOK = A Discord webhook, used for logging
- JWT_SECRET_KEY = Arbitrary value used for authenticating users
- COOKIE_SECRET_KEY = Arbitrary value used for signing cookies

You'll also need to update app.js with your Guild name along with the frontend with your Guild's name.
