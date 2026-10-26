# The Brief

What you read before you walk in. Twelve rooms. Each room has its directions (cold, imperative, with the why), its facts (with the source) and its stories (true moments where someone handled that room, ending with the line they said and the move underneath it).

Nothing to perform. Read it, close it.

## Publish with GitHub Pages

1. Create a new **public** repository called `the-brief` on GitHub.
2. **Add file > Upload files** and drag in everything in this folder so `index.html` sits at the top level: `index.html`, `content.js`, `manifest.webmanifest`, `sw.js`, the `icons` folder and this README. Commit.
3. **Settings > Pages**, **Source** = *Deploy from a branch*, branch `main`, folder `/ (root)`, save.
4. After a minute or two it's live at `https://djsumd.github.io/the-brief/`.

## Install it on the phone

Android: open the link in Chrome, three-dot menu, **Install app**. If Chrome's install record is poisoned ("Could not open app"), install from Samsung Internet instead; it keeps its own install state.

iPhone: Safari, Share, **Add to Home Screen**, "Open as web app" on.

## What's in it

- **Today**: one story, three directions, one fact.
- **Rooms**: Chairing, The ask, Saying no, Bad news, Praise, Grief and care, The first minute, Silence and timing, The bandstand, The classroom, Rapport, Words. Each with Directions, Facts, Stories.
- **Walking in** (from Today): pick the room and get six directions and three lines from people who handled it. Things you've saved or kept come first.
- **Search** across everything. **Saved** and notes on anything. **Review**: "Make it stick" brings it back tomorrow, then at doubling intervals; you get the setting first and recall the rest.
- Listen (stories), paper or charcoal theme, text size, backup and restore, notes export.

Counts: 219 stories, 750 directions (including The Register's 91 rails, The Floor's phrasebook and phrasing moves, and the Lexicon), 115 facts.

## Facts worth a spot-check

The writers were told to leave out anything they could not source. These are the ones they flagged as least certain: the WA Associations Incorporation Act 2015 Part numbers; the WA standing order on dissent from a ruling; the Fair Work Act section ranges for compassionate leave; the Live Performance Award and Musicians Australia minimum-fee details; the WHS noise regulation number; Roy et al. 2004 teacher voice-disorder percentages; the Jack Benny 1948 air date; the Oscar 45-second convention; the cold-water peak-end study details. The substance is right in each case; the numbering or decimals are from memory.

## Updating

Upload changed files and commit. Change `VERSION` at the top of `sw.js` (for example `brief-v2`) whenever any file changes so installed copies pick it up.

## Adding content

`content.js` is one array. Stories have `title, who, when, where, room, tags, text, line, move`. Directions have `room, do, why, when`. Facts have `room, fact, source, use`. Every item has a unique `id` and a `kind` of story, direction or fact. If something is wrong, delete it; a wrong line is worse than no line.
