# 🔍 ContactLookup (NexLookup)

A modern, lightweight contact lookup tool designed to instantly find the correct contact — even when replacements exist.

Built with a focus on **speed, usability, and real-world workflow efficiency**, this tool eliminates manual searching and reduces errors during contact selection.

---

## ✨ Key Features

### 🔎 Smart Search
- Minimum 3-character input
- Real-time suggestions (fuzzy + partial match)
- Keyboard navigation (↑ ↓ Enter)

### 🔄 Replacement-Aware Logic
- Automatically detects replaced contacts
- Shows **Active Contact first**, then original (Replaced)
- Clear visual connection between both

### 📋 Clean Result Display
- Card-based modern UI
- Status indicators (Active / Replaced)
- Highlighted matches
- One-click email copy

### 📊 Data Management
- Import contacts via Excel (.xlsx, .csv)
- Export updated data anytime
- Add / Edit / Delete contacts
- Bulk import preview before confirmation

### ⚡ Performance
- Handles 1000+ contacts smoothly
- Instant search results
- No backend required

### 💾 Persistence
- Uses browser localStorage
- Works fully on GitHub Pages (no server needed)

---

## 🧠 Why This Tool?

In daily operations, identifying the **correct active contact** is critical.  
Manual lookup often leads to:
- Wrong emails
- Missed replacements
- Time wasted switching between systems

This tool solves that by:
✔ Centralizing contact data  
✔ Handling replacement logic automatically  
✔ Providing instant, reliable results  

---

## 🛠 Tech Stack

- HTML5
- CSS3 (Modern UI / Glassmorphism)
- Vanilla JavaScript
- SheetJS (Excel import/export)

---

## 🚀 Getting Started

### Option 1: Run Locally
1. Download `index.html`
2. Open in any browser
3. Start searching

### Option 2: Deploy on GitHub Pages
1. Create a new repo
2. Upload `index.html`
3. Go to **Settings → Pages**
4. Select branch → `main`
5. Done ✅

---

## 📂 Data Format

| Full Name | Clean Email | Status | Replaced By | Replacement Email |
|----------|-------------|--------|-------------|-------------------|

---

## 🎯 Example

Search: `Ruth`

Result:
- ✅ Kyle Magenheimer (Active)
- ⚠️ Ruth Kelly (Replaced)

---

## 💡 Future Enhancements

- Nexsure integration
- API-based shared database
- Role-based access
- Auto-sync contact updates

---

## 🤝 Contribution

This tool is designed for internal productivity improvement.  
Enhancements and ideas are always welcome.

---

## 📌 Author

Built as a Kaizen initiative to improve operational efficiency and reduce manual effort in contact management.

---
