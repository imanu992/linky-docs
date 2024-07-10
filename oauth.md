## About Linky Oauth
We have created a Linky Authorization that allows you to be added to the "Linky’s Showcase" server once you add the bot to your server! Let me explain better.

### Scopes
In the authorization, we have selected 2 scopes: `guilds.join` & `identify`.

> [!IMPORTANT]
> For now, the `identify` scope is not used and no information is collected. This scope is enabled because in the future we plan to create a website dedicated to Linky, and the active scope will help facilitate the login process via Discord.

### guilds.join Scope
We know this scope can seem very intimidating, but it's not! You can leave the server at any time. Rest assured, if you decide to leave the server, the authorization will not automatically add you back.
Just remember, if you leave the server, the `/bump` command will be disabled!

### Where are the OAuth redirects located?
You can find them in the **"Add App"** button in the bot's profile.
![Add App Button](https://i.imgur.com/v2RL3fu.jpeg)
And in the invite command, both in the text and the button message. Both links are the same, except the text link is in the form of a hyperlink because the original link is too long.
![invite cmd](https://i.imgur.com/DBwZNN9.jpeg)

### Direct Oauth Link
https://linky-oauth.vercel.app/login
