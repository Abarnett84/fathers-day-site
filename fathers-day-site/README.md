# Happy Father's Day Website for Dad 🎉

**Goofy • Fun • Minimalistic • Loving • Clever Animations**

This is a complete **3-page** website (I added a third "Letter to Dad" page as requested). Ready for you to customize with your own photos and songs. Built to be edited easily in Cursor, VS Code, or any text editor. Phone-first but looks great on desktop too.

## Quick Start

1. Download this entire `fathers-day-site` folder to your computer.
2. Open `index.html` in your browser (double-click it).
3. Edit the files in Cursor / VS Code / your editor of choice.
4. Replace the placeholder images (now 7 slots) and add your two songs where it literally says **"LEAVE SONG 1 HERE"** and **"LEAVE SONG 2 HERE"**.
5. When ready, send the whole folder to Dad or upload to a free host.

**New 3rd page**: `letter.html` — a warm, goofy personal letter from you to him. I filled it with loving + roast-y content you can tweak. It has its own confetti button and is fully phone-friendly.

## Folder Structure

```
fathers-day-site/
├── index.html          ← Page 1: Goofy greeting + music (LEAVE SONG 1 HERE)
├── gallery.html        ← Page 2: Photo memory vault (7 slots ready, LEAVE SONG 2 HERE)
├── letter.html         ← Page 3: Personal letter to Dad (newly added)
├── README.md           ← You're reading this
└── assets/
    ├── images/         ← PUT ALL YOUR PHOTOS HERE (7 slots)
    └── audio/          ← PUT THE TWO SONGS HERE
```

**The folder you were trying to remember is called `assets/`** (very common in web development). Inside it we have `images/` and `audio/` subfolders. You can rename them later if you want, just update the paths in the HTML.

## How to Add Your Photos (Page 2)

1. Put your photos inside the `assets/images/` folder.
2. Open `gallery.html` in your editor.
3. Find any of the 6 memory slots (they have big dashed placeholder boxes).
4. Replace the entire `<div class="memory-placeholder ...">` block with a real `<img>` tag.

**Example replacement:**

```html
<img src="assets/images/fishing-with-dad-2023.jpg" 
     alt="Dad and me fishing at the lake, summer 2023" 
     class="w-full h-full object-cover">
```

The cards already have nice captions and hover effects. Just update the text below the image too.

You can add more than 6 photos — just copy one of the existing cards and change the numbers.

## How to Add Background Songs

There are **two separate songs** — one for each page.

### Page 1 Song (Greeting page)
- File location: `assets/audio/dads-song-page1.mp3`
- In `index.html`, look for the `<audio id="dad-song-1">` tag near the music player.
- Change the `src` to match your filename.

### Page 2 Song (Gallery / Memory Vault)
- File location: `assets/audio/dads-song-page2.mp3`
- In `gallery.html`, look for `<audio id="dad-song-2">`.
- Update the `src`.

**Tips for songs:**
- Use MP3 format (best compatibility).
- Keep files under ~4-5 MB if possible (faster loading).
- The player has a spinning vinyl record animation when music is playing.
- Click the vinyl or the button to play/pause. Songs loop automatically.
- Autoplay is intentionally disabled (browser rules). User has to click play — this is normal and respectful.

## What Makes This Site Special

- **Clever animations**: Hover effects that tilt/scale cards goofily, confetti explosions with dad-themed emojis (🎉👨‍👧‍👦🛠️🍔), smooth stat counters, spinning vinyl records.
- **Minimalistic but fun**: Clean Tailwind design with lots of breathing room, but playful touches everywhere.
- **Loving tone**: Heartfelt messages wrapped in humor so it feels like *you* wrote it.
- **Dad jokes included**: There's a joke rotator on page 2. Press "J" on keyboard for instant new joke.
- **Mobile friendly**: Works great on phones and tablets.
- **Zero dependencies** after the initial Tailwind CDN (you can remove the CDN later and install Tailwind properly if you want to host it long-term).

## Keyboard Shortcuts

- **Spacebar** (on page 1): Toggles the song
- **J** key (on page 2): New dad joke
- **Escape**: Closes photo modal

## Questions So I Can Make It Even Better

To make this *perfectly* tailored for your dad, reply with any of these:

1. What does your dad like to be called? (Dad, Papa, Old Man, [His Name], etc.)
2. Any specific inside jokes, hobbies, or memories you want highlighted? (fishing, grilling, bad puns, a particular trip, sports, etc.)
3. Favorite colors or vibe? (I used warm orange + clean slate. We can change it.)
4. Roughly how many photos do you want to add? I can add more slots easily.
5. Do you want a **3rd page**? Examples:
   - A personal letter from you to him (with nice typography)
   - "Dad's Life Lessons" or "Things I Learned From You"
   - A silly quiz like "How Well Do You Know Your Kid?"
6. Any must-include text or a specific message you want front and center?
7. Will Dad mostly view this on phone, desktop, or both?
8. Do you already have the two songs picked out, or need format/conversion tips?

## Future Polish Ideas (I Can Add These)

- Drag-and-drop photo upload area (more advanced)
- Print button for a physical version
- Dark mode toggle
- More dad jokes or a "rate the joke" feature
- Confetti intensity slider (for maximum chaos)
- Simple password so only Dad can see it (if you want privacy)

Just say the word and I'll update the files instantly.

---

**Made with love, sarcasm, and way too much CSS** for your dad.  
He’s going to love it. Happy Father’s Day! ❤️

If anything breaks or you want changes, just paste the error or describe what you want different. I’m here.