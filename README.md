# 📱 Daily Wallpaper (Bing)

![iOS](https://img.shields.io/badge/iOS-Shortcuts-blue)
![Automation](https://img.shields.io/badge/Automation-Enabled-success)
![Maintenance](https://img.shields.io/badge/Maintenance-Automatic-orange)
![License](https://img.shields.io/badge/License-Free-lightgrey)

Automatically set your iPhone wallpaper using **Bing’s daily images** — fully automated, clean, and maintenance-free.

---

## ✨ Features

- 🌄 Fetches **Bing Daily Wallpaper**
- 🔄 Automatically sets **Lock Screen + Home Screen**
- 🗂 Stores wallpapers in a dedicated album
- 🕒 Keeps a **7-day history**
- 🧹 Auto-deletes old wallpapers to prevent clutter
- ⚡ Runs via **iOS Automation (no prompts required)**

---

## 🚀 Install

👉 **Download Shortcut**  
https://www.iCloud.com/shortcuts/18ee1b299795445e9be8b0f80543dc9b

---

## ⚙️ Setup Guide

### 1️⃣ Create Album

Open the **Photos app** and create an album named exactly:

```
Daily wallpaper
```

---

### 2️⃣ Update Shortcut Album Reference

Inside the shortcut:
- Locate **Find Photos**
- Locate **Save to Photo Album**
- Set both to:

```
Daily wallpaper
```

---

### 3️⃣ Allow Automatic Deletion

This shortcut removes wallpapers older than 7 days.

Go to:

```
Settings → Shortcuts → Advanced
```

Enable:

```
Allow Deleting Without Confirmation
```

When prompted during first run:
```
Always Allow
```

---

### 4️⃣ Create Automation (Fully Automatic)

To make this fully hands-free:

1. Open **Shortcuts → Automation**
2. Tap **+ → Create Personal Automation**
3. Choose **Time of Day**
4. Pick a time (e.g., 8:00 AM)

Add action:
```
Run Shortcut → Daily Wallpaper (Bing)
```

⚠️ **Critical Step**
Turn OFF:
```
Ask Before Running
```

This ensures the shortcut runs **automatically without prompts**.

---

### 🔁 Recommended Automation Setup

To improve reliability:

- ⏰ 8:00 AM (primary)
- ⏰ 12:00 PM (fallback)

---

## 🧠 How It Works

1. Calls Bing API:
   ```
   https://bing.com/HPImageArchive.aspx
   ```
2. Extracts latest wallpaper URL
3. Downloads the image
4. Saves it to **Daily wallpaper**
5. Sets it as wallpaper
6. Keeps images for **7 days**
7. Deletes anything older automatically

---

## 🗂 Storage Logic

| Action          | Behavior     |
|-----------------|------------|
| Save wallpaper  | Daily       |
| Retention       | 7 days      |
| Cleanup         | Automatic   |
| Manual reuse    | Supported   |

---

## 📸 Why Keep 7 Days?

- Lets you reuse previous wallpapers  
- Provides fallback if a new image isn’t appealing  
- Prevents unnecessary storage buildup  

---

## ⚠️ Notes

- Requires iOS Shortcuts permissions
- First run may ask for:
  - Photo access
  - Wallpaper access
  - Deletion permission
- Works best with automation enabled

---

## 🛠 Troubleshooting

**Wallpaper not updating?**
- Check internet connection
- Run shortcut manually once
- Verify automation is enabled

**Images not deleting?**
- Confirm:
  ```
  Allow Deleting Without Confirmation = ON
  ```

**Album not found?**
- Ensure exact name:
  ```
  Daily wallpaper
  ```

---

## 💡 Pro Tip

Open the **Photos album** anytime to manually set any of the last 7 wallpapers if you prefer an older one.

---

## 📎 Shortcut Link

https://www.iCloud.com/shortcuts/18ee1b299795445e9be8b0f80543dc9b
