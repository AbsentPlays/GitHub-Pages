# ⚔️ OSRS Content Creator Portfolio & Link Hub

Welcome to the repository for my official Old School RuneScape (OSRS) creator landing page, hosted using **GitHub Pages**.

This website serves as a central hub for my social media links, streaming schedule, account progression, and community announcements.

---

## 🚀 Quick Setup & Deployment

1. **Fork or Clone this repository** to your GitHub account.
2. **Customize `index.html`** with your creator details (social handles, stream times, and stats).
3. **Enable GitHub Pages**:
   - Go to **Settings** > **Pages** inside your repository settings.
   - Under **Build and deployment**, set the **Source** to `Deploy from a branch`.
   - Select the `main` (or `master`) branch and save.
4. Your website will be live at:  
   `https://<your-username>.github.io/<repository-name>/`

---

## 🛠️ Customization Guide

All styling and layout structure are contained in `index.html` for simple maintenance.

### 1. Basic Profile Info
Search for the header section in `index.html` to modify your display name, tagline, and bio:

```html
<h1 class="creator-title">YourName</h1>
<p class="subtitle">Ironman Enthusiast & High-Level PvM Guide Creator</p>

```

### 2. Avatar / Profile Picture

Replace the default placeholder image with your own avatar URL, or upload an image (e.g., `avatar.jpg`) directly into this repository and update the source:

```html
<img src="avatar.jpg" alt="Profile Picture" class="avatar">

```

### 3. Social Media Links

Update the `href` links for Twitch, YouTube, Twitter/X, and Discord inside the `.socials-grid` section:

```html
<a href="[https://twitch.tv/YOUR_CHANNEL](https://twitch.tv/YOUR_CHANNEL)" target="_blank" class="social-card twitch">

```

### 4. Stream Schedule & In-Game Stats

Edit the text inside the `.info-grid` container to display your current max total, kill counts, or favorite skills.

---

## 🎨 Design Features

* **Authentic OSRS Aesthetics**: Built using classic stone/gold interface colors and retro pixel fonts (`Press Start 2P`).
* **Responsive Layout**: Designed for seamless display on desktops, tablets, and mobile devices.
* **Live Banner**: Integrated top alert bar to highlight stream status or new video releases.
* **Lightweight**: Zero external JS dependencies—built purely with vanilla HTML and CSS.

---

## 📜 Disclaimer

*Old School RuneScape is a registered trademark of Jagex Ltd. This landing page is a community fan project and is not affiliated with or endorsed by Jagex.*

```

```