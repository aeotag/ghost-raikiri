# Setup Instructions

## To publish this to GitHub:

1. Go to https://github.com/new
2. Create a new repository named "ghost-raikiri"
3. Make it **PUBLIC** (important for raw file access)
4. Don't initialize with README (we already have one)

## Then run these commands:

```bash
cd c:\Users\yannic\Desktop\Ghost-Bot\ghost-raikiri
git remote add origin https://github.com/YOUR-USERNAME/ghost-raikiri.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## After pushing, your CSS URL will be:

```
https://raw.githubusercontent.com/YOUR-USERNAME/ghost-raikiri/main/raikiri-ii.css
```

## Use in Gamepad Viewer:

Go to this URL (replace YOUR-USERNAME):
```
https://gamepadviewer.com/?p=1&css=https://raw.githubusercontent.com/YOUR-USERNAME/ghost-raikiri/main/raikiri-ii.css
```

Or manually:
1. Visit https://gamepadviewer.com/
2. Click the settings gear icon
3. Paste the raw GitHub URL into "Custom CSS"
4. Click Apply
