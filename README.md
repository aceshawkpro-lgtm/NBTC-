# 📋 Timesheet Portal - PWA

## Files
```
timesheet-pwa/
├── index.html      ← Main app
├── manifest.json   ← PWA config
├── sw.js           ← Offline support
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## 🚀 Free Hosting - GitHub Pages (Recommended)

### Step 1: GitHub Account banao
- https://github.com pe jaao, free account banao

### Step 2: New Repository banao
- "New repository" click karo
- Name: `timesheet-portal`
- Public select karo
- Create repository click karo

### Step 3: Files upload karo
- "uploading an existing file" click karo
- Saari files drag & drop karo (index.html, manifest.json, sw.js)
- icons/ folder bhi upload karo
- "Commit changes" click karo

### Step 4: GitHub Pages enable karo
- Repository Settings → Pages
- Source: "Deploy from a branch"
- Branch: main → Save

### Step 5: Link milega!
```
https://[tera-username].github.io/timesheet-portal/
```

Ye link employees ko WhatsApp pe bhej do! ✅

---

## 📱 Employees App Kaise Install Karenge?

### Android (Chrome):
1. Link kholo Chrome mein
2. Niche "Add to Home screen" popup aayega → Tap karo
3. Done! App icon home screen pe aa jaayega

### iPhone (Safari):
1. Link kholo Safari mein
2. Share button (square with arrow) tap karo
3. "Add to Home Screen" select karo
4. Done!

---

## ✏️ Naye Employees Kaise Add Karein?

`index.html` file mein `EMPLOYEES` array mein naya object add karo:

```javascript
{
  empId: "220999",        // Employee ID
  dob: "01011990",        // DDMMYYYY format
  name: "EMPLOYEE NAME",
  designation: "HELPER",
  month: "JUNE 2026",
  company: "NASER M. AL-BADDAH & PARTNER",
  project: "HIGHLAND-2",
  rows: [
    {dt:1, project:"P024", wh:8, ot:2, incentive:"", ta:1, sun:false, hol:false},
    // ... baki days
  ],
  notes: "Payment notice text..."
}
```

---

## 🔒 Security
- Employee ID + Date of Birth dono match karna zaroori hai
- Koi bhi doosre ka timesheet nahi dekh sakta
- Data app mein hi stored hai (no server needed)

---

## Demo Credentials
| Name | ID | DOB |
|------|----|-----|
| SRIMANTA KUMAR SAHU | 220140 | 15/06/1985 |
| RAJESH KUMAR SHARMA | 220201 | 22/03/1990 |
