The 9am Brief: for the girlypops who want easy, accessible news in style 
A daily news brief shown on a 2000s phone or iPod screen. Each morning at 9:00 AM Central a new edition is added to `editions/` and the site shows it automatically.

**What's in each edition**
- *In brief*: 3–4 one-line takeaways of the biggest things to know today.
- *United States*: 5 stories on national politics: the White House, Congress, the courts, elections and federal policy.
- *States & Local*: 5 stories on governors, state legislatures, mayors, key races, ballot measures and rising political figures, plus St. Louis and Missouri news when something big happens.
- *World*: 7–8 stories:
  - *Top 5* ranked by scale of impact, shifts in power, ripple effects, what's new in the last 24 hours, and how widely it's covered.
  - *2–3 policy and conflict picks* on diplomacy, sanctions, development, aid, migration, climate and long-running conflicts, focusing on regions the top 5 missed.
- *Economy & Markets*: 5 stories on the Fed, inflation, jobs, trade and markets, in the US and worldwide.

Every story includes:
- Headline and summary
- Why it matters
- Who's involved 
- links to the exact articles the summary was written from.

**Devices**
Tap *customize* in the top right to switch between four devices. Your choice is saved for next time.
- Silver phone
- Pink keyboard phone
- Blue iPod mini
- Silver iPod classic

Each one works through its real buttons.

| Action | Phones | iPods |
|---|---|---|
| Next / previous story | D-pad left and right | ⏮ ⏭ |
| Read aloud (play / pause) | Center button (heart) | Center button |
| Jump to a section | Left soft key (Option / Menu) | MENU |
| Past editions | Right soft key (Standby / Editions) | ▶ II |
| Open the story's first source | Green call key | — |
| Back to the cover | Red end key | MENU → Cover |

You can also:
- tap the pixel cursor arrows under the device
- swipe left or right on the screen
- use the ← → keys on a keyboard

Tap **ⓘ** for a quick guide to the controls of whichever device you're using.

*Read-aloud*

Press the center button to hear the brief like a morning phone call.
- *Call-style opening* – two rings, then a greeting with the date and today's top stories.
- *Screen follows along* – it flips to each story as it's read, with short section intros.
- *Call timer* – the status bar shows "On call 0:42" while it plays.
- *Pause and skip** – press the center button again to pause. Use the arrows to skip, and the audio jumps with you.
- *Voice** – choose Female or Male in the ⓘ panel. It plays at 1.2x speed.
- *Spacebar** – plays and pauses on a computer.

The audio uses your device's built-in voice. For a more natural sound on iPhone, download a Premium voice (such as Ava or Zoe) under Settings → Accessibility → Spoken Content → Voices.

**Archive**

Every edition is saved. Open *Past editions* to go back to any earlier day.

**How it's made**

1. Each morning, a scheduled task in Claude researches the past 24 hours of news.
2. It reads articles from wire services, major newspapers and broadcasters, regional outlets, think tanks and development sources. These include AP, Reuters, BBC, NPR, The Guardian, Al Jazeera, Politico, Nikkei Asia, The Jakarta Post, Crisis Group, CFR, Brookings, Devex, ReliefWeb and state and local outlets like Stateline and St. Louis Public Radio.
3. It picks and ranks the stories, writes neutral summaries, and writes a separate spoken script for the read-aloud.
4. It saves the edition as a JSON file in this repo, and GitHub Pages updates the site.

Summaries are written by AI and can contain mistakes. Always check the linked sources for anything important.

## Files

- `index.html` – the whole site: design, devices, controls and read-aloud
- `editions/index.json` – list of edition dates, newest first
- `editions/YYYY-MM-DD.json` – one file per day's edition
- `phone.png`, `pink.png`, `mini.png`, `classic.png` – device images
- `cursor-left.png`, `cursor-right.png` – arrow buttons
