# DreamMax B9S2X Remote Control PWA

A free, web-based remote control app for your DreamMax B9S2X Beout Receiver. Works on any iPhone without App Store installation!

## 🚀 Quick Setup (5 Minutes)

### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up"
3. Follow the registration steps (it's free!)
4. Verify your email address

### Step 2: Create Repository
1. After logging in, click the **"+"** icon (top right) → **"New repository"**
2. Repository name: `dreammax-remote`
3. Make sure it's set to **Public**
4. Click **"Create repository"**

### Step 3: Upload Files
1. On your new repository page, click **"uploading an existing file"**
2. Drag all files from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - The entire `icons/` folder
3. Click **"Commit changes"** at the bottom

### Step 4: Enable GitHub Pages
1. Click **"Settings"** tab (top of repository)
2. In the left sidebar, click **"Pages"**
3. Under "Source", select **"Deploy from a branch"**
4. Under "Branch", select **"main"** and folder **"/ (root)"**
5. Click **"Save"**
6. Wait 1-2 minutes for deployment
7. You'll see a link like: `https://yourusername.github.io/dreammax-remote/`

### Step 5: Install on iPhone
1. Send the GitHub Pages link to your father's iPhone (via iMessage, WhatsApp, etc.)
2. On iPhone, open the link in **Safari**
3. Tap the **Share button** (square with arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Name it "DreamMax Remote" (or whatever you prefer)
6. Tap **"Add"** in the top-right corner
7. ✅ Done! The app icon now appears on the home screen

### Step 6: Configure Receiver IP
1. Open the new "DreamMax Remote" app from home screen
2. Tap the **⚙️ Settings** icon (top right)
3. Enter your receiver's IP address (e.g., `192.168.1.100`)
4. Tap **"Test"** to verify connection
5. Tap **"Save"**
6. ✅ Ready to use!

---

## 📡 Finding Your Receiver's IP Address

### Method 1: Router Admin Panel (Easiest)
1. Open a browser on any device on your network
2. Go to your router's IP (usually `192.168.1.1` or `192.168.0.1`)
3. Log in (check router label for default credentials)
4. Look for "Connected Devices", "DHCP Clients", or "Device List"
5. Find "DreamMax", "B9S2X", or similar
6. Note the IP address

### Method 2: Network Scanner App
1. Install **"Fing"** app on any phone (free on App Store/Play Store)
2. Open the app and scan your network
3. Look for "DreamMax" or unknown device
4. Note the IP address

---

## ⚙️ OpenWebif Setup

### Check if OpenWebif is Installed
Most BeoutQ firmware comes with OpenWebif pre-installed. To verify:

1. Open a browser on any device
2. Go to: `http://{receiver-ip}` (replace with actual IP)
3. If you see a web interface, OpenWebif is working!

---

## 🎮 Button Reference

All 42 buttons from the original remote are included:

| Button | Function |
|--------|----------|
| ⚡ Power | Power on/off |
| ↑↓←→ OK | Navigation |
| 0-9 | Channel numbers |
| 🔊🔉 | Volume control |
| ⬆️⬇️ | Channel change |
| 🔴🟢🟡🔵 | Colored buttons |
| ⏮⏯⏭ | Media playback |
| 📋 Menu | Settings menu |
| ℹ Info | Show info |
| 🏠 Home | Return to home |
| ❌ Back | Go back |

---

## 📱 Features

- ✅ **42 Full Remote Buttons** - Every button from the original remote
- ✅ **No App Store Needed** - Works as a PWA (Progressive Web App)
- ✅ **Offline Support** - Works even without internet (once loaded)
- ✅ **Native App Feel** - Full-screen, no browser UI
- ✅ **Vibration Feedback** - Haptic response on button press
- ✅ **Quick Channel Entry** - Type channel number directly
- ✅ **Connection Status** - Visual indicator if receiver is reachable
- ✅ **Dark Mode** - Perfect for TV viewing
- ✅ **100% Free** - No subscriptions, no ads

---

## 📝 Technical Details

- **Technology**: HTML5, CSS3, JavaScript, PWA
- **Hosting**: GitHub Pages (free)
- **Dependencies**: FontAwesome (CDN) for icons
- **Browser Support**: Safari iOS 11+, Chrome Android 55+
- **Offline**: Service Worker caches all assets

---

## 📄 License

Free for personal use. Created for DreamMax B9S2X Beout Receiver remote control.

---

**Enjoy your new remote control! 🎉**