# teamotes
![Project Status](https://img.shields.io/badge/🏷-v1.0.3-green)

![teamotes-v1 0 2](https://user-images.githubusercontent.com/5164617/90266303-0e7e5180-de54-11ea-98ad-ae8abdcdbf53.gif)

Your app to use emotes anywhere - simply point the app to a folder and click on one of the images. [Download your free copy now!](https://github.com/lostdesign/teamotes/releases)

## Features
- Copy any image to clipboard and paste it almost anywhere
- Searching for emotes in app

### Coming soon
- Variable Image sizes
- Emote stats
- Auto update and Codesigning
- Quick access like macOS spotlight

### Demo
![teamotes-v1 0 2-demo](https://user-images.githubusercontent.com/5164617/90267087-594c9900-de55-11ea-83c2-9282ac7b7e4a.gif)

Post emotes/images in Github, Twitter, Photo/Video editing software, Discord, Whatsapp, Telegram, your business presentation and many many more!

### FAQ
**Why is it called teamotes?**

The app originally was meant for MS Teams, since they [haven't added them since 2016](https://microsoftteams.uservoice.com/forums/555103-public/suggestions/16934329-allow-adding-custom-emoji-memes-gifs-reactions).

**Why can't I use gifs?**

Due to current technical limitations, GIFs cannot be copied and pasted in places. We maybe working on a drag and drop feature to enable this.

**Why do I get a warning when I start the app?**

This app does not have code signing for macOS or windows yet. We'll soon add it to remove these warnings.

**How do I update?**

Currently you have to revisit the releases tab inside this repo, the app doesn't update itself. It will be added once the codesigning is in place.

# For Developers
## How to install
1. Clone and npm install
```bash
git clone https://github.com/lostdesign/teamotes.git && cd teamotes
npm install
```
### How to use
1. Run the app
```bash
npm run dev
```
2. Click on settings and select the directory of your emotes.
3. Click on home and then on the emote to copy it.
4. Paste the emote on a discord chat to use it :sparkles:
