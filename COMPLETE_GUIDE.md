# 🎮 ROG Raikiri II Gamepad Viewer Skin - Complete Setup Guide

## ✅ Files Created

Your ROG Raikiri II gamepad viewer skin is ready! Here's what was created:

1. **raikiri-ii.css** - The main CSS skin file
2. **README.md** - Documentation
3. **preview.html** - Local preview (open in browser)
4. **SETUP_INSTRUCTIONS.md** - Quick setup guide

## 📤 Step 1: Push to GitHub

1. Go to: **https://github.com/new**
2. Create a new repository:
   - Repository name: `ghost-raikiri`
   - Make it **PUBLIC** ⚠️ (Required for raw file access)
   - Don't initialize with README
3. Click "Create repository"

## 💻 Step 2: Push Your Files

Open PowerShell and run:

```powershell
cd c:\Users\yannic\Desktop\Ghost-Bot\ghost-raikiri
git remote add origin https://github.com/YOUR-USERNAME/ghost-raikiri.git
git branch -M main
git push -u origin main
```

**Replace `YOUR-USERNAME` with your actual GitHub username!**

## 🔗 Step 3: Get Your CSS Link

After pushing, your direct CSS link will be:

```
https://raw.githubusercontent.com/YOUR-USERNAME/ghost-raikiri/main/raikiri-ii.css
```

## 🎯 Step 4: Use in Gamepad Viewer

### Method 1: Direct URL
Go to this URL (replace YOUR-USERNAME):
```
https://gamepadviewer.com/?p=1&css=https://raw.githubusercontent.com/YOUR-USERNAME/ghost-raikiri/main/raikiri-ii.css
```

### Method 2: Manual Setup
1. Go to https://gamepadviewer.com/
2. Connect your ROG Raikiri II controller
3. Click the ⚙️ settings/gear icon
4. Paste your CSS URL into the "Custom CSS" field
5. Click "Apply"

## 🎨 Skin Features

✨ **Design Elements:**
- Premium black finish with textured grips
- Signature ROG pink/magenta accents (#ff0066)
- RGB player indicator lighting
- All buttons glow pink when pressed
- Authentic Xbox button colors:
  - A = Green
  - B = Red
  - X = Blue
  - Y = Yellow

✨ **Supported Inputs:**
- All face buttons (A, B, X, Y)
- D-Pad (Up, Down, Left, Right)
- L1/R1 bumpers
- L2/R2 triggers
- Left and Right analog sticks (L3/R3)
- View and Menu buttons
- Xbox logo button
- ROG button indicator
- 4-player RGB lighting

## 🔍 Preview Locally

Open `preview.html` in your browser to see a demo of the skin with interactive buttons.

## 🛠️ Customization

Want to change colors? Edit `raikiri-ii.css`:

- **ROG Pink:** `#ff0066` (main accent)
- **Background:** `#1a1a1a` (controller body)
- **Button A (Green):** `#4ade80`
- **Button B (Red):** `#ff4444`
- **Button X (Blue):** `#60a5fa`
- **Button Y (Yellow):** `#fbbf24`

After editing, commit and push:
```powershell
git add raikiri-ii.css
git commit -m "Update colors"
git push
```

## 📱 For OBS/Streaming

1. Add a "Browser Source" in OBS
2. Use your gamepad viewer URL with the CSS parameter
3. Set dimensions to 1920x1080 or your preferred size
4. Make background transparent if needed

## ❓ Troubleshooting

**CSS not loading?**
- Make sure your GitHub repository is PUBLIC
- Wait a few minutes after pushing for GitHub to update
- Clear your browser cache
- Check the URL has `raw.githubusercontent.com` not `github.com`

**Controller not showing?**
- Connect your controller before loading the page
- Try refreshing the page
- Check browser console for errors (F12)

## 📝 Example URLs

Replace `YOUR-USERNAME` with your GitHub username:

**Basic:**
```
https://gamepadviewer.com/?p=1&css=https://raw.githubusercontent.com/YOUR-USERNAME/ghost-raikiri/main/raikiri-ii.css
```

**Multiple controllers:**
```
https://gamepadviewer.com/?p=1&p=2&css=https://raw.githubusercontent.com/YOUR-USERNAME/ghost-raikiri/main/raikiri-ii.css
```

## 🎉 You're All Set!

Your ROG Raikiri II skin is ready to use. Just follow the steps above to publish it to GitHub and start using it in Gamepad Viewer!

---

**Created:** January 17, 2026
**Controller:** ASUS ROG Raikiri II Xbox Wireless Controller
**Compatible with:** https://gamepadviewer.com/
