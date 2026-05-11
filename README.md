# 🎵 Chorale Saint Padre Pio — Website Guide

This is your choir's website, built on the Agency Jekyll Theme.
Below is a simple guide to help you manage the site — no coding required!

---

## 📁 Folder Structure (What Each File Does)

```
chorale-saint-padre-pio/
│
├── _config.yml          ← Site title, email, logo settings
├── _data/
│   ├── sitetext.yml     ← All text on the HOME page (titles, descriptions, etc.)
│   ├── navigation.yml   ← Menu links at the top of every page
│   └── style.yml        ← Colors and fonts
│
├── assets/
│   ├── img/
│   │   ├── choir-logo.png       ← Your choir logo
│   │   ├── header.png           ← Big background image on the home page
│   │   ├── gallery/             ← Put gallery photos here
│   │   ├── team/                ← Put team/member photos here
│   │   └── timeline/            ← Photos for the history section
│   └── scores/                  ← Put PDF music scores here
│
├── index.md             ← Home page
├── about.md             ← About Us page
├── events.md            ← Events page
├── gallery.md           ← Gallery page
├── music-scores.md      ← Music Scores page
├── join.md              ← Join Us page
└── contact.md           ← Contact page
```

---

## ✏️ How to Edit Text

### To change text on the HOME page:
Open `_data/sitetext.yml` and edit the text fields.
Everything is clearly labeled (header, services, about, team, contact, etc.)

### To change text on other pages:
Open the `.md` file for that page (e.g., `about.md`, `events.md`) and edit directly.
The text uses simple Markdown formatting:
- `**bold text**` → **bold text**
- `*italic text*` → *italic text*
- `## Big Heading` → a large heading
- `- Item` → a bullet point

---

## 🎨 How to Change Colors

Open `_data/style.yml` and change the hex color codes:
- `highlight: "#F5C518"` → Golden Yellow (buttons, accents)
- `black: "#1A3A7C"` → Royal Blue (navbar, headings)

---

## 🖼️ How to Add Photos

### Header background image:
Replace `assets/img/header.png` with your own photo (keep the same filename).

### Gallery photos:
1. Put your `.jpg` or `.png` photos in `assets/img/gallery/`
2. Open `gallery.md` and add a line like:
   ![Description of photo](assets/img/gallery/yourphoto.jpg)

### Team photos:
Put photos in `assets/img/team/` and update names in `_data/sitetext.yml` under `team: people:`

---

## 🎵 How to Add Music Scores

1. Put your PDF file in `assets/scores/` (e.g., `gloria.pdf`)
2. Open `music-scores.md`
3. Add a new row to the correct table:
   | Gloria | SATB | Latin | [Download](assets/scores/gloria.pdf) |

---

## 🚀 How to Publish on GitHub Pages

1. Create a free account at https://github.com
2. Create a new repository named: chorale-saint-padre-pio
3. Upload all these files to the repository
4. Go to: Settings → Pages → Source: main branch
5. Your site goes live at: https://yourusername.github.io/chorale-saint-padre-pio

---

## ❓ Need Help?

Ask Claude at https://claude.ai — just describe what you want to change
and Claude will tell you exactly which file to edit and what to write!
