# 🏫 ElimuTrack – School Analytics System

A live, real-time school management system hosted free on GitHub Pages
with Supabase as the database backend.

---

## 🚀 SETUP GUIDE (takes about 10 minutes)

### STEP 1 — Set up Supabase (Free Database)

1. Go to **https://supabase.com** and create a free account
2. Click **"New Project"** → give it a name like `elimutrack`
3. Set a database password (save it somewhere)
4. Wait ~2 minutes for the project to be created

### STEP 2 — Run the Database SQL

1. In your Supabase project, click **"SQL Editor"** in the left menu
2. Click **"New Query"**
3. Open the **`setup_sql.txt`** file from this folder
4. Copy ALL the SQL and paste it into the editor
5. Click **"Run"** — you should see "Success"

### STEP 3 — Get Your Supabase Keys

1. In Supabase, click **"Project Settings"** (gear icon)
2. Click **"API"**
3. Copy these two values:
   - **Project URL** (looks like: `https://abcdefgh.supabase.co`)
   - **anon/public key** (long text starting with `eyJ...`)

### STEP 4 — Host on GitHub Pages (Free)

1. Go to **https://github.com** → Sign in or create free account
2. Click the **"+"** button → **"New repository"**
3. Name it: `elimutrack` (or any name)
4. Set it to **Public**
5. Click **"Create repository"**
6. Click **"uploading an existing file"**
7. Drag and drop BOTH files:
   - `index.html`
   - `setup_sql.txt`
8. Click **"Commit changes"**

### STEP 5 — Enable GitHub Pages

1. In your repository, click **"Settings"**
2. Scroll to **"Pages"** in the left menu
3. Under "Source", select **"Deploy from a branch"**
4. Branch: **main** → Folder: **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes, then your site is live at:
   **`https://YOUR-USERNAME.github.io/elimutrack`**

### STEP 6 — First Login Setup

1. Open your GitHub Pages URL on any phone or computer
2. Paste your **Supabase Project URL** and **anon key**
3. Click **"Connect"**
4. Enter your school name and admin password
5. Click **"🚀 Launch"**
6. You're in! 🎉

---

## 📱 Sharing With Teachers

Just send them your GitHub Pages link:
**`https://YOUR-USERNAME.github.io/elimutrack`**

They log in with their username + `teacher123` (you can change this in the Teachers section).

Default teacher accounts created automatically:
- `tr.amran` / `teacher123`
- `tr.ruto` / `teacher123`
- `tr.isaac` / `teacher123`

---

## ✅ Features

- 📊 Live dashboard with real-time stats
- 🎓 Student management + Excel bulk import
- 👩‍🏫 Teacher accounts (each sees only their subjects)
- 📚 Subject management with teacher assignment
- 📝 Score entry → saves to cloud instantly
- 🏆 Auto-rankings by class and term
- 📋 Zeraki-style report cards with photo upload
- 🖨️ Print-ready report cards
- 🔄 Real-time sync — any change by any teacher is instantly visible to everyone

---

## 🆘 Troubleshooting

**"Cannot connect to Supabase"**
→ Make sure you ran the SQL from setup_sql.txt first
→ Double-check you copied the correct URL and anon key

**"Row level security" error**
→ Re-run the RLS section at the bottom of setup_sql.txt

**Teachers can't log in**
→ Admin must add them in the Teachers section first

---

Made with ❤️ for Kenyan schools
