<div align="center">

  <img src="icons/Icon-192.png" alt="ZanNav Mapper Logo" width="120" height="120" style="border-radius: 24px;" />

  # ZanNav Mapper

  **Community-Powered Public Transit Data Collection & Field Mapping for Zanzibar**

  [![Flutter Web](https://img.shields.io/badge/Flutter-Web%203.47.2-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
  [![PWA Ready](https://img.shields.io/badge/PWA-Ready-4F46E5?logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)
  [![Version](https://img.shields.io/badge/Version-1.0.4-10B981)](#)
  [![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web-blue)](#)

  <p align="center">
    <img src="og.png" alt="ZanNav Mapper Social Preview" width="100%" style="border-radius: 12px; margin-top: 16px;" />
  </p>

</div>

---

## 🌍 About ZanNav Mapper

**ZanNav Mapper** is a community-driven initiative and mapping tool designed to document, trace, and modernize Zanzibar's public transit network (dala-dalas and buses). 

Volunteers and field mappers use this application to record transit routes in real-time with high-precision GPS, pin bus stops along Stone Town and rural transit corridors, and build open transit data for the island.

---

## 📱 How to Use on iOS (iPhone & iPad)

This web application is built as a **Progressive Web App (PWA)**, allowing iOS users to install and run it without needing the Apple App Store:

1. Open the website in **Safari** on your iPhone or iPad.
2. Tap the **Share** button (the square icon with the upward arrow) at the bottom toolbar.
3. Scroll down and tap **"Add to Home Screen"**.
4. Confirm by tapping **"Add"** in the top-right corner.
5. The **ZanNav Mapper** icon will now appear on your home screen. When opened, it runs in **standalone mode** (full-screen without browser address bars) just like a native iOS application.

---

## 🤖 How to Use on Android

1. Open the website in **Google Chrome** on your Android device.
2. An **"Install App"** banner will automatically appear at the bottom.
3. Tap **Install**, or tap the three dots `⋮` in the top right and select **"Install ZanNav Mapper"**.
4. The app installs directly to your launcher with offline caching enabled.

---

## 🚀 Features

- **📍 High-Precision GPS Tracing**: Record transit trajectories in real-time as vehicles move.
- **🚏 Bus Stop Mapping**: Capture coordinates, names, and landmarks for informal and formal stops.
- **📶 Offline-First Capabilities**: Service worker caching allows mappers to access the interface even in low-connectivity areas.
- **⚡ Modern UI**: Tailored for both mobile touchscreens and desktop survey analysis.

---

## 🛠 GitHub Pages Hosting Instructions

This directory contains the production-ready static web bundle built with Flutter.

### Steps to Host:

1. **Push to GitHub**:
   Upload or push the files in this directory to your GitHub repository (either on the `main` branch or a dedicated `gh-pages` branch).

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Navigate to **Settings** > **Pages** (under the "Code and automation" section).
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select your branch (e.g., `main` or `gh-pages`) and set the folder to `/ (root)`.
   - Click **Save**.

3. **Included GitHub Pages Optimizations**:
   - `.nojekyll`: Included in the root so GitHub's Jekyll engine doesn't hide or drop Flutter engine files or WebAssembly modules.
   - `404.html`: Configured to support Flutter Single Page App (SPA) client-side routing on page refresh.
   - `apple-touch-icon.png` & `icons/`: Pre-linked for iOS home screen bookmarks.

> [!TIP]
> If your site is hosted at `https://<username>.github.io/<repository-name>/` rather than a custom domain, ensure `<base href="/<repository-name>/">` is set in `index.html` if required by your repository path structure.

---

<div align="center">
  <sub>Built with ❤️ for Zanzibar Public Transit • ZanNav Project</sub>
</div>
