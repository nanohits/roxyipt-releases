# RoxyIPT Downloads
Download the latest version of Mac and Windows from the Releases section.

**Release Notes - v1.0.6**

This hotfix release addresses playback stability issues on macOS and introduces new tools for troubleshooting.

## 🛠️ Improvements & Fixes

### 🎥 Player Stability
- **macOS Playback Fix**: Resolved an issue where some Movie and Series streams would fail to open due to strict security settings in the internal player. We've optimized the configuration to better handle various provider setups.

### 🐞 Debugging Tools
- **Stream Inspector**: Added a new **(i)** info button in the player controls for Movies and Series. This opens a debug panel showing the exact Stream URL and connection details, making it easier to identify broken links or provider issues.

---

# Release Notes - v1.0.5

This update introduces the highly anticipated **Multi-View** feature and a new **Compact Mode** for better channel browsing.

## 🌟 New Features

### 📺 Multi-View (Sports Mosaic)
Turn your screen into a command center with the new **Multi-View** mode (accessible from the Dashboard):
- **2x2 Grid**: Watch up to **4 live streams** at the same time.
- **Easy Setup**: Click any empty slot to add a channel using the new channel picker.
- **Smart Audio**: Only one stream plays audio at a time. Simply click a video to unmute it and mute the others.
- **Independent Controls**: Mute, unmute, or remove channels individually from the grid.

### 📝 Compact Mode (Live TV)
We've added a requested feature for users with long channel names:
- **Toggle View**: Switch between "Standard" and "Compact" views using the new button in the channel list header.
- **Text Wrapping**: Compact mode wraps long channel names (e.g., sports events) to 2 lines so you can read the full title.
- **More Visibility**: See more channels at once with reduced row height.

## 🛠️ Improvements & Fixes
- **Channel Picker Fix**: Fixed a bug where selecting a category in the Multi-View picker would incorrectly show channels from the first category.
- **Windows Layout**: Fixed an issue where the "Submit" button was hidden on smaller screens when adding Xtream Codes playlists.
- **macOS Support**: Added full support for Apple Code Signing and Notarization for a smoother installation experience.

---

# Release Notes - v1.0.4

RoxyIPTV v1.0.4 brings essential family safety features and a significant upgrade to the video player experience.

## 🌟 New Features

### 🛡️ Parental Control
Protect your family with robust new content restrictions (Settings > Parental Control):
- **PIN Protection**: Secure sensitive content with a 4-digit PIN.
- **Smart Auto-Lock**: One-click scanner to automatically find and lock adult categories.
- **Category Locking**: Manually select specific categories to hide from view.
- **Global Toggle**: Quickly lock or unlock the entire app using the new Lock icon in the header. When locked, restricted content is completely hidden from all lists.

### 🎥 Enhanced Video Player
We've supercharged the playback experience:
- **Immersive Mode**: Double-click the video to enter a distraction-free full-screen theater mode. Double-click again to exit.
- **Aspect Ratio Control**: Quick toggle button to switch between **Fit** (default) and **Zoom** (fill screen). A "Stretch" option is also available in the player settings.
- **Stats for Nerds**: Tech-savvy users can now toggle an overlay showing real-time resolution, bandwidth, buffer health, and dropped frames.
- **Quality Selection**: Manually select your preferred video quality (e.g., 1080p, 720p) or leave it on Auto for HLS streams.

### 🕒 Recently Watched
- **Quick History**: A new **Recently Watched** category has been added to the Live TV sidebar (right under Favorites), giving you instant access to your last 50 viewed channels.

## 🛠️ Improvements & Fixes
- **Picture-in-Picture**: Fixed issues where the PiP button could get stuck or fail to work after changing channels.
- **Performance**: Optimized player state management for smoother channel switching.

---

# Release Notes - v1.0.3

Welcome to RoxyIPTV v1.0.3! This release introduces powerful tools to manage your playlist content, performance optimizations, and smart navigation features.

## 🌟 What's New

### 🧹 Content Manager & Smart Cleanup
Keep your channel list clean and organized with our new **Content Manager** (found in Settings):
- **Advanced Category Management**: Browse all your channel groups with new filters (All, Visible, Hidden). Easily hide unwanted sections like "24/7" or foreign language groups to declutter your view.
- **Smart Duplicate Finder**: Automatically scan your playlist for duplicate channels (e.g., "CNN HD" vs "CNN FHD").
- **Bulk Cleanup**: Remove clutter by hiding hundreds of duplicate channels instantly, keeping only the primary version.

### ⚡ Performance & Navigation
- **Favorites First**: When opening Live TV, the app now intelligently defaults to your **Favorites** list if you have any, getting you to your content faster.
- **Instant Navigation**: Switching between Home, Settings, and Live TV is now instant. We've added persistent session caching so you don't have to wait for channels to reload when navigating back.
- **Improved Caching**: Category and channel lists are cached more aggressively during your session for a smoother experience.

### 🎨 Visual Improvements
- **Better Logo Handling**: Fixed an issue where channel logos would look pixelated or stretched while loading the video player.
- **Refined UI**: Polished the Content Manager interface with search and filter options.

## 🚀 Recent Highlights
- **Multiple EPG Support**: Add multiple TV Guide sources to a single playlist.
- **Global Search**: Press `Cmd+K` / `Ctrl+K` to search everything.
- **Auto-Refresh**: Flexible options (1h - 72h) to keep your content up to date.

---
*Thank you for your feedback!*
