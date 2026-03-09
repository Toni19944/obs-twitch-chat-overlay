# obs-twitch-chat-overlay
Simple HTML you can load as a browser source. Connects anonymously via Twitch IRC. Does not require log in or API keys or anything.  
---
- Displays username colors and twitch default chat badges.  
- Also supports emotes yippeee! (twitch emotes and channel emotes only. No 7tv etc. support for now. sorry...)  
- Should display correct colors that users have set and only use random color if an user has never set a custom color on twitch.  

---
### Setup/installation
- Download or copy paste the chat-overlay.html
- CHANGE YOUR CHANNEL NAME (around the line 142 where the "config" part is")
  - additionally you can change the max messages amount and fade out timer.  
    - default max messages: ```25```. Fade out: ```30s```
  - if you don't want messages to fade out:  
    - comment out the ```scheduleFade(div);``` lines with ```//``` - these are on lines 383 and 392
- Add the html file as a browser source in OBS.
- profit???

I'm using 400x700 size on a 1080p stream (just a point of reference you know...). No need to change any other settings if you don't want to. I have shutdown and refresh boxes ticked. Custom CSS and permissions are just default.

---

![demo](chat-overlay-demo.gif)
