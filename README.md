# OBS Twitch Chat Overlay
Simple HTML browser source overlay. Connects anonymously via Twitch IRC. Does not require log in or API keys or anything.  
---
- Displays username colors and twitch default chat badges.
  >custom badges require you to register a developer app on twitch. But it's free and takes about 2-minutes. Refer to setup guide for more info on that. :)
- Also supports bttv/ffz/7tv emotes yippeee!

---
## Setup

1. Go to the **[Setup Page](https://toni19944.github.io/obs-twitch-chat-overlay/)**
2. Enter your channel name and preferences
3. Click **Generate OBS URL**
4. In OBS, add a new **Browser Source**
5. Paste the generated URL into the URL field
6. Set your desired width/height (I'm using 400x700 on a 1080p stream, just for reference)
7. Check **Allow transparency**
8. Click OK — you're done!

## Custom Sub Badges (optional)

To show your channel's custom subscriber badge art:

1. Register a free app at [dev.twitch.tv](https://dev.twitch.tv/console/apps)
2. Set the OAuth redirect URL to `https://toni19944.github.io/obs-twitch-chat-overlay/`
3. Set the Client Type to **Confidential**
4. Copy your **Client ID** and generate a **Client Secret**
5. Enter both in the setup page before generating your URL

> ⚠️ Keep your generated URL private if it contains your Client ID and Secret — don't share it publicly.

## Features

- ✅ Twitch native emotes
- ✅ BTTV, FFZ and 7TV emotes
- ✅ Badges (mod, VIP, sub, broadcaster etc.)
- ✅ Custom channel sub badge art (optional)
- ✅ Messages fade out after 30 seconds
- ✅ No login, no promo emails, no ads — just a single HTML file


---

![demo](chat-overlay-demo.gif)

---

## Disclaimer

This was coded/created with Claude AI (Sonnet 4.6). I know frick-all about programming/coding. Just figured to inform that instead of being all like "I made this" when in reality I mostly copy pasted code.
