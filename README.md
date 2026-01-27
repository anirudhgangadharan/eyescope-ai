# EyeScopeAI

Offline smartphone-based visual acuity screening using Tumbling E optotypes.

**ICMR STS 2025** | Ref: STS2025-20682

## Live App

👉 **https://anirudhgangadharan.github.io/eyescope-ai/**

## Setup (2 minutes)

1. Fork/clone this repo
2. Go to repo **Settings** → **Pages**
3. Source: **Deploy from branch** → **main** → **/ (root)** → **Save**
4. Wait 1 min, your app is live at `https://anirudhgangadharan.github.io/eyescope-ai/`

## Install on Phone

1. Open the live URL in Chrome (Android)
2. Tap **⋮** → **"Add to Home screen"**
3. Done - works offline

## Usage

- Enter Subject ID → Start Test
- Swipe direction the **E** points (↑↓←→)
- Tests both eyes sequentially
- Records LogMAR / Snellen / Decimal VA

## Test Protocol

| Lines | LogMAR | Snellen |
|-------|--------|---------|
| 1-11  | 1.0→0.0 | 6/60→6/6 |

- 3 trials per line
- 2/3 correct to advance
- 2 consecutive wrong = stop

## License

MIT
