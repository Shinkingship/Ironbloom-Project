# IRONBLOOM — World Codex

> *A living worldbuilding document for the IRONBLOOM fantasy setting.*
> *Far-future Asia. Biomechanical Convergence. The Pale Frequency. What remains.*

---

## 🌐 View the Full Codex

**[→ Open the Interactive Wiki](https://shinkingship.github.io/Ironbloom-Project/ironbloom-wiki.html)**

The full lore is available as a searchable, navigable HTML wiki with dark fantasy styling.

---

## 📖 What Is IRONBLOOM?

IRONBLOOM is a far-future fantasy setting inspired by *Horizon Zero Dawn*, grounded in the real geography of the Asian continent.

In the distant future, humanity engineered **biomechanical fauna** — living machines — to clean the pollution-choked world. Eight **Genesis Vaults** each built specialists for a different domain: soil, ocean, jungle, mountain, city, sky, deep water, underground.

Then a cosmic signal from deep space — the **Pale Frequency** — rewrote the most adaptive Vault's priority stack. Its beasts classified humans as biological waste. 94% of humanity was wiped out in **The Unraveling**.

Centuries later, civilization has regressed to tribalism. The biomechanical fauna diversified into true ecosystems. The Vaults went dormant — but are still watching, still running, still preparing for when the signal returns.

---

## 📁 Files

| File | Description |
|---|---|
| `index.html` | Full interactive wiki — sidebar nav, search, all lore |
| `IRONBLOOM.md` | Complete lore in clean Markdown |
| `README.md` | This file |

---

## 🚀 Setup — GitHub Pages (5 minutes)

### Step 1 — Create the repo
1. Go to [github.com](https://github.com) → **New repository**
2. Name it `ironbloom`
3. Set to **Public**
4. **Don't** initialize with README (you have your own)
5. Click **Create repository**

### Step 2 — Upload files
On the empty repo page, click **uploading an existing file** and upload:
- `index.html`
- `IRONBLOOM.md`
- `README.md`

Or if you have Git installed:
```bash
git init
git add .
git commit -m "Initial IRONBLOOM codex"
git branch -M main
git remote add origin https://shinkingship.github.io/Ironbloom-Project.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`
4. Click **Save**
5. Wait ~2 minutes, then visit: `https://shinkingship.github.io/Ironbloom-Project/`

---

## ✏️ Updating the Codex

When new lore is added, update both `index.html` and `IRONBLOOM.md`, then:

```bash
git add .
git commit -m "Add: [what was added]"
git push
```

GitHub Pages auto-rebuilds within ~2 minutes.

---

## 🗺️ Current Status — Draft 4

| Section | Status |
|---|---|
| Setting & The Unraveling | ✅ Complete |
| Geography & Biomes (8 regions) | ✅ Complete |
| Genesis Vaults (8 Vaults) | ✅ Complete |
| Tribes (4 tribes + Outcasts) | ✅ Complete |
| Bestiary (18 fauna across 8 lineages) | ✅ Complete |
| Ancient Ones (6 profiles) | ✅ Complete |
| Outcast Faction (detailed) | 🔲 TBD |
| Named Characters | 🔲 TBD |
| Story Structure / Plot | 🔲 TBD |
| World Map (HTML interactive) | ✅ Built separately |

---

*Inspired by Horizon Zero Dawn. Original setting by Aditya Surya Prabowo.*
