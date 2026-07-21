# JioHotstar Ad Studio & Resizer

A premium, interactive web application to resize, crop, and normalize creative assets for JioHotstar ad delivery specifications.

🚀 **Live Site**: [https://yaarzee.github.io/preview/](https://yaarzee.github.io/preview/)

---

## Features

### 📐 Creative Resizer & Spec Normalizer
*   **Ad Formats Support**:
    *   **Banner Ad** (640 × 100 px, JPEG) with safe-area guides.
    *   **Brand Logo** (120 × 120 px, JPEG).
    *   **Carousel Card** (440 × 440 px, JPEG).
    *   **Takeover Poster** (970 × 250 px, JPEG).
    *   **Ad Video Asset** (1920 × 1080 px, MP4).
*   **Interactive Crop & Zoom**: Adjust and position raw image assets directly inside the targeted dimensions.
*   **Video Normalizer**: Bypasses browser timing drift to enforce a strict mathematical 25.00 FPS progression rate for ad spots (6s, 10s, 15s, or 30s).
*   **Smart Quality Compressing**: Automatically downscales export quality to meet the target file size limits (e.g., 200KB for banners).

### 📱 Ad Studio Mockup Preview
*   **Realistic Preview Frame**: Real-time rendering inside a premium iPhone frame with theme support (Entertainment Dark vs. Live Sports Green).
*   **Interactive Controls**: Update brand names, headlines, CTA text, colors, and upload demo images or videos on the fly.
*   **Mockup Export**: One-click download of the complete device mockup container as a high-quality PNG.

---

## Getting Started

To run the project locally, simply clone the repository and open `index.html` in any modern web browser:

```bash
# Clone the repository
git clone https://github.com/yaarzee/preview.git

# Open the project folder
cd preview

# Open index.html in your browser
open index.html
```

---

## Tech Stack
*   **Frontend**: Plain HTML5, Vanilla JavaScript (ES6+), Modern Custom CSS.
*   **Libraries**: [html2canvas](https://github.com/niklasvh/html2canvas) for high-fidelity browser screenshots.
*   **Fonts**: Inter (via Google Fonts).
*   **Hosting**: GitHub Pages.
