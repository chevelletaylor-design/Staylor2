# S. Taylor Bookkeeping — Website

A refined, mobile-first landing page with a built-in admin panel for easy content editing.

## 🌸 Quick Start — Editing the Site

You don't need to edit code to update your website. Everything is editable through a visual admin panel.

### To edit any text, photo, or link:

1. Go to **`[YOUR SITE URL]/admin/`**
2. Log in with your email + password
3. Click any section (Hero, About, Services, etc.) to expand it
4. Make your edits in the form fields
5. Click **"Publish"**
6. Your live site updates within 60 seconds

## 📁 File Structure (for reference only)

```
S-Taylor-Bookkeeping/
├── index.html           ← the site template
├── config.json          ← the content (admin panel edits this)
├── README.md            ← this file
├── ASSET-GUIDE.md       ← photo naming & sizing guide
└── admin/
    ├── index.html       ← admin panel login
    └── config.yml       ← admin panel field definitions
└── assets/
    └── images/          ← photos uploaded via admin panel
```

## 📸 Uploading Photos

Photos upload directly through the admin panel (📷 icons throughout the editor). See `ASSET-GUIDE.md` for exact photo naming and sizing.

## 📧 Contact Form Setup

The form is currently in **demo mode** (shows a confirmation but doesn't send). To activate real submissions:

1. Sign up at [formspree.io](https://formspree.io) with sophia@staylorbookkeeping.com
2. Create a new form → copy the endpoint URL
3. In the admin panel → 📬 Contact Section:
   - Paste URL in "Form Endpoint"
   - Change "Form Provider" from `demo` to `formspree`
4. Click Publish

## 🌐 Deployment

Site is deployed via Netlify. Every publish from the admin panel auto-rebuilds the live site in ~60 seconds.

- **Live site:** `[YOUR NETLIFY URL]`
- **Admin panel:** `[YOUR NETLIFY URL]/admin/`
- **GitHub repo:** `[YOUR REPO URL]`

## 🎨 Design Credit

Designed by [Chevelle](https://www.bychevelle.com) — brands, built the right way.
