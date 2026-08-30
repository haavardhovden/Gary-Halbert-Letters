# CLAUDE.md

Standing instructions for working in this repo.

## Processing a pasted Gary Halbert letter

When the user pastes a Gary Halbert letter (or similar long marketing text) directly into
the chat, treat it as the next letter to process — without the user needing to repeat these
steps each time:

1. **Check for duplicates.** Search `letters-read.md` and `archive-index.md` (by title and
   by opening line) to confirm this letter hasn't already been logged or saved.
2. **Save it verbatim.** Write the pasted text as-is to the next `letters/letter-XXX.md`
   (zero-padded, next number after the highest existing file in `letters/`).
3. **Assess its copywriting value.** Yes/no, plus the key techniques it demonstrates (or,
   if no: why not — e.g. pure logistics/admin content with no reusable mechanism).
4. **Update the tracking files accordingly:**
   - `letters-read.md` — append an entry in the existing numbered format (file link + short
     opening-line excerpt).
   - `archive-index.md` — mark the matching title `[x]` with a link to the new
     `letter-XXX.md`, if a matching title exists in the master list; otherwise leave it (the
     archive index is the *official* title list from thegaryhalbertletter.com — don't invent
     new entries in it for letters that aren't already named there).
   - `mechanisms.md` — only if the letter has real standalone copywriting value. Add a new
     numbered entry (with a `Kilde:` line pointing at the new `letter-XXX.md`) or extend an
     existing entry as an additional example, whichever fits better. Low-value/logistics
     letters get logged in `letters-read.md` but do **not** get a mechanisms.md entry.

## mechanisms.md ground rules

- Treat `mechanisms.md` as a draft, not settled truth. When re-assessing a letter against
  it, challenge freely — if an entry misreads a letter, overgeneralizes, or the technique is
  weaker than the notes claim, say so directly and explain why, rather than silently
  preserving it.
- The document mixes general Halbert mechanisms with the user's own client-application notes
  (Stille, Vidda — e.g. the "DIN EGEN PROSESS" section, "For Stille/Vidda" asides,
  "2026-oversettelse" notes). **Propose changes to any existing entry that touches those
  client applications in chat before applying them** — the user wants to see and weigh in on
  what's changing there. Everything else in mechanisms.md can be edited freely.
- Client-specific application ideas (new Stille/Vidda angles, copy twists, etc.) belong in
  `client-applications.md`, not `mechanisms.md` — keep the split between general technique
  and client application intact.

## Context hygiene

Only customer data and ad-sparring content (angles, copy, conclusions reached together)
belongs in this repo. Don't pull in unrelated personal/business context (e.g. employment
terms, schedules, unrelated career discussion) even if it's sitting in the same source
document or chat export.
