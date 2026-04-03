# #65 Post Guard

A professional-grade safe zone overlay tool for short-form video creators. It allows users to instantly check if their captions or key visual elements will be hidden by TikTok, Instagram Reels, or YouTube Shorts' UI elements.

## Core Philosophy
* **1 Tool / 1 Action**: Upload a screenshot and instantly see the "Danger Zones" where UI elements (buttons, descriptions) usually appear.
* **Maintenance-Free Design**: Uses generalized "Danger Boxes" rather than exact icon replicas, ensuring the tool remains useful even after minor SNS updates.
* **Privacy First**: All image processing happens locally in the browser. No data is ever uploaded to a server.

## Key Features
* **Multi-Platform Support**: Toggle between TikTok, Reels, and Shorts layouts with a single tap.
* **Dynamic Safe Zone Guide**: Features a high-visibility green dashed box indicating the "Golden Zone" for text placement.
* **Smart Transparency**: Low-opacity overlays (20%) allow creators to see through to their content for pixel-perfect adjustments.
* **Sticky Navigation**: A fixed header menu allows for seamless platform switching while scrolling through long screenshots.

## Design System
* **Background**: #fff
* **Safe Zone**: rgba(39, 174, 96, 0.8) (Green Dashed)
* **Danger Zone**: rgba(231, 76, 60, 0.2) (Red Fill)
* **Border Radius**: 15px
* **Responsive**: Adapts to any screenshot aspect ratio without adding artificial letterboxing.

## Performance
* **Browser-only**: Zero backend, zero latency.
* **Ultra-Lightweight**: Optimized CSS-based rendering for smooth operation on mobile devices.

---
**Fridge Combo** | 100 Tools Project by afrorakda © 2026
