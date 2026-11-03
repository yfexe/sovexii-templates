# Sovexii Studio sounds

Music and sound effects shown in the app's Audio -> Sounds / Effects library. Every file here is CC0
(public domain, no credit needed). `index.json` lists them; the app downloads a file the first time
it is played or added and keeps it offline.

- Music: CC0 tracks from OpenGameArt, loudness-matched to -14 LUFS. Each entry's `source` links the
  original page (authors are credited there as a courtesy; CC0 needs no credit).
- Effects: made from scratch for Sovexii Studio (procedural synthesis), released as CC0.

To add a sound: put an .m4a (AAC) in music/ or sfx/, add an entry to index.json (lowercase id,
`kind` music|sfx, an existing `category`), push. Bump `version` when a file changes.
