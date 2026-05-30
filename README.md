# **Everything Deduper v1.37 — Standard Edition**

A fast, safe, and intuitive tool for auditing and deduplicating files across any folder structure.  
Everything Deduper provides a clean three‑stage workflow — **Audit → Review → Dedupe** — with strong safety guarantees, optional automation, and full manual control.

---

## ✨ **Features at a Glance**

### 🔍 **Audit Engine**
- Recursive folder scanning  
- Raw TSV + human‑readable summaries  
- Deterministic, timestamped output  
- Handles unreadable files safely  
- “Open latest audit file” button

### 🧩 **Dedupe Engine**
- Multi‑stage hashing (size → quick → full)  
- Accurate duplicate detection  
- Safe deletion with full logs  
- Dry Run mode  
- STOP button for safe interruption  
- Fully threaded (no UI freezing)  

### 🎛️ **Manual Multi‑Keeper Mode**
- Select **one or more** files to keep  
- Ideal for RAW+JPEG, edited/original, variants  
- Logs reflect all keeper decisions  

### ⚡ **Auto‑Mode (copy first found)**
- One‑click automatic dedupe  
- Keeps the first file in each group  
- Fully logged  
- Works with Dry Run  
- Interruptible with STOP  

### 📁 **Unified Picker System**
- Consistent folder/file selection  
- Callback‑based  
- Thread‑safe  
- Clean, predictable behaviour  

### 📝 **Logging**
- Raw audit logs  
- Human‑readable summaries
- Audit Summary displayed and saved to file  
- Raw dedupe logs  
- Human‑readable dedupe summaries  
- Skipped files log  
- Deterministic naming  

### 🛡️ **Safety**
- Confirmation before destructive actions  
- Safe deletion (no partial deletes)  
- Skip unreadable files  
- No silent overwrites  
- No silent auto‑deletes  
- Cleanup/reset confirmation
- Only ever copies files 

### ⚙️ **Settings & Persistence**
- UI fields restore correctly, if present  
- Cleanup removes all generated files and summary 

---

## 📦 **Installation**

Everything Deduper is a single file so is fully portable.

1. Download the latest **EverythingDeduper.exe** from the Releases page  
2. Place it anywhere you like  
3. Run it. (All user files created in same directory.)  

No installer.  
No dependencies.  
No registry changes.

Optional download to include documentation.

---

## 🚀 **Usage**

### **1. Audit**
1. Open the **Audit** tab  
2. Select a folder  
3. Click **Start Audit**  
4. Review the summary or open the raw audit file  

### **2. Review**
- Inspect duplicate groups  
- Open logs  
- Confirm what will be deduped  

### **3. Dedupe**
1. Open the **Deduper** tab  
2. Select the audit file  
3. Select a destination folder  
4. Choose **Manual** or **Auto‑mode**  
5. Click **Start Dedupe**

Manual mode supports multi‑keeper.  
Auto‑mode keeps the first file only.

---

## 🧹 **Cleanup**

The **Cleanup** button removes all files created by Everything Deduper:

- Audit logs  
- Dedupe logs  
- Skipped files  
- Hash cache  
- Settings file  

(Note: A fresh Settings file  is created on next launch.)

---

## 🚫 **Not Included (By Design)**

To keep the tool focused and predictable:

- File‑type filtering  
- Auto‑mode multi‑keeper  
- Preset extension groups  
- Update checker  
- Favourites system  
- Safe‑mode launch flag  
- Embedded version metadata  

These may be considered for future versions based on user demand.

---

## 🧪 **Stability & Performance**

- Fully threaded operations  
- Deterministic behaviour  
- Predictable log output  
- Clean shutdown  
- No leftover state between sessions  

---

## 💛 **Donationware**

Everything Deduper is released as **Donationware**.  Suggested donation £5
You may use it freely for personal and/or professional work.  
If you find it useful, consider supporting development — it helps keep the project alive and evolving.

**Donate:** https://PayPal.Me/carlrwaring

---

## 🤝 **Contributing**

Bug reports, suggestions, and feature requests are welcome.  
Please open an issue on the GitHub repository.
