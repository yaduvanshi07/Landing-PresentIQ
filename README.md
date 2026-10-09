# Present IQ — AI-Powered Attendance System Landing Page

A modern, responsive landing page for **Present IQ** (an AI-powered classroom attendance system leveraging facial recognition and voice biometrics), built with Python Flask and vanilla CSS/JS.

---

## 🎨 Theme & Design
- **Color Palette**: Dark crimson-to-deep maroon gradient backdrop (`#1a0000` to `#5c1010`) accented with gold/amber highlights (`#e6a817`) inspired by AttendIQ.
- **Typography**: Google Fonts (*Climate Crisis* for display headings, *Outfit* for modern body text).
- **Responsive Layout**: Optimized for mobile, tablet, and desktop viewports.
- **Interactions**: Smooth scroll-reveal animations via IntersectionObserver.

---

## 📂 Project Structure

```text
Landing page/
├── app.py                  # Flask web server entry point
├── requirements.txt        # Python dependencies
├── vercel.json             # Vercel deployment configuration
├── templates/
│   └── index.html          # Main landing page template
└── static/
    ├── css/
    │   └── style.css       # Complete design system & responsive styling
    ├── js/
    │   └── script.js       # Scroll-reveal animations and interactive logic
    ├── image/              # Visual assets and demo previews
    └── fonts/              # Custom web fonts (if loaded locally)
```

---

## 🚀 Getting Started

### 1. Prerequisites
- Python 3.8+ installed on your system
- `pip` package manager

### 2. Installation
Install the project dependencies:
```bash
pip install -r requirements.txt
```

### 3. Run Locally
Start the Flask development server:
```bash
python app.py
```

Then open your browser and navigate to:
```text
http://127.0.0.1:5000/
```
*(If port 5000 is in use, check your terminal for the active port, e.g. port 5002)*

---

## ☁️ Deployment

### Deploying to Vercel
The repository includes a configured [vercel.json](file:///c:/Projects/Upgradation/Landing%20page/vercel.json) for fast deployment on Vercel:
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project root directory.

---

## 📄 License
This project is for educational and institutional demonstration purposes.
