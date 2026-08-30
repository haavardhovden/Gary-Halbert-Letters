# CLAUDE.md

Standing instructions for working in this repo.

## curriculum.md

`curriculum.md` (repo root) is the full 30-day plan. This repo's letters/mechanisms work is
step 1 (section 1) of it. Sections 2–6 (Ogilvy/Caples/other copywriters, classic ads beyond
the swipe-file canon, modern DTC ad study via Atria, books, follows/newsletters/courses) are
later stages — **not started yet**. Don't act on them without being asked.

Going forward, once later stages are underway: `mechanisms.md` is the single running
knowledge base across *every* stage of the curriculum, not just the Halbert letters —
techniques from classic ads, modern DTC ad study, and books all land in the same file,
cross-referenced by source (the existing `Kilde:` convention extends naturally: a book gets
`Kilde: <title>, ch. X` or similar instead of `letter-XXX.md`). Same numbered-entry format,
same "new pattern only" bar, same rule about proposing Stille/Vidda-touching changes first.

## Processing a pasted Gary Halbert letter

When the user pastes a Gary Halbert letter (or similar long marketing text) directly into
the chat, treat it as the next letter to process — without the user needing to repeat these
steps each time:

1. **Don't block on duplicate-checking.** A quick glance at `letters-read.md` /
   `archive-index.md` is fine, but completeness matters more than avoiding duplicates — if
   it's unclear whether a letter was already saved, save it anyway rather than spending time
   verifying. A duplicate `letters/letter-XXX.md` is a non-issue; a missing letter is the
   actual failure mode.
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
   - `mechanisms.md` — **only touch it when the letter contributes a genuinely new pattern**,
     not already captured (even loosely) by an existing entry. A weak or partial variant of a
     technique that's already in there is just `value: no` + a short reason in chat — don't
     add it as a new entry, and don't extend an existing entry with it as "another example"
     either. The bar is a new mechanism, not a new instance of one already logged.

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
