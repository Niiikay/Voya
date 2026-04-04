# VOYA — AI Travel Intelligence

> An AI-powered travel planning app that gives you personalized destination intel, packing lists, scored spot recommendations, and photography tips — built module by module.

**Live demo:** *(add your Vercel URL here after deployment)*  
**Built with:** HTML, CSS, JavaScript, Anthropic Claude API

---

## What it does (Module 1)

- Enter your destination and travel dates
- Select your interests (photography, food, nightlife, culture, etc.)
- AI analyzes your trip and returns:
  - Weather vibe + historical temperature for your dates
  - Personalized packing list
  - Top spots scored 1–10 by local recommendation frequency
  - Photography and content creator tips per spot
  - Local events and seasonal experiences

## Roadmap

| Module | Feature | Status |
|--------|---------|--------|
| 1 | Destination intel, weather, packing, scored spots | ✅ Live |
| 2 | Itinerary builder + route optimization | 🔜 Next |
| 3 | Hotel/Airbnb search around itinerary midpoint | 🔜 Planned |
| 4 | Outfit & photo planning per spot | 🔜 Planned |
| 5 | Local events & experiences on travel dates | 🔜 Planned |
| 6 | Flight search & booking | 🔜 Planned |

---

## How to run locally

1. Download or clone this repo
2. Open `index.html` in any web browser — no setup needed
3. On first load, enter your [Anthropic API key](https://console.anthropic.com) (free to get)
4. Start planning

---

## How to deploy (Vercel — free, takes 5 minutes)

### Step 1 — Put the code on GitHub

1. Go to [github.com](https://github.com) and create a free account
2. Click the **+** icon → **New repository**
3. Name it `voya`, set it to **Public**, click **Create repository**
4. On the next page, click **uploading an existing file**
5. Drag and drop the `index.html` and `README.md` files
6. Click **Commit changes**

### Step 2 — Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign up with your GitHub account
2. Click **Add New Project**
3. Find your `voya` repo and click **Import**
4. Leave all settings as default and click **Deploy**
5. In ~60 seconds you'll get a live URL like `voya-yourname.vercel.app`

That's it — share that link on your resume and in interviews!

---

## API key note

This app asks users to enter their own Anthropic API key on first use. The key is stored only in the browser session (not on any server) and is never logged or shared. This is the standard approach for portfolio/demo apps.

For a production version, the API key would live in a secure backend environment variable.

---

## Tech stack

- **Frontend:** Vanilla HTML, CSS, JavaScript (no frameworks, no build step)
- **AI:** Anthropic Claude API (`claude-sonnet-4-20250514`)
- **Fonts:** Cormorant Garamond (display) + DM Sans (body) via Google Fonts
- **Images:** Unsplash (travel photos per spot)
- **Deployment:** Vercel (static hosting)
