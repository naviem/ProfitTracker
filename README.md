# Profit Tracker

A comprehensive profit tracking application designed for resellers to manage inventory, track sales, and analyze "business" performance.
(It's just an application for resellers to keep track of their sales) 

## Data Storage

### What's in the folder?
- **`settings.json`** - Your app settings (theme, categories, column visibility, etc.)
- **`data.json`** - All your product data (items, prices, notes, photos, history)
- **`images/`** folder - Product photos and thumbnails

### What happens if these files are missing?
- **Missing `settings.json`** - App will use default settings (dark theme, default categories)
- **Missing `data.json`** - App will start with empty product list
- **Missing `images/` folder** - Product photos won't display (but data is safe)

## Making the App Portable

### If you started with non-portable mode:
1. Go to **Settings** → **Data Management**
2. Click **"🔄 Make App Portable"**
3. Choose a folder where you want to store your data
4. The app will copy all your data to that folder and switch to portable mode

### What "Portable" means:
- **Portable mode**: Data stays in the same folder as the app
- **Non-portable mode**: Data is stored in your system's AppData folder

### Benefits of portable mode:
- Take your data with you (copy the whole folder)
- Easy to backup (just copy the folder)
- Works on USB drives
- No data left behind when uninstalling

### Benefits of non-portable mode:
- Data persists through app updates
- Follows system conventions
- Automatic system backups may include your data

## Backup Your Data

**Always backup your data folder before:**
- Updating the app
- Moving to a different computer
- Making major changes

Simply copy the entire Profit Tracker folder to a safe location.

## Support

If you find this software useful, consider supporting the project:
- **Contact**: nave3d@gmail.com
- **Donate**: Click "Buy me a coffee ☕" in Settings → About
