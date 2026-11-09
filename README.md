# Multi Chat Viewer

A simple, clean multi-platform chat viewer for **Twitch**, **YouTube**, and **TikTok**.

Built with pure HTML/CSS/JS. No backend required. Perfect for GitHub Pages.

## Features

- Official Twitch chat embed
- YouTube Live chat embed
- TikTok section with link to official live page
- Dark theme, responsive layout
- Load channels via URL parameters

## How to use

1. Open the page
2. Enter:
   - Twitch channel name
   - YouTube video ID or full live URL
   - TikTok @username or live URL
3. Click **Load Chats**

### URL parameters (optional)

You can pre-load channels:

```
?tw=channelname&yt=VIDEO_ID&tt=@username
```

## Deploy on GitHub Pages

1. Go to the repository **Settings** → **Pages**
2. Source: Deploy from a branch
3. Branch: `main` / root
4. Save

Your site will be available at:

`https://Lichengantv.github.io/multi-chat-viewer/`

## Notes

- TikTok does **not** provide a public chat embed. For real combined TikTok + YouTube + Twitch chat, use tools like **AxelChat**, **StreamBuddy**, or **Multistream**.
- This project only uses official embeds and stays within platform terms.

## License

MIT