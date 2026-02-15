# VoX - Overlay Pro (English Version)

**Based on shinkonet’s code, adapted and improved for Wplace.**

Welcome to **VoX - Overlay Pro v5.1.3 (English Version)**!

This guide will help you master all the tools that the script makes available. The engine has been updated for better performance and ease of use.

---

## 1. Installation

To use the script, you need a browser extension called **Tampermonkey**.

### Supported Browsers

| Platform                       | Recommended Browsers                                 |
| :----------------------------- | :--------------------------------------------------- |
| **PC / Mac**             | Chrome, Firefox, Brave, Edge, Opera GX               |
| **Mobile (Android/iOS)** | **Microsoft Edge (Recommended)**, Kiwi Browser |

### Steps

1. **Install Tampermonkey**:

   - [Tampermonkey for Chrome/Brave/Edge](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

   **Note for Mobile:** Edge users can install the extension directly from the browser’s "Extensions" menu.
2. **Install the Script:**
   The script updates automatically.
   
   [**⬇️ Click here to install the English version (v5.1.3)**](https://raw.githubusercontent.com/Jay-pn34/Wplace_VoX-Overlay-Pro-ENG/main/WplacePro-VoX.user.js)

   Tampermonkey will prompt you to confirm. Click "Install".

---

## 2. Your First Overlay

Follow these steps to place your design on the canvas:

1. Open the **VoX panel** in Wplace.
2. Go to the **Overlays** tab and click **+ Add**.
3. Go to the **Editor** tab.

### Choose Color Mode

Select the **Mode** that best fits your design:

- **🌿 Natural:** Default; ideal for photos, memes, soft gradients.
- **⚡ Vibrant:** Perfect for logos, text, bright neon colors.
- **💀 Heavy (Anime):** Prioritizes exact color precision (HSV). Use for complex pixel art or anime.
  ⚠️ *Very heavy; may slow performance.*

### Upload the Image

- **From URL:** Paste the direct link and click **Upload**.
- **Local File:** Click the box to upload from your device.
  *(Colors are processed automatically.)*

### Pin to Canvas

1. Click **Set Position: OFF** (will switch to ON).
2. Click on the canvas at the pixel where you want the top-left corner (0,0) of your image.
3. Done! Your image is fixed.

---

## 3. Main Panel and Display Modes

- **Overlay: ON/OFF** → Show or hide all designs.
- **Mode: Minify** → Change overlay display:
  - *Minify (Recommended)*: Small dots for seeing below the overlay.
  - *Behind/Above*: Displays the image behind or in front of the canvas.
  - *Original*: Hides the overlay to see the real map.
- **Show Errors: ON/OFF** → Highlights pixels that do not match your design using inverted colors for better visibility (especially on unpainted areas).
- **Player Stats (Username / Level / Droplets / Next Level)** → Automatically reads your account data from Wplace and shows:
  - **Droplets** with dynamic color based on amount:
    - 0–499: default text color
    - 500–1999: yellow (able to increase max by 5 paint or buy 30 paint)
    - 2000–19,999: green (buy a color)
    - 20,000+: red (buy flag or change icon)

💡 **Tip:** Adjust opacity, position, or filters, then move the map slightly or paint a pixel to see changes. No reload required.

---

## 4. Advanced Features

### Overlays Tab

- Each overlay stores its own color filter settings. Multiple assets can have different configurations.

### Editor Tab

- **Opacity:** Control transparency of overlay.
- **Nudge:** Use arrows to move the image pixel by pixel.
- **Capacity:** Supports images up to **3000x3000px**.

### Tools Tab

- **Copy Canvas:**

  1. Set **Point A**.
  2. Set **Point B**.
  3. Click **Detect and Download** to copy that canvas area.
- **Show Overlay Progress:** Opens a floating panel:

  - **Color List:** Shows missing pixels by color.
  - **Filters (⚙️):** Hide finished colors or filter to delegate tasks.
  - **Optimization:** Dashboard loads instantly without freezing.
  - **🔄 Refresh Counts:** Button to refresh the remaining pixel counts for all colors.
  - **📍 Show Remaining Pixel Locations:** Button to view all remaining pixels with their exact canvas coordinates. Click on any pixel to navigate directly to that location on the canvas.

---

## 5. New Features (v5.1.3)

### Error Mode Improvements

- **Inverted Empty Space Display:** Error mode now shows inverted colors for better visibility, making it easier to spot pixels that need to be placed, especially on unpainted areas.
- **Fixed Black Color Visibility:** Black pixels now properly display in error mode even when the original tile is unpainted, ensuring all missing pixels are visible.
- **Customizable Error Color:** New setting in General Settings to choose between inverse color mode or a custom color for error highlighting. Your preference is saved in browser storage.

### Remaining Pixels Management

- **Refresh Remaining Pixel Counts:** New button in the Overlay Progress panel to manually refresh and update the count of remaining pixels for each color.
- **Remaining Pixel Locations:** New feature that shows a detailed list of all remaining pixels with:
- **Group colors by their progress status:** Each color will be grouped based on their status selected, completed, Not started, In Progress.
  - Exact canvas coordinates for each pixel
  - Color grouping for easy organization
  - Direct navigation links to jump to each pixel location
  - Copy and download options for pixel coordinates

---

## 6. Support and Settings

- **Settings (⚙️):** 
  - Switch theme (Light/Dark)
  - Adjust panel transparency
  - **Error Color Mode:** Choose between "Inverse Color" (default) or "Custom Color" for error highlighting
  - **Custom Error Color:** When Custom Color mode is selected, pick any color from the color picker
- **Support the Project:** Free and community-maintained. Consider donating via the settings menu if you find it helpful.
  - **Want to donate?** Please contact me on my [GitHub page](https://github.com/Jay-pn34) for additional donation details.

---

Enjoy creating on **wplace.live** with **VoX Overlay Pro (English Version)**! 🚀
