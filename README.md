# Pi-hole Mobile Doom Scroll Block List

A comprehensive block list for Pi-hole to block mobile social media domains and prevent doom scrolling.

## 📋 Block List

The `mobile_doomscroll_blocklist.txt` file contains domains for major social media platforms including:

- TikTok
- Instagram
- X (Twitter)
- LinkedIn
- YouTube
- Facebook
- Snapchat
- Reddit
- Pinterest
- Twitch
- Discord
- Netflix
- Amazon Prime Video
- And more...

## 🚀 Usage

Add this URL to your Pi-hole's adlists:
```
https://raw.githubusercontent.com/msteele3/pihole-mobile-blocklist/master/mobile_doomscroll_blocklist.txt
```

## 📖 Full Instructions

See the detailed setup and customization instructions in the repository files.

## 📝 Format

- One domain per line
- Lines starting with `#` are comments
- Compatible with Pi-hole adlist format

## 🔄 Updates

Update your Pi-hole gravity after adding:
```bash
pihole -g
```