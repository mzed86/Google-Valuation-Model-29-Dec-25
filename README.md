# Google vs the Zero-Click Internet  
### A Python valuation model for Alphabet under AI-driven search decay

This repository contains the Python notebook that backs a bearish valuation thesis on **Alphabet (Google)**.

The core question is:

> What happens to Google’s business model when people stop clicking?

AI Overviews, answer engines, and agentic search are collapsing paid click-through rates in Google Search — the engine that still drives ~55% of group revenue. This notebook translates that narrative into numbers.

📖 **Read the full research article on Substack**  
👉 https://open.substack.com/pub/michaelzedzed/p/modelling-the-google-death-spiral?r=1rfoub&utm_campaign=github&utm_medium=web

---

## Executive summary (the short version)

- **Paid CTR drops ~68%** on searches with AI Overviews (“meteor strike” scenario)
- **Search ad inventory deflates** while CPCs temporarily spike due to fixed budgets
- **Amazon exiting Google Shopping (July 2025)** is the canary in the coal mine
- **Cloud (GCP) margins are improving**, but mathematically cannot offset Search decay
- Loss of monopoly power alone destroys **~$29/share** of intrinsic value

**My fair value (Bear case): ~$230/share**  
Base case sits near current price. Upside requires perfection.

---

## What’s in this repo

- A single, fully executable **Jupyter notebook**
- A **segment-level valuation model** for Alphabet:
  - Search (CTR, CPC, CVR dynamics under AI Overviews)
  - AdSense structural decay
  - GCP growth + margin expansion
  - YouTube & subscriptions as stabilizers
- **Bear / Base / Bull scenarios**
- **Monte Carlo simulation** to visualize uncertainty
- A valuation bridge isolating the impact of the “Zero-Click” shift

The numbers either survive contact with reality or they don’t.

---

## Key modeling assumptions

- **Search volume** declines as users shift to answer engines (ChatGPT, Perplexity, etc.)
- **CTR** drops sharply on AI Overview queries (−68% where applicable)
- **CPC** initially inflates, then decays as advertisers adjust (the “Amazon vacuum”)
- **Conversion rates** improve (4–5×), but not enough to offset inventory loss
- **WACC inflated by +1%** in the Bear case to reflect monopoly decay and regulation
- **GCP margins** expand toward AWS levels over time due to TPU-driven inference economics

You don’t have to agree with these assumptions — the notebook is built so you can change them.

---

## How to run the notebook

### Option 1: Run locally
1. Clone the repo  
   `git clone
2. install dependencies  
   ```bash
   cd google-zero-click
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
jupyter notebook

### Option 2: Zero-setup (recommended)

👉 Run in Colab / Binder


### Why this exists

This is not an academic exercise and it’s not investment advice.

It’s an attempt to pressure-test one uncomfortable idea:

Google’s monopoly was built on clicks.
AI is killing clicks.

If that’s true, Alphabet doesn’t just need better products — it needs a new economic model.

The notebook exists so readers can:
Inspect the mechanics, challenge the assumptions, stress-test the valuation themselves

### Counter-arguments (addressed in the model)

1. AI Overviews increase high-intent clicks for cited brands
2. Agents, not humans, may become the real customers
3. Retail media networks may backfill auction pressure
4. GCP could become the dominant profit engine by 2030


### Important caveat

The −68% CTR figure comes from third-party studies (e.g. Seer Interactive) and applies specifically to searches with AI Overviews present.
Only Google has the full dataset. This model reflects directional risk, not omniscience.

### More like this

I write about:

Market structure

Incentives

Second-order effects in tech and finance

Where the narratives break when the math shows up
