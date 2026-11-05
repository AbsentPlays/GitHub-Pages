# 🎮 Streamer & Content Creator GitHub Pages Hub

Welcome to the repository for **Absentplays**' official streamer portfolio and link hub, built for deployment via **GitHub Pages**.

This landing page serves as a central showcase for live streams, social handles, weekly streaming schedules, video guides, and an interactive Web Audio soundboard.

---

## ✨ Features & Highlights

- **Live Stream Banner Indicator**: Highlight active stream status right at the top of your landing page.
- **Interactive Audio Engine**: Web Audio API soundboard generating retro sound effects (*GG Fanfare*, *Rare Loot*, *Level Up*) without external audio files.
- **Social Media Hub**: Instant links and handle copying for Twitch, YouTube, Kick, Discord, and Twitter/X.
- **Weekly Schedule Section**: Clean display for stream times and game schedules.
- **Featured Video Showcase**: Grid displaying video thumbnails, titles, and view counts.
- **Separated Clean Stylesheet**: All styles reside inside `css/style.css` for simple maintenance.

---

## What it looks like
![Streamer Preview](images/streamerpreview.png)

---

## 🚀 Deployment Instructions (GitHub Pages)
1. Fork or Clone this repository to your GitHub account.
2. Update the profile details, links, and text inside index.html.
3. Add your profile picture as images/absent.png.
4. Go to your repository settings on GitHub:
* Navigate to Settings > Pages.
* Under Build and deployment, set Source to Deploy from a branch.
* Select the main branch and / (root) directory, then click Save.
5. Your portfolio site will be live at:https://<your-username>.github.io/<repository-name>/
  
---

## 🛠️ Customization Guide

1. Profile Information
Edit the <header> block in index.html to change your streamer name, bio, and category tags:


```<h1 class="streamer-name">YourName</h1> <p class="streamer-tagline">Variety Gaming & Community Streams</p>```

2. Social Media Links
Update the href values inside .socials-grid:
``<a href="[https://twitch.tv/YOUR_HANDLE](https://twitch.tv/YOUR_HANDLE)" target="_blank" class="social-card twitch">``

4. Stream Schedule
Update stream times and days inside the .schedule-item elements in index.html.

---

## 📜 License
This project is open-source under the MIT License. Feel free to modify and adapt it for your own stream landing page!
