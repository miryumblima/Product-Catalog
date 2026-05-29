# Product Catalog

A private product management app with cloud storage via Supabase.

## Setup

### 1. Supabase
Run the SQL in `supabase_setup.sql` in your Supabase SQL Editor.

### 2. Deploy to Vercel
1. Push this folder to a GitHub repository
2. Go to vercel.com → New Project → Import your GitHub repo
3. Click Deploy — no configuration needed
4. Your app is live at the Vercel URL

### 3. Import existing data
If you have a previous JSON export, open the app and use ↑ Import to load it.

## Updating features
All features are in `index.html`. When a new version is ready:
1. Download the new `index.html`
2. Replace the file in your GitHub repo (drag and drop on GitHub.com)
3. Vercel redeploys automatically in ~60 seconds
4. Refresh the app — your data is untouched

## Data storage
- **Products & lists** — Supabase cloud database (safe, persistent)
- **Files & images** — Browser localStorage (backed up in JSON export)
