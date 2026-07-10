# Test_Beat_Game's

A browser-based, offline, no-account rhythm game with a gritty cyberpunk aesthetic. Click the notes in time, chain combos, and don't touch the bombs. It ships as a single file — **`neon-beats.html`** — so you can just double-click it to play in any modern browser.

> ### ⚠️ Made with AI
> This game (its code, visuals, and this README) was generated with the help of an AI assistant
This is just something i want to be upfront about to make sure people are aware this was more of just a project to muck around on so i wasnt too serious about me programming it entirely

---

## How to Play

Move the glowing cursor with your mouse and hit notes as their shrinking approach ring collapses onto them. You can also hover a note and press **Z** or **X**. The **next note to hit is marked with a bright, rotating targeting bracket** so it's easy to find. Overlapping notes are each hittable on their own.

**Note types:**

- **◎ Tap** — click the circle on the beat.
- **⊙ Hold** — press and hold on the pad until the ring fills.
- **×2 Double** — click it twice, quickly.
- **➤ Flick** — slash the cursor through it in the arrow's direction (no click needed).
- **↻ Spinner** — hold and spin the cursor around the core.
- **◐ Follow** — keep your cursor on the moving target.
- **☢ Bomb** — do **not** touch these; they break your combo.

**Grades:** PERFECT · GREAT · OK · MISS. Build combo to raise your score and keep the sync-bar alive. Press **Esc** any time to pause, change settings (volume, approach speed, note size), restart, or end the track early.

New to the game? Use the **Interactive Tutorial** button on the main menu for a hands-on, can't-fail walkthrough of every note type.

---

## Features

- Three built-in preset tracks with **original synthwave music generated live in your browser** (no copyrighted audio, works fully offline).
- Seven note types with distinct neon visuals and scoring.
- Difficulty tuned so Normal and Hard stay reachable.
- **Beatmap Creator:** load your own music, place any note type on a timeline, set a custom background (image, GIF, or video), then test, save, export, or re-open maps to edit.
- Adjustable settings that persist between sessions.
- No accounts, no servers, no tracking — everything runs locally.

---

## Getting the Music (Free & Legal)

The built-in preset songs are synthesized by the game itself, so they carry no licensing baggage. For **custom maps**, you supply the music. A great source of free, royalty-free tracks is **Pixabay**:

**➡️ Download music here: https://pixabay.com/music/**

Under the [Pixabay Content License](https://pixabay.com/service/license-summary/), tracks are free to use (attribution appreciated but not required) and can be used inside a game like this. Please respect the license: don't redistribute the raw audio file on its own, and check individual tracks for any additional rights. Crediting the artist is a kind touch.

> **Why you download the media yourself:** To keep everything clean and legal, the songs, images, and videos are **not bundled inside the game**. Instead, each community map below links to the original source so you download the media directly from the rights holder, then load it into the game locally. Nothing copyrighted is redistributed by this project.

---

## How to Load a Downloaded Map

1. Open **`neon-beats.html`** and click **✚ Beatmap Creator**.
2. Click **📁 Load Music** and select the track you downloaded from Pixabay (the map's linked song).
3. Click **⬆ Import** and select the map's **`.json`** file.
4. Click **🖼 Set Background** and select the map's downloaded image or video (optional).
5. Click **▶ Test Play**, or **💾 Save to Library** to add it to your Play menu.

The beatmap `.json` only contains note timing/positions — it needs the matching music file loaded to play.

---

## 🎶 Map Pack — Downloadable Community Maps

Each map lists three separate downloads so no media is redistributed here: the **song** (from its source), the **beatmap file**, and the **background**. Fill in the links below.

<!-- ============================================================
     MAP ENTRY TEMPLATE — copy this block for each new map.
     Replace the PASTE_..._LINK_HERE placeholders with your URLs.
     ============================================================ -->

### Map 1 — _[Map / Song Title]_

- **Difficulty:** _Easy / Normal / Hard_
- **Mapper:** _your name_
- 🎵 **Song (download from source):** [https://pixabay.com/music/beats-no-sleep-hiphop-music-473847/] — Artist: kontraa – Title: No Sleep | Hiphop Music, via Pixabay_
- 📄 **Beatmap file (.json):** [within the basic files you download called (kontraa-no-sleep-hiphop-music-473847.nbmap.json)]
- 🖼️ **Background image / video (download):** [https://pixabay.com/videos/seoul-hangang-river-yeouido-336755/] - Creator: YounStudios - Title: Seoul, hangang river, yeouido free stock video. Free for use & download.

### Map 2 — _[Map / Song Title]_

- **Difficulty:** _Easy / Normal / Hard_
- **Mapper:** _your name_
- 🎵 **Song (download from source):** [PASTE_SONG_PAGE_LINK_HERE](PASTE_SONG_PAGE_LINK_HERE) — _Artist – Title, via Pixabay_
- 📄 **Beatmap file (.json):** [PASTE_BEATMAP_JSON_LINK_HERE](PASTE_BEATMAP_JSON_LINK_HERE)
- 🖼️ **Background image / video (download):** [PASTE_BACKGROUND_MEDIA_LINK_HERE](PASTE_BACKGROUND_MEDIA_LINK_HERE)

### Map 3 — _[Map / Song Title]_

- **Difficulty:** _Easy / Normal / Hard_
- **Mapper:** _your name_
- 🎵 **Song (download from source):** [PASTE_SONG_PAGE_LINK_HERE](PASTE_SONG_PAGE_LINK_HERE) — _Artist – Title, via Pixabay_
- 📄 **Beatmap file (.json):** [PASTE_BEATMAP_JSON_LINK_HERE](PASTE_BEATMAP_JSON_LINK_HERE)
- 🖼️ **Background image / video (download):** [PASTE_BACKGROUND_MEDIA_LINK_HERE](PASTE_BACKGROUND_MEDIA_LINK_HERE)

<!-- Add more maps by copying a block above. -->

---

## Making & Sharing Your Own Maps

1. In the **Beatmap Creator**, load a track, place notes, and set a background.
2. Click **⬇ Export** to save the beatmap as a `.json` file.
3. Upload that `.json` somewhere shareable (e.g. a file host or repo) and add it as a new map entry above.
4. Link the song's original source (so others download it legally) and the background media separately.

Because the `.json` holds only note data — no audio, no images — sharing it never redistributes anyone's copyrighted media.

---

## Legal & Credits

- **Music:** Not included. Download from the linked sources (e.g. [Pixabay](https://pixabay.com/music/)) under their respective licenses. Credit artists where possible.
- **Backgrounds:** Not included. Provide your own images/videos, or link to freely licensed sources.
- **Game code & assets:** Generated with AI assistance (Anthropic's Claude) and provided as-is. You are responsible for ensuring any media you add complies with its license.
- This project does not host, bundle, or redistribute any third-party copyrighted media.
