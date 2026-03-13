# OBS Twitch Chat Overlay
Simple HTML browser source overlay. Connects anonymously via Twitch IRC. Does not require log in or API keys or anything.  
---
- Displays username colors and twitch default chat badges.
  >custom badges would've been a lot harder to get to work, but if you really really want those then hit me up on socials and I can give you the version for that, it just requires a twitch dev app registration and you need to fill in your Client ID+Secret to the html file and host it through a command line local server if you want to keep it private. I personally didn't want to share mine publicly so I'll just take the hit on the badges and be happy that at least 3rd party emotes are working :)
- Also supports emotes yippeee!
  >twitch emotes and channel emotes only if you run locally. If you want 7tv/ffz/bttv support then you have to fork the repo and edit your channel name in the file, enable github pages and point OBS source to that pages url/overlay.html instead of local file. 
- Should display correct colors that users have set and only use random color if an user has never set a custom color on twitch.  

---
### Setup/installation
- Download or copy paste the twitch-chat-overlay.html
- CHANGE YOUR CHANNEL NAME (around the line 133 where the "config" part is")
  - additionally you can change the max messages amount and fade out timer.  
    - default max messages: ```25```. Fade out: ```30s```
  - if you don't want messages to fade out:  
    - comment out the ```scheduleFade(div);``` lines with ```//``` - these are on lines 383 and 392
- Add the html file as a browser source in OBS.
- profit???

I'm using 400x700 size on a 1080p stream (just a point of reference you know...). No need to change any other settings if you don't want to. I have shutdown and refresh boxes ticked. Custom CSS and permissions are just default.

---

![demo](chat-overlay-demo.gif)

---

## Disclaimer

This was coded/created with Claude AI (Sonnet 4.6). I know frick-all about programming/coding. Just figured to inform that instead of being all like "I made this" when in reality I mostly copy pasted code.
