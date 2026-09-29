# Portfolio & Content Creator Landing Page

A sleek, responsive dark-mode portfolio landing page built for tech content creators, developers, and streamers. Features dynamic YouTube channel statistics using the YouTube Data API v3, animated counters, smooth scroll animations, and responsive card layouts.

---

## Features

* **Dark Theme UI**: Clean, dark aesthetic with YouTube-inspired red accent highlights.
* **YouTube API Integration**: Automatically fetches channel subscriber count, video count, and total view count.
* **Animated Stat Counters**: Smooth counting animations for channel statistics on initial page load.
* **Intersection Observer Animations**: Scroll-triggered fade-in animations for section cards and featured content.
* **Responsive Video Embed**: Fully responsive 16:9 aspect ratio container for featured YouTube videos.
* **Zero Dependencies**: Pure HTML, CSS, and vanilla JavaScript—no external frameworks required.

---

## Directory Structure

```text
.
├── index.html
└── images/
    └── Absent.png       # Profile / avatar image

```

---

## Quick Start

1. **Clone or Download** the project repository.
2. Ensure your avatar image is located at `images/Absent.png` (or update the `src` attribute on line 223 in `index.html`).
3. Open `index.html` in any web browser to preview locally.

---

## Configuration & Customization

### 1. Connecting Your YouTube Channel API

To enable live statistics, edit the JavaScript block near the bottom of `index.html`:

```javascript
// Replace with your YouTube Channel ID and API Key
const YOUTUBE_CHANNEL_ID = 'YOUR_CHANNEL_ID_HERE'; 
const YOUTUBE_API_KEY = 'YOUR_API_KEY_HERE';

```

> **Note**: If left as default placeholders or if the API call fails, the page gracefully falls back to default fallback numbers (50k subs, 120 videos, 2M views).

### 2. Updating Profile Details & Links

* **Channel Name & Tagline**: Update the `<h1>` and `.tagline` text inside the `<header>` block.
* **Subscribe Button**: Change the `href` attribute in the primary CTA button:
```html
<a href="https://youtube.com/@yourchannel" class="btn" target="_blank" rel="noopener">Subscribe on YouTube</a>

```


* **Featured Video**: Replace `dQw4w9WgXcQ` in the `<iframe>` `src` URL with your own YouTube video ID:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen title="Featured Video"></iframe>

```


* **Playlists & Social Links**: Update the card headers, description text, and social anchor links (`href`) inside the `<main>` and `<footer>` sections.

---

## Customization & Styling

All key branding colors and font settings are defined using CSS custom properties at the top of the `<style>` block in `index.html`:

```css
:root {
  --bg: #0f0f0f;           /* Background color */
  --card-bg: #1f1f1f;      /* Card background color */
  --text: #ffffff;         /* Primary text color */
  --text-muted: #aaaaaa;   /* Secondary text color */
  --accent: #ff0000;       /* Primary accent color (YouTube Red) */
  --accent-hover: #cc0000; /* Accent hover color */
  --border: #333333;       /* Border stroke color */
}

```

---

## License

This project is open source and available under the MIT License.